# 🧠 Handwritten Digit Recognition Using Convolutional Neural Networks (CNN)

A deep learning project that recognizes handwritten digits (0–9) using a Convolutional Neural Network (CNN) trained on the MNIST dataset. The project also includes an interactive drawing canvas where users can draw a digit and receive real-time predictions.

---

## 📌 Project Overview

This project demonstrates image classification using a CNN built with TensorFlow and Keras. The model is trained on the MNIST handwritten digit dataset and achieves approximately **99.55% test accuracy**.

An interactive canvas allows users to draw digits directly in Google Colab and instantly obtain predictions along with confidence scores.

---

## ✨ Features

- CNN-based handwritten digit recognition
- Trained on the MNIST dataset
- Test Accuracy: **99.55%**
- Interactive drawing canvas
- Real-time digit prediction
- Confidence score for predictions
- Top-3 predicted digits
- Classification report
- Confusion matrix visualization
- Model saving and loading using `.keras`

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV
- ipycanvas
- ipywidgets
- Google Colab

---

## 🧠 CNN Architecture

The model consists of:

- Input Layer (28×28×1)
- Conv2D (32 filters)
- Batch Normalization
- Conv2D (32 filters)
- MaxPooling
- Dropout
- Conv2D (64 filters)
- Batch Normalization
- Conv2D (64 filters)
- MaxPooling
- Dropout
- Flatten Layer
- Dense (256 neurons)
- Dropout
- Output Layer (10 neurons with Softmax)

---

## 📊 Model Performance

| Metric | Value |
|---------|-------|
| Training Accuracy | 99%+ |
| Validation Accuracy | 99%+ |
| Test Accuracy | **99.55%** |

The model performs exceptionally well on unseen handwritten digit images and generalizes effectively.

---

## 📁 Project Structure

```
Handwritten-Digit-Recognition-CNN/
│
├── Handwritten_Digit_Recognition.ipynb
├── handwritten_digit_cnn.keras
├── requirements.txt
├── README.md
└── images/
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/tharakvenkat/Handwritten-Digit-Recognition-CNN.git
```

Move into the project directory:

```bash
cd Handwritten-Digit-Recognition-CNN
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Run all cells.
3. Train or load the saved model.
4. Draw a digit on the interactive canvas.
5. Click **Predict Digit**.
6. View the predicted digit, confidence score, and top three predictions.

---

## 📸 Screenshots

Add screenshots here after uploading them to the `images` folder.

Example:

- Training Accuracy Graph
- Confusion Matrix
- Drawing Canvas
- Prediction Result

---

## 🔮 Future Improvements

- Support recognition of multiple handwritten digits
- Deploy using Streamlit or Flask
- Improve preprocessing for handwritten paper images
- Train on larger handwritten datasets
- Mobile-friendly web interface

---

## 👨‍💻 Author

**Tharak Venkat**

B.Tech Computer Science Engineering  
VIT-AP University

GitHub: https://github.com/tharakvenkat

---

## ⭐ If you like this project

Please consider giving this repository a ⭐ on GitHub.
