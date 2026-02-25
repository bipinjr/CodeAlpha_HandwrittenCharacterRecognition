# CodeAlpha_HandwrittenCharacterRecognition

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lRzbVEJOcFYAJ9nKRXG2Pkw7yaRjiPGM)

## Overview
This project implements a Handwritten Character Recognition system for the CodeAlpha Machine Learning Internship (Task 3). The model uses Convolutional Neural Networks (CNN) to identify handwritten digits from the MNIST dataset with high accuracy.

## Features
- **Deep Learning Architecture**: Custom CNN model with multiple convolutional layers
- **MNIST Dataset**: 60,000 training images and 10,000 test images of handwritten digits (0-9)
- **Data Preprocessing**: Normalization and reshaping for optimal CNN performance
- **Comprehensive Evaluation**: Accuracy metrics, classification reports, and confusion matrix
- **Visualizations**: 
  - Sample digit images from dataset
  - Class distribution analysis
  - Training/validation accuracy and loss curves
  - Confusion matrix heatmap
  - Per-class accuracy breakdown

## Technologies Used
- **Python 3.x**
- **TensorFlow / Keras** - Deep learning framework
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Evaluation metrics

## Model Architecture
The CNN model consists of:
- **Convolutional Layers**: 3 Conv2D layers (32, 64, 64 filters)
- **Pooling Layers**: MaxPooling2D for dimensionality reduction
- **Dense Layers**: Fully connected layer with 64 neurons
- **Dropout**: 0.5 dropout rate to prevent overfitting
- **Output Layer**: Softmax activation for 10-class classification

## Dataset
- **Name**: MNIST (Modified National Institute of Standards and Technology)
- **Images**: 28x28 grayscale pixels
- **Classes**: 10 (digits 0-9)
- **Training Samples**: 60,000
- **Test Samples**: 10,000

## Results
The model achieves excellent performance on the MNIST test set:
- **High test accuracy** (typically >98%)
- **Strong per-class performance** across all digits
- **Detailed confusion matrix** showing prediction patterns
- **Training completed in 10 epochs** with validation monitoring

## How to Run
1. Click the "Open in Colab" badge above
2. Run all cells in sequence (Runtime → Run all)
3. View the training progress and visualizations
4. Analyze the model performance metrics

## Project Structure
```
├── Data Loading & Exploration
├── Data Visualization
├── Data Preprocessing
├── CNN Model Building
├── Model Training
├── Performance Visualization
└── Evaluation & Metrics
```

## Key Insights
- CNN architecture is highly effective for image classification tasks
- Proper data normalization significantly improves model convergence
- Dropout layers help prevent overfitting on training data
- MNIST digits show excellent inter-class separability

## Future Enhancements
- Extend to EMNIST for full alphabet recognition
- Implement data augmentation for improved robustness
- Add sequence modeling (CRNN) for word/sentence recognition
- Deploy as a web application for real-time predictions

## Author
**Bipin JR** - CodeAlpha Machine Learning Internship Program

## Acknowledgments
- CodeAlpha for the internship opportunity
- MNIST dataset creators
- TensorFlow/Keras community

---
*Completed as part of CodeAlpha Machine Learning Internship - Task 3*
