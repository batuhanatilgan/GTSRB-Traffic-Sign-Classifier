🚦 GTSRB Traffic Sign Classifier (CNN)

Bu proje, Alman Trafik İşareti Tanıma Kıyaslama (GTSRB) veri setini kullanarak geliştirilmiş bir derin öğrenme tabanlı trafik işareti sınıflandırma modelidir. Proje, bir mülakat görevi kapsamında tamamlanmıştır ve model, 43 farklı trafik işaretini yüksek doğrulukla tanıyabilir.

🎯 Proje Hedefleri ve Özellikler

Veri Yönetimi: Kaggle API kullanılarak GTSRB veri seti Google Colab ortamına çekilmiş ve ön işleme tabi tutulmuştur.

Model Eğitimi: Evrişimsel Sinir Ağları (CNN) mimarisi ile model eğitilmiş, .h5 veya saved_model formatında model dosyası üretilmiştir.

Performans Görselleştirme: Eğitim sürecinde Accuracy ve Loss grafikleri sunulmuştur.

Çıkarım Fonksiyonu (Inference): Grafik arayüz gerektirmeyen özel bir fonksiyon, dışarıdan görüntü dosyası alarak sınıf etiketini ve olasılık değerini döndürür.

Ortam Optimizasyonu: TensorFlow sürümünden kaynaklanabilecek hatalar, TensorFlow 2.x API’si kullanılarak önlenmiştir.

🛠️ Kullanılan Teknolojiler
Kategori	Teknoloji / Kütüphane
Programlama Dili	Python
Derin Öğrenme	TensorFlow, Keras (CNN Mimarisi)
Veri İşleme	NumPy, Pandas
Görüntü İşleme	OpenCV (Görüntü boyutlandırma ve ön işleme)
Görselleştirme	Matplotlib (Accuracy / Loss Grafikleri)
Ortam	Google Colab
📂 Proje Yapısı
GTSRB-Traffic-Sign-Classifier/
│── README.md
│── model/                 # Eğitilmiş model dosyaları (.h5 veya saved_model)
│── data/                  # Veri seti veya örnek veri
│── src/
│   ├── preprocessing.py   # Veri ön işleme kodları
│   ├── train.py           # Model eğitimi
│   └── inference.py       # Tahmin ve çıkarım fonksiyonları

📈 Model Performansı

Model, 43 farklı trafik işaretini yüksek doğrulukla sınıflandırabilir.

Eğitim süreci boyunca Accuracy ve Loss grafikleri ile performans izlenebilir.

📌 Notlar

Çıkarım fonksiyonu, herhangi bir GUI gerektirmez ve CLI veya başka Python projelerinde kolayca entegre edilebilir.

Modern TensorFlow 2.x API’si ile uyumludur.

🔗 GitHub Repository: https://github.com/batuhanatilgan/GTSRB-Traffic-Sign-Classifier



🚦 GTSRB Traffic Sign Classifier (CNN)

This project implements a deep learning-based traffic sign classification model using the German Traffic Sign Recognition Benchmark (GTSRB) dataset. Completed as part of an interview task, the model can accurately recognize 43 different traffic signs.

🎯 Project Goals & Features

Data Management: The GTSRB dataset was downloaded via the Kaggle API into Google Colab and preprocessed for training.

Model Training: The model was trained using a Convolutional Neural Network (CNN) architecture and saved in .h5 or saved_model format.

Performance Visualization: Accuracy and Loss graphs were plotted throughout the training process.

Inference Function: A dedicated function allows classifying external image files without a graphical interface, returning the class label and probability.

Environment Optimization: TensorFlow 2.x API is used to prevent compatibility issues with different TensorFlow versions.

🛠 Technologies
Category	Technology / Library
Programming Language	Python
Deep Learning	TensorFlow, Keras (CNN Architecture)
Data Processing	NumPy, Pandas
Image Processing	OpenCV (resizing & preprocessing)
Visualization	Matplotlib (Accuracy / Loss plots)
Environment	Google Colab
📂 Project Structure
GTSRB-Traffic-Sign-Classifier/
│── README.md
│── model/                 # Trained model files (.h5 or saved_model)
│── data/                  # Dataset or sample data
│── src/
│   ├── preprocessing.py   # Data preprocessing scripts
│   ├── train.py           # Model training script
│   └── inference.py       # Prediction and inference function

📈 Model Performance

The model achieves high accuracy in classifying 43 different traffic signs.

Training performance can be monitored through Accuracy and Loss graphs.

📌 Notes

The inference function does not require a GUI and can be easily integrated into CLI or other Python projects.

Fully compatible with modern TensorFlow 2.x API.

🔗 GitHub Repository

https://github.com/batuhanatilgan/GTSRB-Traffic-Sign-Classifier
