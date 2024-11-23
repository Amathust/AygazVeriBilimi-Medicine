# AygazVeriBilimi-Medicine

Kaggle link: https://www.kaggle.com/code/furkancokunsu/aygazverianalizi-medical

README.md: Aygaz Veri Analizi - Tıbbi Öğrenci Analizi
Bu proje, Öğrenci grubuna ait bir veri setini analiz ederek demografik ve tıbbi değişkenler arasındaki ilişkileri keşfetmeyi amaçlamaktadır. Proje, veri işleme, analiz, görselleştirme ve çıkarım aşamalarını kapsamaktadır. Veri seti, kullanıcıların çeşitli özelliklerini içermekte olup, bu özelliklerin analiz edilmesi sonucunda anlamlı örüntüler elde edilmiştir.

📁 Proje İçeriği
1. Veri Yükleme ve İlk İnceleme
Projede kullanılan veri seti, Pandas kullanılarak yüklenmiştir.
Veri setindeki sütunlar, veri tipleri ve özet istatistikler incelenmiştir:
Toplam kayıt sayısı ve değişken tipleri.
Eksik veri oranlarının belirlenmesi ve temizlenmesi.
Gerekli durumlarda, kategorik değişkenler one-hot encoding veya benzeri yöntemlerle işlenmiştir.
2. Veri Temizleme ve Hazırlık
Eksik veya hatalı veriler:
Ortalama, medyan veya mod ile doldurulmuş.
İlgisiz kayıtlar (örneğin, uç değerler) filtrelenmiştir.
Yeni değişkenler oluşturulmuş ve veri seti zenginleştirilmiştir.
3. Keşifsel Veri Analizi (EDA)
Verinin genel yapısını anlamak ve hipotez geliştirmek için detaylı bir keşif süreci gerçekleştirilmiştir:
Tanımlayıcı İstatistikler:
Ortalama, standart sapma, minimum, maksimum değerler.
Kategorik Veriler:
Sıklık tablosu ve yüzdesel dağılımlar incelenmiştir.
Sayısal Veriler:
Korelasyon matrisleri oluşturulmuş, değişkenler arasındaki doğrusal ilişkiler analiz edilmiştir.
Gruplama ve Segmentasyon:
Kullanıcı gruplarına göre ayrım yapılmış (örneğin, yaş, cinsiyet veya tıbbi durumlara göre).
4. Görselleştirme
Proje boyunca, veriyi daha iyi anlamak için çeşitli grafikler oluşturulmuştur:

Histogramlar ve Yoğunluk Grafikleri:
Kullanıcıların özelliklerinin dağılımı.
Kutu Grafikleri (Boxplot):
Değişkenlerin uç değerlerinin tespiti.
Dağılım Grafikleri (Scatterplot):
Sayısal değişkenler arasındaki ilişkilerin görselleştirilmesi.
Korelasyon Matrisleri:
Matplotlib ve Seaborn kullanılarak oluşturulmuş ısı haritaları.
5. Modelleme ve Tahmin
Projede makine öğrenimi veya istatistiksel analiz için temel yöntemler uygulanmıştır (eğer varsa):
Regresyon modelleri veya sınıflandırma algoritmaları.
Öngörü ve tahmin süreçleri.
6. Sonuçlar ve Çıkarımlar
Proje sonucunda elde edilen temel bulgular şunlardır:
Tıbbi değişkenler ve demografik özellikler arasında anlamlı korelasyonlar.
Kullanıcı gruplarının genel davranış ve özellik farklılıkları.
Elde edilen sonuçların iş süreçlerine veya tıbbi araştırmalara uygulanabilirliği tartışılmıştır.

Bu proje boyunca kullanılan başlıca araçlar ve teknolojiler:
Programlama Dili: Python
Kütüphaneler:
Pandas: Veri manipülasyonu ve analizi.
NumPy: Sayısal hesaplamalar.
Matplotlib ve Seaborn: Veri görselleştirme.
Scikit-learn (varsa): Makine öğrenimi modellemesi.
