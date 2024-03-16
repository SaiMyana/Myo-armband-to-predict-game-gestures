# Gesture Recognition with Myo Armband

## Overview
This repository contains the code and documentation for a gesture recognition system using the Myo armband. The system predicts the gestures performed by users based on sensor data captured by the Myo armband.

## Dataset Description
The dataset used for training and evaluation consists of sensor readings recorded while users perform three gestures namely rock, paper, scissor. Each entry in the dataset includes sensor data along with metadata such as the label indicating the performed gesture, recording time, arm used, battery level, and connection quality. But here I did not use the metadata information.

## Methodology

#Reading Data: Aggregate data from multiple CSV files within subdirectories and concatenate them into a single DataFrame while also computing some statistics for each gesture. 
#Preprocessing: Data preprocessing involves handling missing values and normalizing features. Features extracted include sensor readings and additional features such as gesture duration and muscle activity intensity.

## Model Selection and Training:

Implemented machine learning algorithms include:
k-Nearest Neighbors (KNN)
Random Forest
XGBoost
TensorFlow (neural networks)
Each model is trained on the preprocessed dataset to predict the performed gestures.
Model Evaluation: Evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess the performance of each model. Cross-validation techniques are employed for robust evaluation.

Comparative Analysis: Performance of each model is compared to determine the best-performing model for gesture prediction.

