Maaş Verisi Analizi Projesi
# İçindekiler
- [Veri Seti](#veri-seti)
- [Gereksinimler](#gereksinimler)
- [Model Yapısı](#model-yapısı)
- [Eğitim Süreci](#eğitim-süreci)
- [Sonuçlar](#sonuclar)
- [Karmaşıklık Matrisi](#karmaşık-matris)
- [Kaggle Proje Linki](#kaggle-proje-linki)

Bu projede kullanılan veri seti, çalışanların maaşları, iş unvanları ve faydaları hakkında bilgiler içeren "Salaries.csv" dosyasından alınmıştır.

## Gereksinimler
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
## Veri Temizliği
Eksik veriler rastgele eklenmiş ve bu eksiklikler daha sonra medyan değeri ile doldurulmuştur.
Negatif maaş değerleri sıfıra dönüştürülmüştür.
Eksik sütunlar "NaN" ile işaretlenmiş ve gerekli işlemler yapılmıştır.
## Keşifsel Veri Analizi
Veri setinin yapısı ve temel istatistiksel bilgileri incelenmiştir.
Eksik verilerin oranı hesaplanmış ve analiz edilmiştir.
## Görselleştirmeler
Maaş Dağılımı: Toplam maaşın dağılımı histograma dökülerek incelenmiştir.
Yıllara Göre Ortalama Maaş: Yıllık maaşların ortalama değerleri çizgi grafiği ile gösterilmiştir.
En Yüksek Maaş Alan İş Unvanları: En yüksek maaş alan 10 iş unvanı bar grafiği ile sunulmuştur.
Kazanç Dağılımı (Boxplot): En yaygın 10 iş unvanı için maaş dağılımı boxplot ile görselleştirilmiştir.
Mesai Ücretleri: Yıl bazında mesai ücretlerinin dağılımı boxplot ile gösterilmiştir.
Maaş ve Mesai Ücretleri İlişkisi: Temel maaş ile mesai ücretleri arasındaki ilişkiyi inceleyen scatter plot oluşturulmuştur.
Korelasyon Matrisi: Çeşitli maaş türleri arasındaki korelasyon matrisi görselleştirilmiştir.
İş Unvanlarının Popülerliği: En popüler 10 iş pozisyonu pasta grafiği ile sunulmuştur.
## Sonuçlar
Maaşların genel dağılımı ve en yüksek maaş alan iş unvanları belirlenmiştir.
Yıllara göre ortalama maaşlar incelenmiş ve bazı iş unvanlarının daha yüksek maaşlara sahip olduğu tespit edilmiştir.
## Sonuç
Bu analiz, şirket içerisindeki maaş ve iş unvanları hakkında değerli bilgiler sunmuştur. Çalışan maaşlarının belirli iş unvanları ve yıllara göre nasıl değiştiğini görmek, hem çalışanlar hem de yöneticiler için faydalı olabilir.
