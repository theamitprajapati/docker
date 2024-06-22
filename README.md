# docker

## Create new Image 
sudo docker build -t imageName .

## Create Container
sudo docker run -it iamgeName 

## conatiner map with port 
docker sudo docker run -p 127.0.0.1:8080:80 730f988c36cb


## Map container with local volume
sudo docker run -it -v /home/amit/Desktop/R_AND_D/vedio/outputs:/home/app/vedios  vedio_transcoder

