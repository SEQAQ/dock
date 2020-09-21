# QAQ Backend Docker

Use `docker-compose` to set up backend dependencies.

## Getting Started

```sh
git submodule update
./init.sh
./update.sh
docker-compose up --build -d
```

To stop:

```sh
docker-compose stop
```

To update:

```sh
git pull origin master
./update.sh
```
