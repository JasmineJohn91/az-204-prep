<h1>Develop Azure compute solutions (25-30%)</h1>
<h2>Implement IaaS solutions</h2>

<h3>1.Provision VMs</h3>
<a href='https://docs.microsoft.com/en-us/azure/virtual-machines/windows/overview'>1.1 VM Overview</a><br>
<a href='https://docs.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-powershell'>1.2 VM Quick Start</a><br>
<a href='https://docs.microsoft.com/en-us/azure/virtual-machines/windows/tutorial-manage-vm'>1.3 VM Tutorials</a><br>
<a href='https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/tutorial-autoscale-powershell'>1.4 VM Auto Scaling</a><br>

<h3>2.Configure VMs for remote access</h3>
<a href='https://docs.microsoft.com/en-us/azure/security-center/security-center-just-in-time'>2.1 Configure Just-in-time access to a VM</a><br>

<h3>3.Create ARM templates</h3>
<a href='https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview'>3.1 ARM Templates Overview</a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-quickstart-create-templates-use-the-portal'>3.2 ARM Templates Quickstart</a><br>
<a href='https://docs.microsoft.com/en-us/azure/architecture/building-blocks/extending-templates'>3.3 Extending ARM Templates</a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template'>3.4 ARM Templare Tutorials</a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-functions'>3.5 ARM Template Functions</a><br>

<h3>4.Create container images for solutions by using Docker</h3>
If you are new to docker, it's good to get basic idea from the below plural sightvideo and docker basics document.
Video : <a href='https://app.pluralsight.com/library/courses/microsoft-azure-containers-deploying-managing/table-of-contents'>Deploying and Managing Containers </a><br>
Document: <a href='https://docs.docker.com/get-started/overview/'>Docker Basics</a><br>

<a href='https://docs.microsoft.com/en-us/azure/container-registry/container-registry-intro'>4.1 Private container registry in azure- Overview </a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-overview'>4.2 Azure Container Instance Overview </a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-app'>4.3 Tutorial Create and Deploy container image</a><br>
<a href='https://docs.microsoft.com/en-us/learn/modules/build-and-store-container-images/'>4.4 Build and Store Azure Container Images</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-registry/container-registry-tutorial-quick-task'>4.5 Automate container image builds</a><br>

<h3>5.Publish an image to the Azure Container Registry</h3>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-acr'>5.1 Create ACR and Push Images</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-docker-cli'>5.2 Push images to container registry using CLI</a><br>

<h3>6.Run containers by using Azure Container Instance</h3>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-deploy-app'>6.1 Deploy container application to azure container instance</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart'>6.2 Container Instances Quickstart</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-volume-secret'>6.3 Mount a secret volume to azure container instance</a><br>

<b>Learning Module</b><a href='https://docs.microsoft.com/en-us/learn/modules/run-docker-with-azure-container-instances/'>Run docker with azure container instances</a><br>

<h2>Create Azure App Service Web Apps</h2>

<h3>Create an Azure App Service Web App</h3>
https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-dotnet

Enable diagnostics logging
https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-diagnostic-logs
Capture Web Application Logs with App Service Diagnostics Logging

Deploy code to a web app
https://docs.microsoft.com/en-us/azure/app-service/deploy-zip
Deploy an Azure Web App
Provision and deploy microservices predictably in Azure
https://docs.microsoft.com/en-us/azure/app-service/containers/tutorial-custom-docker-image
Configure web app settings including SSL, API, and connection strings
1. Configuring web app settings with SSL
2. Configuring web app settings with connection strings
3. Host Restful APIs in Azure App Service

Custom configuration and application settings in Azure Web Sites
Configure an App Service app in the Azure portal
Buy a custom domain name for Azure App Service
Add a TLS/SSL certificate in Azure App Service

Implement autoscaling rules, including scheduled autoscaling, and scaling by operational or system metrics
Azure App Service Autoscaling rules
Scheduled Autoscaling & scaling by operational or system metrics
Also, review the common autoscale patterns
https://docs.microsoft.com/en-us/azure/app-service/manage-scale-up?WT.mc_id=thomasmaurer-blog-thmaure

Implement Azure functions

Implement input and output bindings for a function
https://docs.microsoft.com/en-us/azure/azure-functions/functions-triggers-bindings
Azure Functions trigger and binding example

Implement function triggers by using data operations, timers, and webhooks
https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-timer
Azure Functions HTTP triggers and bindings overview

Implement Azure Durable Functions
https://docs.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-create-portal
What are Durable Functions?
Create your first durable function in C#

Additional Links from Udemy
https://azure.microsoft.com/en-us/blog/announcing-azure-integration-service-environment-for-logic-apps/
https://docs.microsoft.com/en-us/cli/azure/webapp/cors?view=azure-cli-latest
https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook
https://azure.microsoft.com/en-us/pricing/details/app-service/windows/
https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-diagnostic-logs
https://docs.microsoft.com/en-us/azure/aks/ingress-basic
https://docs.microsoft.com/en-us/azure/container-registry/container-registry-authentication
https://github.com/projectkudu/kudu/wiki/Customizing-deployments
https://docs.microsoft.com/en-us/azure/aks/tutorial-kubernetes-deploy-cluster
https://docs.microsoft.com/en-us/azure/aks/kubernetes-helm
https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/docker-application-development-process/docker-app-development-workflow
