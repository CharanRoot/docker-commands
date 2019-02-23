# docker-commands
docker-commands

Passing Aws credentials to docker 
docker run -v ${HOME}/.aws/credentials:/root/.aws/credentials:ro  ...
mount to root folder 

running commands inside docker 
docker exec -it <container_id_or_name> echo "Hello from container!"

docker running images 
docker run <image>
  
docker passing mounting files 
docker run -v ${HOME}/.aws/credentials:/root/.aws/credentials:ro  ...

docker passing environment variables
docker run  -e KEY=KEY1  -e KEY2=Key2<Image>
