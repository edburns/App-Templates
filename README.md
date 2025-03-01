# App Templates

App Templates are packaged app samples designed to reduce the time it takes a developer to deploy their code to Azure. Unlike standalone example code, the goal of App Templates is to provide all the components to deploy an app to Azure with automation via GitHub Actions or other CI/CD services. 

Each sample consists of example code, CI/CD components, and documentation containing all the required steps.

App Templates are designed to be compatible with the [Azure Developer CLI(azd)](https://github.com/Azure/azure-dev/) which is currently in preview. These templates follow the same file structure and are straightforward to convert to `azd` compatible templates once all the components of the template (e.g. programming language) are supported. 

App Templates are open to any technology some may not be on the azd roadmap and can be deployed using the READ ME guidance. The purpose of App Templates is to deliver and prove the value of accelerated onboarding for developers who are new to Azure. Developing examples for `azd` is one of our aims that fit into the broader goal of accelerated developer onboarding.

## Pre-requisites
- Azure Subscription and you must be the owner(or know the owner) of the subscription for configuring automatated deployments

## Sample templates

- [.NET app on App Service](https://github.com/Azure-Samples/app-templates-dotnet-azuresql-appservice)
- [Integration Services - APIM + ServiceBus + Functions + Cosmos](https://github.com/Azure-Samples/app-templates-integration-services)
- [JBoss EAP on Appservice](https://github.com/Azure-Samples/app-templates-JBossEAP-on-AppService)
- [Jakarta EE IBM Open Liberty on AKS](https://github.com/Azure-Samples/app-templates-Liberty-on-aks)
- [Jakarta EE Oracle WebLogic Server (WLS) on AKS](https://github.com/Azure-Samples/app-templates-WLS-on-aks)
- [Java Spring boot on AKS](https://github.com/Azure-Samples/app-templates-springboot-app-on-AKS)
- [Java microservices based spring boot on AKS](https://github.com/Azure-Samples/app-templates-springboot-microservices-on-AKS)
- [Microservices integration - APIM + Container Apps + AppService + Functions](https://github.com/Azure-Samples/app-templates-microservices-integration)
- [Spring Boot PetClinic Microservices Application on Azure Red Hat Openshift (ARO)](https://github.com/Azure-Samples/app-templates-springboot-microservices-on-ARO)
- [Spring Boot on Azure Spring Apps](https://github.com/Azure-Samples/apptemplates-microservices-spring-app-on-AzureSpringApps)
- [Static Web App with Cosmos DB](https://github.com/Azure-Samples/app-templates-staticwebapp-cosmosdb)
- [WordPress on Azure Container Apps](https://github.com/Azure-Samples/apptemplate-wordpress-on-ACA)


## Contributing

- Identify a sample app you plan to make into an app template
- Follow the steps listed here to make the template azd compatible: [Make your project compatible with Azure Developer CLI](https://learn.microsoft.com/azure/developer/azure-developer-cli/make-azd-compatible?pivots=azd-create)
- Add .devcontainer, .github and .github/workflow components

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Data Collection
The software may collect information about you and your use of the software and send it to Microsoft. Microsoft may use this information to provide services and improve our products and services. You may turn off the telemetry as described in the repository. There are also some features in the software that may enable you and Microsoft to collect data from users of your applications. If you use these features, you must comply with applicable law, including providing appropriate notices to users of your applications together with a copy of Microsoft's privacy statement. Our privacy statement is located at https://go.microsoft.com/fwlink/?LinkId=521839. You can learn more about data collection and use in the help documentation and our privacy statement. Your use of the software operates as your consent to these practices.

## Telemetry Configuration
Telemetry collection is on by default.

To opt-out, set the variable enableTelemetry to false in Bicep/ARM file and disable_terraform_partner_id to false on Terraform files.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
