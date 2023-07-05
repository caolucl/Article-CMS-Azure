# Write-up Template
App Deployement using Azure App Service

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
### Appropriate solution
The solution for deploying this web application is using Azure App Service.

### Reason to choose Azure App Service
Azure App Service is a fully managed platform for creating web applications.
Azure App Service helps quickly build, deploy, and scale web apps.
Azure App Services support multi languages: php, nodejs, python, .net, java.
The update, security, scaling are taken care by Azue.

### Reason to not choose Virtual Machine
When using Virtual Machine, We have to control the OS of VM, the networking, security patching.
We also have to install libraries or other applications needed to run the application.

### Justification based on cost, scalability, avaliability and workflow:
- Cost: Azure App Service is less expensive than VM
- Scalability: It's much eaiser to scale Azure App Service than VM. Azure has built-in features to scale out/up for Azure App Serivice.
- Avaliability: Global scale with high availability.
- Workflow: Azure App service supports automated deployments from GitHub, Azure DevOps, or any Git repository.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
- Some programming applications are not supported by Azure App Service. Some can only run by Virtual machines.
- Some applications need much more resources (cpu, ram) which Azure App Service cannot statisfy, so we have to choose Virtual machines.
- We need to control the OS of the servers, so we have to deploy Applications on the VM.