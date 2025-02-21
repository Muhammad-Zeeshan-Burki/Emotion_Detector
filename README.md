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
dataset /train /happy /sad /angry /neutral ... /validation /happy /sad /angry /neutral ..
