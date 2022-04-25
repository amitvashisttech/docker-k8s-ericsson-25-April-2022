```
 184  docker ps
  185  docker run -d --name test-web-server-1 nginx
  186  docker ps
  187  docker run -d --name test-1 ubuntu:16.04
  188  docker ps
  189  docker ps -a
  190  docker run -itd --name test-2 ubuntu:16.04
  191  docker ps
  192  ls
  193  docker ps
  194  docker inspect test-web-server-1
  195  docker network ls
  196  docker network inspect 2e99aa235c8b
  197  ip addr
  198  curl 172.17.0.2
  199  curl -vv 172.17.0.2
  200  curl 172.17.0.2
  201  ip addr
  202  curl -vvv 172.31.0.101:80
  203  curl -vvv localhost:80
  204  curl 172.17.0.2
  205  netstat -tulnp
  206  ip addr
  207  ls
  208  netstat -tulnp
  209  docker ps
  210  docker run -d --name test-web-server-2 -p 8080:80 nginx
  211  docker ps
  212  netstat -tulnp
  213  systemctl status docker
  214  docker ps
  215  docker inspect test-web-server-2
  216  docker ps
  217  docker run -d --name test-web-server-3 -p 8080:80 nginx
  218  docker run -d --name test-web-server-4 -p 8081:80 nginx
  219  docker run -d --name test-web-server-5 -p 8082:80 nginx
  220  docker ps
  221  docker run -d --name test-web-server-6 80 nginx
  222  docker run -d --name test-web-server-6  nginx
  223  docker ps
  224  docker run -d --name test-web-server-7 -P nginx
  225  docker ps
  226  docker run -d --name my-web -P amitvashist7/mypython-webapp-18-oct-2021:v2
  227  docker ps
  228  netstat -tulnp
  229  systemctl status docker
  230  docker run -d --name my-web-2 -P amitvashist7/mypython-webapp-18-oct-2021:v2
  231  docker run -d --name my-web-3 -P amitvashist7/mypython-webapp-18-oct-2021:v2
  232  docker ps
```
