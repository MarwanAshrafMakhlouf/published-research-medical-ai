# Medical AI Research — Skin Disease Diagnosis

> Published work in deep learning-based dermatological diagnosis. Covers binary skin cancer detection and multi-class skin disease classification using Xception and ResNet50 architectures.

## Publications Overview

| # | Title | Venue | Type | Submitted | Published|
|---|---|---|---|---|---|
| 1 | Automatic Skin Cancer Diagnosis Using Brute Force and Xception | Springer (AISI 2024) | Conference Paper 🏆 | 2024 | Dec 2024 |
| 2 | Advanced Skin Cancer Classification Using Xception | Taylor & Francis | Book Chapter | 2024 | Sep 2024 |
| 3 | A Mobile-Based Deep Learning System for Skin Disease Diagnosis | IEEE (IMSA 2024) | Conference Paper | 2024 | Mar 2025 |
| 4 | Deep Learning-Based Multi-class Skin Disease Diagnosis Toward Sustainable Healthcare | Springer | Book Chapter | 2024 | Oct 2025 |

---

## Paper 1 — Automatic Skin Cancer Diagnosis Using Brute Force and Xception

> **Venue:** Springer — AISI 2024 | **Type:** Conference Paper 🏆 Best Paper Award

### Abstract

Skin cancer is a serious health issue that, if not identified and treated promptly, might have disastrous effects. This paper proposes a model for automatically detecting skin cancer using the Xception deep learning architecture to distinguish benign and malignant dermoscopic images. Brute force hyperparameter optimization is applied alongside data augmentation and oversampling techniques.

### Key Contributions

- Brute-force hyperparameter optimization of Xception
- Data augmentation + oversampling to address class imbalance
- Binary classification: Benign / Malignant
- Evaluated on the ISIC2020 benchmark dataset

### Results

| Metric | Score |
|---|---|
| Accuracy | 95.2% |
| Precision | 98.9% |
| Sensitivity | 90.0% |
| F1-Score | 95.2% |

### Methodology

```
ISIC2020 Dataset
      │
      ▼
Data Preprocessing
  ├── Image Augmentation (rotation, flipping, zoom, shear)
  └── Oversampling (class imbalance correction)
      │
      ▼
Xception Architecture
  └── Brute-force Hyperparameter Optimization
      │
      ▼
Binary Classification: Benign / Malignant
```

### Dataset

**ISIC 2020** — International Skin Imaging Collaboration
Binary classification: Benign / Malignant
[https://challenge2020.isic-archive.com](https://challenge2020.isic-archive.com)

### Publication

| Venue | DOI |
|---|---|
| Springer — AISI 2024 | [Link](https://link.springer.com/chapter/10.1007/978-3-031-77299-3_33#Abs1) |

---

## Book Chapter 2 — Advanced Skin Cancer Classification Using Xception

> **Venue:** Taylor & Francis | **Type:** Book Chapter

### Abstract

Skin cancer poses significant health risks if not detected early. This chapter presents an automated skin cancer detection model using the Xception deep learning architecture to differentiate between benign and malignant dermoscopic images. Oversampling techniques address data imbalance, and brute force is used for hyperparameter optimization.

### Key Contributions

- Extended and refined version of the AISI 2024 conference paper
- Automated binary classification pipeline using Xception
- Brute-force hyperparameter tuning for optimal performance
- Comprehensive comparison against state-of-the-art models

### Results

| Metric | Score |
|---|---|
| Accuracy | 95.2% |
| Precision | 98.9% |
| Sensitivity | 90.0% |
| F1-Score | 95.2% |

### Methodology

```
ISIC2020 Dataset
      │
      ▼
Data Preprocessing
  ├── Image Augmentation
  └── Oversampling
      │
      ▼
Xception Architecture
  └── Brute-force Hyperparameter Optimization
      │
      ▼
Binary Classification: Benign / Malignant
```

### Dataset

**ISIC 2020** — International Skin Imaging Collaboration
[https://challenge2020.isic-archive.com](https://challenge2020.isic-archive.com)

### Publication

| Venue | DOI |
|---|---|
| Taylor & Francis | [Link](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003486640-11/advanced-skin-cancer-classification-using-xception-deep-learning-architecture-using-dermoscopic-images-wafaa-abdelgawad-esraa-darwish-mohammed-hassan-el-tohamy-marwan-makhlouf-hady-abdalla-youssef-nassar-gehad-ismail-sayed) |

---

## Paper 2 — A Mobile-Based Deep Learning System for Skin Disease Diagnosis

> **Venue:** IEEE — IMSA 2024 | **Type:** Conference Paper

### Abstract

A proper and timely diagnosis of dermatological conditions is critical for maximizing therapy efficacy. This paper presents a mobile-based system for diagnosing skin diseases using a smartphone camera and a modified ResNet50 architecture, classifying five distinct skin disease categories and returning a detailed diagnosis report to the user.

### Key Contributions

- End-to-end mobile system: camera capture → deep learning inference → diagnosis report
- Modified ResNet50 with additional classification layers
- 5-class skin disease classification
- Hybrid dataset: ISIC2020 (cancer class) + custom collected images (remaining classes)

### Results

| Metric | Score |
|---|---|
| Accuracy | 90.74% |
| Precision | 87.78% |
| Sensitivity | 86.84% |
| F1-Score | 87.04% |

### Methodology

```
Mobile Camera (Front-end)
      │
      ▼ captured image
Back-end Inference Engine
  ├── Preprocessing
  │     ├── Image Resizing
  │     ├── Data Augmentation
  │     └── Oversampling
  └── Modified ResNet50
        └── Additional Classification Layers
      │
      ▼
5-Class Output: Cancer / Lupus / Urticaria / Burns / Normal
      │
      ▼
Detailed Report: Diagnosis + Recommended Treatment
```

### Dataset

A hybrid dataset combining:

| Class | Source |
|---|---|
| Cancer | ISIC2020 |
| Lupus | Custom collected |
| Urticaria | Custom collected |
| Burns | Custom collected |
| Normal | Custom collected |

### Publication

| Venue | DOI |
|---|---|
| IEEE — IMSA 2024 | [Link](https://ieeexplore.ieee.org/document/10652699) |

---

## Book Chapter 1 — Deep Learning-Based Multi-class Skin Disease Diagnosis Toward Sustainable Healthcare

> **Venue:** Springer | **Type:** Book Chapter

### Abstract

Timely and precise identification of skin conditions is essential for patient outcomes and efficient treatment. This chapter introduces a deep learning-based multi-class skin disease diagnosis model built on a pre-trained ResNet50 architecture, supporting UN Sustainable Development Goal 3 by improving access to accurate and efficient diagnosis.

### Key Contributions

- Multi-class classification across 5 skin disease categories
- Pre-trained ResNet50 with additional layers for fine-grained discrimination
- Directly supports **UN SDG 3** — Good Health and Well-being
- Hybrid dataset: ISIC2020 (cancer class) + custom collected images (remaining classes)

### Results

| Metric | Score |
|---|---|
| Accuracy | 90.74% |
| Precision | 87.78% |
| Sensitivity | 86.84% |
| F1-Score | 87.04% |

### Methodology

```
Hybrid Dataset (ISIC2020 + Custom)
      │
      ▼
Data Preprocessing
  ├── Image Resizing (uniformity)
  ├── Data Augmentation
  └── Oversampling
      │
      ▼
Pre-trained ResNet50
  └── Additional Classification Layers
      │
      ▼
5-Class Output: Cancer / Lupus / Urticaria / Burns / Normal
```

### Dataset

A hybrid dataset combining:

| Class | Source |
|---|---|
| Cancer | ISIC2020 |
| Lupus | Custom collected |
| Urticaria | Custom collected |
| Burns | Custom collected |
| Normal | Custom collected |

### Publication

| Venue | DOI |
|---|---|
| Springer | [Link](https://link.springer.com/chapter/10.1007/978-3-031-78038-7_7) |

---
