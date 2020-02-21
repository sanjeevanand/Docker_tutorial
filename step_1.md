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
