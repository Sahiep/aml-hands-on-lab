[[_TOC_]]

# Train your first ML model in an AzureML experiment:

## Prerequisites

To run through below instructions, you need an Azure subscription, an AzureML workspace, a registered data set (i.e. **german-credit**) and an AzureML compute target (i.e. **cpu-cluster**). See instructions on how to create a workspace [here](../../../0-Setup/README.md), register an AzureML dataset [here](../../1-Concepts/2-Datastores-datasets/UI/README.md) and create an AzureML compute target [here](../../1-Concepts/0-Compute/UI/README.md).

## Train a model using the AzureML SDK

In this module we train a machine learning model using the AzureML SDK.

1. Training on local compute: [Python SDK](./Python/1-aml-training-and-hyperdrive/1-scikit-learn-local-training-on-notebook-plus-aml-ds-and-log/binayclassification-german-credit-notebook.ipynb) 

2. Training on a remote compute:  [Python SDK](./Python/1-aml-training-and-hyperdrive/2-scikit-learn-remote-training-on-aml-compute-plus-hyperdrive/binayclassification-german-credit-aml-compute-notebook.ipynb)  / [R SDK](./R/README.md)

3. Hyper-parameter optimization:  [Python SDK](./Python/1-aml-training-and-hyperdrive/2-scikit-learn-remote-training-on-aml-compute-plus-hyperdrive/binayclassification-german-credit-aml-compute-notebook.ipynb)

For more details and examples on model training using SDK & hyper-parameter optimization see [here](https://docs.microsoft.com/en-us/azure/machine-learning/tutorial-train-models-with-aml?view=azure-ml-py) and [here](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-tune-hyperparameters?view=azure-ml-py).