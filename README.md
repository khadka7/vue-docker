# vue.js with docker

## Build and preview the docs locally

On your local machine, clone this repo:

```bash
git clone https://github.com/khadka7/vue-docker.git
cd vue-docker
```

Then build and run the documentation with [Docker Compose](https://docs.docker.com/compose/)

```bash
docker-compose up -d --build
```

> Docker Compose is included with [Docker Desktop](https://docs.docker.com/desktop/).
> If you don't have Docker Compose installed, [follow these installation instructions](https://docs.docker.com/compose/install/).

Once the container is built and running, visit [http://localhost:8081](http://localhost:8081)
in your web browser to view the docs.

To stop the staging container, use the `docker-compose down` command:

```bash
docker-compose down
```

To start the staging container again, use the `docker-compose up -d` command:

```bash
docker-compose up -d
```
