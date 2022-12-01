# Module 00 - Lab Environment Setup

**[Home](../README.md)**

## Introduction
In order to follow along with the Databricks lab exercises, you need to provision a set of resources.

## Prerequisites
* An [Azure account](https://azure.microsoft.com/free/) with an active subscription.

    > :warning: If you are using an **Azure Pass promo code**, the following resource providers - `Microsoft.Storage`, `Microsoft.EventHub`, and `Microsoft.Synapse` are not registered by default. Follow the instructions on [how to register a resource provider](./providers.md) before proceeding with the lab environment deployment below.

## Lab Environment Setup
1. Right-click or `Ctrl + click` the button below to open the Azure Portal in a new window.

    [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ftayganr%2Fpurviewlab%2Fmain%2Ftemplate%2Fazuredeploy.json)


2. Beneath the **Resource group** field, click Create new and provide a unique name (e.g. databricks-rg), create a unique Workspace name (e.g. DatabricksHoL), select a valid region (e.g. East US 2), select the Trial Pricing Tier, and then click Review + create.

 ![Deploy Template](../DbAzureDeploy.png)
