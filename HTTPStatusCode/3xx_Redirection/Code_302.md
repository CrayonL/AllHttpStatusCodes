# HTTP状态码 302 (Found) 含义详解

---

## HTTP 302 状态码

HTTP 302 (Http Status Code 302) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的3xx 重定向状态系列响应码之一。

---

**状态码含义：**  
**HTTP302状态码代表的意思是** **临时重定向**，即 **HTTP 302 Found** 响应状态。

**状态详细说明：**  
**【http code 302】** 表示请求的资源现在临时从不同的URI响应请求，即302跳转。由于这样的重定向是临时的，客户端应当继续向原有地址发送以后的请求。只有在Cache-Control或Expires中进行了指定的情况下，这个响应才是可缓存的。  
注意：虽然RFC 1945和RFC 2068规范不允许客户端在重定向时改变请求的方法，但是很多现存的浏览器将302响应视作为303响应，并且使用GET方式访问在Location中规定的URI，而无视原先请求的方法。状态码303和307被添加了进来，用以明确服务器期待客户端进行何种反应。

**常见应用案例：**  
Status Code: 302 Found 表示URL发生临时跳转。通常是旧Url临时不使用，内容需要在新的Url获取时，使用此状态码。

  

---

与**HTTP状态302**相似的同系列状态码： - [HTTP 305](https://seo.juziseo.com/doc/http_code/305 "HTTP 305详细说明")
 - [HTTP 304](https://seo.juziseo.com/doc/http_code/304 "HTTP 304详细说明")
 - [HTTP 306](https://seo.juziseo.com/doc/http_code/306 "HTTP 306详细说明")
 - [HTTP 301](https://seo.juziseo.com/doc/http_code/301 "HTTP 301详细说明")
 - [HTTP 303](https://seo.juziseo.com/doc/http_code/303 "HTTP 303详细说明")

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