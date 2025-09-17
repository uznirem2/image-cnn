# image-cnn
CNN tabanlı görüntü sınıflandırma projesi
# Intel Image Classification - CNN Projesi

##  Proje Amacı
Bu projede, Convolutional Neural Network (CNN) mimarisi kullanarak farklı doğal ve yapay ortamların görsellerini sınıflandırmak amaçlanmıştır. 

Proje, Akbank Derin Öğrenme Bootcamp kapsamında gerçekleştirilmiştir.

##  Veri Seti

- **Kaynak:** [Intel Image Classification Dataset on Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)
- **Sınıflar (6 tane):** `Buildings`, `Forest`, `Glacier`, `Mountain`, `Sea`, `Street`
- **Boyut:** ~25.000 eğitim verisi, ~14.000 test verisi

## Kullanılan Yöntemler

- CNN tabanlı model (Conv2D, MaxPooling, Dropout, Dense)
- Veri önişleme (Resim boyutlandırma, normalize etme)
- Veri artırma (Data Augmentation)
- Model değerlendirme (Accuracy, Loss, Confusion Matrix)
- Grad-CAM görselleştirme (modelin görselden nereden etkilendiğini analiz etmek için)
- Hiperparametre optimizasyonu (Batch size, filtre sayısı, dropout oranı vs.)

##  Elde Edilen Sonuçlar

Model, test verisi üzerinde yaklaşık `%XX` doğruluk oranına ulaşmıştır.  
(Modeli eğittikten sonra bu kısmı dolduracaksın.)

##  Kaggle Notebook Linki

 [Kaggle Notebook’a Gitmek için Tıklayın](https://www.kaggle.com/USERNAME/NOTEBOOK-LINK)  
(Bu linki projen bittikten sonra buraya eklersin.)

---

