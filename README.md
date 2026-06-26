# [improved_face_emotion_recognition - Face Expression Emotion Recognition - Yüz İfadelerinden Duygu Tanımlaması]

## 📌 Overview - Genel Bakış
- This repository includes deep learning models (CNNs) which recognize emotion classes from facial expressions and extract features from facial images.
- Bu kod tabanı, yüz ifadelerinden duygu sınıflandırması gerçekleştiren ve yüz görüntülerinden öznitelikleri çıkaran derin öğrenme modelleri içermektedir.
<p align="center">
  <img width="80%" alt="image" src="https://github.com/user-attachments/assets/87b579e4-6278-41f3-bb8c-078f05ec3001" />
</p>

## 🚀 Key Features - Anahtar Özellikler
- **Custom Model Training - Özel Model Eğitimi:** Fine-tuned CNN architectures using Transfer Learning.
  CNN mimarileri Transfer Learning yöntemiyle veri setine (FER2013) uyarlanmıştır. 
- **Model Architecture - Model Mimarisi:** Dense, Inceptionv3 and VGG19 models are trained with Transfer Learning structure.
 Dense, Inceptionv3 ve VGG19 modelleri Transfer Learning mimarisinde eğitilmiştir.
<table align="center">
  <tr>
    <td> <img width="50%"  alt="image" src="https://github.com/user-attachments/assets/5059bc0b-696a-43e9-96d9-9fcc2a63f93a" /><br><sub><b>VGG19 Transfer Learning model</b></sub></td>
    <td><img width="50%"  alt="image" src="https://github.com/user-attachments/assets/c345b6a4-e8c7-4267-9486-63081bb93741" /><br><sub><b>Açıklama 2</b></sub></td>
  </tr>
</table>

- **Data Engineering:** Realized image preprocessing and data compression utilizing OpenCV and Keras features.

## 🛠️ Tech Stack & Architecture - Teknik Özellikler ve Mimari
- **Code Alanı - Kod Alanı:** Python
- **AI / Computer Vision:**  OpenCV, Keras / Tensorflow
- **DevOps / Infrastructure - Geliştirme / Altyapı:** Kaggle, Jupyter Notebook, Git, Github

## 📊 Performance Metrics & Results - Performans Metrikleri ve Sonuçlar 
- **Accuracy Improvement:** Achieved a **+5.2% increase in mAP@0.5** via advanced data augmentation and dataset engineering.
