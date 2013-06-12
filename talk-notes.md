# NoSQL

## 2-1: Brief History of NoSQL

* Carlo Strozzi's NoSQL database was simply a relational database without a SQL interface
* Eric Evans (Rackspace), Johan Oskarsson (Last.fm)
* 2009 landscape
  * Hypertable (inspired by Google BigTable)
  * HBase (inspired by Google BigTable, used by Facebook)
  * LinkedIn Voldemort
  * Amazon Dynamo
  * Facebook Cassandra (BigTable data model on Dynamo-like infrastructure
  * CouchDB (released in 2005, Apache incubator 2008)
* Apache Incubator is the entry path

## 2-3: Why Not Relational?

* relational databases were [first described by Edgar Codd (IBM)](http://dx.doi.org/10.1145%2F362384.362685) in 1970
* the modern web introduces a new scale for applications
  * concurrent users (requests per second)
  * volume of data (TB? PB?)
  * variety of formats
  * transformation and processing
* scale out
  * linear elastic scaling on commodity hardware
  * massive volumes hard to manage by single RDBMS
* information may be unstructured or have varying structures
* impedence issues
  * electrical engineering term
  * data too complex to be described by a two-dimensional grid of rows and columns
  * data type, structural, object-oriented, manipulative, transactional
* administration
* historical cruft
  * MySQL's utf8 support only encodes the first 3 bytes, not 4
    * utf8mb4 has the proper support
  * in Oracle, empty string is equivalent to a null
* 

## 2-4: Types of Non-Relational Databases

* column stores:
* graph databases: do not reuqire expensive join operations
  * good for graph-like queries like shortest path between nodes, community detection, etc.

## 2-5: Why NoSQL?

* handles Big Data challenges
  * automatic sharing of data
  * automatic replication of data
  * schema-less data
  * automatic scalability
  * multiple write nodes

## 3-2: REST

* Roy Fielding's 2000 doctoral dissertation
* constraints
  * client-server: separation of concerns; clear separation of user interface from data storage
  * stateless: communication must be stateless; each request from client to server must contain all information necessary and cannot take advantage of any stored context on the server
  * cache: data in a response must implicitly or explicitly labeled as cacheable or non-cacheable
  * uniform interface: implementations are decoupled from the services they provide; this is what most people know
  * layered system: architecture can be composed of hierarchical layers; each component cannot see beyond the immediate layer which they are interacting with
  * code-on-demand (optional): allows client functionality to be extended by downloading and exeuting code in the form of applets or scripts

## 3-3: RESTful APIs

## 4-2: Firebase

* 

* launched April 2009

##