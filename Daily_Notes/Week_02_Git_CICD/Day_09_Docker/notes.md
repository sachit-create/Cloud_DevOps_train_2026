# Today's Work

- Creating Instatnce
- Dowloaded a docker image
- then insatlled a docker image `postgre sql`
- thnen create a instance of it and run it
- after that insatll another httpd server
- create  folder
- then create a docker file : `Dockerfile` with
  FORM httpd:2.4
- COPY ./public-html/ /usr/local/apache2/htdocs/
- then create a folder and add a index.html file in it with content
- after that `sudo docker exec - it <0ce4f3804d61> /bin/bash`
- then build and after that run the instance.
- then go to loacal host 8080 and find index.htm file there.


## 1411  sudo doecker ps

 1412  sudo docker ps
 1413  sudo docker run -d -it --rm --user www-data -e
 1414  sudo docker run -d -it --rm --user www-data-e
 1415  cls
 1416  sudo docker ps
 1417  ls
 1418  cat Dockerfile
 1419  sudo docker build -t apache-site .
 1420  sudo docker run -d -p 8080:80 --name apache_container apache-site
 1421  wget loaclhost:8080
 1422  cls
 1423  ls
 1424  cls
 1425  ls
 1426  sudo docker ps
 1427  cls
 1428  sudo docker ps
 1429  history 10
 1430  history 20
