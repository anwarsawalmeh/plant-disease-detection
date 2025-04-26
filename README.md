# Plant Disease Detection using CNNs and Perceptron-Based Hybrid Ensemble

This project presents a deep learning-based system for classifying plant leaf diseases using multiple Convolutional Neural Network (CNN) architectures and a novel hybrid ensemble model. The goal is to provide an effective, scalable, and highly accurate method for early disease detection, particularly valuable in low-resource and rural agricultural settings.

## Overview

- Trained and evaluated CNN architectures: VGG-16, ResNet-50, and a custom 7-layer CNN
- Developed a hybrid perceptron-based ensemble model to optimize model selection and leverage individual strengths
- Achieved a peak classification accuracy of 98.71%
- Dataset used: PlantVillage
- Frameworks: PyTorch and TensorFlow
- Includes preprocessing, model training, evaluation, and hybrid ensemble logic

## Key Features

- Transfer learning with pre-trained models
- Data augmentation and preprocessing for robust model training
- Custom CNN architecture for lightweight deployment
- Perceptron ensemble to enhance classification generalization
- Performance evaluation with accuracy, precision, recall, F1-score, and confusion matrices

## Technologies Used

- Python 3.x
- PyTorch
- TensorFlow
- NumPy
- Matplotlib
- Scikit-learn
- OpenCV
## Current Status
**Important Notice: Experimental Phase**

The hybrid model is currently in an **experimental stage**. Although the model achieves **high classification accuracy** in **controlled lab settings** (using clean and structured datasets like PlantVillage), **real-world performance is yet to be validated**.  
Thus, **there is considerable room for improvement**, especially regarding:
- Generalization to **noisy**, **unstructured**, and **real-world environments**.
- Robustness to **dataset biases**, **environmental variability**, and **image quality variations**.
- Efficiency for deployment on **resource-constrained devices** (e.g., mobile, embedded systems).

Users and researchers are encouraged to view the current results as **proof-of-concept** rather than a production-ready solution.

## Key Points
- **High Lab Accuracy**: Model achieves strong results on curated datasets.
- **Real-World Caution**: Current results may not fully translate to field conditions without further adaptation.
- **Future Improvements**: Work is ongoing to enhance robustness, scalability, and deployment capabilities.
