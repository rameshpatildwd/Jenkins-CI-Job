#CI (Continuous Integration) Part:

#Code Fetch and Jenkinsfile Execution:

##Jenkins fetches the latest code from the GitHub repository.
#The repository contains a Jenkinsfile that defines the CI/CD pipeline steps.
#Build and Quality Testing:

##Jenkins initiates the build process using Maven.
#Comprehensive quality checks are performed using SonarQube to ensure code quality.
#Docker Image Creation:

##Jenkins uses the Dockerfile to build a Docker image.
#This Docker image encapsulates the application artifacts.
#Docker Image Publishing:

##The Docker image is securely pushed to DockerHub, a container registry.

##Triggering CD Job:

#Once the Docker image is successfully published, a secure Jenkins API token triggers the Continuous Deployment (CD) job.
