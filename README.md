## Project Description
This project implements a Convolutional Neural Network (CNN) for handwritten digit recognition using the MNIST dataset using TensorFlow and Keras.

---

## Dataset
MNIST Dataset:
https://keras.io/api/datasets/mnist/

---

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

## Data Preprocessing
The following preprocessing steps were applied:
- Normalization
- Reshaping
- One-Hot Encoding

---

## Model Architecture
The CNN model contains:
- Convolutional Layers
- MaxPooling Layers
- Batch Normalization
- Dropout
- Dense Layers

---

## Experiments

### Experiment 1
Optimizer: Adam

Results:
- Accuracy: 99%
- Loss: 0.029

### Experiment 2
Optimizer: SGD

Results:
- Accuracy: 98.43%
- Loss: 0.048

---

## Results Comparison

| Model | Accuracy | Loss |
|-------|-----------|------|
| CNN + Adam | 99% | 0.029 |
| CNN + SGD | 98.43% | 0.048 |

---

## Visualizations
The project includes:
- Training vs Validation Accuracy Curves
- Training vs Validation Loss Curves

---

## How to Run
1. Open the notebook in Google Colab
2. Run all cells sequentially
3. Train and evaluate the model
