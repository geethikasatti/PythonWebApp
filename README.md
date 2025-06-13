# Python Web App Deployment on Azure using Azure DevOps CI/CD

This project demonstrates how to deploy a Python web application to Azure App Service using Azure DevOps pipelines.

## Project Overview

We deployed a Python-based web app hosted on GitHub to Azure App Service using a CI/CD pipeline configured via Azure DevOps. Here's a step-by-step breakdown:

## Tools & Services Used

- Azure App Service
- Azure DevOps
- GitHub
- Azure Resource Manager (ARM) and App Registration (for service connection)
- YAML-based CI/CD Pipeline

## Steps to Reproduce

### 1. Create Azure App Service
- Go to [Azure Portal](https://portal.azure.com/)
- Create a new *App Service* with your preferred configuration (Python version, region, etc.)
### 3. Create Service Connection
- Navigate to *Project Settings > Service Connections*
- Choose *Azure Resource Manager*
- Select *Service Principal (automatic)* via *App Registration*
- Authenticate and select your subscription and resource group

### 4. Create CI/CD Pipeline
- Go to *Pipelines > New Pipeline*
- Choose *Azure Repos Git* as your code source
- Select your repository
- Choose *YAML*
- If not present, Azure will auto-generate a YAML pipeline file. You can also customize it.

### 5. Configure Deployment
- The pipeline will automatically detect the App Service created in Step 1
- Connect the pipeline to the App Service
- Save and Run the pipeline

### 6. Verify Deployment
- Once the pipeline execution is successful, go to the App Service in Azure
- Open the URL to see your Python app running live!

## Outcome

✅ Continuous Integration & Continuous Deployment setup from GitHub to Azure  
✅ Automated deployment triggered on each push  
✅ Python app running successfully on Azure App Service

### 2. Set Up Azure DevOps
- Create a new project in *Azure DevOps*
- Navigate to *Repos* and clone the GitHub repo:https://github.com/CKNAVIN1009/PythonWebApp
