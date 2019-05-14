# VulnerableWordpress
[![Build Status](https://img.shields.io/docker/cloud/build/l505/vulnerablewordpress.svg)](https://cloud.docker.com/repository/docker/l505/vulnerablewordpress/builds)
[![Docker Pulls](https://img.shields.io/docker/pulls/l505/vulnerablewordpress.svg)](https://hub.docker.com/r/l505/vulnerablewordpress)

# if already running
```
docker kill vulnerablewordpress
docker rm vulnerablewordpress
```

# build and run
```
docker build --rm -t wpscan/vulnerablewordpress .
docker run --name vulnerablewordpress -d -p 80:80 -p 3306:3306 wpscan/vulnerablewordpress
```

# Get a shell
```
docker exec -i -t vulnerablewordpress bash
```
