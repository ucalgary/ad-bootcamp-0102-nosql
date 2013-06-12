---
layout: default
title: "Document-Oriented Databases"
published: true
classes:
 - slide
data:
  x: 2000
  y: 0

---

* store **documents** addressed by **keys**
* documents might be encoded in JSON, BSON, XML, YAML, or could possibly be binary formats like PDF, Microsoft Word, Microsoft Excel, etc.
* JSON encoding with a RESTful HTTP API is popular
	* JSON and REST are easy to work with in the context of a browser
	* JSON maps directly to primitive data types and collections
	* REST **is** HTTP, so caching, load-balancing, and other techniques easily apply to the database
