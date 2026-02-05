# ci-cd-pipeline-azure-devops
End-to-end CI/CD pipeline implementation using Azure DevOps with automated build, test and deployment Or CI/CD pipeline using Azure DevOps YAML pipelines for automated build and deployment.
# Azure DevOps CI/CD Pipeline

This project demonstrates an end-to-end CI/CD pipeline using Azure DevOps YAML pipelines.

## Tools & Technologies
- Azure DevOps Pipelines
- Python (Flask)
- Docker
- Linux

## Pipeline Workflow
1. Code pushed to repository
2. Azure DevOps pipeline triggered
3. Application build & test
4. Docker image created
5. Application deployed

## How to Run Locally
```bash
git clone <repo-url>
docker build -t azure-pipeline-app .
docker run -p 5000:5000 azure-pipeline-app
✅ Folder & File Structure (EXACT)
azure-devops-ci-cd-pipeline/
│
├── README.md
├── .gitignore
│

├── app/
│   ├── app.py
│   └── requirements.txt
│
├── docker/
│   └── Dockerfile
│
└── azure-pipelines.yml
Author
Anjali Singh
GitHub: https://github.com/singhanjali33375-rgbREADME.md
.gitignore
app/app.py
app/requirements.txt
docker/Dockerfile
azure-pipelines.yml


🔥 Interview Ready Explanation (1 Line)
“I created an Azure DevOps YAML-based CI/CD pipeline that automatically builds and deploys a Dockerized Python application on every code push.”


