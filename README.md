# Azure Community Demos

This repository is a collection of demos that have been built by Azure Community members. Their purpose is to demonstrate how to achieve certain functionalities using Azure services. These repositories and their code are open-source and not production ready code.

## How to submit a new demo

You may submit a new demo by opening an issue. Include the name of your demo, a link to a public Github repository, a description for the project, an architecture diagram of the Azure services used, and tags of the Azure services you used.

# Demos:

| Link | Author | Description | Image | Tags |
| --- | --- | --- | --- | --- |
| [APIM Terraform](https://github.com/hugogirard/apimTerraform) | [hugogirard](https://github.com/hugogirard) | This Github show a simple CI/CD using Terraform to publish your APIs in Azure API Management. | ![image](https://user-images.githubusercontent.com/35609369/150876210-4dc22a90-6c79-4ec1-ae93-4105df081f28.png) | azure api management, terraform |
| [Text-to-Speech Demo](https://github.com/hugogirard/textToSpeechDemo) | [hugogirard](https://github.com/hugogirard) | This demo exposes an Azure Architecture using Azure Cognitive Services to convert text to audio. The user enters a text in a Blazor Server web app. A job is created and an azure function is triggered, the function will call Azure Cognitive Services to detect the text language (currently french and english are supported). When the text is detected another function will be triggered and will call again Azure Cognitive Services to conver the text to audio file and save it in a blob. | ![image](https://user-images.githubusercontent.com/35609369/150875709-72c9713a-9fba-4f99-9884-6e8d3d7cee23.png) | azure cognitive services, azure functions, azure blob storage |
| [Secure Logic App Using Azure AD and APIM](https://github.com/hugogirard/secureLogicApp) | [hugogirard](https://github.com/hugogirard) | This sample show a way to secure your Logic App with Azure Active Directory and exposed using Azure Api Management. Another logic app will call the protected logic retrieving a JWT token from Azure AD. An Azure policy will validate the JWT token inside APIM to be sure the audience is valid. The protected logic app have an IP restriction that accepts HTTP call only from the public IP of Api Management. | ![image](https://user-images.githubusercontent.com/35609369/150875981-8d024c38-e150-42ed-b267-21e9c939dcf6.png) | azure logic apps, azure active directory |
