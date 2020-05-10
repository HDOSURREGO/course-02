CLOUD DEVELOPMENT USING AWS

This course is part of the  Cloud Developer Nanodegree from Udacity, and covers Microservices using Docker
and Kubernetes.

The application Udagram allows users to register, login and upload a picture and a caption to the server.
The application was containerized keeping in mind that the User module could grow separate from the Feed
process. A proxy server was added to route the calls from the frontend (developed in Ionic), and a backend
developed in Node.js was the one in charge of the calls to the components used in Amazon Web Services.
AWS services used were: S3, RDS, EC2, Elastic Beanstalk, Elastic Kubernetes Service (EKS).  Other
technologies used:  Docker, Kubernetes, GitHub, DockerHub, Travis-CI.