# Brain Tumor MRI Classification using Transfer Learning

## Project Overview

This project implements a deep learning approach for classifying brain tumor MRI images using transfer learning. A pre-trained Convolutional Neural Network (CNN) is fine-tuned on a brain tumor dataset to improve classification performance on medical imaging data.

The objective of this project was to apply modern deep learning techniques to a real-world healthcare problem and evaluate model performance using standard classification metrics.

---

## Problem Statement

Brain tumor detection from MRI scans is a critical task in medical diagnostics. Manual analysis can be time-consuming and prone to variability. This project explores how transfer learning can assist in automating tumor classification with improved accuracy and efficiency.

---

## Approach

1. Data preprocessing:
   - Image resizing
   - Normalization
   - Data splitting (training and testing)

2. Transfer Learning:
   - Used a pre-trained CNN model
   - Fine-tuned selected layers
   - Added custom classification layers

3. Model Training:
   - Optimization using appropriate loss functions
   - Monitoring validation performance

4. Evaluation:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Project Structure

Brain_Tumor_Classification/
│
├── Brain_tumor_classification.ipynb
├── README.md

---

## Key Features

- Transfer learning implementation
- Fine-tuning of pre-trained CNN model
- Structured preprocessing pipeline
- Performance evaluation using classification metrics
- Medical image classification workflow

---

## Results and Observations

- Transfer learning significantly improves classification performance compared to training from scratch.
- Fine-tuning deeper layers enhances feature extraction for medical imaging data.
- Proper preprocessing and normalization contribute to stable training performance.

(Performance metrics can be added here if required.)

---

## Future Improvements

- Experiment with multiple pre-trained architectures
- Apply data augmentation techniques
- Implement cross-validation
- Deploy the model using a web interface
- Explore explainability techniques (Grad-CAM)

---

## Author

Tanya Mediratta  
