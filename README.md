# Cloud-DevOps-Nanodegree-Capstone-Project
This is the capstone project of Cloud DevOps Nandegree Program. It demonstrates the ability to use AWS, Jenkins, Docker, Kubernetes, build a CI/CD Pipeline, deploy EKS Cluster as IaC.

## Instructions
##### Pipeline1 branch
It consists of the pipeline to create a EKS Cluster and creates the config file of the created cluster and adds to `/var/lib/jenkins/.kube/config`

##### Pipeline2 branch
It consists of the pipeline to do linting of HTML files. Dockerfile. It also builds the docker image and push it to the DockerHub and deploy the app in the created EKS cluster.

##### Master branch
It consists of the files related to both the pipelines and currently its doesn't get involved during Jenkins CI/CD build. It has the screenshots of all the stages of this project in order wise.
