---
layout: default
title: Api Gateway
parent: Architecture
nav_order: 1
---

# API Gateway
{: .fs-9 }

The API Gateway acts like a front door for applications to access data, logic and functionalities from all the microservices.
{: .fs-6 .fw-300 }

---

According to **RedHat**[^1], an *API gateway* is an API management tool that sits between a client and a collection of backend services.
An *API gateway* acts as a reverse proxy to accept all application programming interface (API) calls, aggregate the various services required to fulfill them, and return the appropriate result.

Most enterprise APIs are deployed via *API gateways*. It’s common for *API gateways* to handle common tasks that are used across a system of API services, such as user authentication, rate limiting, and statistics.

At its most basic, an API service accepts a remote request and returns a response. But real life is never that simple. Consider your various concerns when you host large-scale APIs.

*{address}/munity/api/v2*

| Method |     Rest     | Responses  |
| :----- | :----------- | :--------  |
|   GET  | /titles/{id} | ✅ 200 OK <br/> ❌ 404 Not found  |

{: .note }
> This section is still not completed.

[^1]: [Why use an API Gateway?](https://www.redhat.com/en/topics/api/what-does-an-api-gateway-do)