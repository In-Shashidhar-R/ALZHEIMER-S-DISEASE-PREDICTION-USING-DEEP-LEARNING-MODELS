## 3. ResNet50  

ResNet50 is a **deep residual network** designed to address the **vanishing gradient problem**, but in this case, it struggled with classification accuracy.

### **Performance Metrics**  
#### **5-Fold Cross-Validation**  
- **Accuracy:** 77.72%  
- **Precision:** 0.83  
- **Recall:** 0.77  
- **F1-Score:** 0.76  
- **Inference Time:** 0.91 seconds  
- **Memory Usage:** 315 MB  

#### **Confusion Matrix**
![image](https://github.com/user-attachments/assets/20ae864f-ccdb-40c5-8737-bc3d8458220c)


#### **1-Fold Cross-Validation**  
- **Accuracy:** 65.6%  
- **Precision:** 0.68  
- **Recall:** 0.60  
- **F1-Score:** 0.61  
- **Inference Time:** 0.89 seconds  
- **Memory Usage:** 310 MB  

#### **Confusion Matrix**
![image](https://github.com/user-attachments/assets/a28d2689-9852-43a1-9d44-f581681fde04)

### **Observations**  
❌ **Lowest accuracy among all models (77.72% in 5-fold, 65.6% in 1-fold)**.  
❌ **Struggles with recall and F1-score**, leading to **higher misclassification rates**.  
✅ **Moderate memory usage (~315 MB), better than VGG19 but still higher than MobileNetV2**.  
✅ **Inference time is acceptable (~0.91s), but not optimal for real-time applications**.  

