# Cancer Cell Classification – Machine Learning Project

## Overview

This project demonstrates a full machine learning pipeline designed to classify cancer cells using image data. The workflow includes dataset preparation, image preprocessing, feature extraction, model training, evaluation, and performance analysis.

The objective is to identify whether microscopy images contain cancerous or non-cancerous cells using classical machine learning techniques and/or convolutional neural networks (CNNs), depending on the dataset and approach.

This project was originally completed as part of the Fanshawe College AI/ML program and is reconstructed here as a full technical portfolio example.

---

## Project Objectives

- Build a fully reproducible ML classification workflow  
- Preprocess and normalize image data for model training  
- Train and evaluate one or more models (CNN or classical ML)  
- Compare accuracy, precision, recall, and F1-score  
- Demonstrate clear code structure and documentation  
- Provide a notebook that can be run locally on any machine  

---

## ML Workflow

### 1. Data Preparation
- Resize and normalize image data  
- Train/validation split  
- Label encoding  
- Optional: grayscale conversion or histogram equalization  

### 2. Model Development
Two approaches are demonstrated:

**A. Convolutional Neural Network (CNN)**  
- Feature extraction performed automatically via convolutions  
- Suitable for complex image data  
- Uses Keras/TensorFlow or PyTorch  

**B. Classical ML Approach (if applicable)**  
- Extract features manually using image descriptors  
- Models may include SVM, Random Forest, or Logistic Regression  

### 3. Training & Evaluation
- Model training using training set  
- Evaluation using validation/test set  
- Metrics include:  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Confusion matrix  

### 4. Results & Analysis
- Side-by-side model comparison  
- Visualization of predictions  
- Analysis of false positives and false negatives  
- Notes on model limitations and improvements  

---

## Repository Structure

```
cancer-cell-classification-ml-project/
│
├── data/                # Placeholder for dataset (not included)
├── notebooks/
│   └── cancer_cell_classification.ipynb  # Main ML notebook
├── models/              # Saved models (if applicable)
├── utils/               # Helper scripts (preprocessing, loaders, etc.)
└── README.md            # Project documentation
```

---

## Requirements

This project will include a `requirements.txt` file containing (at minimum):

- Python 3.x  
- TensorFlow or PyTorch  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- OpenCV (optional, for preprocessing)  

---

## How to Run This Project

1. Clone the repository  
2. Install dependencies via `pip install -r requirements.txt`  
3. Download or place dataset in the `/data` directory  
4. Open the notebook in `notebooks/`  
5. Run all cells to reproduce the training process  

A full step-by-step “How to Run” guide will be added when the notebook is uploaded.

---

## Next Steps

The next commits to this repository will include:

- Fully documented Jupyter notebook  
- Model training results  
- Visualizations  
- Optional hyperparameter tuning  
- Optional deployment example (Flask API or lightweight UI)

---

## Contact

For questions about this project or other AI/ML work, feel free to reach out.
