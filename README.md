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
 Dense, InceptionV3 ve VGG19 modelleri Transfer Learning mimarisinde eğitilmiştir.
<table align="center">
  <tr align="center">
    <td><img width="100%"  alt="image" src="https://github.com/user-attachments/assets/5059bc0b-696a-43e9-96d9-9fcc2a63f93a" /><br><sub><b>VGG19 Transfer Learning model</b></sub></td>
    <td><img width="100%"  alt="image" src="https://github.com/user-attachments/assets/c345b6a4-e8c7-4267-9486-63081bb93741" /><br><sub><b>InceptionV3 Transfer Learning model</b></sub></td>
  </tr>
</table>

- **Data Engineering:** Realized image preprocessing and data compression utilizing OpenCV and Keras features. Görüntü önişleme ve veri sıkıştırma işlemleri OpenCV ile Keras özellikleriyle gerçekleştirilmiştir. 

## 🛠️ Tech Stack & Architecture - Teknik Özellikler ve Mimari
- **Code Alanı - Kod Alanı:** Python
- **Deep Learning Tools / Derin Öğrenme Araçları :**  OpenCV, Keras / Tensorflow
- **DevOps / Infrastructure - Geliştirme / Altyapı:** Kaggle, Jupyter Notebook, Git, Github

## 📊 Performance Metrics & Results - Performans Metrikleri ve Sonuçlar 
##VGG19 performance metrics - VGG19 performans metrikleri
---
- **Accuracy - Doğruluk:** Achieved a **approximately 66% validation accuracy rate** in VGG16 model.
VGG19 modelinde yaklaşık **66% validasyon doğruluk oranı** elde edilmiştir. 
<table align="center">
  <tr align="center">
    <td><img width="%100" alt="image" src="https://github.com/user-attachments/assets/f54e0337-b353-4ada-8554-89d926cd48cc" /><br><b>VGG19 training and validation accuracy - VGG19 eğitim ve validasyon doğruluk oranı</b></td>
    <td><img width="%100"  alt="image" src="https://github.com/user-attachments/assets/2663ebe6-e37d-4e8b-8aef-5ac0d53e6c02" /><br><b>VGG10 training and validation loss - VGG19 eğitim ve validasyon kaybı</b></td>
  </tr>
</table>

<table align="center">
  <tr align="center">
    <td><img width="%100" alt="image" src="https://github.com/user-attachments/assets/5cf496d9-3d65-46ac-9176-25036fdeb039" /><br><sub><b>correlation matrix of VGG19 model - VGG19 modelinin korelasyon matrisi</b></sub></td>
  </tr>
</table>
<hr>

##InceptionV3 performance metrics - InceptionV3 performans metrikleri
--- 
- **Accuracy - Doğruluk:** Achieved a **approximately 63% validation accuracy rate** in InceptionV3 model.
InceptionV3 modelinde yaklaşık **63% validasyon doğruluk oranı** elde edilmiştir. 
<table align="center">
  <tr align="center">
    <td><img width="%100" alt="image" src="https://github.com/user-attachments/assets/81f3a266-9ac0-4525-9019-2a3a94394cb2" /><br><b>InceptionV3 training and validation accuracy - InceptionV3 eğitim ve validasyon doğruluk oranı</b></td>
    <td><img width="%100"  alt="image" src="https://github.com/user-attachments/assets/52e4ccec-8555-4ebb-9baf-3aa1827811ac" />
<br><b>InceptionV3 training and validation loss - InceptionV3 eğitim ve validasyon kaybı</b></td>
  </tr>
</table>
- Correlation matrix depicts alignment of true labels and predicted labels in terms of emotion classes of ferplus facial expression dataset. 
Korelasyon matrisi
<table align="center">
  <tr align="center">
    <td><img width="%100"  alt="image" src="https://github.com/user-attachments/assets/aecf59d7-8084-475a-96ec-24f05dfa5d0e" /><br><sub><b>correlation matrix of InceptionV3 model - InceptionV3 modelinin korelasyon matrisi</b></sub></td>
  </tr>
</table>

##Dense performance metrics - Dense performans metrikleri 
---
- **Accuracy - Doğruluk:** Achieved a **66% validation accuracy rate** in Dense model.
Dense modeline **66% validasyon doğruluk oranı** elde edilmiştir.

<table align="center">
  <tr align="center">
    <td><img width="737" height="627" alt="image" src="https://github.com/user-attachments/assets/1f56b79a-b3a8-4905-a8ad-f656a1cc65ca" /><br><b>correlation matrix of Dense model - Dense modelinin korelasyon matrisi</b></td>
  </tr>
</table>

