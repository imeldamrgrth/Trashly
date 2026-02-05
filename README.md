# Trashly 
Automatic Waste Classification Using Deep Learning

Trashly is a computer vision project that classifies waste images into 10 categories using a deep learning model based on MobileNet with transfer learning and fine-tuning. This system aims to support automated waste sorting and environmental sustainability.

---

## Features
- Classifies waste into 10 categories:
  - Battery  
  - Biological  
  - Cardboard  
  - Clothes  
  - Glass  
  - Metal  
  - Paper  
  - Plastic  
  - Shoes  
  - Trash
- Transfer learning using MobileNet (ImageNet pretrained)
- Data augmentation for better generalization
- Fine-tuning on selected convolutional layers
- Evaluation with confusion matrix, classification report, and ROC curve

---

## Dataset
Source: Kaggle – Garbage Classification V2 
All images resized to **224 × 224**.

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Pandas  
- Matplotlib & Seaborn  
- Scikit-learn  
