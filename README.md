# ✍️ Interactive Handwritten Digit Recognition Using CNN

A Convolutional Neural Network (CNN) implementation for handwritten digit recognition using the MNIST dataset. This project is developed with TensorFlow and Keras and includes an interactive drawing canvas built with `ipycanvas`, allowing users to draw digits and obtain real-time predictions directly in Google Colab.

---

## Project Overview

This project demonstrates the complete workflow of a deep learning image classification system, including:

- Data preprocessing
- CNN model development
- Model training and evaluation
- Performance visualization
- Interactive handwritten digit prediction
- Model saving and reloading

The trained model achieves a **99.55% test accuracy** on the MNIST dataset.

---

## Features

- CNN-based handwritten digit recognition
- Interactive drawing canvas
- Real-time digit prediction
- Prediction confidence score
- Top-3 predicted classes
- Accuracy and loss visualization
- Confusion matrix
- Classification report
- Saved trained model (`.keras`)
- Google Colab compatible

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV
- Pillow
- ipycanvas
- ipywidgets

---

## Dataset

The model is trained using the **MNIST Handwritten Digits Dataset**.

| Property | Value |
|----------|-------|
| Training Images | 60,000 |
| Testing Images | 10,000 |
| Classes | 10 (Digits 0–9) |
| Image Size | 28 × 28 |

---

## CNN Architecture

The network consists of the following layers:

- Conv2D (32 filters)
- Batch Normalization
- Conv2D (32 filters)
- Max Pooling
- Dropout
- Conv2D (64 filters)
- Batch Normalization
- Conv2D (64 filters)
- Max Pooling
- Dropout
- Flatten
- Dense (256 neurons)
- Dropout
- Dense (10 neurons, Softmax)

---

## Model Performance

| Metric | Value |
|---------|------:|
| Test Accuracy | **99.55%** |
| Precision | ~99% |
| Recall | ~99% |
| F1-Score | ~99% |

The trained model performs consistently on unseen handwritten digit images and is capable of recognizing user-drawn digits with high accuracy.

---

## Results

### Training Accuracy and Loss

![Training Accuracy](images/accuracy_loss.png)

The graph shows the improvement in training and validation performance over multiple epochs, indicating stable convergence with minimal overfitting.

---

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

The confusion matrix demonstrates that the trained CNN correctly classifies almost all handwritten digits, with very few misclassifications.

---

### Interactive Drawing Canvas

![Canvas](images/canvas.png)

Users can draw a handwritten digit directly within Google Colab using an interactive canvas powered by **ipycanvas**.

---

### Example Prediction

![Prediction](images/example_prediction.png)

After preprocessing the drawn digit, the model predicts the digit along with its confidence score and the top three predicted classes.

---

## Project Structure

```
Handwritten-Digit-Recognition-CNN/
│
├── Interactive_Handwritten_Digit_Recognition_Using_CNN.ipynb
├── handwritten_digit_cnn.keras
├── requirements.txt
├── README.md
└── images/
    ├── accuracy_loss.png
    ├── canvas.png
    ├── confusion_matrix.png
    └── example_prediction.png
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/tharakvenkat/Handwritten-Digit-Recognition-CNN.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

1. Open the notebook in Google Colab.
2. Install the required dependencies.
3. Run all notebook cells.
4. Train the CNN model or load the saved model.
5. Draw a handwritten digit using the interactive canvas.
6. Execute the prediction cell to obtain the predicted digit, confidence score, and top three probabilities.

---

## Future Enhancements

- Deploy as a Streamlit web application
- Support multi-digit recognition
- Extend the model to the EMNIST dataset
- Improve preprocessing for handwritten paper images
- Integrate webcam-based digit recognition

---

## Author

**Tharak Venkat**

B.Tech – Computer Science Engineering  
VIT-AP University

GitHub: https://github.com/tharakvenkat

---

## License

This project is intended for educational purposes.
