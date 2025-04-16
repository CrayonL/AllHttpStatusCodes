# HTTP状态码 206 (Partial Content) 含义详解

---

## HTTP 206 状态码

HTTP 206 (Http Status Code 206) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的2xx 成功状态系列响应码之一。

---

**状态码含义：**  
**HTTP206状态码代表的意思是** **请求已成功处理，但仅返回了部分内容**，即 **HTTP 206 Partial Content** 响应状态。

**状态详细说明：**  
**【http code 206】** 表示服务器已经成功处理了部分GET请求。类似于迅雷这类的HTTP下载工具都是使用此类响应实现断点续传或者将一个大文档分解为多个下载段同时下载。该请求必须包含Range头信息来指示客户端希望得到的内容范围，并且可能包含If-Range来作为请求条件。

  

---

与**HTTP状态206**相似的同系列状态码： - [HTTP 200](https://seo.juziseo.com/doc/http_code/200 "HTTP 200详细说明")
 - [HTTP 201](https://seo.juziseo.com/doc/http_code/201 "HTTP 201详细说明")
 - [HTTP 203](https://seo.juziseo.com/doc/http_code/203 "HTTP 203详细说明")
 - [HTTP 205](https://seo.juziseo.com/doc/http_code/205 "HTTP 205详细说明")
 - [HTTP 207](https://seo.juziseo.com/doc/http_code/207 "HTTP 207详细说明")

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