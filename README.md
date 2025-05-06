# 🧠 Derin Öğrenme ile Ses Tanıma Projesi

Bu proje, **Yapay Sinir Ağları** dersi kapsamında geliştirilmiş ve ses verisi üzerinden sınıflandırma yapmayı amaçlayan bir çalışmadır. Proje, Jupyter Notebook ortamında yürütülmüş ve çeşitli Python kütüphaneleri kullanılarak hayata geçirilmiştir.

## 🎯 Proje Amacı

Ses sinyalleri kullanılarak konuşmacı ya da sınıf tespiti yapılması. Girdi olarak verilen ses dosyaları uygun şekilde işlenerek, yapay sinir ağı yardımıyla sınıflandırılmaktadır.

## 🛠 Kullanılan Teknolojiler

- Python 3
- NumPy, SciPy
- Librosa (jenerik ses işleme)
- Keras / TensorFlow (derin öğrenme)
- Matplotlib (görselleştirme)
- Jupyter Notebook

## 🧪 Projede Uygulanan Adımlar

1. Veri yükleme ve ön işleme (MFCC çıkarımı vs.)
2. Eğitim ve test verisinin hazırlanması
3. Sinir ağı mimarisinin kurulması (Keras kullanılarak)
4. Modelin eğitimi
5. Performans değerlendirme ve sonuçların görselleştirilmesi

## 📁 Proje Dosya Yapısı
├── DerinSesTanma.ipynb                # Ana notebook dosyası
├── README.md                      
├── requirements.txt                    # Gerekli kütüphaneler
├── report/
│ ├── Yapay Sinir Ağları Raporu.pdf     # PDF formatında ders raporu
│ └── Yapay Sinir Ağları Sunum.pptx     # PowerPoint sunumu

## 🔧 Kurulum

1. Python 3.9+ ortamı oluşturun.
2. Gerekli kütüphaneleri yükleyin:   pip install -r requirements.txt
3. Notebook'u çalıştırın:            jupyter notebook DerinSesTanıma.ipynb

## ✍️ Notlar
- Proje, bireysel öğrenim ve akademik çalışma amacıyla geliştirilmiştir.
- Ses dosyaları, proje klasörüne dahil edilmemiştir. Çalışma için gerekli veri, kullanıcı tarafından eklenmelidir.