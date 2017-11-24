# Setup
Open a terminal and use the following commands:

Clone the repo and move into its directory:
```
git clone https://github.com/weirdwater/dksql
cd dksql
```

Start the container using [docker-compose](https://docs.docker.com/compose/overview/):
```
sudo docker-compose up -d
```

`docker-compose` will automatically use the docker-compose.yml file when run in the same directory.

# Stopping

If no project name is provided Docker will name the compose the same as the directory, so in this case `dksql`.

```
sudo docker-compose stop dksql
sudo docker-compose rm dksql
```
