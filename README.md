# 🖼️ Fruits & Vegetables Image Classification

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

A Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify images of fruits and vegetables. The project covers the full deep learning pipeline from data preprocessing and model architecture to training, evaluation, and prediction on unseen images.

---

## 🧠 Model Architecture

Sequential CNN designed for multi-class image classification:

| Layer | Details |
|-------|---------|
| Rescaling | Normalize pixel values to [0, 1] |
| Conv2D + ReLU | 16 filters |
| MaxPooling2D | Reduce spatial dimensions |
| Conv2D + ReLU | 32 filters |
| MaxPooling2D | Reduce spatial dimensions |
| Conv2D + ReLU | 64 filters |
| MaxPooling2D | Reduce spatial dimensions |
| Flatten | Convert to 1D |
| Dropout | 20% — prevent overfitting |
| Dense | 128 units |
| Output Layer | Softmax — multi-class classification |

---

## ⚙️ Training Configuration

| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Loss Function | Sparse Categorical Crossentropy |
| Metric | Accuracy |
| Strategy | Train/Validation split |

---

## 📊 Evaluation

- Training vs validation accuracy and loss visualized across epochs
- Final evaluation on unseen test data for real performance estimation
- Iterative hyperparameter tuning to improve accuracy

---


## 👤 Author

**Ali Mohamed** — CS Graduate | AI & ML Engineer | Qatar

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/vksox1404-web)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ali-mohamed-5777b2403)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/Vksox)
