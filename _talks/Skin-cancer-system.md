---
title: "Deep Learning-Based Skin Cancer Recognition System](https://github.com/ChenShuhan02/Skin-cancer-system"
collection: talks
type: "Tutorial"
permalink: /talks/
date: 2023
---

### 2. [Deep Learning-Based Skin Cancer Recognition System](https://github.com/ChenShuhan02/Skin-cancer-system)

**Author**: Shuhan Chen  
**Date**: 2023  
**Project Type**: Final Year Thesis  
**Focus**: Skin Cancer Detection using Deep Learning  
**Dataset**: HAM10000 (Dermatoscopic Images)

#### 📜 Overview
The **Skin Cancer Recognition System** aims to assist in the early detection of skin cancer by employing a **deep learning-based model** to analyze dermatoscopic images. Early diagnosis is crucial for reducing morbidity and improving the survival rate among patients. This project uses the **MobileNetV2** model, a lightweight and efficient convolutional neural network, for classifying images of skin lesions.

#### 🔗 Links
- **GitHub Repository**: [Skin Cancer Detection System](https://github.com/ChenShuhan02/Skin-cancer-system)

#### 🔑 Key Highlights
- **Data Preprocessing**: Images from the **HAM10000** dataset were preprocessed, including resizing, grayscale conversion, and histogram equalization to enhance the quality.
- **Deep Learning Model**: Used **MobileNetV2** pre-trained on ImageNet, which was fine-tuned for the skin cancer classification task.
- **GUI Development**: Developed a **Graphical User Interface (GUI)** using **Tkinter** to allow users to easily load and classify skin lesion images.

#### 🛠️ Methodology Summary
- **Data Collection**: The **HAM10000** dataset, consisting of 10,000 dermatoscopic images, was used to train and test the model.
- **Model Training**: The **MobileNetV2** model was employed with a custom head for binary classification (benign or malignant).
- **Performance Metrics**: Evaluated using **Accuracy**, **Precision**, **Recall**, and **F1-Score**.

#### 📊 Results Overview
- Achieved an **F1-Score** of **0.91**, indicating high accuracy in classifying skin lesions.
- The GUI allows users to import images, classify them in real-time, and visualize results, providing an easy-to-use tool for dermatological analysis.

| Metric         | Value       |
|----------------|-------------|
| **Accuracy**   | 93%         |
| **F1-Score**   | 0.91        |
| **Precision**  | 0.90        |
| **Recall**     | 0.92        |

#### 🚀 Future Work
- **Expand Dataset**: Incorporate additional public skin lesion datasets to enhance model generalization.
- **Model Optimization**: Use more advanced architectures like **EfficientNet** or **ResNet** for improved performance.
- **Deployment**: Deploy the model using **Flask** or **FastAPI** for web-based accessibility and scalability.

---

