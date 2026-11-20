# VProfile – High Availability DevOps Deployment on AWS Kubernetes

## Project Overview

VProfile is a multi-tier Java web application that I customized and containerized, then deployed on an AWS Kubernetes cluster using kOps.

The project demonstrates DevOps practices including Docker image management, Kubernetes orchestration, high availability, autoscaling, persistent storage, application health monitoring, and secure network communication.

The infrastructure is designed to distribute application workloads across three AWS Availability Zones to improve availability and resilience.



## Technology Stack

| Category | Technologies |
|---|---|
| Cloud Platform | AWS |
| Containerization | Docker |
| Container Orchestration | Kubernetes |
| Cluster Management | kOps |
| Application Runtime | Java, Apache Tomcat 9 |
| Build Tool | Apache Maven |
| Database | MySQL 5.7 |
| Networking | AWS Application Load Balancer |
| Storage | Amazon EBS |
| Autoscaling | Kubernetes HPA, AWS Auto Scaling |
| Version Control | Git, GitHub |
| Operating System | Linux (Amazon Linux) |

## Key DevOps Implementations

- Multi-stage Docker build for the Java application.
- Separate application and MySQL container images.
- Kubernetes Deployment with multiple application replicas.
- Kubernetes StatefulSet with persistent EBS storage for MySQL.
- High Availability architecture across three Availability Zones.
- Horizontal Pod Autoscaler (HPA) for application scaling.
- Pod Disruption Budget (PDB) for maintenance availability.
- AWS Application Load Balancer integration.
- Kubernetes ConfigMaps and Secrets for configuration management.
- Kubernetes Network Policies for controlled communication.
