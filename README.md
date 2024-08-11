# Automated Detection andSegmentation of Oral Tumors using 3D SegResNet 

## Overview
This project focuses on the automated detection and segmentation of oral tumors in 3D images using MONAI's SegResNet. 

#### The goal is to create a model capable of accurately identifying and segmenting tumor regions in medical images, aiding in early diagnosis and treatment planning.

## Relevant Medical Explanations
Heart diseases are one of the leading causes of mortality worldwide, often resulting from a combination of genetic and environmental factors. Early identification of heart disease risks can improve quality of life and reduce mortality. Machine learning models can detect complex patterns in medical data and support medical decision-making.

## Data Preparation
### 1. Convert DICOM to NIfTI: 
The DICOM series of images are converted to NIfTI format after correcting spatial orientation.
### 2. Image Resizing and Stretching:
Images and labels were resized, and the images were also stretched to ensure uniformity in the dataset.
### 3. Visualization:
Tumor regions are visualized to confirm the correctness of the data preparation.

## Data Division
The data used in this project was divided into a training set and a testing set in a 80:20 ratio.

## Model Performance
The model achieved a mean dice of 85% on test samples. Hopefully, with an expended dataset and optimizimg model features we will get better performances.

## Conclusions
This project successfully identifies abnormal tumor regions. By leveraging MONAI’s SegResNet, we achieved accurate segmentation results, as demonstrated by the high Dice coefficient scores and the genrated label for given image. (As shown in the 'Check_model' notebook)


## Credits
- Developer: Levona Hayoun
- Supervisors: Dr. Moshe Amitai & Dr. Talya Yeshua
- Data Source: Hadassah Eun Kerem hospital
- Description: Oral Tumors Dtection using SegResNet.
