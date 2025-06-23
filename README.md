# pet-classifier-cnn (Computer Vision Projesi 🐱🐶)

Bu proje, TensorFlow ve Keras kullanılarak yapılmış basit bir görüntü sınıflandırma modelidir. Amaç, yüklenen bir görselin kedi mi yoksa köpek mi olduğunu tahmin etmektir.

## 🚀 Kullanılan Teknolojiler
- Python
- TensorFlow / Keras
- Google Colab
- CNN (Convolutional Neural Network)
- Görsel ön işleme: `ImageDataGenerator`

## 📁 Veri Seti
Veri seti `cats/` ve `dogs/` olmak üzere iki alt klasörden oluşmaktadır.  
%80 eğitim, %20 doğrulama verisi olarak ayrılmıştır.

## 📊 Model Eğitimi
Model 10 epoch boyunca eğitilmiş ve hem eğitim hem doğrulama verilerinde yüksek doğruluk elde etmiştir.

## 🧪 Örnek Test
Test görseli başarıyla sınıflandırılmıştır:
- `catt.jpg` → **Kedi 🐱**

## 📁 Dosyalar
- `model_egitimi.ipynb` – Eğitim süreci ve testler
- `test_set.zip` – Eğitimde kullanılan veri seti
- `kedi_kopek_modeli.h5` – Eğitilen model dosyası
- `test_gorsel/` – Test için kullanılan görseller

## 📝 Not
Bu proje, bilgisayarla görü alanına giriş için yapılmıştır.  
Geliştirilmiş sürümlerde farklı türler, daha büyük veri setleri ve web arayüzü eklenebilir.
