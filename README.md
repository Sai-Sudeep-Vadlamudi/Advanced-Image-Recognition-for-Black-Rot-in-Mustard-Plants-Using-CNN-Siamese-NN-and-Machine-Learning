# Advanced Image Recognition for the Diagnosis of Bacterial Blight / Black Rot in Mustard Plants Using CNN, Siamese CNN, and Diverse Machine Learning Algorithms

## Comparative Agricultural Computer Vision Framework for Xcc-Driven Disease Diagnosis

This repository presents a **comparative computer vision and machine learning framework** for the automated diagnosis of **Bacterial Blight / Black Rot in mustard plants**, a high-impact agricultural disease caused by *Xanthomonas campestris* pv. *campestris* (**Xcc**).

The project is designed as a **multi-model experimental research pipeline** that evaluates how different algorithmic paradigms perform on the same disease-classification task. Rather than treating plant disease detection as a one-model demonstration, this work benchmarks a portfolio of **deep learning, similarity-based representation learning, and classical machine learning models** for binary image recognition of **healthy vs infected mustard plant imagery**.

At a high level, the system integrates:

- **Transfer-learning-based Convolutional Neural Networks (CNNs)**
- **Siamese CNN architecture for similarity-aware classification**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Random Forest**

The result is a **research-oriented agricultural AI workflow** that combines image preprocessing, augmentation, classification modeling, quantitative evaluation, and comparative performance analysis to support **early-stage crop disease recognition and proactive agricultural intervention**.

---

## Executive Overview

Accurate and timely detection of Bacterial Blight / Black Rot is essential for reducing crop loss, improving agricultural productivity, and enabling more proactive disease management strategies. Traditional diagnosis often depends on subjective visual inspection, which can be labor-intensive, inconsistent, and difficult to scale.

This project addresses that problem through an **automated image-based disease recognition system** built specifically for mustard plants. It uses **advanced image recognition and machine learning algorithms** to distinguish healthy plant imagery from disease-affected samples, thereby creating a foundation for **scalable, technology-assisted crop diagnostics**.

The project is structured as a **comparative evaluation study**, making it stronger than a single-model prototype. By benchmarking multiple learning paradigms on the same task, it provides a more rigorous view of which approach is most suitable for mustard-plant disease recognition.

---

## Problem Statement

Bacterial Blight / Black Rot in mustard plants poses a significant threat to agricultural yield and food security. Because the disease can spread rapidly and damage crop quality, there is a strong need for an **automated, precise, and reliable diagnostic system** capable of identifying infection symptoms from plant images at an early stage.

The central goal of this project is to develop a **robust image recognition system** that can reduce dependence on manual diagnosis and strengthen disease-monitoring workflows in agriculture.

---

## Project Objectives

- Build an **automated image-classification system** for early detection of Black Rot / Bacterial Blight in mustard plants
- Compare multiple learning paradigms across the same classification task
- Study the effectiveness of **CNN-based deep learning** versus **classical machine learning baselines**
- Evaluate model performance using **accuracy, precision, recall, and F1-score**
- Contribute to **AI-assisted disease diagnostics** in agriculture and precision farming

---

## Model Suite

### 1. CNN-Based Deep Learning Model
A convolutional neural network serves as the baseline deep learning architecture for plant disease recognition. CNNs are especially well-suited for image-classification tasks because they learn spatially meaningful hierarchical features directly from raw image data.

### 2. Siamese CNN
The project extends beyond standard classification by incorporating a **Siamese CNN**, enabling a more advanced similarity-based learning strategy. This architecture is designed to better capture structural similarity and dissimilarity across plant images, which helps improve disease discrimination.

### 3. Support Vector Machine (SVM)
A classical but powerful margin-based classifier used for binary classification of plant imagery after preprocessing and feature preparation.

### 4. K-Nearest Neighbors (KNN)
A proximity-based classification baseline used to evaluate how simple distance-driven classification performs relative to more expressive models.

### 5. Random Forest
An ensemble tree-based classifier used as an interpretable machine learning baseline for disease prediction.

---

## Methodology

## Data Preparation
The project is built around two image groups:

- **Healthy mustard plant images**
- **Infected mustard / cruciferous plant images affected by Xcc**

These image collections form the basis of the binary classification problem.

## Preprocessing Pipeline
To improve model quality and robustness, the workflow applies preprocessing strategies such as:

- image resizing
- image normalization
- train-test splitting
- augmentation for better generalization
- flattened feature-vector generation for classical ML models

## Deep Learning Strategy
The deep learning pipeline relies on **CNN-based feature learning**, while the Siamese variant introduces a more discriminative representation-learning mechanism focused on similarity relationships between image samples.

## Classical Machine Learning Strategy
The project complements deep learning with **SVM, KNN, and Random Forest**, enabling comparative benchmarking across fundamentally different classification families.

## Evaluation Framework
Model performance is measured using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

This allows the project to compare both overall correctness and the balance between false positives and false negatives.

---

## Experimental Results

The project report documents the following model-level performance:

| Model | Accuracy | Precision | Recall | F1 Score |
|------|---------:|----------:|-------:|---------:|
| CNN | 0.4857 | 0.5000 | 0.5000 | 0.5000 |
| Siamese CNN | 0.9714 | 1.0000 | 0.9444 | 0.9714 |
| SVM | 0.9714 | 1.0000 | 0.9444 | 0.9714 |
| KNN | 0.9143 | 0.8571 | 1.0000 | 0.9231 |
| Random Forest | 0.9143 | 0.8947 | 0.9444 | 0.9189 |

### Interpretation
- The **Siamese CNN** and **SVM** delivered the strongest overall performance, both achieving **97.14% accuracy**
- The **KNN** and **Random Forest** models also demonstrated strong classification capability with **91.43% accuracy**
- The baseline **CNN** underperformed relative to the other approaches, indicating that architecture design and representation strategy materially affect classification quality

These results suggest that **similarity-aware deep learning** and **well-optimized classical classifiers** can both be highly effective for mustard-plant disease recognition.

---

## Key Contributions

- Developed a **comparative image-recognition pipeline** for agricultural disease diagnosis
- Applied **deep learning and classical machine learning** to the same crop-health classification problem
- Evaluated multiple models under a common metrics framework
- Demonstrated the practical viability of **AI-assisted early disease detection**
- Created a foundation for more scalable **precision agriculture diagnostic systems**

---

## Repository Structure

```text
Advanced-Image-Recognition-for-Black-Rot-in-Mustard-Plants-Using-CNN-Siamese-NN-and-Machine-Learning/
│
├── CNN.ipynb
├── siamase cnn.ipynb
├── SVM.ipynb
├── Random Forest.ipynb
├── PIT
└── PHT
