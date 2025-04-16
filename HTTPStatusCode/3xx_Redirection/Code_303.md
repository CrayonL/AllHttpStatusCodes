# HTTP状态码 303 (See Other) 含义详解

---

## HTTP 303 状态码

HTTP 303 (Http Status Code 303) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的3xx 重定向状态系列响应码之一。

---

**状态码含义：**  
**HTTP303状态码代表的意思是** **当前请求的资源在其它地址**，即 **HTTP 303 See Other** 响应状态。

**状态详细说明：**  
**【http code 303】** 表示对应当前请求的响应可以在另一个URI上被找到，而且客户端应当采用GET的方式访问那个资源。这个方法的存在主要是为了允许由脚本激活的POST请求输出重定向到一个新的资源。这个新的URI不是原始资源的替代引用。  
注意：许多HTTP/1.1版以前的浏览器不能正确理解303状态。如果需要考虑与这些浏览器之间的互动，302状态码应该可以胜任，因为大多数的浏览器处理302响应时的方式恰恰就是上述规范要求客户端处理303响应时应当做的。

  

---

与**HTTP状态303**相似的同系列状态码： - [HTTP 301](https://seo.juziseo.com/doc/http_code/301 "HTTP 301详细说明")
 - [HTTP 305](https://seo.juziseo.com/doc/http_code/305 "HTTP 305详细说明")
 - [HTTP 308](https://seo.juziseo.com/doc/http_code/308 "HTTP 308详细说明")
 - [HTTP 306](https://seo.juziseo.com/doc/http_code/306 "HTTP 306详细说明")
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