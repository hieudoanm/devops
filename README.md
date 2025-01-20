# DevOps

## Table of Content

- [DevOps](#devops)
  - [Table of Content](#table-of-content)
  - [Operating Systems](#operating-systems)
  - [Docker](#docker)
  - [Database](#database)
  - [Hosting](#hosting)
    - [Serverless](#serverless)
    - [Platform as a Service (P.a.a.S)](#platform-as-a-service-paas)
  - [API](#api)
    - [AI](#ai)

## Operating Systems

| No  | Device  | Group | Name                            | Maintainer |
| --- | ------- | ----- | ------------------------------- | ---------- |
| 1   | Desktop |       | Windows                         | Microsoft  |
| 2   | Desktop |       | macOS                           | Apple      |
| 3   | Desktop |       | Chrome OS                       | Google     |
| 4   | Desktop | Linux | Ubuntu                          |            |
| 5   | Desktop | Linux | Debian                          |            |
| 6   | Desktop | Linux | Kali                            |            |
| 7   | Desktop | Linux | Red Hat Enterprise Linux (RHEL) |            |
| 8   | Desktop | Linux | Fedora                          |            |
| 9   | Desktop | Linux | Arch                            |            |
| 10  | Desktop | Linux | Mint                            |            |
| 11  | Tablet  |       | iPadOS                          | Apple      |
| 12  | Mobile  |       | Android                         | Google     |
| 13  | Mobile  |       | iOS                             | Apple      |

## Docker

| Type    | Category | [Docker][docker]          |
| ------- | -------- | ------------------------- |
| OS      | Linux    | [Alpine][docker-alpine]   |
| OS      | Linux    | [Ubuntu][docker-ubuntu]   |
| Runtime | Golang   | [Golang][docker-golang]   |
| Runtime | Java     | [OpenJDK][docker-openjdk] |
| Runtime | Node.js  | [Node][docker-node]       |
| Runtime | Python   | [Python][docker-python]   |
| Server  |          | [nginx][docker-nginx]     |

## Database

| Paradigm          | Name                                                  | [Docker][docker]               | Maintainer       |
| ----------------- | ----------------------------------------------------- | ------------------------------ | ---------------- |
| Key-Value         | [Memcached](https://memcached.org/)                   | [Docker][docker-memcached]     |                  |
| Key-Value         | [Redis](https://redis.io/)                            | [Docker][docker-redis]         |                  |
| Wide Column       | [Cassandra](https://cassandra.apache.org/)            | [Docker][docker-cassandra]     | [Apache][apache] |
| Document Oriented | [CouchDB](https://couchdb.apache.org/)                | [Docker][docker-couchdb]       | [Apache][apache] |
| Document Oriented | [MongoDB](https://www.mongodb.com/)                   | [Docker][docker-mongo]         |                  |
| Relational        | [CockroachDB](https://www.cockroachlabs.com/)         | [Docker][docker-cockroach]     |                  |
| Relational        | [MySQL](https://www.mysql.com/)                       | [Docker][docker-mysql]         |                  |
| Relational        | [PostgreSQL](https://www.postgresql.org/)             | [Docker][docker-postgres]      |                  |
| Graph             | [Dgraph](https://dgraph.io/)                          | [Docker][docker-dgraph]        |                  |
| Graph             | [Neo4j](https://neo4j.com/)                           | [Docker][docker-neo4j]         |                  |
| Search Engine     | [ElasticSearch](https://www.elastic.co/elasticsearch) | [Docker][docker-elasticsearch] |                  |
| Search Engine     | [Solr](https://solr.apache.org/)                      | [Docker][docker-solr]          | [Apache][apache] |
| Multi-Model       | [Fauna](https://fauna.com/)                           | [Docker][docker-fauna]         |                  |

## Hosting

### Serverless

- [Vercel](https://vercel.com/)

### Platform as a Service (P.a.a.S)

- [Render](https://render.com/)

## API

### AI

- [HuggingFace Serverless Inference API](https://huggingface.co/docs/api-inference/index)

[apache]: https://apache.org/
[docker]: https://www.docker.com/
[docker-alpine]: https://hub.docker.com/_/alpine
[docker-golang]: https://hub.docker.com/_/golang/
[docker-node]: https://hub.docker.com/_/node/
[docker-nginx]: https://hub.docker.com/_/nginx
[docker-openjdk]: https://hub.docker.com/_/openjdk
[docker-python]: https://hub.docker.com/_/python/
[docker-ubuntu]: https://hub.docker.com/_/ubuntu/
[docker-cassandra]: https://hub.docker.com/_/cassandra
[docker-cockroach]: https://hub.docker.com/r/cockroachdb/cockroach
[docker-couchdb]: https://hub.docker.com/_/couchdb
[docker-dgraph]: https://hub.docker.com/r/dgraph/dgraph
[docker-elasticsearch]: https://hub.docker.com/_/elasticsearch
[docker-fauna]: https://hub.docker.com/r/fauna/faunadb
[docker-memcached]: https://hub.docker.com/_/memcached
[docker-mongo]: https://hub.docker.com/_/mongo
[docker-mysql]: https://hub.docker.com/_/mysql
[docker-neo4j]: https://hub.docker.com/_/neo4j
[docker-postgres]: https://hub.docker.com/_/postgres
[docker-redis]: https://hub.docker.com/_/redis/
[docker-solr]: https://hub.docker.com/_/solr
