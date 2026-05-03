# 🏃 context-pe: Kişisel Spor Zekâsı ve Performans Hafızası Sistemi

*Beden eğitimi öğrencileri ve sporcular için, kişisel verilerden beslenen, sıfır halüsinasyon prensibiyle çalışan, çok modüllü spor öğrenme ve performans sistemi.*

---

## 1. Tez (Thesis)

Spor ve beden eğitimi alanında en kritik eksik, **kişisel bağlama dayalı öğrenme ve performans yönetimidir.**

context-pe’in çekirdek iddiası:

**Kullanıcının tüm akademik, fiziksel ve performans verilerinin birleştiği kişisel wiki yapısı, tüm sistemin tek gerçek kaynağıdır.**

Bu yapı:
- öğrenme (dersler)
- performans (antrenman)
- sağlık (sakatlık & toparlanma)

katmanlarını birleştirerek **kişisel spor zekâsı** üretir.

---

## 2. Problem

### 📌 1. Genel Tavsiye Problemi
- Herkese aynı antrenman önerileri
- Kişisel geçmiş dikkate alınmıyor

### 📌 2. Veri Parçalanması
- Antrenman uygulamaları
- Notlar
- Videolar
- Sağlık verileri

Birbirinden kopuk sistemler

### 📌 3. Öğrenme & Performans Ayrılığı
- Teori ayrı
- Pratik ayrı

### 📌 4. Güven Problemi
- AI sistemleri veri uydurabiliyor
- Spor/sağlık alanında riskli

---

## 3. Nasıl Çalışır (How It Works)

### Temel İçgörü 1 — Kişisel Wiki = Tek Gerçek Kaynak

Toplanan veriler:
- Ders notları
- Antrenman kayıtları
- Video analizleri
- Sakatlık geçmişi
- Performans testleri
- Uyku & toparlanma

➡️ Tek yapı: **context-pe wiki**

---

### Temel İçgörü 2 — Veri → Anlam → İlişki

Örnek ilişkilendirme:

- Squat → diz valgusu
- Koşu yükü ↑
- Uyku ↓
- Diz ağrısı ↑

➡️ Sistem çıkarımı:
**yük + teknik + toparlanma ilişkisi**

---

### Temel İçgörü 3 — Strict RAG

Kural:

> Wiki’de olmayan veri yoktur.

Sistem:
- uydurma yapmaz
- eksik veride kesin konuşmaz

---

### Temel İçgörü 4 — Modüler Yapı

- narrate-pe
- cert-pe
- coach-pe
- performance-map

---

## 4. Mimari (Architecture)

### 1. Ingestion Layer
- PDF
- Notlar
- Antrenman logları
- Video
- Sağlık verileri

---

### 2. Structuring Agent
- konu çıkarımı
- etiketleme
- veri formatlama

---

### 3. Relation Engine
- teknik ↔ sakatlık
- yük ↔ performans
- uyku ↔ yorgunluk

---

### 4. Personal Wiki Builder

Alt yapılar:

- Akademik Wiki
- Antrenman Wiki
- Performans Wiki
- Teknik Analiz Wiki
- Sakatlık Wiki
- Toparlanma Wiki

---

### 5. Strict RAG Layer

Tüm modüller sadece buradan veri alır.

---

### 6. Output Modülleri

- narrate-pe
- cert-pe
- coach-pe
- performance-map

---

## 5. Wiki Yapısı

### 📚 Akademik Wiki
- Anatomi
- Egzersiz fizyolojisi
- Antrenman bilimi
- Spor psikolojisi

---

### 🏋️ Antrenman Wiki
- Kuvvet
- Dayanıklılık
- Teknik çalışmalar

---

### 📊 Performans Wiki
- VO2max
- Cooper testi
- 1RM
- gelişim trendleri

---

### 🎥 Teknik Analiz Wiki
- hareket analizi
- video çıkarımları

---

### ⚠️ Sakatlık & Risk Wiki
- ağrı kayıtları
- risk ilişkileri
- uyarılar

---

### 😴 Toparlanma Wiki
- uyku
- yorgunluk
- beslenme

---

## 6. Modüller

### 🎙️ narrate-pe
- ders anlatımı
- performans özeti

---

### 🧪 cert-pe
- sadece yüklenen kaynaklardan sınav

---

### 🧠 coach-pe
- tamamen kişisel veri bazlı öneri

---

### 📈 performance-map
- gelişim grafikleri
- yük analizi
- risk haritası

---

## 7. Başarı Kriterleri

- %100 veri doğruluğu
- %0 halüsinasyon
- izlenebilir öneriler
- kullanıcı güveni
- performans gelişimi

---

## 8. Fark

❌ Genel sistem:
"Haftada 3 gün koş"

✅ context-pe:
"Yük arttı + diz ağrısı + düşük uyku → toparlanma odaklı ilerle"

---

## 9. Vizyon

**Sporcunun ikinci beyni**

---

## 10. Profesyonel Tanım

context-pe, spor bilimleri öğrencileri ve sporcular için geliştirilen, akademik bilgi, antrenman verisi, performans ölçümleri ve sağlık kayıtlarını tek bir kişisel bilgi ağı altında birleştiren yapay zekâ destekli bir sistemdir. Sistem yalnızca kullanıcı verisine dayanır ve sıfır halüsinasyon prensibiyle çalışır.

---

## 11. Sistem Akışı

Kullanıcı Verisi  
↓  
Ingestion  
↓  
LLM Anlamlandırma  
↓  
Kişisel Wiki  
↓  
Strict RAG  
↓  
Modüller  

---

## 12. Kısa Özet

context-pe:

- kişisel antrenman hafızası  
- akademik öğrenme sistemi  
- performans analiz motoru  
- sakatlık risk farkındalığı  
- AI destekli gelişim haritası
