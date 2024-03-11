# react-docker
Deploy in docker with Reactjs

## npx create-react-app  dockerapp

## cd dockerapp 

## sudo docker build . 

## sudo docker image ls

## sudo docker build -t dockerapp/latest   //to give some tag name to my docker file

## sudo docker run dockerapp/latest   //to run a container

## sudo docker container ls            //to check the container id.

## sudo docker run -p 5000:3000 globalapp/latest    //it means whatever traffic coming to port 5000 will be ## directed to port 3000

## sudo docker run redis             //to install redis database

