# BERT Finetuning for Multilingual Subjective Classification
This repository contains the code for finetuning the pre-trained multilingual BERT model from Hugging Face using PyTorch and Adam Optimizer for subjective classification task of 15 labels in 12 languages with 1500 examples.

## Dataset
The dataset consists of 1500 examples in 12 languages annotated with 15 subjective classification labels. The annotations were done by the author, who re-annotated everything after a few days, keeping the labels which didn't match for each example in a separate column.

## Dependencies
The code is written in Python 3. The following dependencies are required to run the code:

* PyTorch
* Hugging Face transformers
* pandas

The required packages are installed in the given notebook

# Fine-tuning
To fine-tune the pre-trained BERT model, run the BERT_Finetune.ipynb notebook in Jupyter Notebook or JupyterLab. The notebook contains step-by-step instructions on how to prepare the data, fine-tune the model, and evaluate the performance.

# Results
The model achieved an accuracy of 60% on the test set.
