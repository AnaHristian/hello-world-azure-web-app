# Create and deploy an app service web app on Microsoft Azure.

## Create an App Service Web App
Create an App Service Web App with the following configuration:

Resource-Group: resource-group-west
- Web App Name: unique name
- Publish: Code
- Runtime stack: Python 3.7
- Operating System: Linux
- Region: West US or the closest region to you
- App Service Plan: Default name or Create new with a name of your choice
- SKU and size: F1 (Free)

**Note:** Azure free account only allows one Linux App Service of size F1. You will need to delete the App Service along with the App Service Plan after this exercise since we will create other Linux App Services throughout this course.

## Deploy the App Service Web App
It’s finally time to deploy some code to Azure! Download the web app code provided here.

1. Create a new repo and push the web app code to the repo
2. On Azure portal in the Deployment Center, deploy the web app from GitHub
Navigate to the deployed URL
