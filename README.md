# 🧬 Cancer Cell Detection using Deep Learning  

## 📌 Project Overview  
This project utilizes **Convolutional Neural Networks (CNNs)** to detect cancerous cells in microscopic images. By analyzing cell images, the model classifies them as either **Benign (Non-Cancerous)** or **Malignant (Cancerous)**, helping in early detection of cancer.  

## 🔬 Dataset  
The dataset contains labeled cell images organized into two classes:  
- **Benign (Non-Cancerous) → Labeled as `0`**  
- **Malignant (Cancerous) → Labeled as `1`**
- for dataset see the [Datasets](Datasets)

## 🏗 Model Architecture  
The **CNN architecture** consists of:  
✔ **Conv2D (32 filters, 3x3 kernel, ReLU activation)**  
✔ **MaxPooling2D (2x2 pool size)**  
✔ **Conv2D (64 filters, 3x3 kernel, ReLU activation)**  
✔ **MaxPooling2D (2x2 pool size)**  
✔ **Flatten Layer**  
✔ **Dense Layer (64 neurons, ReLU activation)**  
✔ **Output Layer (Sigmoid activation for binary classification)**  

📌 **Loss Function:** `Binary Crossentropy`  
📌 **Optimizer:** `Adam`  

## 📈 Model Training and Evaluation  
- **Preprocessing:** Used `ImageDataGenerator` to rescale images to `[0,1]`.  
- **Early Stopping:** Monitors validation loss to prevent overfitting.  
- **Evaluation Metrics:** Accuracy and loss graphs plotted for performance analysis.  

### 🔹 **Training & Validation Accuracy/Loss**  
![image](https://github.com/user-attachments/assets/a28c4bf6-bfd4-45b8-95f4-d4b93cb05ca9)
## 🔍 Sample Cell Images  
The dataset includes high-resolution microscopic images of cells.  
![00a1a702c655aa91b62ce07cc9885f3b625f6ff4](https://github.com/user-attachments/assets/00e03a6c-841a-4778-b5a8-82ec34f20a46)
![0000ec92553fda4ce39889f9226ace43cae3364e](https://github.com/user-attachments/assets/74331153-0d52-4576-b79b-63bb6d8441b5)
![00b592c66e533059be4538c36a6acfccdbaafab7](https://github.com/user-attachments/assets/9eff1710-d402-40c4-833a-90a921fb49e2)
![00be641322741e42fb8cb3301c543ae9d242e77f](https://github.com/user-attachments/assets/9170ddd6-ae97-4b50-abfa-d0ca2684db29)


### **Training Images**  
**Non-Cancerous**

![00aa78f05a342349734a337389a52f720d146b8b](https://github.com/user-attachments/assets/a0043252-1ae2-407f-a061-72234b23108d)
![00ba015bf839a6762c1f0fc45114c3499c9db294](https://github.com/user-attachments/assets/f0cc6028-dd5e-4278-b7d2-ebf1b006474c)
![0a0ef4b242298265169e7274da36554181238496](https://github.com/user-attachments/assets/1bbcc18c-be18-4288-ae50-7d81a3797a05)
![0a98ae1c99e53a08c68626ed54f1aa239614eaaf](https://github.com/user-attachments/assets/cbb4a606-5ff4-4d5a-9b26-5f4c3f97f8be)

**Cancerous**

![00a8d8d85b10949c03436ea38117513787b3abeb](https://github.com/user-attachments/assets/76383b5b-5b21-4ef8-a212-04e6f8aa2d63)
![00b9c0592a7e3ebf73630d6819411d9b56bab175](https://github.com/user-attachments/assets/d2f754c0-4da2-4b23-9a28-aef81437eaaf)
![047350806473865e1f6e03f87cb7de0fa06f717a](https://github.com/user-attachments/assets/ec6f0cd6-e7c0-4fa2-b6da-3939fff8ffd8)
![15962708384ff782b9e8e99f9d64d710cbe6c207](https://github.com/user-attachments/assets/7f77b04c-7267-4a40-965b-b7a09d93dfc1)


### **Test Images**  
![00af1151d5a87d93f50001e20236ec50ec6112e3](https://github.com/user-attachments/assets/02685e3d-71f4-4112-8c46-7ead28e4f7d0)
![00add86d5243b3c083f37ebdf52aa9d59a8fd9e8](https://github.com/user-attachments/assets/b6aef3b1-68ea-41ed-b3d5-4fa3e075bb92)
![00b6c59bc941604bd4725d957796a0635f0f4bce](https://github.com/user-attachments/assets/19278773-0276-46a4-9a78-c8bc779e0517)
![00a04c277c1a4bd14b7636d4c1c346d098a0f805](https://github.com/user-attachments/assets/148cb74c-4f70-44e2-99f7-268b956488b7)


## 🚀 Future Enhancements  
✅ **Data Augmentation** to improve generalization.  
✅ **Transfer Learning** using pre-trained models like VGG16/ResNet.  
✅ **Web App Deployment** for real-time cancer cell detection.  


## 🏆 Key Achievements  
✔ **88% Accuracy** on validation dataset  
✔ **Efficient cancer detection using deep learning**  
✔ **Helps in early diagnosis and treatment**  
## 📜 License  
This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.
 
## 🤝 Acknowledgments  
This project is inspired by research in **Medical AI & Deep Learning Applications**.  
Special thanks to **OpenAI, TensorFlow, and Kaggle datasets** for resources.  

