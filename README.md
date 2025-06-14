# 🧠 SAGAN-DermMNIST-Generation

This project demonstrates a Self-Attention Generative Adversarial Network (SAGAN) trained on the **DermMNIST** dataset from the [MedMNIST](https://medmnist.com/) collection. The goal is to generate realistic 28×28 dermoscopic skin lesion images from random noise using deep generative modeling.

---

## 📊 Project Highlights

- **Dataset**: DermMNIST (7-class skin lesion dataset)
- **Model**: Self-Attention GAN (SAGAN) for better spatial consistency
- **Framework**: PyTorch
- **Training Environment**: Google Colab with GPU
- **Output**: Grid of generated lesion samples visualized every few epochs

---

## 🎥 Sample Output

Training visualization (GAN output over epochs):

![training gif](training_evolution.gif)

---

## 🧬 Dataset Info

DermMNIST consists of 10,015 28×28 RGB images categorized into:
- Actinic keratoses
- Basal cell carcinoma
- Benign keratosis-like lesions
- Dermatofibroma
- Melanocytic nevi
- Vascular lesions
- Melanoma

Source: [MedMNIST Benchmark](https://medmnist.com/)

---

## 🚀 Features

- Self-Attention layers in the generator to improve texture realism
- Stable training using BatchNorm + Adam optimizer
- Visual output grids saved every epoch
- Training visualization as animated GIF or MP4

---

## 💻 How to Run

### ▶️ Google Colab (recommended)
- Click here to open: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK_HERE)

### 🛠 Requirements (if running locally)
```bash
pip install torch torchvision medmnist matplotlib
