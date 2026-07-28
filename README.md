# CodeAlpha_HandwrittenCharacterRecognition
# 📝 Handwritten Character Recognition using CNN

A Deep Learning project that recognizes handwritten digits using a **Convolutional Neural Network (CNN)** trained on the **MNIST dataset**. The model learns image patterns and predicts handwritten numbers with high accuracy.

---

## 📌 Project Overview

Handwritten Character Recognition is one of the most common computer vision applications. This project uses TensorFlow and Keras to build a CNN model capable of classifying handwritten digits (0–9).

The project includes:

- Dataset loading
- Image preprocessing
- CNN model building
- Model training
- Performance evaluation
- Accuracy visualization
- Model saving
- Digit prediction

---

## 🚀 Features

✅ Automatic MNIST dataset loading

✅ Image normalization and preprocessing

✅ Convolutional Neural Network (CNN)

✅ Training and validation accuracy tracking

✅ Model evaluation on test dataset

✅ Prediction visualization

✅ Saves trained model

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

## 📂 Project Structure

```
CodeAlpha_HandwrittenCharacterRecognition/
│
├── dataset/
├── models/
│   └── handwritten_model.h5
│
├── outputs/
│   └── accuracy_graph.png
│
├── screenshots/
│
├── main.py
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

**MNIST Dataset**

- 70,000 handwritten digit images
- Image Size: **28 × 28 pixels**
- 60,000 Training Images
- 10,000 Testing Images
- Classes: **0–9**

---

## 🧠 CNN Architecture

```
Input (28×28×1)

↓

Conv2D (32 Filters, 3×3)

↓

MaxPooling2D

↓

Conv2D (64 Filters, 3×3)

↓

MaxPooling2D

↓

Flatten

↓

Dense (128 Neurons)

↓

Dropout (0.3)

↓

Dense (10 Neurons)

↓

Softmax Output
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/CodeAlpha_HandwrittenCharacterRecognition.git
```

Move into the project folder

```bash
cd CodeAlpha_HandwrittenCharacterRecognition
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python main.py
```

---

## 📈 Training Process

The model performs the following steps:

1. Loads MNIST dataset
2. Normalizes images
3. Reshapes images for CNN
4. Converts labels using One-Hot Encoding
5. Trains the CNN model
6. Evaluates test accuracy
7. Saves trained model
8. Displays predictions
9. Generates accuracy graph

---

## 📊 Output

After training, the project generates:

- Trained CNN Model
- Test Accuracy
- Prediction Samples
- Accuracy Graph

---

## 📷 Sample Output

Add screenshots inside the **screenshots/** folder.

Example:

```
screenshots/
│
├── training.png
├── predictions.png
└── accuracy_graph.png
```

---

## 📦 Requirements

```
tensorflow
numpy
matplotlib
```

Install them using:

```bash
pip install -r requirements.txt
```

---

## 🎯 Future Improvements

- Support handwritten alphabet recognition
- Real-time webcam prediction
- GUI using Tkinter
- Streamlit Web Application
- Model optimization
- Support custom image uploads

---

## 👨‍💻 Author

**Bhuvanasivakrishna**

B.Tech CSE (AI & ML)

GITAM University

---

## 📜 License

This project is developed for educational and learning purposes.

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub and share it with others!
