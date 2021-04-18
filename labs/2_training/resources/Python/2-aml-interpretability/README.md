[[_TOC_]]

# Model Interpretability

## Prerequisites

To run through below instructions, you need an Azure subscription, an AzureML workspace, a registered data set (i.e. **german-credit**) and an AzureML compute target (i.e. **cpu-cluster**). See instructions on how to create a workspace [here](../../../0-Setup/README.md), register an AzureML dataset [here](../../../1-Concepts/2-Datastores-datasets/UI/README.md) and create an AzureML compute target [here](../../../1-Concepts/0-Compute/UI/README.md).

## Model interpretability in AzureML

In this module, you will learn how to explain why your model made the predictions it did with the interpretability package of the Azure Machine Learning Python SDK (Preview).

Using the classes and methods in the SDK, you can get:

- Feature importance values for both raw and engineered features
- Interpretability on real-world datasets at scale, during training and inference.
- Interactive visualizations to aid you in the discovery of patterns in data and explanations at training time

During the training phase of the development cycle, model designers and evaluators can use interpretability output of a model to verify hypotheses and build trust with stakeholders. They also use the insights into the model for debugging, validating model behavior matches their objectives, and to check for bias.

In machine learning, features are the data fields used to predict a target data point. For example, to predict credit risk, data fields for age, account size, and account age might be used. In this case, age, account size, and account age are features. Feature importance tells you how each data field affected the model's predictions. For example, age may be heavily used in the prediction while account size and age don't affect the prediction accuracy significantly. This process allows data scientists to explain resulting predictions, so that stakeholders have visibility into what data points are most important in the model.

Using these tools, you can explain machine learning models globally on all data, or locally on a specific data point using the state-of-art technologies in an easy-to-use and scalable fashion.

## Setup

You are going to work on the Compute Instance and environment you created earlier [here](../../../../1-Concepts/0-Compute/UI/README.md) and [here](../../../../1-Concepts/1-Notebooks/README.md). 

1. To get started, first navigate to the Jupyter(Lab) instance running on your Compute Instance by clicking on the Jupyter(Lab) link 

2. In the file explorer of Jupyter, navigate to the folder `aml_workshop_template/2-Training/Code/Python/2-aml-interpretability`. Here we try model interpretability in both local and remote compute mode. Follow instructions in either of the notebooks below.

   - [using the local compute](1-simple-feature-transformations-explain-local.ipynb)
   - [using the AML remote compute](2-explain-model-on-amlcompute.ipynb)
