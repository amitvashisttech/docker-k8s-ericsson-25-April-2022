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

```
140  docker volumes
  141  docker volume ls
  142  docker volume rm my-vol
  143  docker run -it --name volume-test-2 -v /var/www/html/app ubuntu:16.04
  144  docker ps
  145  docker volume ls
  146  docker volume inspect 93ae921c8d605004928f32cc504f1e1486d03e6fe3765a7b790035401830bc2a
  147  ls -ltr "/var/lib/docker/volumes/93ae921c8d605004928f32cc504f1e1486d03e6fe3765a7b790035401830bc2a/_data"
  148  ls -ltr /var/lib/docker/volumes/93ae921c8d605004928f32cc504f1e1486d03e6fe3765a7b790035401830bc2a/_data/Hello.txt
  149  cat /var/lib/docker/volumes/93ae921c8d605004928f32cc504f1e1486d03e6fe3765a7b790035401830bc2a/_data/Hello.txt
  150  docker ps
  151  docker inspect volume-test-2
  152  ls
  153  cd
  154  ls
  155  docker ps
  156  docker kill volume-test-2
  157  docker volumes ls
  158  docker volume ls
  159  docker volume ls -q
  160  docker volune rm $(docker volume ls -q)
  161  docker volume rm $(docker volume ls -q)
  162  docker ps
  163  docker ps -a
  164  docker rm  volume-test-2
  165  docker ps -a
  166  docker volume rm $(docker volume ls -q)

```
