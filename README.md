# Summary of project 14


Project 14. This is a full stack deployment of the vprofile java app ( frontend tomcat, memcached, rabbitmq and   backend mysql) onto a k8s cluster created with kops. This is meant to be a production grade roll out of the   **containerized** version of the vprofile java app onto k8s. Use EC2 instance on AWS2 with kubectl, aws cli,kops   
installed/IAM  


# Detail on the implementation:

## First get the k8s yaml files from the vprofile-project (branch kube-app branch)

## Getting kops up using the EC2 instance

The EC2 instance has to have aws cli and kops installed as well as kubectl.  
ubuntu@ip-172-31-88-11:~$ kops version  
Client version: 1.26.4 (git-v1.26.4)  
ubuntu@ip-172-31-88-11:~$ aws --version  
aws-cli/1.22.34 Python/3.10.12 Linux/6.5.0-1016-aws botocore/1.23.34  
ubuntu@ip-172-31-88-11:~$ kubectl version --client  
Client Version: v1.29.3  
Kustomize Version: v5.0.4-0.20230601165947-6ce0bf390ce3  



