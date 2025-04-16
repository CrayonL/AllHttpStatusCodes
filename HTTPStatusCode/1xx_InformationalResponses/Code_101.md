# HTTP状态码 101 (Switching Protocols) 含义详解

---

## HTTP 101 状态码

HTTP 101 (Http Status Code 101) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的1xx 请求信息系列响应码之一。

---

**状态码含义：**  
**HTTP101状态码代表的意思是** **请切换协议**，即 **HTTP 101 Switching Protocols** 响应状态。

**状态详细说明：**  
**【http code 101】** 表示服务器已经理解了客户端的请求，并将通过Upgrade消息头通知客户端采用不同的协议来完成这个请求。在发送完这个响应最后的空行后，服务器将会切换到在Upgrade消息头中定义的那些协议。  
只有在切换新的协议更有好处的时候才应该采取类似措施。例如，切换到新的HTTP版本（如HTTP／2）比旧版本更有优势，或者切换到一个实时且同步的协议（如WebSocket）以传送利用此类特性的资源。

  

---

与**HTTP状态101**相似的同系列状态码： - [HTTP 100](https://seo.juziseo.com/doc/http_code/100 "HTTP 100详细说明")
 - [HTTP 102](https://seo.juziseo.com/doc/http_code/102 "HTTP 102详细说明")

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