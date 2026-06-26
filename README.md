# Multimodal Product Classification for E-Commerce Catalog

## Overview

This project presents a multimodal deep learning framework for automatic product classification in e-commerce platforms by jointly leveraging textual and visual information.

The framework combines:

- DistilBERT for textual feature extraction
- CNN/ResNet for image feature extraction
- Feature fusion for multimodal learning

The objective is to improve product classification accuracy and robustness in large-scale e-commerce catalogs.

---

## Problem Statement

Traditional product classification systems rely on either text or images independently. These unimodal approaches often struggle when product descriptions are incomplete, noisy, or ambiguous.

This project proposes a multimodal framework that integrates text and image modalities for accurate product categorization.

---

## Dataset

- Total Samples: ~84,916
- Product Categories: 27
- Modalities:
  - Product Title
  - Product Description
  - Product Images

> Due to confidentiality constraints, the original dataset is not included.

---

## Technologies Used

- Python
- TensorFlow
- PyTorch
- Transformers
- OpenCV
- Scikit-Learn
- DistilBERT
- CNN / ResNet

---

## Project Workflow

1. Data Cleaning
2. Text Translation
3. Text Preprocessing
4. Image Preprocessing
5. Feature Extraction
6. Model Training
7. Multimodal Fusion
8. Evaluation

---

## Model Performance

| Model | Validation Accuracy |
|--------|-------------------|
| SVC + TF-IDF | 70.95% |
| Logistic Regression + TF-IDF | 69.07% |
| DistilBERT | 83.00% |

---

## Repository Structure

```text
data/
notebooks/
src/
saved_models/
reports/
results/
images/
```

---

## Future Enhancements

- Attention-based fusion mechanisms
- Vision Transformers (ViT)
- Multimodal Retrieval Systems
- Real-time Product Classification APIs

---

## Author

**Feenaz Tasneem Sayed**

M.Tech Artificial Intelligence & Machine Learning  
BITS Pilani