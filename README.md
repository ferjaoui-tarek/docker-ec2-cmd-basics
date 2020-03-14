Prerequisite
OS should be 64 bit
Linux kernel ver 3.10 or greater

command to check
```
# uname -r
```

STEP 1 - Connect to Linux system

STEP 2 - Install DOCKER
```
# sudo yum -y update
# sudo yum install -y docker
```

docker
```
# docker --version
```

STEP 3 - start DOCKER
```
# sudo service docker start
# sudo usermod -a -G docker "ec2-user"
# docker info
```

To run hello-world image
```
# docker run hello-world
```

To get list of images present locally
```
# docker images
```

To get list of running containers
```
# docker ps
```

To get list of all containers
```
# docker ps -a .
```

STEP 4 - stop DOCKER
```
# sudo service docker stop
# uninstall DOCKER
# sudo yum remove docker
```

Basic
```
# docker version
# docker -v
# docker info
# docker --help
# docker login
```
————————————
Images
```
# docker images
# docker pull
# docker rmi
```
————————————
Containers
```
# docker ps
# docker run
# docker start
# docker stop
```
————————————
System
```
# docker stats
# docker system df
# docker system prune
```

cmd  iamges
```
# docker images --help
# docker pull image
# docker images
# docker images -q
# docker images -f “dangling=false”
# docker images -f “dangling=false” -q
```

```
# docker run image
```

delete image
```
# docker rmi image
# docker rmi -f image
```

```
# docker inspect
```

```
# docker history imageName
```
