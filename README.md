# Docker activity

This repository is from an activity of the Software Engineering MBA .
Team: Rodrigo Bighetti, Gian Matheus and Estevão Fekete

## Installation

1 - Clone this repository. [Github/atividade-03](https://github.com/GMatheusFP/atividade-3-docker.git)\
2 - Make sure you have [Docker](https://www.docker.com/) installed \
3 - To make containers up run "docker-compose up -d" \

```bash
git clone https://github.com/GMatheusFP/atividade-3-docker.git
```

```bash
cd atividade-3-docker
docker-compose up -d
```

## How do I connect to the database?

In your Workbench or other DBMS, put the following configuration: \
Host: localhost \
Port: 3306 \
Database: mysql \
User: dev \
Password: dev

### If you receive any error message to connect, follow steps bellow:

1 - Edit your Connection \
2 - Go to driver properties \
3 - Add 2 new properties

- useSSL - false
- allowPublicKeyRetrieval - true

4 - Try again
