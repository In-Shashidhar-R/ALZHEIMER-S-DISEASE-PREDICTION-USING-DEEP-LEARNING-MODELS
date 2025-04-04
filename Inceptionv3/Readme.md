## 4. InceptionV3  

InceptionV3 is a **deep convolutional network with a complex architecture** designed for **efficiency** and **accuracy**.

### **Performance Metrics**  
#### **5-Fold Cross-Validation**  
- **Accuracy:** 94.00%  
- **Precision:** 0.945  
- **Recall:** 0.94  
- **F1-Score:** 0.94  
- **Inference Time:** 1.07 seconds  
- **Memory Usage:** 305 MB  

#### **Confusion Matrix**  
![image](https://github.com/user-attachments/assets/8bb3cf5b-b290-4e14-9f8e-a83adb335e00)


#### **1-Fold Cross-Validation**  
- **Accuracy:** 86.94%  
- **Precision:** 0.87  
- **Recall:** 0.85  
- **F1-Score:** 0.86  
- **Inference Time:** 1.05 seconds  
- **Memory Usage:** 300 MB

#### **Confusion Matrix**  
![image](https://github.com/user-attachments/assets/ec799641-762f-4466-bd79-abdfd307989a)


### **Observations**  
✅ **Competitive accuracy (94% in 5-fold, 86.94% in 1-fold)**, making it a **strong alternative to MobileNetV2**.  
✅ **Balanced performance between accuracy and computational requirements**.  
❌ **Higher memory usage (~305 MB)** compared to MobileNetV2.  
❌ **Inference time is relatively long (~1.07s), which may impact real-time applications**.  
