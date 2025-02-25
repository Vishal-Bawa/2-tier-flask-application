# 2-tier-flask-application
1.Prerequisites:
  a)AWS CLI - For interacting with AWS services.
  b)Docker - For building and running the containers locally.
  c)Kubernetes (kubectl) - For managing Kubernetes resources.
  d)AWS Account - For creating the EKS cluster and related resources.
  
2.Project Title:
  This project is a 2-tier Flask application with a PostgreSQL database running on Amazon Elastic Kubernetes Service (EKS). It demonstrates how to deploy a web application with a backend database 
  in a containerized environment.

3.Project Overview:
  This project is designed to demonstrate how to deploy a Flask application in a containerized environment using AWS EKS. It includes:
   a)A Flask application container that serves the web application.
   b)A PostgreSQL database container that stores the application's data.
   c)The app is deployed using Amazon EKS to manage the Kubernetes cluster.

4.Technologies Used:
  a)Flask - A micro web framework for Python.
  b)Docker - Used to containerize the application and its database.
  c)Amazon EKS (Elastic Kubernetes Service) - Used to manage and deploy the containers in Kubernetes.
  d)PostgreSQL - Relational database used for storing application data.
  e)AWS VPC - For managing the network and subnets for secure communication between services.
  f)Elastic IP & Internet Gateway - For public access to the Flask application.  
  
5.Deployment Instructions
  a)Install and configure AWS CLI
  b)Set up Kubernetes Cluster with EKS
  c)Create Kubernetes resources
    Deploy your Flask app and PostgreSQL database using Kubernetes YAML files .
  d)Verify Deployment
    After the deployment, access the public IP address of your load balancer or EKS service to see the app running.

6.Usage
  Once the application is up and running, navigate to http://<public-ip>:5000 in your web browser to access the Flask app.
