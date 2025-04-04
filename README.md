# ALZHEIMER-S-DISEASE-PREDICTION-USING-DEEP-LEARNING-MODELS

# AI-Based Alzheimer’s Detection Using MobileNetV2

## Objective

The primary objective of this study is to develop and evaluate an AI-based Alzheimer’s detection system using **MobileNetV2** as the main model. The study aims to assess MobileNetV2’s capability to accurately classify medical images into three distinct categories:

- **Alzheimer’s Disease (AD)**

- **Cognitively Impaired (CI)**

- **Common Normal (CN)**


By comparing its performance against well-established deep learning architectures such as **VGG19**, **ResNet50**, and **InceptionV3**, this research seeks to determine whether MobileNetV2 can provide a **lightweight, efficient, and deployable** solution for real-world clinical use.

## Research Goals

To achieve this objective, the study will:

- Train and validate MobileNetV2 on an Alzheimer’s detection dataset, ensuring the model generalizes well across different patient scans.
- Perform **k-fold cross-validation** to analyze the model’s robustness, accuracy, and consistency across multiple data splits.
- Compare MobileNetV2 with other models (VGG19, ResNet50, and InceptionV3) to evaluate:
  - Accuracy
  - Computational efficiency
  - Suitability for real-time deployment
- Analyze **computational requirements**, including memory usage and inference time, to determine whether MobileNetV2 is a viable alternative for real-time Alzheimer’s diagnosis.
- Optimize and fine-tune MobileNetV2 to maximize performance while maintaining a balance between accuracy and resource efficiency.

This research will provide insights into whether MobileNetV2 can serve as a **cost-effective, mobile-friendly** solution for Alzheimer’s detection, helping doctors and researchers implement AI-based diagnostic tools in **resource-constrained environments**.

---

## Dataset Description

The dataset used in this study consists of **brain scan images** labeled into three categories:

- Alzheimer’s Disease (AD)
- Cognitively Impaired (CI)
- Common Normal (CN)

These images are obtained from **MRI scans**, **PET scans**, or other medical imaging techniques commonly used in neurological assessments.

### Key Features

- Diverse image samples representing variations in:
  - Disease severity
  - Patient demographics
  - Imaging conditions

### Preprocessing Steps

To ensure consistency and enhance model performance, the following preprocessing steps are applied:

- **Image Resizing**: To match the input dimensions required by deep learning models.
- **Normalization**: Scaling pixel values to improve convergence during training.
- **Data Augmentation**:
  - Rotation
  - Flipping
  - Brightness adjustments

These techniques help improve generalization and reduce overfitting.

---

## Evaluation Strategy

- The dataset is split into **training**, **validation**, and **test** sets to ensure robust performance and prevent overfitting.
- **K-fold cross-validation** is performed to evaluate the model’s reliability and consistency across different data splits.

This dataset supports a **comprehensive comparison** between MobileNetV2, ResNet50, InceptionV3, and VGG19, helping identify the model that offers the best trade-off between:

- Accuracy  
- Computational efficiency  
- Resource consumption  

---

## Conclusion

By leveraging this dataset and applying modern deep learning techniques, the study aims to develop an AI-driven Alzheimer’s detection system that is both **accurate and resource-efficient**, promoting **early diagnosis** and making healthcare more accessible to broader populations.
