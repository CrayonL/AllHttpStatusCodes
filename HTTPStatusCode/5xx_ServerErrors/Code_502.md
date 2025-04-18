# HTTP状态码 502 (Bad Gateway) 含义详解

---

## HTTP 502 状态码

HTTP 502 (Http Status Code 502) 状态是HTTP协议的一种响应码，是我们请求访问网站时，服务器端返回的5xx 服务器错误状态系列响应码之一。

---

**状态码含义：**  
**HTTP502状态码代表的意思是** **网关无响应**，即 **HTTP 502 Bad Gateway** 响应状态。

**状态详细说明：**  
**【http code 502】** 表示作为网关或者代理工作的服务器尝试执行请求时，从上游服务器接收到无效的响应。在webserver+后端脚本语言的环境中（如Nginx + php-fpm），通常由脚本处理语言未启动或宕机引起。

**常见应用案例：**  
Status Code: 502 Bad Gateway 表示服务器端脚本解释器或代理端，如PHP，ASP，JSP，Python等脚本语言端未启动或无响应，以及反向代理端无响应。需要管理员检查脚本配置，若配置正确，通常重启脚本端可排除故障。

  

---

与**HTTP状态502**相似的同系列状态码： - [HTTP 504](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_504.md "HTTP 504详细说明")
 - [HTTP 510](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_510.md "HTTP 510详细说明")
 - [HTTP 501](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_501.md "HTTP 501详细说明")
 - [HTTP 508](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_508.md "HTTP 508详细说明")
 - [HTTP 507](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/5xx_ServerErrors/Code_507.md "HTTP 507详细说明")

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