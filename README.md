# DevOps-Project
This project sets up a Kubernetes cluster on AWS using EKS (Elastic Kubernetes Service) 🖥️ and follows GitOps principles for continuous deployment with ArgoCD 🔄.

The application is a website built with multiple microservices in Python 🐍, Ruby 💎, Java ☕, and Node.js.

We use Istio for managing traffic and deployments, Prometheus and Grafana for monitoring 📊, and Kiali for observability 👀.

SonarQube helps with code quality checks.

Together, these tools ensure smooth, automated deployments, efficient scaling, and real-time monitoring of the application 🚀.

# 1. Prerequisites

Before you get started with the project, make sure you have the following tools installed and set up:

AWS CLI: This helps you manage AWS services and configure your EKS clusters.
eksctl: A handy command-line tool to create and manage EKS clusters easily.
kubectl: The command-line interface for Kubernetes, which you’ll use to interact with your cluster.
ArgoCD CLI: This tool lets you manage your GitOps workflows and interact with the ArgoCD server.
Istio CLI (istioctl): Needed to install and manage Istio, a service mesh for traffic management.
Git: For version control, ensuring you can manage your code and collaborate with others.
GitHub: This is where you’ll store your application code and configuration files.

# 2. Basic Understanding:

It’s helpful to have some knowledge of Kubernetes, ArgoCD, and Istio before diving in, but don’t worry if you’re new to these concepts — they’ll become clearer as you go!
