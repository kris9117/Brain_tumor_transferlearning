# Brain Tumor Classification using Transfer Learning (EfficientNet)

This project aims to classify brain tumor images into different categories using transfer learning with EfficientNet. The model is fine-tuned to achieve high accuracy in detecting and classifying brain tumors based on MRI scans.

---

## Project Overview

### **Objective**
The primary goal of this project is to classify brain tumors using a pre-trained EfficientNet model. Transfer learning allows us to leverage EfficientNet's pre-trained weights on ImageNet and adapt them to our custom dataset.

### **Dataset**
- **Source**: [Kaggle Brain Tumor MRI Dataset](https://drive.google.com/drive/folders/1CurTcbQ_liXtctCjMmjwGm3EnKjzIsiB?usp=drive_link)
- **Classes**: Tumor (Positive) vs No Tumor (Negative)

### **Methodology**
- Data is split into training, validation, and test sets.
- Image preprocessing includes resizing, normalization, and augmentation.
- EfficientNet is fine-tuned using transfer learning to classify the tumor images.

### **Results**
- Achieved a test accuracy of **98%** and an F1-score of **98%** on the validation dataset.

---


