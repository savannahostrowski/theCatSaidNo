# GitHub to Cloud in Minutes with the Azure Developer CLI

Building applications that use multiple cloud services, connecting them all together in a secure way, and setting up a CI/CI pipeline can be a confusing and daunting task. Not to mention a time consuming one with many options. Learn how you can use the Microsoft Azure Developer CLI and the associated code templates to quickly get these types of applications up and running in cloud in minutes; build upon them and templatize your own ideas to do the same.

## Prerequisites

1. Azure Account
    - Sign up for [FREE](https://azure.microsoft.com/free/?WT.mc_id=A261C142F). You also need [contributor role assigned](https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-portal) to your Azure subscription.
2. Install [azd](https://aka.ms/azd-install)

## Quickstart

Create a new directory.

`mkdir gh-universe`.

Next, change directories,

`cd gh-universe` and run the following command:

 ```bash
 azd up -t spboyer/thecatsaidno
 ```

 The command clones the template, creates the infrastructure and publishes the application code to Azure.
