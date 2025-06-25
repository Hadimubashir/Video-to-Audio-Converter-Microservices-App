# Video-to-Audio-Converter-Microservices-App
A cloud-native microservices application that converts user-uploaded videos to MP3 audio, featuring authentication, asynchronous processing, notifications, and scalable deployment using Kubernetes on AWS EKS.

#Architecture

 ![image](https://github.com/user-attachments/assets/ef712929-c667-4ddd-99c6-f9413075b1d3)

## Deploying a Python-based Microservice Application on AWS EKS

# 🚀 Features
User authentication with JWT

Video upload and audio (MP3) conversion

Asynchronous task processing with RabbitMQ

Email notifications using Gmail SMTP

REST APIs managed via an API Gateway microservice

End-to-end workflow automation and validation via curl

#🧰 Tools & Technologies
🛠️ Core Stack
Python

Docker

Kubernetes (EKS)

📦 Infrastructure & Deployment
AWS EKS

Terraform

Helm

🗃️ Databases & Messaging
PostgreSQL

MongoDB

RabbitMQ

🔒 Security & Integration
JWT Authentication

Gmail SMTP (Email notifications)

Kubernetes Secrets

📁 Storage
Amazon S3

🧪 Testing & CLI
curl (for API testing)

🧱 AWS Services Used
Amazon EKS

Amazon EC2

Amazon S3

IAM (for permissions)

VPC (networking)
