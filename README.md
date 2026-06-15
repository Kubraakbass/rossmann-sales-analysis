# rossmann-sales-analysis
Exploratory Data Analysis and Clustering on Rossmann Store Sales
# 🏪 Rossmann Sales Analysis

## 📌 Proje Hakkında

Bu projede Rossmann mağazalarına ait satış verileri analiz edilmiştir. 
Amaç; satışları etkileyen faktörleri keşfetmek, mağaza performanslarını incelemek ve benzer satış davranışına sahip mağazaları gruplandırmaktır.

Proje kapsamında **Keşifsel Veri Analizi (EDA)**, **Zaman Serisi Analizi** ve **K-Means Clustering** yöntemleri kullanılmıştır.

---

# 🎯 Proje Amaçları

- Satış trendlerini analiz etmek
- Promo kampanyalarının satışlara etkisini incelemek
- Tatil günlerinin satış davranışına etkisini görmek
- En iyi ve en düşük performanslı mağazaları belirlemek
- Benzer özelliklere sahip mağazaları kümelendirmek

---

# 📂 Veri Seti

Projede Rossmann Store Sales veri seti kullanılmıştır.

Veri setleri:

### train.csv
Günlük satış bilgileri:

- Store
- Date
- Sales
- Customers
- Promo
- StateHoliday
- SchoolHoliday


### store.csv

Mağaza özellikleri:

- StoreType
- Assortment
- CompetitionDistance
- Promo2
- PromoInterval

---

# 🛠 Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# 🧹 Veri Ön İşleme

Yapılan işlemler:

- Veri setleri birleştirildi (`train.csv` + `store.csv`)
- Tarih sütunu datetime formatına çevrildi
- Eksik değer kontrolleri yapıldı
- `StateHoliday` değişkeni düzenlendi
- Analiz için gerekli özellikler hazırlandı

---

# 📊 Keşifsel Veri Analizi (EDA)

## 📈 Promo Etkisi

Promo kampanyalarının satışlar üzerindeki etkisi incelendi.

Sonuç:

- Kampanya yapılan günlerde ortalama satışların daha yüksek olduğu gözlemlendi.
- Promo değişkeninin satış üzerinde önemli bir etkisi olduğu görüldü.

---

## 📅 Zaman Serisi Analizi

Günlük, haftalık ve aylık satış trendleri analiz edildi.

İncelenen konular:

- Zaman içinde satış değişimleri
- Dönemsel dalgalanmalar
- Kampanya dönemlerinin etkisi

---

# 🏪 Store Performans Analizi

Mağazalar:

- Toplam satış
- Ortalama satış
- Müşteri sayısı

değerlerine göre analiz edildi.

Bu analiz ile:

- En yüksek performanslı mağazalar
- Düşük performans gösteren mağazalar

belirlendi.

---

# 📊 Store Clustering (K-Means)

Mağazalar benzer satış davranışlarına göre gruplandırıldı.

Kullanılan özellikler:

- Ortalama satış
- Toplam satış
- Ortalama müşteri sayısı
- Promo kullanım oranı


Model:

- K-Means Clustering
- PCA ile görselleştirme

Sonuç olarak mağazalar farklı performans segmentlerine ayrıldı.

---

# 📌 Elde Edilen İçgörüler

- Promo kampanyaları satışları artırmaktadır.
- Mağazalar arasında belirgin performans farkları bulunmaktadır.
- Bazı mağazalar benzer satış davranışları göstermektedir.
- Satışlarda zaman bağlı değişimler bulunmaktadır.

---

# 🚀 Gelecek Çalışmalar

Projeyi geliştirmek için:

- Sales Prediction modeli oluşturulabilir
- Feature Engineering yapılabilir
- XGBoost / Random Forest modelleri denenebilir
- Streamlit ile interaktif dashboard hazırlanabilir

---

# 👩‍💻 Geliştirici

**Kübra**

Computer Programming Student  
Data Science & Data Analysis ile ilgileniyorum.
