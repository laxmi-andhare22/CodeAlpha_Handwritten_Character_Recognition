# Handwritten Character Recognition - CodeAlpha Internship

## Task 3: Handwritten Character Recognition

This project recognizes handwritten characters (0-9) using Deep Learning and CNN.

### 🚀 Tech Stack
- Python
- TensorFlow / Keras
- CNN (Convolutional Neural Network)
- MNIST Dataset

### 📂 Dataset
MNIST Dataset - 70,000 images of handwritten digits (28x28 pixels)

### 🧠 Model Architecture
- Conv2D (32 filters) + MaxPooling
- Conv2D (64 filters) + MaxPooling
- Flatten + Dense (128 neurons)
- Output Layer (10 classes with softmax)
- Accuracy: ~98%

### ▶️ How to Run
```bash
pip install tensorflow numpy
python main.py
