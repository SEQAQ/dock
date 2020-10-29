# QAQ Backend Docker

Use `docker-compose` to set up backend dependencies.

## Getting Started

```sh
./init.sh
./update.sh
docker-compose up --build -d
```

To stop:

```sh
docker-compose down
```

To update:

```sh
git pull origin master
./update.sh
```

To run only mysql and backend:

```sh
docker-compose up -d mysql backend
```

## Configurations

Update `.env` files in [./secrets](./secrets/).
