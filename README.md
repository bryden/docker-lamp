# docker-lamp
This repository contains a basic dev-ops environment for docker.

##Requirements
You will need the following:

1. docker
2. composer
3. virtualbox

##Installation
```
git clone https://github.com/bryden/docker-lamp.git
cd docker-lamp
```

#How to use it
```
docker-machine start default
```

Windows users only:
```
eval $(docker-machine env)
```

All users..
```
docker-compose up -d
```
Visit 192.168.99.100 in your web browser. To add your website files, just paste them into the root directory (/docker-lamp/your-files here). To access phpMyAdmin, visit 192.168.99.100:8080.
