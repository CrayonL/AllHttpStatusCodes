# HTTP状态码 405 (Method Not Allowed) 含义详解

---

## HTTP 405 状态码

HTTP 405 (Http Status Code 405) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的4xx 客户端错误系列响应码之一。

---

**状态码含义：**  
**HTTP405状态码代表的意思是** **不允许的请求方法**，即 **HTTP 405 Method Not Allowed** 响应状态。

**状态详细说明：**  
**【http code 405】** 表示请求行中指定的请求方法不能被用于请求相应的资源。该响应必须返回一个Allow头信息用以表示出当前资源能够接受的请求方法的列表。  
鉴于PUT，DELETE方法会对服务器上的资源进行写操作，因而绝大部分的网页服务器都不支持或者在默认配置下不允许上述请求方法，对于此类请求均会返回405错误。

  

---

与**HTTP状态405**相似的同系列状态码： - [HTTP 425](https://seo.juziseo.com/doc/http_code/425 "HTTP 425详细说明")
 - [HTTP 431](https://seo.juziseo.com/doc/http_code/431 "HTTP 431详细说明")
 - [HTTP 428](https://seo.juziseo.com/doc/http_code/428 "HTTP 428详细说明")
 - [HTTP 429](https://seo.juziseo.com/doc/http_code/429 "HTTP 429详细说明")
 - [HTTP 451](https://seo.juziseo.com/doc/http_code/451 "HTTP 451详细说明")

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