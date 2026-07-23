## Overview

This project uses the **CIFAKE (Real and AI-Generated Synthetic Images)** dataset to train a deep learning model capable of classifying an image as either **Real** or **AI Generated**.

The dataset consists of an equal number of real images collected from CIFAR-10 and synthetically generated images, making it suitable for binary image classification.

---

## Dataset Details

| Property | Value |
|----------|-------|
| Dataset Name | CIFAKE |
| Classification Type | Binary Classification |
| Classes | REAL, FAKE |
| Total Images | 120,000 |
| Image Resolution | 32 × 32 RGB |

---

## Dataset Split

The dataset was divided into:

- **70%** Training Set
- **20%** Validation Set
- **10%** Testing Set

---

## Preprocessing

The following preprocessing steps were performed before model training:

- Image resizing to **32 × 32**
- Pixel value normalization
- Random horizontal flip
- Random vertical flip
- Data augmentation during training

These preprocessing techniques improve the model's ability to generalize on unseen data.

---

## Download Dataset

The dataset is not included in this repository because it exceeds GitHub's storage limit.

Download it from Kaggle:

https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images

After downloading, place the extracted dataset inside the **Dataset/** directory.

---

## Citation

**CIFAKE: Real and AI Generated Synthetic Images Dataset**

Available on Kaggle.
