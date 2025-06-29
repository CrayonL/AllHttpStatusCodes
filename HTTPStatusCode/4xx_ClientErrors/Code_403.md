# HTTP状态码 403 (Forbidden) 含义详解

---

## HTTP 403 状态码

HTTP 403 (Http Status Code 403) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的4xx 客户端错误系列响应码之一。

---

**状态码含义：**  
**HTTP403状态码代表的意思是** **禁止访问**，即 **HTTP 403 Forbidden** 响应状态。

**状态详细说明：**  
**【http code 403】** 表示服务器已经理解请求，但是拒绝执行它。与401的拒绝响应不同的是，这与身份验证无关，而且这个请求也不应该被重复提交。如果这不是一个HEAD请求，而且服务器希望能够讲清楚为何请求不能被执行，那么就应该在实体内描述拒绝的原因。当然服务器也可以返回一个404响应，假如它不希望让客户端获得任何信息。

**常见应用案例：**  
Status Code: 403 Forbidden 表示客户端发起了请求，但此请求被服务器端拒绝。通常是由客户端浏览器UA设置不正确，或所在IP不允许访问该服务器。

  

---

与**HTTP状态403**相似的同系列状态码： - [HTTP 406](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_406.md "HTTP 406详细说明")
 - [HTTP 499](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_499.md "HTTP 499详细说明")
 - [HTTP 423](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_423.md "HTTP 423详细说明")
 - [HTTP 415](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_415.md "HTTP 415详细说明")
 - [HTTP 404](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_404.md "HTTP 404详细说明")

---

其它常见状态码： - [HTTP 200](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/2xx_Success/Code_200.md "HTTP 200详细说明")
 - [HTTP 301](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_301.md "HTTP 301详细说明")
 - [HTTP 302](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_302.md "HTTP 302详细说明")
 - [HTTP 400](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_400.md "HTTP 400详细说明")
 - [HTTP 403](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_403.md "HTTP 403详细说明")
 - [HTTP 404](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_404.md "HTTP 404详细说明")
 - [HTTP 500](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_500.md "HTTP 500详细说明")
 - [HTTP 502](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_502.md "HTTP 502详细说明")
 - [HTTP 503](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_503.md "HTTP 503详细说明")
 - [HTTP 504](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_504.md "HTTP 504详细说明")

---

更多状态码含义说明请查看： [HTTP状态码大全](https://github.com/CrayonL/AllHttpStatusCodes)