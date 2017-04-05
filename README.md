# docker-compose-transmission

Docker Compose File for [nemoalex/docker-transmission](https://hub.docker.com/r/nemoalex/docker-transmission/)

## How to use

1. Install [Docker](https://docs.docker.com/linux/step_one/)

2. Install [Docker Compose](https://docs.docker.com/compose/install/)

3. Clone the repository

  ```
  git clone https://github.com/NemoAlex/docker-compose-transmission.git
  cd docker-compose-transmission
  ```
4. Edit `docker-compose.yml`

5. Grab and run container

  ```
  docker-compose up -d
  ```

6. Edit settings file

Note: before editing, stop the container.

```
docker-compose stop
vim .config/settings.json
```

After editing, start container.

```
docker-compose start
```
