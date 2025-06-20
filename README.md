### 中文 | [英文](https://github.com/CrayonL/AllHttpStatusCodes/edit/master/README-en_us.md) 

# 🌐 全部 HTTP 状态码笔记

欢迎来到 **HTTP 状态码笔记仓库**！

这个仓库整理了所有 HTTP 状态码的分类、含义、使用场景以及开发小贴士。  
适合开发者、学习者，或任何对 Web 通信感兴趣的人查阅。

---

## 📚 目录

- [📖 简介](#-简介)
- [🟢 1xx 信息响应](#-1xx-信息响应)
- [🟡 2xx 成功响应](#-2xx-成功响应)
- [🔵 3xx 重定向](#-3xx-重定向)
- [🟠 4xx 客户端错误](#-4xx-客户端错误)
- [🔴 5xx 服务端错误](#-5xx-服务端错误)
- [📌 参考资料](#-参考资料)

---

## 📖 简介

HTTP 状态码是 Web 服务端返回的标准响应，  
用于表示请求的处理结果，比如是否成功、是否出错、是否需要跳转等。

状态码由 **三位数字**组成，第一位数字表示响应的类别：

- `1xx`：信息类（正在处理）
- `2xx`：成功类（处理完成）
- `3xx`：重定向类（需要进一步操作）
- `4xx`：客户端错误（请求有问题）
- `5xx`：服务端错误（服务器出问题了）

---

## 🟢 1xx 信息响应

| 状态码 | 含义 | 说明 |
|--------|------|------|
| 100    | Continue（继续） | 请求已收到，继续发送剩余部分 |
| 101    | Switching Protocols（切换协议） | 服务器同意切换协议 |

---

## 🟡 2xx 成功响应

| 状态码 | 含义 | 说明 |
|--------|------|------|
| 200    | OK（成功） | 请求成功 |
| 201    | Created（已创建） | 请求成功并创建了资源 |

---

## 🔵 3xx 重定向

| 状态码 | 含义 | 说明 |
|--------|------|------|
| 301    | Moved Permanently（永久重定向） | 资源已永久移动到新位置 |
| 302    | Found（临时重定向） | 暂时从不同 URI 响应请求 |

---

## 🟠 4xx 客户端错误

| 状态码 | 含义 | 说明 |
|--------|------|------|
| 400    | Bad Request（错误请求） | 请求语法错误 |
| 401    | Unauthorized（未授权） | 需要认证才能访问 |
| 404    | Not Found（未找到） | 请求的资源不存在 |

---

## 🔴 5xx 服务端错误

| 状态码 | 含义 | 说明 |
|--------|------|------|
| 500    | Internal Server Error（服务器内部错误） | 服务器处理失败 |
| 503    | Service Unavailable（服务不可用） | 服务器暂时过载或维护中 |

---

## 📌 参考资料

- [MDN 文档 - HTTP 状态码](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Status)
- [RFC 9110 - HTTP 语义](https://datatracker.ietf.org/doc/html/rfc9110)
- [IANA 状态码注册表](https://www.iana.org/assignments/http-status-codes/http-status-codes.xhtml)

---

🛠️ **欢迎贡献更多示例或说明，可以提交 PR 或发起 Issue！**
