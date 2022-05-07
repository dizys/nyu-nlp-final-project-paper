NYU NLP Final Project: Finding ARG1 of Partitive Nouns in NomBank with DistilBERT
    by Ziyang Zeng (zz2960)
    Spring 2022

GitHub Repo: https://github.com/dizys/nyu-nlp-final-project (includes data and output files)

The ipynb files under this folder are the Jupyter notebooks that we used to implement and experiment with the DistilBERT models. For the baseline MaxEnt model, please see https://github.com/dizys/nyu-nlp-homework-6.

The requirements for running these Jupyter notebooks are as follows:
- python 3.7 or later
- Python packages:
  - numpy
  - typing_extensions
  - pytorch
  - datasets
  - fastprogress
  - transformers
  - senegal

Jupyter Notebooks:
- hf_transformer: the notebook for basic DistilBERT pipeline
- hf_transformer_one_arg: the notebook for the DistilBERT pipeline that forces only one ARG1 per sentence
- hf_transformer_enhanced: the notebook for DistilBERT pipeline enhanced with extra two features of POS and NG-BIO tags
- hf_transformer_qa: the notebook for question-answering framed DistilBERT pipeline
