# OpenBMP docker files
Docker files for OpenBMP.

(Prerequisite) Platform Docker Install
--------------------------------------

> Ignore this step if you already have a current docker install

> ####NOTE
> You should use the latest docker version, documented in this section.

Follow the [Docker Install Instructions](http://docs.docker.com/installation/) for your distro/platform. 




Install OpenBMP using Docker
----------------------------
Each docker file contains a readme file, see below:

* [All-In-One](aio/README.md)
* [Collector](collector/README.md)
* [Kafka](kafka/README.md)
* [PostgreSQL](postgres/README.md)
* [MySQL](mysql/README.md)

> **openbmp/ui** is archived. Use [obmp-grafana](https://github.com/OpenBMP/obmp-grafana) instead.


Install OpenBMP using docker-compose
----------------------------
As alternative to [All In One](aio/README.md), docker image Collector, Kafka and Mysql can be started up using [docker-compose](https://docs.docker.com/compose/install/)

```
docker-compose up
```
