GTSRB-Traffic-Sign-Classifier
Trafik İşareti Sınıflandırma Projesi (CNN)
Bu proje, Alman Trafik İşareti Tanıma Kıyaslama (GTSRB) veri setini kullanarak, Derin Öğrenme tabanlı bir trafik işareti sınıflandırma modeli geliştirmek amacıyla bir mülakat görevi kapsamında tamamlanmıştır. Model, 43 farklı trafik işaretini yüksek doğrulukla tanıma yeteneğine sahiptir.

🚀 Projenin Temel Amaçları ve Özellikleri
Mülakat gereksinimlerine göre projede tamamlanan ana adımlar şunlardır:

Veri Yönetimi: Kaggle API kullanılarak veri seti Google Colab ortamına otomatik olarak çekilmiş ve ön işleme tabi tutulmuştur.

Model Eğitimi: Evrişimsel Sinir Ağları (CNN) mimarisi kullanılarak model eğitilmiş ve model dosyası (.h5 veya saved_model formatında) üretilmiştir.

Performans Görselleştirme: Eğitim süreci boyunca Accuracy (Doğruluk) ve Loss (Kayıp) grafikleri sunulmuştur.

Çıkarım (Inference) Fonksiyonu: Grafik arayüze ihtiyaç duymayan, dışarıdan görüntü dosyası yolu alarak sınıf etiketini ve olasılık değerini geri döndüren özel bir çıkarım fonksiyonu geliştirilmiştir.

Ortam Optimizasyonu: TensorFlow sürümünden kaynaklanabilecek olası hatalar, modern TensorFlow 2.x API'si kullanılarak önlenmiştir.

🛠️ Kullanılan Teknolojiler
Kategori	Teknoloji / Kütüphane
Dil	Python
Derin Öğrenme	TensorFlow, Keras (CNN Mimarisi)
Veri İşleme	NumPy, Pandas
Görüntü İşleme	OpenCV (Görüntü boyutlandırma ve ön işleme)
Görselleştirme	Matplotlib (Doğruluk/Kayıp Grafikleri)
Ortam	Google Colab

