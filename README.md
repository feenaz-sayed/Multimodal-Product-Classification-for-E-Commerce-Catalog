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

## Performance Analysis

### Text Classification Performance

The text classification model based on **DistilBERT (`distilbert-base-uncased`)** demonstrated significant improvements in classification accuracy, particularly for underrepresented classes. The model effectively captured contextual and semantic information from product descriptions, leading to better generalization across categories with limited training samples.

These results highlight the effectiveness of transformer-based architectures in handling class imbalance and improving classification performance for less-represented product categories.

### Image Classification Performance

The image classification model, built using CNN/ResNet architectures, achieved satisfactory performance for visually distinctive product categories. However, despite applying image augmentation techniques during preprocessing, the model showed limited improvements for certain underrepresented classes.

Some minority classes continued to be misclassified, suggesting that the adopted augmentation strategy alone was insufficient to completely address class imbalance in image-based classification tasks.

### Multimodal Fusion Performance

The multimodal fusion approach, which combines textual and visual representations, delivered the best overall performance. By leveraging complementary information from both modalities, the fusion model improved classification robustness and reduced ambiguity in cases where either text or image information alone was insufficient.

Overall, the experimental results demonstrate that integrating textual and visual features significantly enhances product categorization accuracy and robustness for large-scale e-commerce catalogs.

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