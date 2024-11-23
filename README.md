# Maaş Verisi Analizi Projesi

## İçindekiler
- [Gereksinimler](#gereksinimler)
- [Veri işlem süreci](#Veri-temizliği)
- [Sonuçlar](#sonuçlar)
- [Öneriler](#stratejik-çıkarımlar-ve-Öneriler)
- [Kaggle Proje Linki](#kaggle-proje-linki)

Bu projede kullanılan veri seti, çalışanların maaşları, iş unvanları ve faydaları hakkında bilgiler içeren "Salaries.csv" dosyasından alınmıştır.

## Gereksinimler
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Veri Temizliği
Eksik veriler rastgele eklenmiş ve bu eksiklikler daha sonra medyan değeri ile doldurulmuştur.  
Negatif maaş değerleri sıfıra dönüştürülmüştür.  
Eksik sütunlar "NaN" ile işaretlenmiş ve gerekli işlemler yapılmıştır.

## Keşifsel Veri Analizi
Veri setinin yapısı ve temel istatistiksel bilgileri incelenmiştir.  
Eksik verilerin oranı hesaplanmış ve analiz edilmiştir.

## Görselleştirmeler
- **Maaş Dağılımı**: Toplam maaşın dağılımı histograma dökülerek incelenmiştir.
- **Yıllara Göre Ortalama Maaş**: Yıllık maaşların ortalama değerleri çizgi grafiği ile gösterilmiştir.
- **En Yüksek Maaş Alan İş Unvanları**: En yüksek maaş alan 10 iş unvanı bar grafiği ile sunulmuştur.
- **Kazanç Dağılımı (Boxplot)**: En yaygın 10 iş unvanı için maaş dağılımı boxplot ile görselleştirilmiştir.
- **Mesai Ücretleri**: Yıl bazında mesai ücretlerinin dağılımı boxplot ile gösterilmiştir.
- **Maaş ve Mesai Ücretleri İlişkisi**: Temel maaş ile mesai ücretleri arasındaki ilişkiyi inceleyen scatter plot oluşturulmuştur.
- **Korelasyon Matrisi**: Çeşitli maaş türleri arasındaki korelasyon matrisi görselleştirilmiştir.
- **İş Unvanlarının Popülerliği**: En popüler 10 iş pozisyonu pasta grafiği ile sunulmuştur.

## Sonuçlar
- Maaşların genel dağılımı ve en yüksek maaş alan iş unvanları belirlenmiştir.
- Yıllara göre ortalama maaşlar incelenmiş ve bazı iş unvanlarının daha yüksek maaşlara sahip olduğu tespit edilmiştir.

## Stratejik Çıkarımlar ve Öneriler


Bu Proje, şirket içerisindeki maaş ve iş unvanları hakkında değerli bilgiler sunmuştur. Maaş verilerini inceleyerek şirketin içindeki maaş yapıları, iş unvanları ve performans üzerine değerli bilgiler sunmaktadır. Bu tür veri analizi, özellikle insan kaynakları ve yönetim ekipleri için önemli karar destek araçları sağlar. Proje, çalışan maaşlarının nasıl iyileştirilebileceğini ve hangi pozisyonların daha yüksek maaşlar gerektirdiğini belirlemeye yardımcı olabilir. Bu bilgiler, ücretlendirme politikalarının yeniden yapılandırılmasında ve rekabetçi maaş stratejilerinin oluşturulmasında kullanılabilir.

Yapay zeka ve makine öğrenimi modelleri, benzer veri setleriyle eğitilerek, maaş tahminleri yapmak için kullanılabilir. Bu tür modeller, gelecekteki maaş artışlarını tahmin edebilir ve şirketin bütçeleme süreçlerini optimize edebilir.
## Kaggle Proje Linki
[Kaggle Proje Linki](https://www.kaggle.com/code/yigitdede/veri-analizi)
