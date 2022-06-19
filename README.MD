# Evangelion01 - SNMPTN Profiling

> Data Exploration, Preprocessing, and Modelling

This repository contains Jupyter Notebooks and Python scripts to explore the dataset, preprocess the data, and run machine learning modelling process using Azure ML.

You can recreate this virtual environment using `conda` or `mamba` using the `requirements.txt` file. For the `train_model.ipynb` and `serve_snmptn.py` it is executed in the Azure ML Notebooks and Azure ML Endpoints to run the training process and serve the model.

At the time of this readme writing, the model has the accuracy of 70% using Gradient Boosting algorithm from `scikit-learn` library.

Video: still in progress
Presentation: https://docs.google.com/presentation/d/1PYp3iUQk7AS_qXICWVH6bCzVSjrARw7D/edit?usp=sharing&ouid=101893075820394963212&rtpof=true&sd=true
Demo: http://evangelion01.kodesiana.com/

Links to related repo:

- [Backend](https://github.com/fahminlb33/azurehackathon2022_backend)
- [Frontend](https://github.com/fahminlb33/azurehackathon2022_frontend) - [Upstream](https://github.com/ImBIOS/azurehackathon2022_frontend)
- [Data](https://github.com/fahminlb33/azurehackathon2022_data)
