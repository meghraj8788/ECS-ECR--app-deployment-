# ECS-ECR--app-deployment-
Deployment Workflow

1️⃣ Create EC2 (Build environment)
2️⃣ Install Docker & AWS CLI
3️⃣ Create ECR Repository
4️⃣ Build Docker Image
5️⃣ Push Image to ECR
6️⃣ Create ECS Cluster (Fargate)
7️⃣ Create Task Definition
8️⃣ Create Service
9️⃣ Configure Security Group
🔟 Access Application






🔁 Internal Architecture Flow (Professional Version)
Developer → Docker Build → ECR (Image Storage)
        ↓
ECS Task Definition → ECS Cluster → Fargate
        ↓
Container Running
        ↓
Security Group Allows Port 8000
        ↓
Application Accessible via Public IP
