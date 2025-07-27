# 🧠 Alzheimer's MRI Image Classification Using CNN

This project aims to classify MRI brain scans into different stages of Alzheimer's Disease using Convolutional Neural Networks (CNNs). 
Multiple approaches were explored including custom CNNs, data augmentation, ResNet from scratch, and transfer learning with pretrained ResNet18.
### My project kaggle link: https://www.kaggle.com/code/abdulrafesajid/alzheimer-mri-disease-classification-97-accuracy

## AIM
Classifying brain MRI scans into the following categories:
- **Non-Demented**
- **Very Mild Demented**
- **Mild Demented**
- **Moderate Demented**

---

## 📊 Dataset

- Source: https://www.kaggle.com/datasets/borhanitrash/alzheimer-mri-disease-classification-dataset
-  Format: Grayscale MRI images
- Class Distribution: Imbalanced (more "Non-Demented" than others)
- It has 5,120 train images and 1,280 test images

---

## 🔍 Modeling Approaches

| Model | Description | Accuracy |
|-------|-------------|----------|
| **SimpleCC1 (Custom CNN)** | Hand-crafted architecture from scratch | 🟢 96.95% |
| **CNN + Data Augmentation** | Added flips, rotations, zooms | 🟡 64.22% |
| **ResNet18 (from scratch)** | Deep residual model without pretraining | 🔴 55.70% |
| **Transfer Learning (ResNet18 Pretrained)** | Used pretrained ImageNet weights | 🔴 43.12% |

---

## 🔑 Key Takeaways

- **Custom-designed CNN (SimpleCC1)** outperformed all other models.
- **Transfer learning** did not yield better performance—likely due to mismatch between medical images and pretrained ImageNet features.
- Class imbalance and grayscale input compatibility are crucial factors in medical imaging tasks.

## 📬 Contact
### Mohammed Abdul Rafe Sajid
email: abdulrafesajid@gmail.com
linkedln: https://www.linkedin.com/in/mohammed-abdul-rafe-sajid-49a716291/
