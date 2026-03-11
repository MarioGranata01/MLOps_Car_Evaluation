# Serverless ML Pipeline – Car Evaluation

## Overview

This project implements an automated **Machine Learning pipeline** based on a **serverless architecture**.

The system uses the **Car Evaluation Dataset** to classify the quality of cars based on several input features.

The pipeline automates the main stages of a typical Machine Learning workflow:

- Dataset upload (pipeline trigger)
- Data preprocessing
- Model training
- Inference service exposed through an HTTP endpoint

The model is trained using **scikit-learn**, and the application is containerized using **Docker**.

---

## Pipeline

The pipeline consists of the following stages:

- **Upload Dataset** – uploading the dataset file triggers the pipeline execution.
- **Preprocessing** – the dataset is cleaned and transformed to prepare it for model training.
- **Training** – a machine learning model is trained using the processed data.
- **Inference** – an HTTP endpoint allows users to send new data and obtain predictions in real time.

---

## Technologies

- Python
- scikit-learn
- Docker
