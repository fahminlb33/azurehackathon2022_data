# Evangelion01 - SNMPTN Profiling

> Data Exploration, Preprocessing, and Modelling

This repository contains Jupyter Notebooks and Python scripts to explore the dataset, preprocess the data, and run machine learning modelling process using Azure ML.

You can recreate this virtual environment using `conda` or `mamba` using the `requirements.txt` file. For the `train_model.ipynb` and `serve_snmptn.py` it is executed in the Azure ML Notebooks and Azure ML Endpoints to run the training process and serve the model.

At the time of this readme writing, the model has the accuracy of 70% using Gradient Boosting algorithm from `scikit-learn` library.
