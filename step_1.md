# From docker hub pull the images

- docker pull nginx

# List out the docker images
- docker images
# List out all running container
- docker ps
# To run images 
- docker run -dt -p 8090:80 nginx
# to stop container
- docker container stop container_name
# To check all container status
- docker ps -a
# to start container 
- docker start container_name
# To check network
-  netstat -ntlp
# To run images with user's provided name
- docker run --name=my_container -d -p 8090:80 nginx
# To get information about container
- docker inspect  container_name
# To stop all container
- docker container stop $(docker container ls -aq)
# To remove comtainer 
- docker container rm container_name
# To run new cmd in running container
- docker exec -it container_name "cmd"
- docker exec -it container_name bash -> and execute all cmd in container
# To get disk space in container
- docker system df -v
# To delete container on exit
- docker run -dt --rm container_name "cmd"


