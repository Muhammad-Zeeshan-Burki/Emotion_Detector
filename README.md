# 🎭 Emotion Detection using Deep Learning  

This project is an AI-powered **Emotion Detector** built using **TensorFlow, Keras, and MobileNetV2**. It classifies facial expressions into different emotions by leveraging **transfer learning** and **data augmentation techniques**.  

---

## 🛠️ Tech Stack  
- **Deep Learning Framework:** TensorFlow, Keras  
- **Model Architecture:** MobileNetV2 (Pretrained)  
- **Computer Vision:** OpenCV  
- **Data Augmentation:** Keras' ImageDataGenerator  
- **Optimization:** Adam Optimizer, EarlyStopping, ModelCheckpoint  

---

## 📌 Features  
✔️ Uses **MobileNetV2** as a feature extractor for better accuracy  
✔️ **Real-time emotion detection** using OpenCV  
✔️ **Data augmentation** to improve model generalization  
✔️ Implements **early stopping & checkpointing** to prevent overfitting  

---

## 📂 Dataset Structure  
Ensure the dataset is structured as follows:  


Replace `/root/.cache/kagglehub/datasets/msambare/fer2013/versions/1` with your actual dataset path.

---

## 🚀 Installation & Setup  

### 1️⃣ Install Dependencies  
```bash
pip install numpy pandas matplotlib tensorflow opencv-python
git clone https://github.com/Muhammad-Zeeshan-Burki/Emotion_Detector.git
cd emotion-detector
📜 License
This project is licensed under the MIT License.
