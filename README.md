# Deep Learning-Based Pneumonia Detection from Chest X-Ray Images Using CNN

This project presents a deep learning-based approach for detecting pneumonia from chest X-ray images using a Convolutional Neural Network (CNN) implemented in MATLAB.

## Project Overview

The system classifies chest X-ray images into two categories:

- NORMAL
- PNEUMONIA

The images are resized to 150 × 150 pixels and processed using a custom CNN architecture. The trained model is evaluated using accuracy, precision, recall, F1-score, specificity, confusion matrix, and ROC-AUC.

## Methodology

1. Chest X-ray image dataset preparation
2. Image preprocessing and resizing
3. Training and validation data splitting
4. CNN model development
5. Model training using Adam optimizer
6. Model testing on unseen test images
7. Performance evaluation
8. ROC curve and confusion matrix generation
9. Single-image pneumonia prediction

## Model Performance

The model achieved the following results on the test dataset:

- Accuracy: 74.04%
- Precision: 70.73%
- Recall: 99.74%
- F1-Score: 82.77%
- Specificity: 31.20%
- ROC-AUC: 0.9351

## Technologies Used

- MATLAB R2026b
- Deep Learning Toolbox
- Convolutional Neural Networks
- Image Processing
- Python/Matplotlib for performance visualization

## Output

The project generates:

- Confusion Matrix
- Performance Metrics
- ROC Curve
- Training Accuracy Curve
- Training and Validation Loss Curve
- Single Chest X-Ray Prediction

## Disclaimer

This project is developed for academic and research purposes. It is not intended to replace professional medical diagnosis or clinical decision-making.
