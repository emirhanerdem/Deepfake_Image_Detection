# Deepfake_Image_Detection
Derin Sahte Tespit Sistemi
Bu proje, derin sahte (deepfake) içeriklerin tespit edilmesine yönelik yeni bir sistemin geliştirilmesini amaçlamaktadır. ResNet50, CNN ve Xception gibi derin öğrenme modelleri kullanılarak, farklı veri setleriyle test edilmiş ve başarıyla uygulanmıştır.

## Projenin Amacı ##
Deepfake teknolojisi, görsel ve işitsel içeriklerde manipülasyon yaparak sahte veriler üretmektedir. Bu teknoloji, özellikle medikal verilerde güvenlik ve doğruluk açısından ciddi sorunlara yol açabilir. Bu çalışmada:
Gerçek ve sahte görüntülerin ayırt edilmesi

## Kullanılan Veri Setleri ##
Manjilkarki-deepfake-and-real-images: 191.720 görüntü içerir (%50 gerçek, %50 sahte).
xhlulu/140k-real-and-fake-faces: 140.000 görüntü içerir (%50 gerçek, %50 sahte).

## Kullanılan Modeller ve Sonuçlar: ##

### ResNet50:
Xhlulu veri setinde %98.87 doğruluk oranı.
Yüksek F1 skoru (%99) ve dengeli performans.

### CNN:
Manjilkarki veri setinde %88.15 doğruluk.
Fake görüntüler için %92 duyarlılık ve %85 kesinlik.

### Xception:
Xhlulu veri setinde %90 doğruluk.
Fake görüntüler için %96 duyarlılık ve %86 kesinlik.

#### Çalışma Ortamı
Google Colab Pro kullanılarak geliştirilmiş ve eğitilmiştir.
Kaggle platformundan alınan veri setleri Google Drive üzerinde saklanmıştır.

### Bu proje:
Deepfake içeriklerin tespiti için etkili bir yöntem sunar.
Tıbbi verilerin güvenilirliğini ve doğruluğunu artırmayı hedefler.
Araştırmacılara derin öğrenme tabanlı sahte içerik tespitinde rehberlik eder.

Eğer detaylı bir kod yapısına ulaşmak isterseniz, her bir derin öğrenme projesiyle ilgili dosyaya tıklayarak inceleyebilirsiniz.
