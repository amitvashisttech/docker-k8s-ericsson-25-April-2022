```
51  cd 01-Docker/00-Setup/
   52  ls
   53  sh install-docker.sh
   54  docker version
   55  docker run busybox echo "Hello World"
   56  docker run busybox echo "Hello World - 2"
   57  docker images
   58  docker pull ubuntu:16.04
   59  docker images
   60  docker pull ubuntu
   61  docker images
   62  docker run -it ubuntu cat /etc/os-release
   63  docker run -it ubuntu:16.04 cat /etc/os-release
   64  docker run -it ubuntu:16.04
   65  docker ps
   66  docker ps -a
   67  docker run -it --name test-1 ubuntu:16.04
   68  docker ps
   69  docker ps -a
   70  docker start test-1
   71  docker ps
   72  docker attach test-1
   73  docker ps
   74  docker ps -a
   75  docker rm  $(docker ps -qa)
   76  docker ps
```
