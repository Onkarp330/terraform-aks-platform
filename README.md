# Terraform AKS Kubernetes Platform

This project demonstrates how to provision a Kubernetes cluster using Terraform and deploy applications to it.

## Technologies Used

- Terraform
- Azure Kubernetes Service
- Kubernetes
- Docker

## Architecture

Terraform provisions:

- Resource Group
- AKS Cluster

Kubernetes deploys:

- Nginx application
- LoadBalancer service

## Deployment Steps

Initialize Terraform

```
terraform init
```

Apply infrastructure

```
terraform apply
```

Deploy application

```
kubectl apply -f kubernetes/
```
