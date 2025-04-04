
## 2. VGG19  

VGG19 is a **deep convolutional neural network** known for its **high accuracy**, but it requires **significantly more computational power and memory** than MobileNetV2.

### **Performance Metrics**  
#### **5-Fold Cross-Validation**  
- **Accuracy:** 95.14%  
- **Precision:** 0.954  
- **Recall:** 0.951  
- **F1-Score:** 0.951  
- **Inference Time:** 1.15 seconds  
- **Memory Usage:** 445 MB  

#### **Confusion Matrix**
![image](https://github.com/user-attachments/assets/f7373d0d-39bc-4f00-aeca-295792d4d718)


#### **1-Fold Cross-Validation**  
- **Accuracy:** 87.65%  
- **Precision:** 0.90  
- **Recall:** 0.85  
- **F1-Score:** 0.87  
- **Inference Time:** 1.12 seconds  
- **Memory Usage:** 440 MB

#### **Confusion Matrix**
![image](https://github.com/user-attachments/assets/bcb3872b-0a7a-44b0-8647-4fb2ea097b0f)


### **Observations**  
✅ **Good accuracy but computationally expensive**.  
❌ **Significantly higher memory usage (445 MB vs. 140 MB for MobileNetV2)**, making it less suitable for deployment on resource-limited devices.  
✅ **Performs well in terms of precision and recall**, making it a strong contender for high-performance systems.  
❌ **Longer inference time (~1.15s), which may slow real-time applications**.  
