# 🐶 Cats vs Dogs Image Classifier using CNN

A deep learning project built with TensorFlow and Keras to classify images of cats and dogs using Convolutional Neural Networks (CNN). The model is trained on the popular Kaggle dataset and achieves over 92% training accuracy.

---

## 📦 Dataset

- **Source:** [Kaggle – Dogs vs Cats](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- **Size:** 25,000 labeled images (20,000 for training, 5,000 for testing)
- **Content:** JPEG images of dogs and cats in separate folders

---

## 🚀 Setup & Download

### 🔐 Step 1: Upload Kaggle API Key

```python
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json  # Fix permissions
