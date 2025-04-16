# HTTP状态码 304 (Not Modified) 含义详解

---

## HTTP 304 状态码

HTTP 304 (Http Status Code 304) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的3xx 重定向状态系列响应码之一。

---

**状态码含义：**  
**HTTP304状态码代表的意思是** **请求资源与本地缓存相同，未修改**，即 **HTTP 304 Not Modified** 响应状态。

**状态详细说明：**  
**【http code 304】** 表示如果客户端发送了一个带条件的GET请求且该请求已被允许，而文档的内容（自上次访问以来或者根据请求的条件）并没有改变，则服务器应当返回这个状态码。304响应禁止包含消息体，因此始终以消息头后的第一个空行结尾。该响应必须包含以下头信息：Date、ETag、Content-Location、Expires、Cache-Control、Vary。

**常见应用案例：**  
Status Code: 304 Not Modified 表示经过本地缓存的内容和服务器端对比，资源未变化，不需要重新拉取资源，可以使用本地缓存数据，从而节省网络流量。需要服务器端支持ETag，且浏览器在请求时发送ETag信息。

  

---

与**HTTP状态304**相似的同系列状态码： - [HTTP 307](https://seo.juziseo.com/doc/http_code/307 "HTTP 307详细说明")
 - [HTTP 305](https://seo.juziseo.com/doc/http_code/305 "HTTP 305详细说明")
 - [HTTP 301](https://seo.juziseo.com/doc/http_code/301 "HTTP 301详细说明")
 - [HTTP 303](https://seo.juziseo.com/doc/http_code/303 "HTTP 303详细说明")
 - [HTTP 302](https://seo.juziseo.com/doc/http_code/302 "HTTP 302详细说明")

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