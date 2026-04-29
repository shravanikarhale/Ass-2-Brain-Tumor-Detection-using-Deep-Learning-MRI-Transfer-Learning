Course Information
Field	Details
Course Name	Deep Learning
Lab Title	Research Paper Implementation with Pre-trained Model (Brain Tumor Detection using CNN)

Student Name	 Shravani Karhale

Student ID	   202301040139

Group Members
Name	             PRN
Shreyasi Bidkar	  202301040042

Nikita Bansod	    202301040110

Shravani Karhale	202301040139

Nishi Agarwal	    202301040219

Project Overview

This project implements a Deep Learning-based Brain Tumor Detection System using MRI images.
A pre-trained Convolutional Neural Network (CNN) model is used to classify brain scans into tumor and non-tumor categories.

The system demonstrates how AI can assist in medical diagnosis by improving speed and accuracy.

Objectives
Study and understand research paper methodology
Implement tumor detection using deep learning
Apply transfer learning using pre-trained models
Train and evaluate model performance
Build an end-to-end AI system

Dataset
Field	Details
Dataset Name	Brain Tumor MRI Dataset

Source	Kaggle
Link	https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

Type	MRI Images
Classes	Tumor / No Tumor
Problem Statement

To develop a model that can:

Analyze MRI brain scans
Detect the presence of tumors
Classify images accurately
 Methodology
1. Data Preprocessing
Image resizing
Normalization
Train-test split

2. Model Development
Pre-trained CNN (MobileNet / ResNet)
Fine-tuning layers

3. Training
Optimizer: Adam
Loss: Categorical Crossentropy

4. Evaluation
Accuracy
Loss
Confusion Matrix


Model Architecture
Input Image
     ↓
Pre-trained CNN (Feature Extraction)
     ↓
Fully Connected Layer
     ↓
Softmax Layer
     ↓
Output (Tumor / No Tumor)


Training Configuration
Parameter	  Value
Epochs	     10–20
Batch Size  	32
Optimizer 	Adam
Loss Function	Categorical Crossentropy

Results
Achieved good classification accuracy
Model successfully detects tumor presence
Performance improves with more training and data

Sample Predictions
Input	Output
MRI Image	Tumor
MRI Image	No Tumor


Requirements
tensorflow
keras
numpy
matplotlib
opencv-python
scikit-learn



References
Kaggle Brain Tumor Dataset
TensorFlow Documentation
Keras Documentation
Research Papers on Medical Image Classification

Conclusion

This project shows how deep learning can be used in healthcare applications for early tumor detection.
The model provides reliable results and can assist doctors in diagnosis.

Future Work
Use advanced models (ResNet50, EfficientNet)
Improve dataset size
Deploy as web application
Enhance accuracy
