---
layout: default
title: 'Trainer demonstrations'
nav_order: 6
has_children: false
---

# Trainer demonstrations
{: .no_toc }


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

<br/>

## Learning Path 1: Introduction to AI and AI on Azure

<!-- Demonstrations -->

**Create an Azure AI services multi-service resource using Azure CLI.**

    ```bash
    resourceGroup="AzureAI-RG"
    resourceLocation="westus2"
    resourceAIServices="AIServicesDemo"

    az group create --name $resourceGroup --location location $resourceLocation

    az cognitiveservices account create --name $resourceAIServices --resource-group $resourceGroup --kind AIServices --sku S0 --location $resourceLocation --yes

    az cognitiveservices account keys list --name $resourceAIServices --resource-group $resourceGroup
    ```



<br/>

---

<br/>


## Learning Path 02: Develop computer vision solutions with Azure AI Vision

<!-- Demonstrations -->


<br/>

---

<br/>


## Learning Path 03: Develop natural language processing solutions

<!-- Demonstrations -->


<br/>

---

<br/>

## Learning Path 04:Develop Generative AI Solutions with Azure OpenAI Service


<!-- Demonstrations -->


<br/>

---

<br/>

## Learning Path 05: Creating a Knowledge Mining Solution

<!-- Demonstrations -->


<br/>

---

<br/>


## Learning Path 06: Develop solutions with Azure AI Document Intelligence

<!-- Demonstrations -->


<br/>

---

<br/>
