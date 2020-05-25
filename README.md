# Ghost Blog Container Setup

## This is just a test bed for understanding compose, containers, etc. This should not be used for production

Version 1.26.2

Start to finish

1. `git clone https://github.com/3bars/ghostlab.git`

2. `cd ghostcontainers`

3. `docker-compose -p "ghost-platform" up -d`

4.  browse to localhost:8080 in your favorite browser

5. `docker-compose -p ghost-platform stop`

Optional

6. `sudo curl -L https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose`

7. `sudo chmod +x /usr/local/bin/docker-compose`


## Things to do

Update to the latest version of Ghost
