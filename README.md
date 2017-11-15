# Azure Functions on Linux quickstart sample project 

The code in the this repository supports the Azure Functions quickstart topic for Linux: [Create your first function running on Linux using the Azure CLI](https://docs.microsoft.com/azure/azure-functions/functions-create-first-azure-function-azure-cli-linux). 

The sample project has three HTTP triggered functions, one each for C#, F#, and JavaScript. These functions are generated from the same HTTP triggered function templates available in the Azure portal. 

This repo is designed to be deployed to Azure Functions on Linux in a built-in Docker image. 

### Deployment scripts

This sample repository currently includes two scripting files, [deploy.sh] and [.deployment]. The [.deployment] file tells the deployment process to use [deploy.sh] as the [custom deployment script](https://github.com/projectkudu/kudu/wiki/Custom-Deployment-Script). In the current preview release, scripts are required to deploy the function app on a Linux image.  


[.deployment]: .deployment
[deploy.sh]: deploy.sh
