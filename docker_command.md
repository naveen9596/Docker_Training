```
    1  apt install docker.io
    6  sudo apt-get update
    7  sudo apt install docker.io
    8  systemctl status docker
    9  docker images
   10  docker ps
   11  docker pull httpd
   12  docker ps
   13  docker images
   14  docker run -itd -p "7070:80" httpd
   15  docker ps
   27  docker exec -it 1688 /bin/bash
   28  clear
   29  docker logs
   30  docker ps
--------------------------------------------------
   31  docker logs
   32  root@ip-172-30-3-244:~# docker logs
   33  docker logs 1688b1
   34  ps aux | grep httpd
   35  docker restart httpd
   36  docker restart 1688b1
--------------------------------------------------
   37  docker run -itd -p "7070:80" httpd
   38  clear
   39  docker ps
   40  docker pull nginx
   41  docker images
   42  docker run -d -p "7070:80" nginx
   43  docker run -d -p 80:80 --name my_nginx nginx
   44  docker ps
   45  docker images
   46  docker logs my_nginx
   47  clear
   48  docker login
   49  docker images
   50  docker tag httpd:latest myhttpd/httpd:V1
   51  docker Images
   52  docker ps
   53  docker images
   54  docker push myhttpd/httpd:V1
-----------------------------------------------
   63  docker push naveen9898/nginx:latest
   64  clear
-----------------------------------------------
   65  docker push myhttpd/httpd:V1
   66  docker tag myhttpd/httpd:V1 naveen9898/httpd:V1
   67  docker push naveen9898/httpd:V1
   68  exit
   69  history
```
