# device-app-backend <!-- omit in toc -->

**Table of Contents**

- [Prerequisites](#prerequisites)
  - [Dev dependencies](#dev-dependencies)
- [Docker compose](#docker-compose)
    - [Build](#build)
    - [Start](#start)
- [Running the project](#running-the-project)
  

## Prerequisites

### Dev dependencies

- Go 1.13
- Make
- Git
- Docker 19.x

## Docker compose

### Build

```bash
### for windows use

$ docker-compose -f store-api-dev/docker-compose.yml build 
```

### Start

```bash
### for windows use

$ docker-compose -f store-api-dev/docker-compose.yml up -d
```

## Running the project
```bash
$ go run main.go
```

