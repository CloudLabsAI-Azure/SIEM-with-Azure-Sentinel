### Get started with deploying your Environment.

This document will help you deploy the SIEM with Microsoft Sentinel envrionment in your Azure environment.To Deploy this lab in your env, Please follow the below steps;


1. You will need following to get started:

   - **Azure subscription**: Create a free account [here](https://azure.microsoft.com/free/).
   - **Azure Permission**: Make sure you have owner Access to the Subscription. 

## Prepare your Azure Lab Environment.

1. Click on the below Deploy to Azure Button.

   [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fexperienceazure.blob.core.windows.net%2Ftemplates%2Fsiem-with-sentinel%2Fsentinel-deploy.json)

   - Select the available subscription and resource group. Provide the unique alpha numeric value for `Deployment` parameter. You can review the ARM template by clicking on Edit Template. Review and create the OpenAI Like A Pro Lab.


Once All the resources got deployed, you can login to the JumpVM to perform the lab. 
