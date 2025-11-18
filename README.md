# Cancer Cell Classification – Machine Learning Case Study

## Overview

This case study summarizes a machine learning project focused on classifying cancer cell images using supervised learning techniques. The objective was to determine whether microscopy images contain cancerous or non-cancerous cells using both classical ML methods and convolutional neural networks (CNNs).

This work was originally completed as part of the Fanshawe College AI/ML program and is presented here as a technical and analytical summary—not as a downloadable or runnable code repository.

---

## Project Objectives

- Explore how AI/ML can assist in early diagnostic workflows  
- Build an end-to-end ML classification workflow  
- Prepare, clean, and preprocess image data  
- Compare classical ML models with CNN-based approaches  
- Interpret performance using appropriate diagnostic metrics  
- Document insights, limitations, and future considerations  

---

## ML Workflow Summary

### 1. Data Preparation
- Standardized microscope images for consistency  
- Applied normalization and resizing techniques  
- Encoded labels for binary classification  
- Considered optional enhancements such as grayscale conversion and contrast adjustments  

### 2. Model Development Approaches

#### A. Convolutional Neural Network (CNN)
- Automatically extracts spatial features  
- Well-suited for image-based classification  
- Demonstrated stronger performance compared to classical models  

#### B. Traditional Machine Learning (if features extracted)
- Feature descriptors derived from image processing  
- Models explored may include SVM, Random Forest, Logistic Regression  
- Useful as a performance benchmark against deep learning  

### 3. Evaluation Methodology
Performance was reviewed using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion matrix  
- Inspection of false positives/false negatives  

### 4. Findings & Analysis
- CNNs provided significantly better accuracy due to superior pattern recognition  
- Classical models performed adequately when supported by strong feature engineering  
- Preprocessing quality had a major influence on model stability  
- Metrics beyond accuracy were essential to judge real diagnostic usefulness  

---

## Key Insights

- AI can meaningfully reduce manual image screening workload  
- Neural networks outperform traditional ML in complex image interpretation  
- Data quality and preprocessing are critical to medical ML solutions  
- False negatives are the highest-risk outcome and require careful evaluation  
- AI should complement—never replace—professional diagnostic review  

---

## Limitations & Future Work

- Larger datasets would improve generalization  
- Data augmentation could reduce overfitting  
- Explainability tools (e.g., Grad-CAM) could enhance trust and interpretability  
- A lightweight deployment model could support real-world trial applications  

---

## Purpose of This Repository

This repository serves as a **portfolio case study**, providing:

- A high-level overview of the ML workflow  
- A description of tasks completed  
- A summary of results, insights, and business implications  
- A demonstration of applied knowledge in machine learning and image classification  

**No runnable code, datasets, or notebooks are provided in this repository.**

---

## Contact

For questions or discussion about machine learning, AI projects, or this case study, feel free to reach out.
