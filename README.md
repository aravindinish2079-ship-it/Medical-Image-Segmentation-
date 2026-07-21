# 🩺 Medical Image Segmentation using U-Net

<div align="center">

# 🧠 AI-Powered Medical Image Segmentation

### Deep Learning-Based Lung Segmentation from Chest X-Ray Images

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20Application-ff4b4b?style=for-the-badge&logo=streamlit)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

**Semantic Segmentation of Lung Regions Using U-Net Architecture**

⭐ Star this repository if you find it useful!

</div>

---

# 📖 Overview

Medical Image Segmentation is one of the most important applications of Artificial Intelligence in Healthcare. This project implements a **U-Net Deep Learning architecture** to accurately segment lung regions from chest X-ray images.

The model is trained on annotated medical images and is capable of generating pixel-wise lung masks. An interactive **Streamlit Web Application** is also included for real-time predictions.

---

# ✨ Features

- 🧠 U-Net Deep Learning Architecture
- 🫁 Lung Segmentation from Chest X-ray Images
- 📊 Dice Loss + Binary Cross Entropy Loss
- 🚀 GPU Training Support
- 🎯 Pixel-Level Semantic Segmentation
- 🌐 Streamlit Web Application
- 💾 Model Saving & Loading
- 📈 Performance Evaluation
- ⚡ Fast Inference Pipeline

---

# 📸 Demo

## Input Image

> Replace with your screenshot

<img src="images/input.png" width="300">

---

## Ground Truth Mask

<img src="images/mask.png" width="300">

---

## Predicted Segmentation

<img src="images/prediction.png" width="300">

---

# 🏗 Project Workflow

```text
Chest X-ray
      │
      ▼
Image Preprocessing
      │
      ▼
Data Augmentation
      │
      ▼
U-Net Model
      │
      ▼
Prediction
      │
      ▼
Segmented Lung Mask
      │
      ▼
Streamlit Web Application
```

---

# 📂 Project Structure

```text
Medical_Image_Segmentation/
│
├── Medical_Image_Segmentation.ipynb
├── app.py
├── model.pth
├── requirements.txt
├── README.md
│
├── dataset/
│
├── images/
│   ├── input.png
│   ├── mask.png
│   └── prediction.png
│
└── outputs/
```

---

# 🧠 Model Architecture

The project uses the **U-Net** architecture consisting of:

- Encoder
- Bottleneck
- Decoder
- Skip Connections
- Output Layer (Sigmoid)

---

# 📊 Training Pipeline

- Dataset Loading
- Image Preprocessing
- Data Augmentation
- DataLoader Creation
- Model Training
- Validation
- Model Evaluation
- Save Best Model
- Prediction

---

# 📈 Performance Metrics

| Metric | Value |
|---------|------|
| Dice Coefficient | XX.XX |
| Training Loss | XX.XX |
| Validation Loss | XX.XX |
| Epochs | XX |

---

# 🛠 Technology Stack

| Category | Technology |
|------------|------------|
| Programming Language | Python |
| Deep Learning | PyTorch |
| Image Processing | OpenCV |
| Numerical Computing | NumPy |
| Data Visualization | Matplotlib |
| Dataset | KaggleHub |
| Web Framework | Streamlit |
| Development Environment | Google Colab |

---

# 📥 Dataset

**Dataset Used**

- Montgomery Chest X-ray Dataset

Dataset contains:

- Chest X-ray Images
- Lung Masks
- Binary Segmentation Labels

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Medical_Image_Segmentation.git

cd Medical_Image_Segmentation
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ Running the Project

## Train the Model

```bash
jupyter notebook Medical_Image_Segmentation.ipynb
```

## Launch Streamlit

```bash
streamlit run app.py
```

---

# 📷 Screenshots

## Home Page

> Add Screenshot

---

## Prediction

> Add Screenshot

---

## Segmentation Output

> Add Screenshot

---

# 🌍 Applications

- 🏥 Healthcare
- 🧬 Medical Research
- 🫁 Lung Disease Detection
- 🤖 AI-assisted Diagnosis
- 📊 Medical Image Analysis
- 🩺 Radiology Automation

---

# 🚀 Future Enhancements

- Attention U-Net
- U-Net++
- DeepLabV3+
- Multi-class Segmentation
- Docker Deployment
- Hugging Face Deployment
- Streamlit Cloud Deployment
- Explainable AI (Grad-CAM)

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

## **P. Aravind**

AI & Data Science Student

- 🧠 Deep Learning Enthusiast
- 💻 Machine Learning Developer
- 📊 Data Science Practitioner
- 🏥 Medical AI Explorer

---

<div align="center">

## ⭐ If you like this project, give it a Star!

### Thank you for visiting my repository ❤️

</div>
