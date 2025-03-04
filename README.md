# Fashion MNIST Pattern Recognition

## Overview
This project focuses on classifying clothing categories using the Fashion MNIST dataset. A deep learning model was built to recognize patterns in grayscale images of fashion items, demonstrating the effectiveness of CNNs in image classification.

## Dataset
The **Fashion MNIST** dataset consists of 70,000 grayscale images (28x28 pixels) categorized into 10 classes:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Methodology
### Data Preprocessing
- **Normalization**: Pixel values were scaled to the range [0,1] for improved model convergence.
- **Train-Test Split**: The dataset was divided into training and testing subsets.

### Model Architecture
A **Sequential CNN model** was implemented using:
- **Convolutional Layers**: Extract spatial features from images.
- **Pooling Layers**: Reduce dimensionality and improve generalization.
- **Dense Layers**: Fully connected layers for classification.
- **Softmax Activation**: Output probability distribution for class labels.

### Model Evaluation
- The trained model was evaluated on the test set, achieving high accuracy in classifying clothing categories.
- Performance metrics included accuracy, loss curves, and confusion matrix analysis.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python (>=3.7)
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
