# slam-pre-trained-LM

This repository contains the necessary code to replicate the experiments in the master thesis Modeling Second Language Acquisition with Pre-trained Neural Language Models'.

# Loading the data

The dataset that we use can be found at https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/8SWHNO.
The data is loaded into our Jupyter Notebook by following https://github.com/Runze/duolingo-slam/blob/master/01-load-data.ipynb.

# Running the models

The different experiments can be run by changing the parameters in the *Configuration* section and selecting different options. 

In order to use BERT instead of DistilBERT, one has to replace 'distilbert' with 'bert' when importing and using the model. For example, `from pytorch_transformers.modeling_distilbert import *` should be changed to `from pytorch_transformers.modeling_bert import *`.
