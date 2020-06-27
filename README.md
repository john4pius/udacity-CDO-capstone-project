# UDACITY CLOUD DEVOPS CAPSTONE PROJECT

In this project i have develop a CI/CD pipeline for micro services applications with blue/green deployment. You will also develop your Continuous Integration steps as you see fit, but must at least include typographical checking (aka “linting”).

I have set up Continuous Deployment, which will include:

* Pushing the built Docker container(s) to the Docker repository.
* Deploying these Docker container to a Kubernetes cluster. I used AWS Kubernetes as a Service. I have used Cloudformation to deploy the Kubernetes cluster. 
*Jenkins was used to run these as an independent pipeline.

In this project I have applied the skills and knowledge which were developed throughout the Cloud DevOps Nanodegree program. These include:

* Working in AWS
* Using Jenkins to implement Continuous Integration and Continuous Deployment
* Building pipelines
* Working with CloudFormation to deploy clusters(this could also be achieved using Ansible)
* Building Kubernetes clusters
* Building Docker containers in pipelines


Completing this project involves the following steps;
- Step 1: Propose and Scope the Project
- Step 2: Use Jenkins, and implement blue/green or rolling deployment.
- Step 3: Pick AWS Kubernetes as a Service, or build your own Kubernetes cluster.
- Step 4: Build your pipeline
- Step 5: Test your pipeline


#### Prerequisites

- AWS account
- AWS CLI
- Jenkins with Blue Ocean, Docker and AWS plugins
- Docker
- tidy
- Eksctl
- Kubectl
- GitHub
- DockerHub
- Browser
- Internet


#### Files and Folders
the following files and folders could be found in the github repositary for this project;

1. clusters-pipeline
- Jenkinsfile:  use to create and configure kubernetes cluster in AWS using EKS

2. deployment
- blue-controller.json: Blue pod replication controller
- blue-service.json: Blue service
- Dockerfile: use for building image of the application.
- green-controller.json: Green pod replication controller
- green-service.json: Creen service
- index.html:  index file of the website.
- Jenkinsfile: use to design the pipelines for all stages.

3. Project Screenshots
This folders contains all the screen shots taking while implementing the pipelines.


## Author

👤 **John Pius**

- Github (https://github.com/john4pius)
- Linkedin (https://www.linkedin.com/in/john-pius-5447b353/)
- Twitter (@John4pius)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check them https://github.com/Ahmed-Benj/mint-sign-up-page/issues.

## Show your support

Give a ⭐️ if you like this project!
