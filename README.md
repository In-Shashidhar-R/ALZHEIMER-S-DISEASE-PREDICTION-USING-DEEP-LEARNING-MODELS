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

- **Alzheimer’s Disease (AD)**
- **Cognitively Impaired (CI)**
- **Common Normal (CN)**

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

## Evaluation Metrics

The models were evaluated based on multiple metrics, including **accuracy**, **precision**, **recall**, **F1-score**, **inference time**, and **memory usage**. We conducted both **1-fold (train-test split)** and **5-fold cross-validation** for performance validation.

### **Model Performance Comparison (5-Fold Cross-Validation)**

| Model        | Accuracy (%) | Precision | Recall | F1-Score | Inference Time (s) | Memory Usage (MB) |
|-------------|-------------|-----------|--------|----------|---------------------|-------------------|
| **MobileNetV2** | **97.88**   | **0.978**  | **0.978** | **0.978**  | **0.46**            | **140**           |
| **VGG19**       | **95.14**   | **0.954**  | **0.951** | **0.951**  | **1.15**            | **445**           |
| **ResNet50**    | **77.72**   | **0.83**   | **0.77**  | **0.76**   | **0.91**            | **315**           |
| **InceptionV3** | **94.00**   | **0.945**  | **0.94**  | **0.94**   | **1.07**            | **305**           |

### **Model Performance Comparison (1-Fold Cross-Validation)**

| Model        | Accuracy (%) | Precision | Recall | F1-Score | Inference Time (s) | Memory Usage (MB) |
|-------------|-------------|-----------|--------|----------|---------------------|-------------------|
| **MobileNetV2** | **93.47**   | **0.94**   | **0.92**  | **0.93**   | **0.45**            | **135**           |
| **VGG19**       | **87.65**   | **0.90**   | **0.85**  | **0.87**   | **1.12**            | **440**           |
| **ResNet50**    | **65.60**   | **0.68**   | **0.60**  | **0.61**   | **0.89**            | **310**           |
| **InceptionV3** | **86.94**   | **0.87**   | **0.85**  | **0.86**   | **1.05**            | **300**           |

> **Observations**:
> - MobileNetV2 performed the best overall in both **accuracy** and **efficiency**, making it the most **suitable** for real-time applications.
> - VGG19 showed **high accuracy** but required significantly **higher computational resources**.
> - ResNet50 had **poor performance**, particularly in recall and F1-score.
> - InceptionV3 provided a **good trade-off** between accuracy and resource usage but was still outperformed by MobileNetV2.

---

## Confusion Matrix Analysis

We analyzed the **confusion matrices** for both **1-fold** and **5-fold cross-validation** to observe the model’s classification performance across different categories.

> **Key Observations**:
> - The **false positive and false negative rates** were lower for MobileNetV2 compared to other models.
> - **ResNet50 had the highest misclassification rate**, affecting its overall reliability.
> - **VGG19 and InceptionV3 showed decent results but were computationally expensive**.

---

## Conclusion

By leveraging this dataset and applying modern deep learning techniques, this study aims to develop an **AI-driven Alzheimer’s detection system** that is both **accurate** and **resource-efficient**.

### **Key Findings**
- **MobileNetV2** demonstrated the best performance in **accuracy, efficiency, and memory consumption**, making it the **best candidate for real-time clinical deployment**.
- **VGG19** performed well but required significantly **higher memory and computational power**.
- **ResNet50 struggled with accuracy**, making it unsuitable for real-world diagnosis.
- **InceptionV3 provided competitive accuracy** but still required more resources than MobileNetV2.

This research contributes to **AI-based early Alzheimer’s detection**, making healthcare more accessible to broader populations.

---

