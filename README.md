# Medical AI Lab

---
## still pending
## Project Overview

**Project Name:** Medical Image Classification for Disease Diagnosis  

This project focuses on developing a deep learning pipeline for **automated disease diagnosis from medical images** (e.g., X-rays, CT scans, or MRIs). The goal is to build a **robust, accurate, and deployable model** that can assist clinicians in medical decision-making.

**Key Objectives:**
- Classify medical images into healthy vs diseased categories  
- Build a reproducible deep learning pipeline using PyTorch  
- Evaluate model performance with standard metrics  
- Deploy the trained model for inference via a simple API  

---

## Methodology

1. **Data Preprocessing:**  
   - Load images and labels  
   - Split dataset into training, validation, and test sets  
   - Apply augmentations to improve generalization  

2. **Model Development:**  
   - Use **CNN architectures** (ResNet18 / DenseNet121)  
   - Transfer learning from pretrained ImageNet weights  
   - Fine-tune on medical dataset  

3. **Training:**  
   - Cross-entropy loss for classification  
   - Adam optimizer with learning rate scheduling  
   - Early stopping based on validation loss  

4. **Evaluation:**  
   - Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC  
   - Confusion matrix visualization  

5. **Deployment:**  
   - Backend API using FastAPI for inference  
   - Upload trained model weights to `models/`  
   - Simple web interface for image upload and prediction  

Everything still pending
needs update...test?
