# UDACITY CLOUD DEVOPS CAPSTONE PROJECT

In this project I developed a CI/CD pipeline for micro services applications with blue/green deployment.

The Continuous Deployment includes:

* Pushing the built Docker container to the Docker repository.
* Deploying this Docker container to a Kubernetes cluster. AWS Kubernetes as a Service was used to implement this. AWS Cloudformation  was used to deploy the Kubernetes cluster.

* Jenkins was used to run these as an independent pipeline.

In this I have applied the skills and knowledge which were developed throughout the Cloud DevOps Nanodegree program. These include:

* Working in AWS
* Using Jenkins to implement Continuous Integration and Continuous Deployment
* Building pipelines
* Working with CloudFormation to deploy clusters(this could also be achieved using Ansible)
* Building Kubernetes clusters
* Building Docker containers in pipelines

Completing this project involves the following steps;

* Step 1: Propose and Scope the Project
* Step 2: Use Jenkins, and implement blue/green or rolling deployment.
* Step 3: Pick AWS Kubernetes as a Service, or build your own Kubernetes cluster.
* Step 4: Build your pipeline
* Step 5: Test your pipeline

## Prerequisites

* AWS account
* AWS CLI
* Jenkins with Blue Ocean, Docker and AWS plugins
* Docker
* tidy
* Eksctl
* Kubectl
* GitHub
* DockerHub
* Browser
* Internet

### Files and Folders

The following files and folders could be found in the github repositary for this project;

1. clusters-pipeline

* Jenkinsfile:  use to create and configure kubernetes cluster in AWS using EKS.;

1. deployment

* blue*controller.json: Blue pod replication controller
* blue*service.json: Blue service
* Dockerfile: use for building image of the application.
* green*controller.json: Green pod replication controller
* green*service.json: Creen service
* index.html:  index file of the website.
* Jenkinsfile: use to design the pipelines for all stages.

1. Project Screenshots

* This folders contains all the screen shots taking while implementing the pipelines.

## Author

👤 **John Pius**

* Github (https://github.com/john4pius)

* Linkedin (https://www.linkedin.com/in/john-pius-5447b353/)

* Twitter (@John4pius)

## Show your support

Give a ⭐️ if you like this project!
