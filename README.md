## Pre-requirements:
1. docker
2. maven

## Install redis server:
docker-compose -f src/main/docker/redis.yml up -d

## Start Redis-demo:
mvn clean package
mvn spring-boot:run

## Reference:
https://spring.io/guides/gs/messaging-redis/