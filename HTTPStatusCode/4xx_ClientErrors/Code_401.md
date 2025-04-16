# TTP状态码 401 (Unauthorized) 含义详解

---

## HTTP 401 状态码

HTTP 401 (Http Status Code 401) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的4xx 客户端错误系列响应码之一。

---

**状态码含义：**  
**HTTP401状态码代表的意思是** **需要身份认证验证**，即 **HTTP 401 Unauthorized** 响应状态。

**状态详细说明：**  
**【http code 401】** 表示当前请求需要用户验证。该响应必须包含一个适用于被请求资源的WWW-Authenticate信息头用以询问用户信息。客户端可以重复提交一个包含恰当的Authorization头信息的请求。如果当前请求已经包含了Authorization证书，那么401响应代表着服务器验证已经拒绝了那些证书。如果401响应包含了与前一个响应相同的身份验证询问，且浏览器已经至少尝试了一次验证，那么浏览器应当向用户展示响应中包含的实体信息，因为这个实体信息中可能包含了相关诊断信息。参见RFC 2617。

  

---

与**HTTP状态401**相似的同系列状态码： - [HTTP 416](https://seo.juziseo.com/doc/http_code/416 "HTTP 416详细说明")
 - [HTTP 499](https://seo.juziseo.com/doc/http_code/499 "HTTP 499详细说明")
 - [HTTP 415](https://seo.juziseo.com/doc/http_code/415 "HTTP 415详细说明")
 - [HTTP 449](https://seo.juziseo.com/doc/http_code/449 "HTTP 449详细说明")
 - [HTTP 406](https://seo.juziseo.com/doc/http_code/406 "HTTP 406详细说明")

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