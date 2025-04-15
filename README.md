# MRI_BRAIN_TUMOR_SEGMENTATION_USING_DEEP_LEARNING

# MRI Brain Tumor Segmentation using Deep Learning Architecture

This project focuses on developing a deep learning-based image classification system for the detection of brain tumors using MRI (Magnetic Resonance Imaging) scans. The core of the project is a custom-built Convolutional Neural Network (CNN) model tailored for binary classification. 

## Key Features

* **Automated Brain Tumor Detection:** Applies CNNs to automate and enhance the diagnostic process. 
* **Image Preprocessing:** Includes resizing, normalization, and augmentation to prepare MRI images for modeling. 
* **Custom CNN Architecture:** Employs multiple convolutional layers, pooling layers, and dense layers for feature extraction and classification. 
* **Performance Evaluation:** Assesses model performance using accuracy, precision, recall, and F1-score. 

## Project Description

The project addresses the challenges of manual diagnosis of brain tumors from MRI scans, which can be time-consuming and prone to error. By leveraging deep learning techniques, particularly CNNs, the system aims to provide an automated, accurate, and efficient tool to assist radiologists in detecting brain tumors. 

## Objectives

1.  Collect and preprocess a labeled dataset of brain MRI images. 
2.  Design and train a CNN-based deep learning model for binary classification (tumor/no tumor). 
3.  Evaluate the model using standard performance metrics. 
4.  Visualize training progress and interpret results using a confusion matrix and performance graphs. 
5.  Identify opportunities for improving and expanding the model for real-world deployment. 

## Technical Specifications

* **Hardware:** The project uses standard hardware specifications. 
* **Software:** Python, TensorFlow, Keras, OpenCV. 

## System Architecture

The system architecture includes:

* **DataLoader:** For ingesting and preprocessing MRI scans. 
* **ResNet50 Base Model:** A pre-trained ResNet50 model for feature extraction. 
* **TumorClassifier:** A custom classifier for tumor detection. 
* **GradCAM Module:** For visualizing important regions in the MRI scans. 
* **Utilities:** Supporting functions for the system. 

## Results

The project demonstrates the potential of deep learning to improve the accuracy and efficiency of brain tumor detection. The CNN model achieved high accuracy in distinguishing between MRI images with and without tumors. 

## Future Enhancements

* Multi-class classification to distinguish between different types of brain tumors. 
* Real-time deployment and integration with clinical systems. 
* Expanding the model to support 3D MRI data. 

## Acknowledgements

The authors would like to thank the Vellore Institute of Technology (VIT) and the faculty of the School of Computer Science and Engineering (SCOPE) for their support and guidance.

## Contributors

* PRANTIK CHAKRABORTY (21BCE0003)
* KRISH PATEL (21BCE0020)
* Supervisor: AJU D
