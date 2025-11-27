# Federated Breast Cancer (PySyft)

Demonstration of a simple federated learning workflow using PySyft and the scikit-learn breast cancer dataset. This repository contains notebooks and notes used to explore privacy-preserving model training and audit workflows between an organisation and external researchers.

## Contents
- `datascientist.ipynb` — exploratory notebook with training/experiments.
- `organisation.ipynb` — project notes and process documentation.


# Federated Learning Breast Cancer with Pysyft
This project is a testing for the Pysyft package which is an Open Source framework that let Data Scientists/researchers do their work while maintaining privacy!
Pysyft comes as a middle between an organisation and a researcher.
The organisation load the metadata into the server:Datasite, it creates an account for external researcher and then goes to drink their coffee.

In the other hand, the researcher log into their account, get answers and allow questions: a code for example in the mock data created by the organisation which is a synthetic artificial version of the dataset and then download the answers.

Next step is the organisation which review the audit code, execute it and submits results.

So for this specific project I used a well known dataset Breast Cancer from sklearn and then made the magical cycle.

The full video : https://youtu.be/9fJ8b51YzCQ?si=za6EMvWgxJqiO1JS