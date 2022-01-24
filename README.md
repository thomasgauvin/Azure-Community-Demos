# Azure Community Demos

This repository is a collection of demos that have been built by Azure Community members. Their purpose is to demonstrate how to achieve certain functionalities using Azure services. These repositories and their code are open-source and not production ready code.

## How to submit a new demo

You may submit a new demo by opening an issue. Include the name of your demo, a link to a public Github repository, and an architecture diagram of the Azure services used.

# Demos:

## Azure Cognitive Services:

| Link | Description | Image |
| --- | --- | --- |
| [Text-to-Speech Demo](https://github.com/hugogirard/textToSpeechDemo) | This demo exposes an Azure Architecture using Azure Cognitive Services to convert text to audio. The user enters a text in a Blazor Server web app. A job is created and an azure function is triggered, the function will call Azure Cognitive Services to detect the text language (currently french and english are supported). When the text is detected another function will be triggered and will call again Azure Cognitive Services to conver the text to audio file and save it in a blob. | ![image](https://user-images.githubusercontent.com/35609369/150875709-72c9713a-9fba-4f99-9884-6e8d3d7cee23.png) |
