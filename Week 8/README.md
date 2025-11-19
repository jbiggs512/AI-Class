# CIFAR-10 Classification Using Transfer Learning (ResNet-18)

This project trains a deep learning model on the **CIFAR-10** dataset using **transfer learning** with a pre-trained **ResNet-18**. The workflow includes data preprocessing, model modification, training, and evaluation.

---

## 📚 Overview

- Uses **PyTorch** and **Torchvision**
- Pre-trained **ResNet-18 (ImageNet)** backbone
- Custom final layer for CIFAR-10’s 10 classes
- Automatic GPU/CPU selection
- TQDM progress bars for training feedback

---

## 🛠 Requirements

Install the dependencies with:

```bash
pip install torch torchvision matplotlib tqdm
