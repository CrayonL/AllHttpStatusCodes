### [中文](https://github.com/CrayonL/AllHttpStatusCodes/edit/master/README.md) | English  
# 🌐 All HTTP 状态 Codes

Welcome 到 为： **HTTP 状态 代码 Notes Repository**!  
This repo is a structured reference for all HTTP status codes， organized 由 category with explanations， common use cases, 和 tips。  
Perfect for developers， learners, 和 anyone curious about how 为： web talks back。

---

## 📚 表格 of Contents

- [📖 Introduction](#-introduction)
- [🟢 1xx Informational Responses](#-1xx-informational-responses)
- [🟡 2xx Success](#-2xx-success)
- [🔵 3xx Redirection](#-3xx-redirection)
- [🟠 4xx Client Errors](#-4xx-client-errors)
- [🔴 5xx Server Errors](#-5xx-server-errors)
- [📌 引用 Links](#-reference-links)

---

## 📖 Introduction

HTTP status codes are standardized responses given 由 web servers。  
They indicate whether a request has been successfully completed， redirected， failed， 或 needs further action。

Each code is made up of **3 digits**, 和 为： first digit classifies 为： response category。

---

## 🟢 1xx Informational Responses

| 代码 | Meaning | Notes |
|------|---------|-------|
| 100  | Continue | 该 server received 为： initial part of 为： request. |
| 101  | Switching Protocols | 该 server is switching protocols as requested. |

---

## 🟡 2xx Success

| 代码 | Meaning | Notes |
|------|---------|-------|
| 200  | OK | Standard response for successful HTTP requests. |
| 201  | Created | Resource has been 创建 successfully. |

---

## 🔵 3xx Redirection

| 代码 | Meaning | Notes |
|------|---------|-------|
| 301  | Moved Permanently | Used for permanent URL redirection. |
| 302  | Found | Temporary redirection. |

---

## 🟠 4xx Client Errors

| 代码 | Meaning | Notes |
|------|---------|-------|
| 400  | Bad Request | 该 request cannot be fulfilled due 到 bad syntax. |
| 401  | Unauthorized | Authentication required. |
| 404  | Not Found | 该 requested resource could not be found. |

---

## 🔴 5xx Server Errors

| 代码 | Meaning | Notes |
|------|---------|-------|
| 500  | Internal Server Error | A generic server error. |
| 503  | Service Unavailable | The server is currently unavailable (e.g. overloaded). |

---

## 📌 Reference Links

- [MDN Web Docs - HTTP Status Codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- [RFC 9110 - HTTP Semantics](https://datatracker.ietf.org/doc/html/rfc9110)
- [IANA Status Code Registry](https://www.iana.org/assignments/http-status-codes/http-status-codes.xhtml)

---

🛠️ *Feel free to contribute more examples or explanations by opening a pull request or issue!*
