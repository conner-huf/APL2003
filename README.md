# Azure Container Apps Project

This is a project I worked on following a microsoft learn module for learning how to create and deploy containerized .NET applications using Azure. I used the following things in this project:

- Azure
- .NET
- C#
- Docker
- Azure CLI
- Azure DevOps
- Azure Virtual Networking
- Managed Identity
- Azure Container Registry

To summarize the work done here, I made a boilerplate .NET weatherforecast webapi, created a dockerfile to containerize this webapi, and deployed that app using an Azure container app. The container app is set up with Azure DevOps for CI. The container app also hosts multiple revisions of the app.

![RG](https://github.com/user-attachments/assets/3ab5708f-4871-48a9-9869-b78a2a3d3889)

UPDATE: I've been watching the billing for this resource group really closely. This will become expensive quick, so I'm deprovisioning the resources. But a great learning experience!
