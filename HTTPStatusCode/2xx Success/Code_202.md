# HTTP状态码 202 (Accepted) 含义详解

---

## HTTP 202 状态码

HTTP 202 (Http Status Code 202) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的2xx 成功状态系列响应码之一。

---

**状态码含义：**  
**HTTP202状态码代表的意思是** **请求已被接受，但尚未处理**，即 **HTTP 202 Accepted** 响应状态。

**状态详细说明：**  
**【http code 202】** 表示服务器端已接受请求，但尚未处理。正如它可能被拒绝一样，最终该请求可能会也可能不会被执行。适用于异步操作场合，允许服务器接受其他过程请求，而不用让客户端一直保持与服务器的连接知道批处理操作全部完成。  
在接受请求处理并返回202状态码的响应应当在返回的实体中包含一些指示处理当前状态的信息，以及指向处理状态监视器或状态预测的指针，以便用户能够估计操作是否已经完成。

  

---

与**HTTP状态202**相似的同系列状态码： - [HTTP 207](https://seo.juziseo.com/doc/http_code/207 "HTTP 207详细说明")
 - [HTTP 204](https://seo.juziseo.com/doc/http_code/204 "HTTP 204详细说明")
 - [HTTP 226](https://seo.juziseo.com/doc/http_code/226 "HTTP 226详细说明")
 - [HTTP 201](https://seo.juziseo.com/doc/http_code/201 "HTTP 201详细说明")
 - [HTTP 205](https://seo.juziseo.com/doc/http_code/205 "HTTP 205详细说明")

---

其它常见状态码： - [HTTP 200](https://seo.juziseo.com/doc/http_code/200 "HTTP 200详细说明")
 - [HTTP 301](https://seo.juziseo.com/doc/http_code/301 "HTTP 301详细说明")
 - [HTTP 302](https://seo.juziseo.com/doc/http_code/302 "HTTP 302详细说明")
 - [HTTP 400](https://seo.juziseo.com/doc/http_code/400 "HTTP 400详细说明")
 - [HTTP 403](https://seo.juziseo.com/doc/http_code/403 "HTTP 403详细说明")
 - [HTTP 404](https://seo.juziseo.com/doc/http_code/404 "HTTP 404详细说明")
 - [HTTP 500](https://seo.juziseo.com/doc/http_code/500 "HTTP 500详细说明")
 - [HTTP 502](https://seo.juziseo.com/doc/http_code/502 "HTTP 502详细说明")
 - [HTTP 503](https://seo.juziseo.com/doc/http_code/503 "HTTP 503详细说明")
 - [HTTP 504](https://seo.juziseo.com/doc/http_code/504 "HTTP 504详细说明")

---

更多状态码含义说明请查看： [HTTP状态码大全]()