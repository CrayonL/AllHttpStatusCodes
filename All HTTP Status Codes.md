### 1、 HTTP Status Code 1xx 请求信息

这一组状态码表明这是一个临时性响应。此响应仅由状态行和可选的HTTP头组成，以一个空行结尾。由于HTTP／1.0未定义任何1xx状态码，所以不要向HTTP／1.0客户端发送1xx响应。

| Http状态码 | Http Status Code                                                                         | Http状态码含义中文说明 |
| ------- | ---------------------------------------------------------------------------------------- | ------------- |
| **100** | [100 Continue](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/1xx_InformationalResponses/Code_100.md "查看http状态码100的详细说明")            | 请继续请求         |

| **101** | [101 Switching Protocols](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/1xx_InformationalResponses/Code_101.md "查看http状态码101的详细说明") | 请切换协议         |
| **102** | [102 Processing](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/1xx_InformationalResponses/Code_102.md "查看http状态码102的详细说明")          | 将继续执行请求       |
|         |                                                                                          |               |
### 2、 HTTP Status Code 2xx 成功状态

这一组状态码表明客户端的请求已经被服务器端成功接收并正确解析。

|Http状态码|Http Status Code|Http状态码含义中文说明|
|---|---|---|
|**200**|[200 OK](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_200 "查看http状态码200的详细说明")|请求成功|
|**201**|[201 Created](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_201 "查看http状态码201的详细说明")|请求已被接受，等待资源响应|
|**202**|[202 Accepted](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_202 "查看http状态码202的详细说明")|请求已被接受，但尚未处理|
|**203**|[203 Non-Authoritative Information](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_203 "查看http状态码203的详细说明")|请求已成功处理，结果来自第三方拷贝|
|**204**|[204 No Content](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_204 "查看http状态码204的详细说明")|请求已成功处理，但无返回内容|
|**205**|[205 Reset Content](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_205 "查看http状态码205的详细说明")|请求已成功处理，但需重置内容|
|**206**|[206 Partial Content](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_206 "查看http状态码206的详细说明")|请求已成功处理，但仅返回了部分内容|
|**207**|[207 Multi-Status](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_207 "查看http状态码207的详细说明")|请求已成功处理，返回了多个状态的XML消息|
|**208**|[208 Already Reported](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_208 "查看http状态码208的详细说明")|响应已发送|
|**226**|[226 IM Used](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_226 "查看http状态码226的详细说明")|已完成响应|

### 3、 HTTP Status Code 3xx 重定向状态

这一组状态码表示客户端需要采取更进一步的行动来完成请求。通常，这些状态码用来重定向，后续的请求地址（重定向目标）在本次响应的Location域中指明。

|Http状态码|Http Status Code|Http状态码含义中文说明|
|---|---|---|
|**300**|[300 Multiple Choices](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_300 "查看http状态码300的详细说明")|返回多条重定向供选择|
|**301**|[301 Moved Permanently](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_301 "查看http状态码301的详细说明")|永久重定向|
|**302**|[302 Found](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_302 "查看http状态码302的详细说明")|临时重定向|
|**303**|[303 See Other](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_303 "查看http状态码303的详细说明")|当前请求的资源在其它地址|
|**304**|[304 Not Modified](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_304 "查看http状态码304的详细说明")|请求资源与本地缓存相同，未修改|
|**305**|[305 Use Proxy](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_305 "查看http状态码305的详细说明")|必须通过代理访问|
|**306**|[306 (已废弃)Switch Proxy](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_306 "查看http状态码306的详细说明")|(已废弃)请切换代理|
|**307**|[307 Temporary Redirect](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_307 "查看http状态码307的详细说明")|临时重定向，同302|
|**308**|[308 Permanent Redirect](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_308 "查看http状态码308的详细说明")|永久重定向，且禁止改变http方法|

### 4、 HTTP Status Code 4xx 客户端错误

这一组状态码表示客户端的请求存在错误，导致服务器无法处理。除非响应的是一个HEAD请求，否则服务器就应该返回一个解释当前错误状况的实体，以及这是临时的还是永久性的状况。这些状态码适用于任何请求方法。浏览器应当向用户显示任何包含在此类错误响应中的实体内容。

|Http状态码|Http Status Code|Http状态码含义中文说明|
|---|---|---|
|**400**|[400 Bad Request](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_400 "查看http状态码400的详细说明")|请求错误，通常是访问的域名未绑定引起|
|**401**|[401 Unauthorized](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_401 "查看http状态码401的详细说明")|需要身份认证验证|
|**402**|[402 Payment Required](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_402 "查看http状态码402的详细说明")|-|
|**403**|[403 Forbidden](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_403 "查看http状态码403的详细说明")|禁止访问|
|**404**|[404 Not Found](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_404 "查看http状态码404的详细说明")|请求的内容未找到或已删除|
|**405**|[405 Method Not Allowed](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_405 "查看http状态码405的详细说明")|不允许的请求方法|
|**406**|[406 Not Acceptable](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_406 "查看http状态码406的详细说明")|无法响应，因资源无法满足客户端条件|
|**407**|[407 Proxy Authentication Required](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_407 "查看http状态码407的详细说明")|要求通过代理的身份认证|
|**408**|[408 Request Timeout](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_408 "查看http状态码408的详细说明")|请求超时|
|**409**|[409 Conflict](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_409 "查看http状态码409的详细说明")|存在冲突|
|**410**|[410 Gone](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_410 "查看http状态码410的详细说明")|资源已经不存在(过去存在)|
|**411**|[411 Length Required](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_411 "查看http状态码411的详细说明")|无法处理该请求|
|**412**|[412 Precondition Failed](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_412 "查看http状态码412的详细说明")|请求条件错误|
|**413**|[413 Payload Too Large](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_413 "查看http状态码413的详细说明")|请求的实体过大|
|**414**|[414 Request-URI Too Long](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_414 "查看http状态码414的详细说明")|请求的URI过长|
|**415**|[415 Unsupported Media Type](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_415 "查看http状态码415的详细说明")|无法处理的媒体格式|
|**416**|[416 Range Not Satisfiable](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_416 "查看http状态码416的详细说明")|请求的范围无效|
|**417**|[417 Expectation Failed](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_417 "查看http状态码417的详细说明")|无法满足的Expect|
|**418**|[418 I'm a teapot](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_418 "查看http状态码418的详细说明")|愚人节笑话|
|**421**|[421 There are too many connections from your internet address](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_421 "查看http状态码421的详细说明")|连接数超限|
|**422**|[422 Unprocessable Entity](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_422 "查看http状态码422的详细说明")|请求的语义错误|
|**423**|[423 Locked](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_423 "查看http状态码423的详细说明")|当前资源被锁定|
|**424**|[424 Failed Dependency](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_424 "查看http状态码424的详细说明")|当前请求失败|
|**425**|[425 Unordered Collection](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_425 "查看http状态码425的详细说明")|未知|
|**426**|[426 Upgrade Required](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_426 "查看http状态码426的详细说明")|请切换到TLS/1.0|
|**428**|[428 Precondition Required](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_428 "查看http状态码428的详细说明")|请求未带条件|
|**429**|[429 Too Many Requests](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_429 "查看http状态码429的详细说明")|并发请求过多|
|**431**|[431 Request Header Fields Too Large](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_431 "查看http状态码431的详细说明")|请求头过大|
|**449**|[449 Retry With](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_449 "查看http状态码449的详细说明")|请重试|
|**451**|[451 Unavailable For Legal Reasons](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_451 "查看http状态码451的详细说明")|访问被拒绝（法律的要求）|
|**499**|[499 Client Closed Request](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_499 "查看http状态码499的详细说明")|客户端主动关闭了连接|

### 5、 HTTP Status Code 5xx 服务器错误状态

这一组状态码说明服务器在处理请求的过程中有错误或者异常状态发生，也有可能是服务器意识到以当前的软硬件资源无法完成对请求的处理。除非这是一个HEAD请求，否则服务器应当包含一个解释当前错误状态以及这个状况是临时的还是永久的解释信息实体。浏览器应当向用户展示任何在当前响应中被包含的实体。

|Http状态码|Http Status Code|Http状态码含义中文说明|
|---|---|---|
|**500**|[500 Internal Server Error](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_500 "查看http状态码500的详细说明")|服务器端程序错误|
|**501**|[501 Not Implemented](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_501 "查看http状态码501的详细说明")|服务器不支持的请求方法|
|**502**|[502 Bad Gateway](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_502 "查看http状态码502的详细说明")|网关无响应|
|**503**|[503 Service Unavailable](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_503 "查看http状态码503的详细说明")|服务器端临时错误|
|**504**|[504 Gateway Timeout](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_504 "查看http状态码504的详细说明")|网关超时|
|**505**|[505 HTTP Version Not Supported](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_505 "查看http状态码505的详细说明")|服务器不支持的HTTP版本|
|**506**|[506 Variant Also Negotiates](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_506 "查看http状态码506的详细说明")|服务器内部配置错误|
|**507**|[507 Insufficient Storage](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_507 "查看http状态码507的详细说明")|服务器无法存储请求|
|**508**|[508 Loop Detected](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_508 "查看http状态码508的详细说明")|服务器因死循环而终止操作|
|**509**|[509 Bandwidth Limit Exceeded](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_509 "查看http状态码509的详细说明")|服务器带宽限制|
|**510**|[510 Not Extended](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_510 "查看http状态码510的详细说明")|获取资源策略未被满足|
|**511**|[511 Network Authentication Required](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_511 "查看http状态码511的详细说明")|需验证以许可连接|
|**599**|[599 Network Connect Timeout Error](https://github.com/CrayonL/AllHttpStatusCodes/blob/master/HTTPStatusCode/3xx_Redirection/Code_599 "查看http状态码599的详细说明")|网络连接超时|
