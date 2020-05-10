CLOUD DEVELOPMENT USING AWS

This course is part of the course Cloud Development from Udacity, and covers Microservices using Docker
and deployment using Kubernetes.

The application Udagram allows users to register, log in and upload a picture and a caption to the server.
The application was containerized keeping in mind that the User module could grow separate from the Feed
process. A proxy server was added to route the calls from the frontend (developed in Ionic), and a backend
deloped in Node.js was the one in charge of the calls to the components used in Amazon Web Services.
AWS services used were: S3, RDS, EC2, Elastic Beanstalk, Elastic Kubernetes Service (EKS).  Other
technologies used:  Docker, Kubernetes, GitHub, DockerHub, Travis-CI.