\# 🕹️ 2048 Game on AWS EKS (Fargate) with ALB Ingress



!\[2048 Game Live](screenshots/01-game-ui.png)



Deploy the classic \*\*2048 game\*\* on \*\*AWS EKS using Fargate (serverless Kubernetes)\*\*  

and expose it publicly using \*\*AWS Application Load Balancer (ALB) Ingress\*\*

managed by the \*\*AWS Load Balancer Controller\*\*.



This repository is intended as a \*\*learning and reference guide\*\* for anyone

who wants hands-on experience with EKS Fargate and Kubernetes Ingress on AWS.



---



\## 📦 Prerequisites



Make sure the following tools are installed:



\- \*\*AWS CLI\*\*

\- \*\*kubectl\*\*

\- \*\*eksctl\*\*

\- \*\*Helm\*\*



AWS account with sufficient IAM permissions is required.



---



\## ☁️ Step 1: Configure AWS CLI



```bash

aws configure



