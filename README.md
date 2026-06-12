# 🏢 Building Damage Assessment Using Deep Learning

## 📌 Project Overview

Building Damage Assessment is a Deep Learning and Computer Vision project designed to automatically analyze post-disaster building images and determine the level of structural damage.

The system uses advanced deep learning architectures for:

- Building Damage Classification
- Building Localization
- Damage Severity Analysis
- Visual Dashboard for Prediction Results

The goal of the project is to assist disaster management teams in rapidly assessing damaged buildings after natural disasters such as earthquakes, floods, hurricanes, and cyclones.

---

## 🎯 Problem Statement

After a natural disaster, manually inspecting thousands of buildings is time-consuming and expensive.

This project aims to automate the damage assessment process by using deep learning models that can identify and classify building damage directly from images.

---

## 🚀 Features

### Building Damage Classification
Classifies buildings into different damage categories based on structural condition.

### Building Localization
Detects and localizes buildings from aerial or satellite imagery.

### Multiple Deep Learning Models
Implemented and evaluated several state-of-the-art architectures including:

- CNN
- ResNet
- EfficientNet
- ConvNeXt
- MaxViT
- Transformer-based Models

### Interactive Dashboard
A Streamlit-based dashboard allows users to upload images and visualize predictions.

### Research and Model Comparison
Performance comparison of multiple architectures to identify the most effective model.

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Deep Learning Frameworks
- TensorFlow
- Keras
- PyTorch

### Computer Vision
- OpenCV
- PIL

### Data Processing
- NumPy
- Pandas

### Visualization
- Matplotlib
- Seaborn

### Dashboard
- Streamlit

### Development Environment
- Jupyter Notebook

---

## 📂 Project Structure

```text
BDA-main/
│
├── Classification/
│   ├── Model1.ipynb
│   ├── Model_Convex.ipynb
│   └── Model_MaxViT.ipynb
│
├── Localization/
│   ├── model0.ipynb
│   ├── model1.ipynb
│   └── ...
│
├── Dashboard/
│   ├── app.py
│   └── .streamlit/
│
├── Final_Merge/
│   ├── Model_MaxViT.py
│   ├── model5_transformer.py
│   └── supporting files
│
├── Initial_Work/
│
├── Reports/
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Building-Damage-Assessment.git
```

### Navigate to Project Folder

```bash
cd Building-Damage-Assessment
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Dashboard

Navigate to dashboard folder:

```bash
cd Dashboard
```

Run Streamlit application:

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🧠 Deep Learning Workflow

1. Collect building damage images
2. Preprocess and augment dataset
3. Train deep learning models
4. Evaluate model performance
5. Compare architectures
6. Deploy best-performing model
7. Visualize results through dashboard

---

## 📊 Applications

- Disaster Management
- Emergency Response Systems
- Insurance Assessment
- Infrastructure Monitoring
- Smart City Planning
- Remote Damage Inspection

---

## 🔮 Future Improvements

- Real-time satellite image analysis
- Mobile application deployment
- Cloud-based inference
- Multi-disaster support
- Improved localization accuracy
- Integration with GIS systems

---

## 👨‍💻 Authors

Developed as part of an academic Deep Learning and Computer Vision project.

---

## 📜 License

This project is intended for educational and research purposes.