# All in one CodeDepot container

## versions

* alpine linux 3.6
* PostgreSQL 9.6.8
* Python 2.7.14
* openjdk8
* apache2 2.4
* tomcat 8.5
* openssh 7.5p1
* git 2.13.5
* CodeDepot
  https://github.com/CodedepotOSS/CodeDepot

## Quick Start

```bash
docker run --name codedepot -d \
  -p 80:80 \
  -v PostgresDataVolmue:/pgdata \
  -v CodeDepotDataVolume:/data \
  codedepot-docker
```