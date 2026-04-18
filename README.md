#  Fruits & Vegetables Image Classification

A Convolutional Neural Network (CNN) implemented in TensorFlow/Keras, designed to classify images of fruits and vegetables. The project demonstrates model architecture, training process, evaluation, and prediction on unseen data.

---

##  Features & Highlights

- **Clear Layered Architecture**: Sequential CNN with:
  - Rescaling → Convolutional (16, 32, 64 filters) + ReLU + Max-Pooling
  - Flatten layer → Dropout (20%) → Dense (128 units) → Output layer
- **Robust Training Pipeline**:
  - Optimizer: **Adam**
  - Loss: **Sparse Categorical Crossentropy**
  - Metrics: **Accuracy**
  - Train–Val split strategy for early stopping insights
- **Comprehensive Evaluation**:
  - Visualizations of training vs. validation accuracy and loss
  - Final model run on test set for real performance estimation
- **User-friendly Prediction**:
  - Load and predict on individual images with a simple function call

---

##  Getting Started

To run this project locally:

```bash
git clone https://github.com/01End/image-classification.git
cd image-classification
# Use virtual env if preferred
pip install -r requirements.txt
