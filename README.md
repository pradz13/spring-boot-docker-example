Build the docker image : docker build -t spring-boot-docker-example.jar .
Show the docker images : docker image ls
Run docker image : docker run -p 9090:8080 spring-boot-docker-example.jar (First post is conatiner port, 2nd port is local port)
Login to dockerhub : docker login(provide your user name and password)
Add a tag : docker tag spring-boot-docker-example.jar nagpradipta1985/spring-boot-docker-example.jar
Push to dockerhub : docker push nagpradipta1985/spring-boot-docker-example.jar
Pull from dockerhub : docker pull nagpradipta1985/spring-boot-docker-example.jar
Push a new tag to an existing repository : docker push nagpradipta1985/spring-boot-docker-example.jar:tagname
