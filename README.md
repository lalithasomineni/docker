# docker
learning docker
 
 
 
 - dockeer packs our code in containers and helps us to run in different environments easilyy
 
 # commands
 - sudo docker version //check the presence of docker(version and all)
 - sudo docker info //check the containers and images in your docker hub
 - sudo docker container run -it(interactive) -p 80:80(default port for (nginx) nginx // create controller
 - docker container ls //list of all  running containers
 - docker container ls -a //all containers
 - docker container rm <first3lettersin the id of container>
 - docker container run -d(detached) 40:80 --name <name> nginx //create container
 - docker container run -d 8081:80 --name <name> httpd //run pache
 - docker container stop <name> //stops the container
 - docker container rm <name> -f //removes a running container
