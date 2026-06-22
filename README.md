# Intel-Image-classification_CNN
CNN Image Classification using TensorFlow and Keras on the Intel Image Classification Dataset with data augmentation, model evaluation, confusion matrix, and prediction visualization.


# CNN Image Classification using TensorFlow

## Project Overview

This project implements a Convolutional Neural Network (CNN) for image classification using the Intel Image Classification Dataset. The model classifies natural scene images into six categories: Buildings, Forest, Glacier, Mountain, Sea, and Street.

## Dataset

The Intel Image Classification Dataset contains more than 25,000 images distributed among six classes:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

Dataset Source:
https://www.kaggle.com/datasets/puneet6060/intel-image-classification

---

## Project Workflow

### Data Preprocessing

- Image resizing to 150 × 150 pixels
- Pixel value normalization
- Training, validation, and test split
- Data augmentation using rotation, zoom, shift, and horizontal flip

### CNN Architecture

- Three convolutional layers
- ReLU activation function
- Max Pooling layers
- Fully connected dense layer
- Dropout layer for regularization
- Softmax output layer

### Model Training

- Adam optimizer
- Categorical cross-entropy loss
- Early stopping
- Model checkpointing

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Visualization

- Training and validation accuracy curves
- Training and validation loss curves
- Prediction results on test images

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Results

The CNN model achieves approximately 85–90% accuracy on the Intel Image Classification Dataset.

---

## Author

Suhaila P T

GitHub:
https://github.com/YOUR_USERNAME
