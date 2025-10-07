# depoly-fullstack-React-Node.js-MongoDB-App-to-AWS
This repository demonstrates a production-style deployment for a Node.js backend and a React/Vite frontend on AWS:

Backend: Node.js → Docker → AWS CodeBuild (build image) → Amazon ECR (store image) → AWS App Runner (auto-deploy from ECR)

Data: Amazon DocumentDB (MongoDB-compatible)

Frontend: React/Vite → AWS CodeBuild (build) → Amazon S3 (static files) → Amazon CloudFront (CDN)

Domain: dennis-zhao.click served via CloudFront + Route 53 (ACM TLS)