# alpine-go

Lightweight yarn docker image on alpine with golang installation on build

## Go Version

version: 1.16.6

## docker-compose.yml sample

```
version: "3.7"
services:
    app:
        build: .
        tty: true
        volumes:
            - ./app:/go/src/app
```
