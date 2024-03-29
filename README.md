---
page_type: sample
languages:
- csharp
products:
- azure
extensions:
  services: App-Service
  platforms: dotnet
---

# Getting started on configuring deployment sources for Web Apps in C# asynchronously #

 Azure App Service basic sample for managing web apps.
 Note: you need to have the Git command line available on your PATH. The sample makes a direct call to 'git'.
  - Create 4 web apps under the same new app service plan:
    - Deploy to 1 using FTP
    - Deploy to 2 using local Git repository
    - Deploy to 3 using a publicly available Git repository
    - Deploy to 4 using a GitHub repository with continuous integration


## Running this Sample ##

To run this sample:

Set the environment variable `CLIENT_ID`,`CLIENT_SECRET`,`TENANT_ID`,`SUBSCRIPTION_ID` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-dotnet-configure-deployment-sources-for-web-apps-async.git

    cd app-service-dotnet-configure-deployment-sources-for-web-apps-async

    dotnet build

    bin\Debug\net452\ManageWebAppSourceControlAsync.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.