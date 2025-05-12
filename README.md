![Version](https://img.shields.io/badge/version-v1.0.0-blue.svg) ![Status](https://img.shields.io/badge/status-completed-green.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg)

# 📡HTTP Status Codes

### Description
This table lists the most common HTTP status codes used in APIs and web applications. They help developers understand the outcome of client-server interactions and diagnose issues more easily.

---

## ✅ Success (2xx)

| Code  | Status     | Description                                                   |
|-------|------------|---------------------------------------------------------------|
| 200 ✅ | OK         | The request was successful.                                   |
| 201 🎉 | Created    | A new resource was successfully created.                      |
| 204 💤 | No Content | The request was successful, but there is no content to return.|

---

## ❌ Client Errors (4xx)

| Code  | Status              | Description                                                        |
|-------|---------------------|--------------------------------------------------------------------|
| 400 ❌ | Bad Request         | The request was invalid or cannot be processed.                    |
| 401 🔒 | Unauthorized        | Authentication is required or has failed.                         |
| 403 ⛔ | Forbidden           | The request is valid, but access is forbidden.                     |
| 404 🕳️ | Not Found           | The requested resource could not be found.                         |
| 405 🙅 | Method Not Allowed  | The HTTP method is not allowed for the requested resource.         |

---

## 💥 Server Errors (5xx)

| Code  | Status                | Description                                                               |
|-------|------------------------|---------------------------------------------------------------------------|
| 500 💥 | Internal Server Error | The server encountered an unexpected condition.                           |
| 502 🚧 | Bad Gateway           | Received an invalid response from the upstream server.                    |
| 503 💤 | Service Unavailable   | The server is temporarily unavailable (overloaded or under maintenance). |
| 504 ⏳ | Gateway Timeout       | The upstream server failed to respond in time.                           |

---

### Clone the repository

```bash
git clone https://github.com/Hugolelis/statusHTTP.git
