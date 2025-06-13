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

### 2. Set Up Azure DevOps
- Create a new project in *Azure DevOps*
- Navigate to *Repos* and clone the GitHub repo:
