# Skin Cancer Classification using CNN

## Project Overview
A deep learning solution to detect melanoma in images of skin lesions. The project aims to build a CNN based model which can evaluate images and alert dermatologists about the presence of melanoma, helping reduce manual effort in diagnosis.

## Problem Statement
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). The data set contains 9 classes of skin cancer:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Project Pipeline
1. Data Reading/Data Understanding
2. Dataset Creation
3. Dataset Visualization 
4. Model Building & training
5. Model Building & training on augmented data
6. Class distribution analysis
7. Model Building & training on rectified class imbalance data

## Technologies Used
- Python 3
- TensorFlow 2.x
- Keras
- Augmentor
- NumPy
- Pandas
- Matplotlib

## Conclusions
1. Initial model showed signs of underfitting with low accuracy
2. Data augmentation improved model performance
3. Class balancing significantly improved model accuracy to 93% training and 66% validation
4. Final model shows some overfitting, suggesting need for further regularization

## Contact
Created by [siddharthmailbox85@gmail.com] - feel free to contact me!
