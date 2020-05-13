**Refactor Udagram app into Microservices and Deploy**

This is the project submission for Udacity Nano Degree for the project Refactor Udagram app into Microservices and Deploy. In this project a monolith application is converted to MicroServices and Deployed with the help of Kubernetes in AWS Cloud. 

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.
###GITHUB Repo :

https://github.com/bhaumikovshek/Udacity-Refactor-Udagram-in-Microservices-and-Deploy.git



###Travis CI

The project is integrated with Travis CI and which helps in automatically building the project whenever a new build is pushed to git repository


###Running the Application Locally

In order to run the application locally download the following Docker Images - 

bhaumikovshek/reverseproxy       (a Node-Express user microservice.)
bhaumikovshek/udacity-frontend    (A basic Ionic client web application which consumes the RestAPI Backend. )
bhaukmikovshek/udacity-c3-restapi-feed   (a Node-Express user microservice.)
bhaumikovshek/udacity-restapi-user       (a Node-Express user microservice.)


Run the command `ionic serve` for the Frontend application and `npm run dev` for the node-express microservices


###Deploying the application in AWS

the project can also be deployed to any cloud infrastructure in a Kubernetes cluster. 



