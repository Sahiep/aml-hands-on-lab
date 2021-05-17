# Introducing Deploying ML models with AzureML 

## Objectives

In the following Excercise you will learn:
- Deploy an AzueML model to Azure Container Instance

### Prerequisites

To run through below instructions, you need an Azure subscription, an AzureML workspace and an AzureML compute target (i.e. **cpu-cluster**). See instructions on how to create a workspace [here](../0_setup/setup.md) and create an AzureML compute target [here](../1_concepts/concepts.md). In addition you require the registered model you have trained here [here](../2_training/training.md)

## Exercise: Deploy your model on Azure Container Instance

In the following exercise you will:
1. Register the model or load the registered model
2. Prepare to deploy. (Specify assets, usage, compute target.)
3. Deploy the model to the compute target.
4. Test the deployed model, also called a web service.

1. Run the notebook to deploy to ACI [Python SDK - deploy-credit-model.ipynb](https://github.com/Sahiep/aml-lab-notebooks/blob/main/labs/3_deployment/deploy-credit-model.ipynb) 
1. Check for your Endpoint in the Azure ML Workspace
1. Test your new Web Service