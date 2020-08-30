# Pneumonia Detection From Chest X-Rays

In this project, I will analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that aims to predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. As part of the submission preparation, I will formally describe my model, the data that it was trained on, and a validation plan that meets FDA criteria.

The project uses a dataset of 112,000 chest x-rays with disease labels acquired from 30,000 patients.

** Example Chest X-Rays of patients with and without Pneumonia **
![pneumonia examples](img/pneumonia_xrays.png)

## Key files

### June 2020

- [Exploratory Data Analysis of Chest X-ray dataset](https://github.com/pranath/pneumonia_detection/blob/master/EDA.ipynb)
- [Building & Training Model for Pneumonia Detection From Chest X-Rays](https://github.com/pranath/pneumonia_detection/blob/master/Build%20and%20train%20model.ipynb)
- [Pneumonia Detection Model - Clinical workflow integration test](https://github.com/pranath/pneumonia_detection/blob/master/Inference.ipynb)
- [FDA for 510(k) clearance report for Pneumonia Detection Model](https://github.com/pranath/pneumonia_detection/blob/master/FDA_Submission.pdf)

## Results

1. In the __[first project](https://github.com/pranath/pneumonia_detection/blob/master/Build%20and%20train%20model.ipynb)__ finished in June 2020, the best result was an overall F1 score for predicting Pneumonia of 0.03
