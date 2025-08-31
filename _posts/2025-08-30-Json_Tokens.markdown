---
layout: post
title: "Json Web Tokens"
date: 2025-08-2230
categories: tech
---

JSON Web Tokens are a URL safe way of authentication and authorization for REST APIs. The claims are enconded as JSON object which is great for public/private key pairs. Web tokens can be stateless which are never saved in server memory.

Typically JSON encryption and authorization will be verified from the server and then passed back to the client. Header algorithms are used ot generate the signature. Payloads contain the set of claims.
