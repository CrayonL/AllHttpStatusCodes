# HTTP状态码 413 (Payload Too Large) 含义详解

---

## HTTP 413 状态码

HTTP 413 (Http Status Code 413) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的4xx 客户端错误系列响应码之一。

---

**状态码含义：**  
**HTTP413状态码代表的意思是** **请求的实体过大**，即 **HTTP 413 Payload Too Large** 响应状态。

**状态详细说明：**  
**【http code 413】** 表示旧称“Request Entity Too Large”。服务器拒绝处理当前请求，因为该请求提交的实体数据大小超过了服务器愿意或者能够处理的范围。此种情况下，服务器可以关闭连接以免客户端继续发送此请求。如果这个状况是临时的，服务器应当返回一个Retry-After的响应头，以告知客户端可以在多少时间以后重新尝试。

  

---

与**HTTP状态413**相似的同系列状态码： - [HTTP 402](https://seo.juziseo.com/doc/http_code/402 "HTTP 402详细说明")
 - [HTTP 408](https://seo.juziseo.com/doc/http_code/408 "HTTP 408详细说明")
 - [HTTP 418](https://seo.juziseo.com/doc/http_code/418 "HTTP 418详细说明")
 - [HTTP 417](https://seo.juziseo.com/doc/http_code/417 "HTTP 417详细说明")
 - [HTTP 421](https://seo.juziseo.com/doc/http_code/421 "HTTP 421详细说明")

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

更多状态码含义说明请查看： [HTTP状态码大全](https://seo.juziseo.com/doc/http_code/)