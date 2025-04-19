# HTTP状态码 100 (Continue) 含义详解

---

## HTTP 100 状态码

HTTP 100 (Http Status Code 100) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的1xx 请求信息系列响应码之一。

---

**状态码含义：**  
**HTTP100状态码代表的意思是** **请继续请求**，即 **HTTP 100 Continue** 响应状态。

**状态详细说明：**  
**【http code 100】** 表示客户端应当继续进行请求。此时服务器端已经收到客户端请求的初始部分，而且也没有关闭连接，客户端应该继续发送请求的剩余部分。不过如果请求已经发送完毕，客户端会直接忽略此响应。服务器要在请求完成时发送一个最终响应。

  

---

与**HTTP状态100**相似的同系列状态码： [HTTP 101](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/1xx_InformationalResponses/Code_101.md "HTTP 101详细说明") [HTTP 102](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCodes/Code_102.md "HTTP 102详细说明")



---

其它常见状态码： - [HTTP 200](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/2xx_Success/Code_200.md "HTTP 200详细说明")
 - [HTTP 301](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_301.md "HTTP 301详细说明")
 - [HTTP 302](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_302.md "HTTP 302详细说明")

其它常见状态码： - [HTTP 200](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_200 "HTTP 200详细说明")
 - [HTTP 301](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_301 "HTTP 301详细说明")
 - [HTTP 302](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCodes/Status_302 "HTTP 302详细说明")
 - [HTTP 400](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_400.md "HTTP 400详细说明")
 - [HTTP 403](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_403.md "HTTP 403详细说明")
 - [HTTP 404](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/4xx_ClientErrors/Code_404.md "HTTP 404详细说明")
 - [HTTP 500](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_500.md "HTTP 500详细说明")
 - [HTTP 502](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_502.md "HTTP 502详细说明")
 - [HTTP 503](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_503.md "HTTP 503详细说明")
 - [HTTP 504](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_504.md "HTTP 504详细说明")

---
更多状态码含义说明请查看： [HTTP状态码大全](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/All_HTTP_Status_Codes.md)
