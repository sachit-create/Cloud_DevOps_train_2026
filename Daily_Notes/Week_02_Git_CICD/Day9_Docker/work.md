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
