# Refactor Udagram app into Microservices and Deploy

Developed an **AWS Cloud** based Instagram application as part of the Udacity Cloud Engineering Nanodegree program. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice. Following are the services involved in this project:
“user” - allows users to register and log into a web client,
“feed” - allows users to post photos, and process photos using image filtering
“frontend” - acts as an interface between the user and the backend-services
"reverseproxy" - For resolving multiple services running on same port in separate containers

The project is based on the Microservice Architecture with the following components - 
The RestAPI Feed Backend, a Node-Express feed microservice.
The RestAPI User Backend, a Node-Express user microservice.
The Simple Frontend - A basic Ionic client web application which consumes the RestAPI Backend.
Nginx as a reverse-proxy server, when different backend services are running on the same port, then a reverse proxy server directs client requests to the appropriate backend server and retrieves resources on behalf of the client.

Run the command `ionic serve` for the Frontend application and `npm run dev` for the node-express microservices

## **Technologies used -**

The project Front End was developed in **Ionic Cli** and backend in **Nodejs**.
The database **PostgreSQL** instance was on **AWS RDS** and the **Postbird tool** have been used to interact remotely with the database. 
Additionally, an **S3 filestore** bucket was created in AWS to store the files. 
The project used the **Kubernetes cluster - kubectl** was used to pull images from DockerHub and deploy the docker containerized images in **AWS Elastic Kubernetes Service. (EKS)**. 
**TravisCI** was used as the continuous deployment tool to continuously deploy the features and functionalities in **Amazon Elastic Kubernetes Services - AWS EKS**. 

## **GitHub Repo** - 

https://github.com/bhaumikovshek/Udacity-Refactor-Udagram-in-Microservices-and-Deploy.git




