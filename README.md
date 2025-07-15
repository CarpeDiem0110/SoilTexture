# Soil Classification Using Computer Vision

This project classifies soil into four distinct categories (A, B, C, D) based on the **combined percentage of clay and silt content** using computer vision and machine learning models. It was developed as part of a capstone project at Abdullah Gül University (AGU) by Ahmet Eren Ceylan and Resul Özkale.

---

## 📌 Project Summary

Accurate soil texture classification is essential for agriculture, irrigation planning, and land management. Traditional methods require specialized equipment and are labor-intensive.

Our goal was to design a scalable, efficient, and cost-effective soil classification system using:
- Soil images
- Augmented datasets
- Machine learning & deep learning techniques

---

## 📸 Dataset Overview

- 🧪 Original soil samples collected from AGU dormitory garden
- 🏷️ Manually labeled into 4 categories:
  - **A**: 0–25% clay + silt  
  - **B**: 26–50%  
  - **C**: 51–75%  
  - **D**: 76–100%
- 🖼️ Total Images: **600**
- 🔄 Augmentation Techniques:
  - Rotation
  - Flipping
  - Scaling
  - Translation

The dataset is divided into:
- 70% Training
- 15% Validation
- 15% Testing

> **Note:** Due to GitHub file size limits, the dataset is hosted externally.  
➡️ [Review results from Google Drive](https://drive.google.com/drive/folders/1A7TmkSoJx9rGk0ZpNt4ixC5VXDAJ7GAF?usp=drive_link)

---

## 🤖 Models Used

We evaluated multiple models for soil classification:

| Model        | Accuracy | Notes                                          |
|--------------|----------|------------------------------------------------|
| CNN          | ~85%     | Best overall performance on 600 images        |
| MobileNet    | ~82%     | Lightweight, good for mobile deployment       |
| Random Forest| ~84%     | High performance for smaller image datasets   |
| ResNet50     | ~64%     | Struggled with small dataset and overfitting  |
| EfficientNet | Moderate | Used transfer learning to boost performance   |
| VGG19        | Moderate | Deep feature extractor                        |

---

## 🧪 Evaluation Metrics

We evaluated the models using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix**

> Class B and C showed the most misclassification due to visual similarity.

---

## 🧰 Technologies Used

- **Language**: Python
- **Libraries**:
  - TensorFlow / Keras
  - OpenCV
  - Scikit-learn
  - Matplotlib, Seaborn
- **Hardware**:
  - NVIDIA RTX 3060 (GPU)
  - Intel Core i5-10300H (CPU)
- **Development**:
  - Visual Studio Code on Windows 10

---

## 🔍 Project Highlights

- Created a **custom soil image dataset** with precise lab preparation
- Applied **extensive augmentation** to simulate real-world scenarios
- Combined **traditional ML and deep learning** models
- Achieved robust performance using **transfer learning**
- Offers a practical solution for **automated soil classification**

---

## 📌 Authors

- **Ahmet Eren Ceylan**   
- **Resul Özkale** – 

---


## 📥 Contact

For access to the dataset or collaboration requests, send an email to this address : eEren_ceylan@hotmail.com

