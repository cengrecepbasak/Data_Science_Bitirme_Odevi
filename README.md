# 🎓 Veri Analizi ve Görselleştirme Ödevleri – README

Bu proje klasörü iki ana ödevden oluşmaktadır: **Ödev 1 (Veri Filtreleme & Sıralama)** ve **Ödev 2 (Veri Görselleştirme)**. Her ödev kendi klasörü içinde gerekli CSV dosyalarını ve Jupyter Notebook çalışmalarını barındırır.

---

## 📁 Klasör Yapısı

```
proje_klasoru/
│
├── ödev1/
│   ├── country.csv
│   └── Veri_filtreleme_siralama_projesi.ipynb
│
└── ödev2/
    ├── 50_Startups.csv
    └── Veri_Gorsellestirme_odevi.ipynb
```

---

# 🧮 ÖDEV 1: Veri Filtreleme ve Sıralama Projesi

Bu ödevde **country.csv** veri seti kullanılarak çeşitli filtreleme, sıralama ve seçim işlemleri yapılmıştır. Veri seti ülkelerin demografik, ekonomik ve coğrafi verilerini içerir.

### 📌 Kullanılan Sütunlar

* **Country**: Ülke adı
* **Region**: Bölge
* **Population**: Nüfus
* **Area (sq. mi.)**: Yüzölçümü
* **Pop. Density (per sq. mi.)**: Nüfus yoğunluğu
* **GDP ($ per capita)**: Kişi başı milli gelir
* **Literacy (%)**: Okur-yazarlık oranı
* ve diğer ekonomik/demografik özellikler...

### 📘 Yapılan Görevler

1. Nüfusa göre **azalan** sırada sıralama
2. GDP per capita değerine göre **artan** sırada sıralama
3. Nüfusu 10 milyonun üzerindeki ülkeleri seçme
4. En yüksek okur-yazarlık oranına sahip **ilk 5 ülke**
5. GDP per capita 10.000'in üzerinde olan ülkeler
6. En yüksek nüfus yoğunluğuna sahip **ilk 10 ülke**

Tüm kodlar: **Veri_filtreleme_siralama_projesi.ipynb** dosyasındadır.

---

# 📊 ÖDEV 2: Veri Görselleştirme Projesi

Bu ödevde **50_Startups.csv** veri seti kullanılarak çeşitli grafik türleri ile görsel analiz yapılmıştır.

### 📌 Veri Seti Sütunları

* **R&D Spend**: Ar-Ge harcaması
* **Administration**: Yönetim harcaması
* **Marketing Spend**: Pazarlama harcaması
* **State**: Eyalet
* **Profit**: Kâr

### 📘 Yapılan Görselleştirme Görevleri

1. **Scatter Plot**: R&D Harcaması vs Kâr
2. **Scatter Plot**: Yönetim Harcaması vs Kâr
3. **Bar Chart**: Eyaletlere göre ortalama kâr
4. **Boxplot**: R&D, Yönetim ve Pazarlama harcamalarının karşılaştırılması

Tüm grafikler: **Veri_Gorsellestirme_odevi.ipynb** dosyasındadır.

---

# 📌 Gereksinimler

Bu ödevleri çalıştırmak için aşağıdaki kütüphaneler gereklidir:

* pandas
* numpy
* matplotlib
* Jupyter Notebook / JupyterLab

Kurulum:

```bash
pip install pandas numpy matplotlib
```

---

# 📚 Notlar

* Notebook dosyaları adım adım açıklamalar içermektedir.
* Grafikler ve tablolar otomatik olarak yeniden üretilebilir şekildedir.
* Veri setleri klasörler içinde hazır bulunmaktadır.

---

### Hazırlayan: Recep Başak (Ödev Sunumu)


