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
If you are new to docker, it's good to get basic idea from the below plural sightvideo and docker basics document.<br>
Video : <a href='https://app.pluralsight.com/library/courses/microsoft-azure-containers-deploying-managing/table-of-contents'>Deploying and Managing Containers </a><br>
Document: <a href='https://docs.docker.com/get-started/overview/'>Docker Basics</a><br>

<a href='https://docs.microsoft.com/en-us/azure/container-registry/container-registry-intro'>4.1 Private container registry in azure- Overview </a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-overview'>4.2 Azure Container Instance Overview </a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-app'>4.3 Tutorial Create and Deploy container image</a><br>
<a href='https://docs.microsoft.com/en-us/learn/modules/build-and-store-container-images/'>4.4 Build and Store Azure Container Images</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-registry/container-registry-tutorial-quick-task'>4.5 Automate container image builds</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-registry/container-registry-authentication'>4.6 Azure container registry authentication</a><br>

<h3>5.Publish an image to the Azure Container Registry</h3>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-prepare-acr'>5.1 Create ACR and Push Images</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-registry/container-registry-get-started-docker-cli'>5.2 Push images to container registry using CLI</a><br>

<h3>6.Run containers by using Azure Container Instance</h3>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-tutorial-deploy-app'>6.1 Deploy container application to azure container instance</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart'>6.2 Container Instances Quickstart</a><br>
<a href='https://docs.microsoft.com/en-us/azure/container-instances/container-instances-volume-secret'>6.3 Mount a secret volume to azure container instance</a><br>

<b>Learning Module: </b><a href='https://docs.microsoft.com/en-us/learn/modules/run-docker-with-azure-container-instances/'> Run docker with azure container instances</a><br>

<h2>Create Azure App Service Web Apps</h2>

<h3>1.Create an Azure App Service Web App</h3>
<a href='https://docs.microsoft.com/en-us/azure/app-service/overview'>1.1 Web app overview</a><br>
<a href='https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-dotnet'>1.2 Quickstart: Create an ASP.NET Core web app in Azure</a><br>

<h3>2.Deploy code to a web app</h3>
<a href='https://docs.microsoft.com/en-us/azure/app-service/deploy-zip'>2.1 Zip Deployment</a><br>
<a href='https://docs.microsoft.com/en-us/azure/app-service/deploy-complex-application-predictably'>2.2 Deployment with Template</a><br>
<a href='https://docs.microsoft.com/en-us/azure/app-service/containers/tutorial-custom-docker-image'>2.3 Run a custom Docker image in App Service</a><br>

<h3>3.Enable diagnostics logging</h3>
<a href='https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-diagnostic-logs'>3.1 Enable diagnostics logging for apps</a><br>

<b>Learning Module: </b><a href='https://docs.microsoft.com/en-us/learn/modules/capture-application-logs-app-service/?WT.mc_id=thomasmaurer-blog-thmaure'> Capture Web Application Logs with App Service Diagnostics Logging</a><br>

<h3>4.Configure web app settings</h3>
<a href='https://docs.microsoft.com/en-us/azure/app-service/configure-common'>4.1 Common configuration</a><br>
<a href='https://docs.microsoft.com/en-us/azure/app-service/app-service-web-tutorial-rest-api'>4.2 REST API with CORS functionality</a><br>
<a href='https://docs.microsoft.com/en-us/cli/azure/webapp/cors'>4.3 Azure WebApp CORS -Azure CLI </a></br>

<h3>5.Configuration -SSL, API, and connection strings</h3>
<a href='https://docs.microsoft.com/en-us/azure/app-service/manage-custom-dns-buy-domain'>5.1 Buy a custom domain name for Azure App Service</a><br>
<a href='https://docs.microsoft.com/en-us/azure/app-service/configure-ssl-certificate'>5.2 Add a TLS/SSL certificate in Azure App Service</a><br>
<a href='https://docs.microsoft.com/en-us/azure/app-service/configure-ssl-bindings'>5.3 Secure a custom DNS name with a TLS/SSL binding in Azure App Service</a><br>

<h3>6.Implement autoscaling rules, including scheduled autoscaling, and scaling by operational or system metrics</h3>
<a href='https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-overview'>6.1 Autoscale overview </a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-get-started'>6.2 Autoscale walkthrough </a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-monitor/learn/tutorial-autoscale-performance-schedule'>6.3 Scheduled autoscaling </a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-monitor/platform/autoscale-common-scale-patterns'>6.4 common autoscale patterns</a><br>
<a href='https://docs.microsoft.com/en-us/azure/app-service/manage-scale-up'>6.5 Scale up an app in azure services</a><br>

<h2>Implement Azure functions</h2>

<h3>1.Implement input and output bindings for a function</h3>
<a href='https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview'>1.1 Azure Functions Overview</a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-functions/functions-triggers-bindings'>1.2 Azure Functions triggers and bindings concepts</a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-example'>1.3 Azure Functions trigger and binding example</a><br>

<h3>2.Implement function triggers by using data operations, timers, and webhooks</h3>
<a href='https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-timer'>2.1 Timer trigger for Azure Functions</a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-functions/functions-bindings-http-webhook'>2.2 Azure Functions HTTP triggers and bindings overview</a><br>

<h3>3.Implement Azure Durable Functions</h3>
<a href='https://docs.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-overview'>3.1 Durable Functions- Overview</a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-create-portal'>3.2 Create Durable Function in Azure Portal</a><br>
<a href='https://docs.microsoft.com/en-us/azure/azure-functions/durable/durable-functions-create-first-csharp'>3.3 Create your first durable function in C#</a><br>

<h2>Additional Links:<h2>
<b>Pricing:</b><a href='https://azure.microsoft.com/en-us/pricing/details/app-service/windows/'>Azure App Service Pricing</a><br>
<b>App workflow:</b><a href='https://docs.microsoft.com/en-us/dotnet/architecture/microservices/docker-application-development-process/docker-app-development-workflow'>Docker app workflow</a><br>
  
  
  
  
