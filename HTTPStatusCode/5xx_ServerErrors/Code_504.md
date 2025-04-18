# HTTP状态码 504 (Gateway Timeout) 含义详解

---

## HTTP 504 状态码

HTTP 504 (Http Status Code 504) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的5xx 服务器错误状态系列响应码之一。

---

**状态码含义：**  
**HTTP504状态码代表的意思是** **网关超时**，即 **HTTP 504 Gateway Timeout** 响应状态。

**状态详细说明：**  
**【http code 504】** 表示作为网关或者代理工作的服务器尝试执行请求时，未能及时从上游服务器（URI标识出的服务器，例如HTTP、FTP、LDAP）或者辅助服务器（例如DNS）收到响应。注意：某些代理服务器在DNS查询超时时会返回400或者500错误。在webserver+后端脚本语言的环境中（如Nginx + php-fpm），通常由脚本处理语言超时引起。

**常见应用案例：**  
Status Code: 504 Gateway Timeout 表示服务器的脚本语言端或代理端，如PHP，ASP，JSP，Python等或反向代理端已接受请求，但在设定的时间内未完成响应，即响应超时。通常可调响应超时的时间，和排除程序无限循环的情况。

  

---

与**HTTP状态504**相似的同系列状态码： - [HTTP 510](https://seo.juziseo.com/doc/http_code/510 "HTTP 510详细说明")
 - [HTTP 511](https://seo.juziseo.com/doc/http_code/511 "HTTP 511详细说明")
 - [HTTP 502](https://seo.juziseo.com/doc/http_code/502 "HTTP 502详细说明")
 - [HTTP 506](https://seo.juziseo.com/doc/http_code/506 "HTTP 506详细说明")
 - [HTTP 501](https://seo.juziseo.com/doc/http_code/501 "HTTP 501详细说明")

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