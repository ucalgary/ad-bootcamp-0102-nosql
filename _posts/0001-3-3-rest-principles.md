---
layout: default
title: "REST Principles in HTTP"
published: true
classes:
 - slide
data:
  x: 2000
  y: 1600

---

* resources are identified by global identifiers (URI)
* components of the network communicate using a standardized interface (HTTP)
* components exchange representations of resources
* any number of connectors (clients, servers, caches, tunnels) can mediate the request, but cannot see past its own request
* applications do need to understand the representation returned (HTTP accepts header)