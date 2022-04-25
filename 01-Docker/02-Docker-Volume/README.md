```
 108  docker volume ls
  109  docker volume create my-vol
  110  docker volume ls
  111  docker inspect my-vol
  112  ls -ltr /var/lib/docker/volumes/my-vol/_data
  113  docker run -it --name volume-test-1 -v my-vol:/var/www/html/app ubuntu:16.04
  114  docker ps
  115  ls -ltr /var/lib/docker/volumes/my-vol/_data
  116  docker ps
  117  docker kill volume-test-1
  118  docker rm volume-test-1
  119  docker ps -a
  120  docker volume ls
  121  ls -ltr /var/lib/docker/volumes/my-vol/_data
  122  cat  /var/lib/docker/volumes/my-vol/_data/abc.txt
  123  ls
  124  cd 01-Docker/
  125  ls
  126  mkdir 02-Docker-Volume
  127  cd 02-Docker-Volume/
```
