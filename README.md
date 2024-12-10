# Build Project Using Maven

mvn clean package


# Create Docker Image

docker build -t mylandmarktech/springapp .

#run application to test with docker 

docker run --name <ContainerName> -d -p <imageName:tag> 


# List Docker Containers in all states 

docker ps -a

