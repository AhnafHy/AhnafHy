# MD Ahnaf Hyder

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-ahnaf-hyder/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:MDahnafhyder@gmail.com)

---

## About

Fourth-year **Computer Science Student @ York University**. Passionate about **cloud architecture**, **data engineering**, and **AI/ML systems**. I build production-grade cloud infrastructure and full-stack applications from serverless data pipelines and RAG-powered AI tools to real-time incident management platforms with WebSocket APIs and distributed job queues. Feel free to check out my [LinkedIn](https://www.linkedin.com/in/md-ahnaf-hyder/) or browse my projects below.

---

## Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Data Engineering**

![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)

**Frameworks & Tools**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

---

## Projects

### Featured Projects

| Name | Description | Stack | Link |
|---|---|---|---|
| [Incident Management Platform](https://github.com/AhnafHy/incident-management-platform) | Real-time incident management with WebSocket live feed, SQS escalation timers, on-call scheduling, and post-mortem editor | Next.js, Lambda, WebSocket API, SQS, DynamoDB | [Live](https://incident-management-platform.vercel.app/) |
| [AI Code Review Platform](https://github.com/AhnafHy/ai-code-review-platform) | AI-powered GitHub PR reviews, webhook ingestion, SQS async pipeline, structured Security/Performance/Quality findings posted back to PRs | Next.js, Lambda, SQS, DynamoDB, GPT-4o-mini | [Live](https://ai-code-review-platform-peach.vercel.app/)  |

### Cloud Applications

| Name | Description | Stack | Link |
|---|---|---|---|
| [RAG Document Assistant](https://github.com/AhnafHy/rag-document-assistant) | Upload any PDF and chat with it, text chunking, OpenAI embeddings, cosine similarity retrieval, and GPT-4o-mini generation | React, Lambda, S3, DynamoDB, OpenAI | [Live](http://rag-document-assistant-frontend-8eed2efc.s3-website-us-east-1.amazonaws.com/)  |
| [SOC 2 Evidence Collector](https://github.com/AhnafHy/soc2-evidence-collector) | Automated SOC 2 compliance evidence collection from AWS APIs mapped to Trust Service Criteria controls | React, Lambda, DynamoDB, EventBridge, API Gateway | [Live](http://soc2-evidence-collector-frontend-c8c748ca.s3-website.us-east-2.amazonaws.com/)  |
| [Policy-as-Code Checker](https://github.com/AhnafHy/policy-as-code-checker) | Terraform security scanner, paste HCL and get instant findings with severity ratings and remediation advice | React, Lambda, DynamoDB, API Gateway | [Live](http://pac-checker-frontend-b1dec6ad.s3-website.us-east-2.amazonaws.com/)  |
| [FinOps Dashboard](https://github.com/AhnafHy/finops-dashboard) | AWS cost visibility tool, pulls Cost Explorer data daily, stores snapshots, and exposes a REST API with budget projection and alerts | Lambda, DynamoDB, API Gateway, Cost Explorer, CloudWatch | — |

### Infrastructure & Pipelines

| Name | Description | Stack |
|---|---|---|
| [Health Check Monitor](https://github.com/AhnafHy/health-check-monitor) | Highly available uptime monitor on EC2 with ALB, Auto Scaling, Multi-AZ RDS, and Cognito authentication | EC2, ALB, RDS, Cognito, VPC, Terraform |
| [NYC Taxi Data Pipeline](https://github.com/AhnafHy/nyc-taxi-pipeline) | End-to-end data pipeline with medallion architecture, dbt transformations, and Great Expectations quality gates | Airflow, dbt, Snowflake, GitHub Actions |
| [Log Analysis Pipeline](https://github.com/AhnafHy/log-analysis-pipeline) | Real-time log streaming pipeline with partitioned S3 storage and serverless SQL analytics via Athena | Lambda, Kinesis Firehose, S3, Athena, Glue |
| [Kubernetes Autoscaler](https://github.com/AhnafHy/k8s-autoscaler) | Python Flask app containerized and deployed on Kubernetes — scales from 1 to 4 replicas under simulated CPU load | Kubernetes, Helm, HPA, Prometheus, Docker |
| [Serverless URL Shortener](https://github.com/AhnafHy/Url-Shortener) | Fully serverless REST API with CI/CD pipeline — provisioned entirely with Terraform IaC | Lambda, DynamoDB, API Gateway, Terraform, GitHub Actions |

---

## Certifications

![AWS CCP](https://img.shields.io/badge/AWS_Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
