# 😷 Face Mask Detection using CNN  
A deep learning project that classifies whether a person is **wearing a mask** or **not** using a **Convolutional Neural Network (CNN)** built with TensorFlow & Keras. Trained on a custom image dataset to support safety in public spaces.

---
## 📌 Features

✅ Real-time face mask detection  
✅ Built using CNN from scratch (no transfer learning)  
✅ Visualized model performance  
✅ Easy-to-follow Jupyter Notebook  
✅ Ideal for beginners in Deep Learning

---

## 🧠 Model Architecture

- 🧱 **Conv2D + MaxPooling**
- 🚪 **Dropout (to prevent overfitting)**
- 🧮 **Dense layers with ReLU + Softmax**
- 🎯 **Binary classification (Mask / No Mask)**

---

## 🗃️ Dataset

> Assumed structure:
```
dataset/
 ┣ with_mask/
 ┗ without_mask/
```
- Each class contains nearly balanced data
- Image size: Resized to 100x100 for training

---

## 📊 Results

| Metric     | Value     |
|------------|-----------|
| Accuracy   | ~92%      |
| Loss       | Very Low  |
| Training Time | ~3 mins on GPU |

📈 Includes graphs for:
- Accuracy vs Epochs  
- Loss vs Epochs

---

## 🚀 Quick Start

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/face-mask-detection-cnn.git
cd face-mask-detection-cnn
```
### 2. Run the notebook
Launch `Face_Mask_Detection_using_cnn.ipynb` in Jupyter or Colab.

---

## 🧾 Requirements

- Python 3.8+
- TensorFlow / Keras
- NumPy
- OpenCV (optional for future real-time webcam detection)
- Matplotlib

---

## 🙌 Contributing

Got an idea or want to improve the project? Fork it, clone it, and raise a pull request!  
Your contributions are highly appreciated 💙

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
