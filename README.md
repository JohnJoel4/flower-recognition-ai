# 🌸 Flower Recognition AI (98.6% Accuracy)

[![Hugging Face Space](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Space-blue)](https://huggingface.co/spaces/JohnJoelMota/flower-recognition)
[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Framework-YOLOv8-red)](https://ultralytics.com/)

An end-to-end Computer Vision system capable of identifying flower species with high precision. This project leverages the **YOLOv8** architecture and is deployed via **Gradio** on Hugging Face Spaces.

## 🚀 Live Demo
**Try the model yourself:** [JohnJoelMota Flower Recognition Space](https://huggingface.co/spaces/JohnJoelMota/flower-recognition)

## 📊 Performance
The model was trained on the Kaggle Flowers Recognition dataset for 10 epochs, achieving the following metrics:
* **Accuracy (Top-1):** 98.6%
* **Inference Speed:** ~3.5ms (Tesla T4 GPU)
* **Classes:** Daisy, Dandelion, Rose, Sunflower, Tulip.

## 🛠️ Tech Stack
- **Model:** YOLOv8 (Ultralytics)
- **Training:** Google Colab (Tesla T4 GPU)
- **Deployment:** Gradio & Hugging Face Spaces
- **Libraries:** PyTorch, OpenCV, Scikit-learn

## 🏗️ Architecture & Logic
To ensure industry-ready code, the project follows a modular structure:
1. **Data Pipeline:** Automated image sorting and 80/20 train-validation split.
2. **Training:** Fine-tuning the `yolov8n-cls` nano-model for efficient real-time inference.
3. **Inference:** A robust Gradio interface that handles out-of-distribution (OOD) images with lower confidence scores, maintaining system reliability.

---
Created by **John Joel Mota** *AI Software Engineer | Full Stack Engineer | ML Engineer*
