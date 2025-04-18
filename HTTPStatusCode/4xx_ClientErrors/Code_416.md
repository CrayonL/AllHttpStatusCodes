# HTTP状态码 416 (Range Not Satisfiable) 含义详解

---

## HTTP 416 状态码

HTTP 416 (Http Status Code 416) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的4xx 客户端错误系列响应码之一。

---

**状态码含义：**  
**HTTP416状态码代表的意思是** **请求的范围无效**，即 **HTTP 416 Range Not Satisfiable** 响应状态。

**状态详细说明：**  
**【http code 416】** 表示旧称“Requested Range Not Satisfiable”。如果请求中包含了Range请求头，并且Range中指定的任何数据范围都与当前资源的可用范围不重合，同时请求中又没有定义If-Range请求头，那么服务器就应当返回416状态码，同时包含一个Content-Range实体头，用以指明当前资源的长度。这个响应也被禁止使用multipart/byteranges作为其Content-Type。

  

---

与**HTTP状态416**相似的同系列状态码： - [HTTP 408](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_408.md "HTTP 408详细说明")
 - [HTTP 414](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_414.md "HTTP 414详细说明")
 - [HTTP 410](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_410.md "HTTP 410详细说明")
 - [HTTP 403](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_403.md "HTTP 403详细说明")
 - [HTTP 451](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_451.md "HTTP 451详细说明")

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