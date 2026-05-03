
## 1. Tez (Thesis)

Günümüzde bilgi:
- dağınık
- bağlamsız
- kişiselleştirilmemiş

context’in temel iddiası:

**Kullanıcıya ait tüm bilgi tek bir yapılandırılmış wiki sisteminde toplanmalı ve tüm çıktı sistemleri sadece bu kaynaktan beslenmelidir.**

Bu sayede:
- bilgi anlam kazanır
- modüller tutarlı çalışır
- halüsinasyon ortadan kalkar

---

## 2. Problem

### 📌 1. Bilgi Dağınıklığı
- Notlar farklı yerlerde
- PDF’ler ayrı
- Deneyimler ayrı

### 📌 2. Bağlam Eksikliği
- AI sistemler kullanıcıyı tanımaz
- Geçmiş veri kullanılmaz

### 📌 3. Güven Problemi
- AI içerik uydurabilir
- Kaynak belirsizdir

### 📌 4. Pasif Bilgi
- Bilgi saklanır ama kullanılmaz
- Aksiyona dönüşmez

---

## 3. Çözüm (Solution)

context, üç ana modülden oluşur:

- **context-wiki → Bilgi Katmanı**
- **context-narrate → Anlatı Katmanı**
- **context-kiosk → Etkileşim Katmanı**

➡️ Sistem döngüsü:

**Veri → Anlam → Anlatı → Etkileşim**

---

## 4. Sistem Bileşenleri

---

### 🧱 4.1 context-wiki (Core Layer)

Sistemin temelidir.

Toplanan veriler:
- akademik içerikler
- kişisel notlar
- performans verileri
- analizler
- ilişkiler

#### Özellikler:
- yapılandırılmış veri
- ilişkisel bilgi ağı
- konu bağlantıları
- zaman bazlı kayıtlar

#### Kural:
> Wiki’de olmayan bilgi sistem için yoktur.

---

### 🎙️ 4.2 context-narrate (Output Layer)

Wiki verisini şu formatlara dönüştürür:
- sesli anlatım
- podcast
- özet içerik

#### Özellikler:
- çok sesli anlatım sistemi
- kritik bilgileri vurgulama
- kaynak seslendirme (citation voice)
- show notes üretimi

#### Amaç:
➡️ Hands-free öğrenme

---

### 🖥️ 4.3 context-kiosk (Interface Layer)

Kullanıcının sistemle etkileşim kurduğu katmandır.

#### Özellikler:
- soru-cevap sistemi
- dashboard
- veri görselleştirme
- hızlı erişim

#### Örnek Kullanım:
- “Bu hafta performansım nasıl?”
- “Bu konuyu özetle”
- “Geçmiş veriye göre öneri ver”

---

## 5. Temel İçgörüler

### 🔹 1. Tek Kaynak Prensibi
Tüm modüller sadece context-wiki’den beslenir.

---

### 🔹 2. Strict RAG
- veri uydurulmaz
- eksik veri → uyarı verilir
- tüm çıktılar izlenebilir

---

### 🔹 3. Modüler Mimari
- wiki → veri
- narrate → içerik
- kiosk → etkileşim

---

### 🔹 4. Kişiselleştirme
- sistem kullanıcıya özeldir
- genel öneri vermez

---

## 6. Mimari (Architecture)

Kullanıcı Verisi  
↓  
Ingestion Layer  
↓  
Structuring & Tagging  
↓  
Relation Engine  
↓  
context-wiki  
↓  
Strict RAG  
↓  
Modüller:  
- context-narrate  
- context-kiosk  

---

## 7. Kullanım Senaryosu

Kullanıcı:
- ders notu yükler
- antrenman kaydeder
- video ekler

Sistem:
- veriyi işler
- ilişkileri kurar
- analiz yapar

Kullanıcı sorar:
> “Bu hafta neye dikkat etmeliyim?”

Sistem:
- geçmiş veriye bakar
- riskleri analiz eder
- kişisel öneri sunar

---

## 8. Başarı Kriterleri

- %100 kaynak izlenebilirliği
- %0 halüsinasyon
- yüksek kullanıcı güveni
- kişiselleştirilmiş çıktı
- modüller arası tutarlılık

---

## 9. Vizyon

**context = kullanıcının ikinci beyni**

---

## 10. Ürün Tanımı

context, kullanıcıya ait bilgileri tek bir yapılandırılmış wiki sisteminde toplayan, bu verileri anlamlandıran ve sesli anlatım ile etkileşim katmanları üzerinden erişilebilir hale getiren modüler bir yapay zekâ platformudur.

---

## 11. Sistem Döngüsü

Veri  
↓  
Wiki  
↓  
Anlamlandırma  
↓  
Anlatı  
↓  
Etkileşim  
↓  
Yeni veri  

---

## 12. Kısa Özet

context:

- kişisel bilgi hafızası  
- anlatı üretim sistemi  
- etkileşim platformu  
- güvenilir AI altyapısı  

---