# 🌾 Rice Leaf Disease Detection using CNN

An intelligent deep learning model to classify rice leaf diseases (**Blast, Blight, Tungro**) using Convolutional Neural Networks (CNN). This system helps in early disease detection, improving crop management and yield.

---

## 📂 Dataset

- Source: https://www.kaggle.com/datasets/tedisetiady/leaf-rice-disease-indonesia
- Contains labeled images of rice leaves across multiple disease categories.

---

## 🚀 Project Structure

```
├── Rice_leaf_detection_using_cnn_model_.ipynb
├── images/
│   ├── sample prediction.png
│   ├── loss graph.png
│   ├── confusion matrix.png
│   ├── accuracy graph.png
└── README.md
```

---

## 🧠 Model Overview

- Model: Convolutional Neural Network (CNN)
- Framework: TensorFlow / Keras
- Classes: Blast, Blight, Tungro
- Task: Multi-class Image Classification

---

## 📊 Results & Visualizations

### 📈 Accuracy Graph
![Accuracy Graph](images/accuracy%20graph.png)

### 📉 Loss Graph
![Loss Graph](images/loss%20graph.png)

### 🔍 Confusion Matrix
![Confusion Matrix](images/confusion%20matrix.png)

### 🧪 Sample Prediction
![Sample Prediction](images/sample%20prediction.png)

Predicted Class : tungro  
Confidence      : 75.97%  
Model Accuracy  : 84.72%  

---

## ⚙️ Features

- Image preprocessing & normalization  
- CNN-based feature extraction  
- Model training with validation tracking  
- Performance visualization (Accuracy, Loss)  
- Confusion matrix evaluation  

---

## 🛠️ How to Run

```
git clone https://github.com/your-username/rice-leaf-disease-detection.git
cd rice-leaf-disease-detection
pip install tensorflow matplotlib numpy pandas scikit-learn
jupyter notebook
```

---

## 📌 Key Insights

- Achieved ~84.7% accuracy on validation data  
- Model performs best on Tungro detection  
- Some confusion between Blast and Blight  

---

## 🔮 Future Improvements

- Use Transfer Learning (ResNet / EfficientNet)  
- Deploy as web/mobile app  
- Increase dataset size  
- Real-time detection  

---

## 📜 License

MIT License
