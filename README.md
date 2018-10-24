# Awesome Distributed Systems
A curated list of awesome distributed systems papers, libraries, software, middleware, books, etc.
Feel free to add your links!

## Table of Contents:  
 * [Consensus protocols](#consensus-protocols)  
 * [Queues](#queues)  
 * [Distributed databases](#distributed-databases)  
 * [NoSQL](#nosql)  
 * [Conflict-free replicated data type](#conflict-free-replicated-data-type)  
 * [Distributed filesystems](#distributed-filesystems)  
 * [Classes](#classes)  
 * [Books](#books)  
 * [Interviews](#interviews)  
 * [Links & articles](#links-and-articles)  
 * [Blogs](#blogs)  
 * [Videos](#videos)  
----

### Consensus protocols:
- [Paxos](https://en.wikipedia.org/wiki/Paxos_%28computer_science%29):
  - [Lessons Learned from Implementing Paxos](http://blog.willportnoy.com/2012/06/lessons-learned-from-paxos.html)
  - [Paxos made live: an engineering perspective](https://dl.acm.org/citation.cfm?id=1281103)
- [Raft](https://raft.github.io/)
- [Gossip Protocol](https://en.wikipedia.org/wiki/Gossip_protocol)
- [SERF](https://www.serf.io/)

#### Used By:
- [Zookeeper](https://zookeeper.apache.org) 
- [ETCD](https://github.com/coreos/etcd)

### Queues
- [Kafka](https://kafka.apache.org/)
- [RabbitMQ](https://www.rabbitmq.com)
  - [Introduction to RabbitMQ](https://www.slideshare.net/old_sound/pivotal-labs)
  - [Dissecting the rabbit: RabbitMQ Internal Architecture](https://www.slideshare.net/old_sound/dissecting-the-rabbit)


### Distributed databases:
- [Cassandra](https://en.wikipedia.org/wiki/Apache_Cassandra)
- [Dynamo](https://en.wikipedia.org/wiki/Dynamo_%28storage_system%29)
- [Riak](https://en.wikipedia.org/wiki/Riak)
- [Couchbase](https://en.wikipedia.org/wiki/Couchbase)
- [Data Access for Highly-Scalable Solutions: Using SQL, NoSQL, and Polyglot Persistence](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/dn271399(v%3dpandp.10))

### NoSQL
- [Couchbase](https://www.couchbase.com)
- [MongoDB](https://www.mongodb.com)

### Conflict-free replicated data type
- [Conflict-free replicated data type](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type) on Wikipedia
- [A Look at Conflict-Free Replicated Data Types (CRDT)](https://medium.com/@istanbul_techie/a-look-at-conflict-free-replicated-data-types-crdt-221a5f629e7e)
- [Operational transform](https://en.wikipedia.org/wiki/Operational_transformation)
- [Consistency levels for both read and writes](http://docs.datastax.com/en/cassandra/2.1/cassandra/dml/dml_config_consistency_c.html) in distributed databases like Cassandra
- CRDT provides an eventually consistent result so long as the data types available are used. Used by [Riak distributed database](http://basho.com/products/) and [presence in Phoenix](https://dockyard.com/blog/2016/03/25/what-makes-phoenix-presence-special-sneak-peek).

### Distributed filesystems
- [GlusterFS](http://www.gluster.org/)
- [Apache Hadoop HDFS](https://hortonworks.com/apache/hdfs/)
- [Ceph: A Linux petabyte-scale distributed file system](https://www.ibm.com/developerworks/library/l-ceph/index.html)
- [InterPlanetary File System (IPFS)](https://ipfs.io/)


## Classes: 
- [MIT CSAIL schedule](http://css.csail.mit.edu/6.824/2014/schedule.html)
- [Class materials for a distributed systems lecture series](https://github.com/aphyr/distsys-class)
- [Reliable Distributed Algorithms - Part 1](https://courses.edx.org/courses/course-v1:KTHx+ID2203.1x+3T_2017/course/)
- [MIT's Distributed Algorithms class](https://learning-modules.mit.edu/class/index.html?uuid=/course/6/fa15/6.852#info) by Lynch
  - [Supplementary Reading List](http://courses.csail.mit.edu/6.852/15/reading.html)
  - [Geambasu's Teaching](https://roxanageambasu.github.io/04-teaching/)

## Books

## Interviews
- [system-design-primer](https://github.com/donnemartin/system-design-primer)
- [system-design-interview](https://github.com/checkcheckzz/system-design-interview)
- [interactive-coding-challenges](https://github.com/donnemartin/interactive-coding-challenges)

## Links and articles:
- [Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)
- [Distributed systems theory for the distributed systems engineer](http://the-paper-trail.org/blog/distributed-systems-theory-for-the-distributed-systems-engineer/)
- [Programming Models for Distributed Computing](http://dist-prog-book.com/chapter/)
- [Jeff Dean's famous talk](https://static.googleusercontent.com/media/research.google.com/it//people/jeff/WSDM09-keynote.pdf)
- [Testing distributed systems](https://asatarin.github.io/testing-distributed-systems/)
- [Self-contained systems (alternative to microservices)](http://scs-architecture.org/)
- [Pease stop calling databases CP or AP](https://martin.kleppmann.com/2015/05/11/please-stop-calling-databases-cp-or-ap.html)
- [The quest for availability in the cloud](https://read.acloud.guru/the-quest-for-availability-771fa8a94a7c)
- [CAP Twelve Years Later: How the "Rules" Have Changed](https://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)

## Blogs:
- [All Things Distributed](https://www.allthingsdistributed.com/)

## Videos:
- [Inside Azure Datacenter Architecture with Mark Russinovich : Build 2018](https://www.youtube.com/watch?v=t3Vo37V9oU8)
- [Scaling Instagram Infrastructure](https://www.youtube.com/watch?v=hnpzNAPiC0E)
