<!-- ===================== PROJECT BANNER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Medical%20Image%20Classification%20using%20CNN&fontSize=36&fontColor=ffffff&animation=fadeIn" />
</p>

<p align="center">
  <strong>Deep Learning • Computer Vision • Healthcare AI</strong>
</p>

---

## 📌 Project Overview
> A **deep learning–powered medical image classification system** built using **Convolutional Neural Networks (CNNs)** to automatically identify different medical imaging modalities.

This project demonstrates **end-to-end AI development**, from data preprocessing to model deployment, with a strong focus on **real-world healthcare applications**.

---

## 🧠 Problem Statement
Medical imaging datasets often contain **multiple imaging modalities**, and manual classification is:
- Time-consuming  
- Error-prone  
- Not scalable  

This project automates the classification of medical images into **six distinct modalities** using a **custom CNN architecture**.

---

## 📂 Dataset Structure
archive (1)/
│
├── AbdomenCT/
├── BreastMRI/
├── ChestCT/
├── CXR/
├── Hand/
└── HeadCT/

---

## 🏥 Image Modalities Classified
| Class | Modality |
|-----|----------|
| 0 | Abdomen CT |
| 1 | Breast MRI |
| 2 | Chest CT |
| 3 | Chest X-Ray |
| 4 | Hand X-Ray |
| 5 | Head CT |

---

## ⚙️ Pipeline Architecture
```mermaid
flowchart LR
A[Raw Medical Images] --> B[Grayscale Conversion]
B --> C[Resize 100x100]
C --> D[Normalization]
D --> E[CNN Feature Extraction]
E --> F[Softmax Classification]
```
## 🧪 Model Architecture

Input (100x100x1)
↓
Conv2D (64) → ReLU → MaxPool → Dropout
↓
Conv2D (128) → ReLU → MaxPool → Dropout
↓
Conv2D (256) → ReLU → MaxPool → Dropout
↓
Flatten
↓
Dense (128) → ReLU → Dropout
↓
Dense (6) → Softmax

## 🚀 Key Features
✅ Multi-class CNN classification

✅ Robust preprocessing pipeline

✅ Medical imaging–focused architecture

✅ Softmax probability-based predictions

✅ End-to-end training & inference

✅ Scalable and extendable design

## 🛠️ Tech Stack & Skills
<p align="center"> <img src="https://skillicons.dev/icons?i=python,tensorflow,keras,opencv,numpy,matplotlib,github&theme=dark" /> </p>

## 📊 Model Performance
Loss Function: Sparse Categorical Crossentropy

Optimizer: Adam

Accuracy Metric: Categorical Accuracy

Training Strategy: Regularization with Dropout

⚠️ Performance improves significantly with increased epochs and dataset size.

## 🖼️ Sample Prediction Output
<p align="center"> <img src="https://raw.githubusercontent.com/yourusername/yourrepo/main/assets/sample_prediction.png" width="500"/> </p>


## 🔮 Future Enhancements
🔹 Transfer Learning (ResNet, EfficientNet)

🔹 Model explainability (Grad-CAM)

🔹 Web-based inference dashboard

🔹 Clinical decision support integration

🔹 Dataset augmentation & balancing

## 📌 Learning Outcomes
Deep understanding of CNNs

Hands-on experience with medical images

Strong grasp of multi-class classification

Practical knowledge of model debugging & optimization

## 👤 Author
Your Name
Aspiring Machine Learning Engineer | Computer Vision Enthusiast

📎 LinkedIn: 
📎 GitHub: https://github.com/yourusername

<p align="center"> <img src="https://capsule-render.vercel.app/api?type=rect&color=0:2C5364,100:0F2027&height=80&section=footer&text=Built%20with%20Deep%20Learning%20for%20Healthcare&fontColor=ffffff"/> </p> ```
