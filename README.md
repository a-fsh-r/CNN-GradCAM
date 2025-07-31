# 💡 CNN and Grad-CAM with PyTorch

![Model](img/download.png)

---

## 📌 Overview

This project demonstrates the use of **Convolutional Neural Networks (CNNs)** in combination with **Grad-CAM (Gradient-weighted Class Activation Mapping)** for visualizing model interpretability in image classification tasks.

Grad-CAM provides visual explanations for decisions made by CNN-based models by producing a **heatmap** that highlights the **most important regions** in the input image contributing to the model’s prediction.

---

## 🔧 What We Did

- ✅ Implemented a convolutional neural network using **PyTorch**
- 🧪 Trained the model on an image dataset
- 🧠 Applied **Grad-CAM** to visualize class-specific activation maps
- 🌡️ Generated heatmaps showing which regions most influenced the classification decision

---

## 🖼️ Output

The final output is a **heatmap image** overlaid on the original input image. This allows for:

- Better **model explainability**
- Understanding of what the CNN is “looking at”
- Debugging and verifying model behavior
- Detecting **bias** or irrelevant focus
