# [improved_face_emotion_recognition - Face Expression Emotion Recognition - Yüz İfadelerinden Duygu Tanımlaması]

## 📌 Overview - Genel Bakış
- This repository includes deep learning models (CNNs) which recognize emotion classes from facial expressions and extract features from facial images.
- Bu kod tabanı, yüz ifadelerinden duygu sınıflandırması gerçekleştiren ve yüz görüntülerinden öznitelikleri çıkaran derin öğrenme modelleri içermektedir.
<p>
  <img width="867" height="282" alt="image" src="https://github.com/user-attachments/assets/87b579e4-6278-41f3-bb8c-078f05ec3001" />
</p>

## 🚀 Key Features - Anahtar Özellikler
- **Custom Model Training - Özel Model Eğitimi:** Fine-tuned CNN architectures using Transfer Learning. CNN mimarileri Transfer Learning yöntemiyle veri setine (FER2013) uyarlanmıştır. 
- **Model Optimization:** Converted PyTorch weights (`.pt`) to ONNX and TensorRT formats for edge deployment.
- **Data Engineering:** Realized image preprocessing and data compression utilizing OpenCV and Keras features.

## 🛠️ Tech Stack & Architecture - Teknik Özellikler ve Mimari
- **Code Alanı - Kod Alanı:** Python
- **AI / Computer Vision:**  OpenCV, Keras / Tensorflow
- **DevOps / Infrastructure - Geliştirme / Altyapı:** Kaggle, Jupyter Notebook, Git, Github

## 📊 Performance Metrics & Results
- **Accuracy Improvement:** Achieved a **+5.2% increase in mAP@0.5** via advanced data augmentation and dataset engineering.
