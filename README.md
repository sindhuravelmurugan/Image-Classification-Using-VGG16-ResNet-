# Image-Classification-Using-VGG16-ResNet-

## 📌 Project Overview  
This project focuses on **image classification** using **VGG and ResNet architectures** on a dataset containing **three categories: Dogs, Food, and Vehicles**, all equally distributed.  

The goal was to explore **advanced techniques** to improve model performance, including **weight initialization, optimizers, batch sizes, regularization, and augmentation techniques**.

🔹 **Due to academic policies, the source code is not publicly available.**  
🔹 **However, this repository provides insights into the approach, methods, and results.**  

---

## 📂 Dataset  
- The dataset consists of **three balanced classes: Dogs, Food, and Vehicles**.  
- Standard **preprocessing techniques** such as **image resizing, normalization, and data augmentation** were applied.  

---

## 🛠️ Tech Stack  
- **Deep Learning Framework:** PyTorch / TensorFlow  
- **Architectures Used:** VGG16 & ResNet18  
- **Libraries Used:**  
  - `Torchvision` – Pretrained models & image transformations  
  - `Matplotlib & Seaborn` – Data visualization  
  - `Numpy & Pandas` – Data handling  
  - `scikit-learn` – Performance evaluation  

---

## 🔍 Model Training & Optimization  

### **1️⃣ VGG Model Architecture & Optimization**  
- Implemented **VGG16** with modifications.  
- Used **two weight initialization techniques:**  
  ✅ **He Initialization** – Worked best  
  ✅ **Xavier Initialization**  
- Tested **multiple optimizers:**  
  ✅ **SGD**  
  ✅ **Adam**  
  ✅ **RMSprop**  
- Experimented with **batch sizes (16, 32)** for performance tuning.  
- Applied **regularization techniques:**  
  ✅ Early Stopping  
  ✅ K-Fold Cross Validation  
  ✅ Data Augmentation  

### **2️⃣ ResNet Model Architecture & Optimization**  
- Implemented **ResNet18** for comparison with VGG.  
- Used **Adam Optimizer** and **Cross-Entropy Loss Function**.  
- Improved model by:  
  ✅ Testing **different batch sizes (16, 32)**  
  ✅ Using **Kaiming Weight Initialization**  
  ✅ Applying **Early Stopping**  
  ✅ Integrating **Learning Rate Scheduling (LRS)**  

---

## 📊 Results & Key Takeaways  

### **Model Accuracy Comparison for VGG16 (Different Optimizations)**  
| Optimization Method | Accuracy |
|---------------------|----------|
| Xavier Weight Initialization | 92.56% |
| He Initialization, Adam Optimizer, Batch Size = 32 | 94.02% |
| He with SGD Optimizer | 89.42% |
| He with RMS Optimizer | 92.24% |
| He (Batch Size = 16) | 90.51% |
| He with Early Stopping | 93.33% |
| He with k-Fold Cross Validation | 90.58% |
| He with Data Augmentation | 90.09% |

### **ResNet18 vs. Improved ResNet18 Model Accuracy**  
| Model | Accuracy |
|------------|----------|
| ResNet18 | 94.13% |
| Improved ResNet18 | 93.93% |

🔹 **VGG with He Initialization and Adam Optimizer performed best at 94.02%.**  
🔹 **ResNet18 had high accuracy (94.13%) but the improved version performed slightly lower at 93.93%.**  
🔹 **Regularization techniques like Early Stopping and LRS improved training stability.**  

---

## 🚀 How to Use This Project  
🚫 **Due to school regulations, the source code is not publicly available.**  
🔹 However, if you are interested in discussing this project or its methodology, feel free to reach out!  

---

## 📌 Future Improvements  
- 🔹 Explore **transfer learning** with deeper architectures like ResNet50 or EfficientNet.  
- 🔹 Implement **semi-supervised learning** to improve performance on unseen data.  
- 🔹 Deploy a **web-based image classifier** using Flask or FastAPI.  

---

## 📜 License  
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.  

---

## 🔗 Connect with Me  
📧 Email: sindhuravel@gmail.com 
🔗 LinkedIn: [Sindhura Velmurugan](https://www.linkedin.com/in/sindhura-velmurugan/)  

---

### ⭐ If you find this project interesting, feel free to **star** this repository!
