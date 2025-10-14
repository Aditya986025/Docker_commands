# Docker_commands


1  apt update && apt install dockeer.io -y

2  docker
    
3  apt install docker.io -y


4  docker -v


5  docker images


6  docker ps


7  docker pull ubuntu


8  docker images


9  docker run -d nginx
   

10  docker ps
   11  docker images
   12  docker image ls
   13  ls
   14  docker mv 07ccdb aditya986025/first_hub
   15  docker tag 07ccdb aditya986025/first_hub:v1
   16  docker ps
   17  docker images
   18  docker login -u aditya986025
   19  docker push aditya986025/first_hub:v1
   20  docker tag 07ccdb aditya986025/first_hub:v2
   21  docker ps
   22  docker images
   23  docker push aditya986025/first_hub:v2
   24  apt install unzip -y
   25  aws ecr get-login-password --region eu-north-1 | docker login --username AWS --password-stdin 775525057193.dkr.ecr.eu-north-1.amazonaws.com
   26  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
   27  unzip awscliv2.zip
   28  sudo ./aws/install
   29  aws configure
   30  aws ecr get-login-password --region eu-north-1 | docker login --username AWS --password-stdin 775525057193.dkr.ecr.eu-north-1.amazonaws.com
   31  docker tag nginx:latest 775525057193.dkr.ecr.eu-north-1.amazonaws.com/aditya986025:latest
   32  docker push 775525057193.dkr.ecr.eu-north-1.amazonaws.com/aditya986025:latest
   33  history
   34  ps
   35  docker images
   36  docker ps
   37  docker image rm -f 07ccdb783875
   38  docker rm -f 07cc
   39  docker rmi 07ccdb783875
   40  docker rmi 97bed23a3497
   41  docker images
   42  docker rmi aditya986025/first_hub:v1
   43  docker ps
   44  docker rm -f c9
   45  docker ls
   46  docker ps
   47  docker rmi 07
   48  docker rmi nginx:latest aditya986025/first_hub:v1 aditya986025/first_hub:v2 775525057193.dkr.ecr.eu-north-1.amazonaws.com/aditya986025:latest
   49  docker ps
   50  docker images
   51  history
