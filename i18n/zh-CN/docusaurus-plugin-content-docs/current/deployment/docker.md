---
title: Docker 部署
sidebar_position: 2
---

通过Docker Compose部署InLong, 这种部署方式只适用于开发调试，不适用于生产环境.

准备条件:
- [Docker](https://docs.docker.com/engine/install/) 19.03.1+
- Docker Compose 1.29.2+

## 编译
可以参考[如何编译](quick_start/how_to_build.md).

## 部署
启动所有组件：
```
cd docker/docker-compose
docker-compose up -d
```

## 使用
当所有容器都成功启动后，可以访问`http://localhost`，并使用以下默认账号登录:
```
User: admin
Password: inlong
```

## 销毁
```
docker-compose down
```