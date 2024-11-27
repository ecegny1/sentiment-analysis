## Duygu Analizi

## Proje Açıklaması

Bu proje, metinlerin duygusal analizini yapmayı amaçlayan bir sentiment analysis modelidir. Model, verilen metinlerdeki duygusal tonları belirlemek için çeşitli doğal dil işleme (NLP) teknikleri ve makine öğrenimi algoritmalarını kullanır. Bu analiz, sosyal medya paylaşımları, yorumlar veya ürün incelemeleri gibi çeşitli metin kaynaklarında duygu tespiti yaparak, işletmelere ve araştırmacılara kullanıcılardan gelen geri bildirimleri anlamada yardımcı olabilir.

## Kullanılan Yöntemler

Veri Kümesi: Projede kullanılan veri seti, kullanıcı yorumlarından veya sosyal medya paylaşımlarından toplanmış metinlerden oluşmaktadır.

Öznitelik Seçimi ve Ön İşleme: Veri ön işleme adımları arasında metin temizliği, stop kelimelerin kaldırılması, küçük harfe dönüştürme ve lemmatizasyon yer almaktadır.

Modelleme: Model, metin verilerini analiz etmek için XGBoost veya LSTM gibi derin öğrenme teknikleri kullanarak eğitim almıştır.
Değerlendirme: Modelin doğruluğu, precision, recall ve F1 skoru gibi metrikler kullanılarak değerlendirilmiştir.

## Gereksinimler

Proje çalıştırılmadan önce aşağıdaki kütüphaneler yüklü olmalıdır:

Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
tensorflow (LSTM model için)
nltk

Bu kütüphaneleri yüklemek için aşağıdaki komutu kullanabilirsiniz:

```bash
pip install -r requirements.txt
```


## Kullanım
Proje, Jupyter Notebook formatında yazılmıştır. Aşağıdaki adımları takip ederek projeyi çalıştırabilirsiniz:

sentiment-analysis.ipynb dosyasını açın.
Gerekli veri setlerini ve dosyaları yükleyin.
Modeli eğitin ve doğruluk gibi metriklerle değerlendirin.

## Sonuçlar
Proje, duygu analizi için çeşitli metin örnekleri üzerinde test edilmiştir. Model, verilen metinlerdeki olumlu, olumsuz ve nötr duyguları doğru bir şekilde sınıflandırabilmektedir. Daha fazla iyileştirme için hiperparametre optimizasyonu ve daha büyük veri setleri kullanılabilir.

