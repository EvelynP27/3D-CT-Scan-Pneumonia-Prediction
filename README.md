# 3D-CT-Scan-Pneumonia-Prediction

## Overview
This repository contains a machine-learning project focused on building a 3D convolutional neural network to predict the presence of viral pneumonia in CT scans. 

## Dataset
The dataset used for this project consists of 200 samples of lung CT scans. The dataset was obtained from [MosMedData: Chest CT Scans with COVID-19 Related Findings](https://www.medrxiv.org/content/10.1101/2020.05.20.20100362v1)

## Approach
- Importing data: Reading, normalizing, and resizing images
- Model training: Training the selected algorithm on the preprocessed dataset.
- Model evaluation: Assessing the performance of the trained model using val_accuracy

## Results

<img width="715" alt="image" src="https://github.com/EvelynP27/3D-CT-Scan-Pneumonia-Prediction/assets/171450202/9858b7ae-e42c-4047-a6c1-b75817b821fa">

<img width="715" alt="image" src="https://github.com/EvelynP27/3D-CT-Scan-Pneumonia-Prediction/assets/171450202/66cccddf-57df-43cc-9bb0-164c1e980348">


## Usage
1. Open this [link](https://colab.research.google.com/drive/1kl7IaIosr33FSTU-9VCxXcRO457Naq-Q?usp=sharing) to access the Google Colab file and make a copy

2. Run the Google Colab to preprocess the data, train the model, and make predictions.

## Technologies Used
- Programming languages: Python
- Libraries: Tensorflow, Numpy, Keras, Scipy, Matplotlib
