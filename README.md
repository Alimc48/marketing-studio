# 🎨 Marketing Studio

> The AI-powered marketing strategy platform that turns business school theory into actionable insights — in 5 minutes, not 5 weeks.

**🌐 Live Demo:** https://alimc48.github.io/marketing-studio/

---

## 💭 Bu Proje Neden Var?

Üniversitede bir pazarlama dersi alan herkes aynı isimleri duyar: STP, 4P, Customer Journey, CAC, LTV, Porter, Kotler...

Sorun şu: Bu kavramlar **çok güçlü** ama gerçek hayatta uygulamak inanılmaz **zaman alıyor**. Bir startup için STP yapmak günler, persona oluşturmak haftalar, doğru bütçe dağılımına karar vermek aylar sürebiliyor.

Marketing Studio bu sorunu çözmeye çalışıyor:

> **Bir markanın bilgilerini gir → 30 saniye içinde 18 farklı modülde profesyonel pazarlama analizi al.**

---

## ✨ Neler Yapabilir?

### 🎯 Stratejik Konumlandırma (4 Modül)

- **STP Analizi** — Segmentation, Targeting, Positioning üçlüsü
- **Marka Konumlandırma Haritası** — Fiyat × Kalite scatter plot ile rakipler arası pozisyon
- **4P Pazarlama Karması** — Product, Price, Place, Promotion için özel öneriler
- **Birincil Persona Deep Dive** — Motivasyonlar, korkular, satın alma tetikleyicileri, itirazlar

### 👥 Müşteri Anlayışı (3 Modül)

- **3 Detaylı Persona** — Early Adopter, Pragmatic Buyer, Loyal Follower
- **Customer Journey Mapping** — Awareness → Loyalty 5 aşamalı yolculuk
- **Conversion Funnel** — Trafikten müşteriye dönüşüm hunisi

### 📊 Müşteri Ekonomisi (3 Modül)

- **CAC & LTV Analizi** — Sektör ortalamasıyla karşılaştırmalı
- **LTV:CAC Oranı + Sağlık Göstergesi** — Healthy / OK / Unhealthy
- **Sektör Benchmark** — Conversion, retention, CAC, LTV:CAC için "siz vs ortalama"

### 📺 Kanal Stratejisi (2 Modül)

- **Kanal ROI Karşılaştırması** — Instagram, Google, SEO, Email, Influencer için bar grafikler
- **Pazarlama Bütçesi Optimizasyonu** — Marka aşamana göre akıllı dağılım (donut chart)

### 📈 Pazar & İş Analizi (3 Modül)

- **TAM/SAM/SOM Pazar Büyüklüğü** — Toplam, hedeflenebilir ve gerçekçi pazar tahminleri
- **Marka Pitch Özeti** — Tek sayfalık investor-ready sunum kartı
- **Canlı Sektör İstihbaratı** — Güncel pazar verileri, trendler, büyük oyuncular

### 🤖 Yapay Zeka Destekli (3 Modül)

- **AI Pazarlama Strateji Raporu** — 6 bölümlü kapsamlı analiz
- **AI Pazarlama Danışmanı** — Soru-cevap formatında strateji desteği
- **90 Günlük Aksiyon Planı** — Önceliklendirilmiş ve etiketlenmiş eylemler

---

## 🚀 Nasıl Kullanılır?

1. **[alimc48.github.io/marketing-studio](https://alimc48.github.io/marketing-studio/)** adresine git
2. 4 sekmeli formu doldur: **Marka → Müşteri → 4P Karması → Metrikler**
3. **"Pazarlama Analizini Başlat"** butonuna bas
4. 30 saniye içinde 18 modülde rapor hazır
5. Sonuçları PDF olarak indir veya sosyal medyada paylaş

**Hızlı denemek istersen:** "Örnek Veri Yükle" butonu ile hayali bir kahve aboneliği şirketi (LumaBrew) yüklenir.

---

## 🎨 Tasarım Felsefesi

Marketing Studio'nun arayüzü kasıtlı olarak **yaratıcı ve enerjik**. Çünkü pazarlama tablodan ibaret değil — bir **his**.

- 🌸 **Magenta + Turuncu** ana paleti
- 🎭 **Bricolage Grotesque** display fontu — modern, dinamik, dikkat çekici
- ✨ **Animasyonlu blob** arka plan — durağan değil, canlı
- 🌓 **Light & Dark** tema — gece kullanım için optimize

---

## 🛠️ Teknik Detaylar

| Kategori | Detay |
|----------|-------|
| **Mimari** | Tek HTML dosyası |
| **Frontend** | Vanilla JavaScript, HTML5, CSS3 |
| **Görselleştirme** | SVG (donut, scatter, bar, pie chart, funnel) |
| **Storage** | LocalStorage API (geçmiş analizler) |
| **AI Layer** | Akıllı pattern matching + kural tabanlı analiz |
| **Build** | Hiç yok — sadece `index.html` |
| **Bağımlılık** | Sıfır harici dependency |

**Toplam kod:** 2.500+ satır, 18 modül, 59 fonksiyon

---

## 📦 Diğer Özellikler

- 🇹🇷 / 🇬🇧 **TR/EN bilingual** — i18n sistemi
- 💾 **Analiz Geçmişi** — son 20 analizi LocalStorage'da saklar, tek tıkla yükler
- 📤 **Sosyal Paylaşım** — LinkedIn, Twitter/X, WhatsApp doğrudan paylaşım butonları
- 📄 **PDF Export** — print-optimized rapor çıktısı
- 📱 **Responsive Design** — masaüstü, tablet ve mobile uyumlu

---

## 🎓 Üç Soru, Üç Araç

İşletme öğrencisi olarak girişimcinin üç temel sorusuna araç ile cevap vermeye çalışıyorum:

| Soru | Araç | Durum |
|------|------|-------|
| Pazara girmeli miyim? | [Traction Scope](https://github.com/Alimc48/traction-scope) | ✅ Live |
| Şirketim ne kadar eder? | [ValuScope](https://github.com/Alimc48/valuscope) | ✅ Live |
| Müşteriye nasıl ulaşırım? | **Marketing Studio** | ✅ Live |

Üç araç, üç farklı anda işine yarar. Hepsi ücretsiz, kayıtsız, açık.

---

## 📊 Test Edildi

Aşağıdaki senaryolar üzerinde defalarca çalıştırıldı:

- **LumaBrew** — Spesiyal kahve abonelik servisi (Türkiye, Growth aşaması, B2C subscription)
- *Daha fazla case study yakında...*

---

## 💬 Geri Bildirim

Bu araç **canlı bir proje.** Eksiklik gördüğünüzde, yeni özellik istediğinizde, bug yakaladığınızda:

- 💼 **LinkedIn:** [Alim Çeler](https://www.linkedin.com/in/alim%C3%A7eler/)
- 🐙 **GitHub Issues:** Repo'da Issues sekmesinden bildir
- 🇹🇷 **Konum:** Denizli, Türkiye

---

## 📝 Lisans

© 2026 Alim Çeler. All rights reserved.

Bu kod yalnızca görüntüleme amacıyla paylaşılmıştır. İzinsiz kopyalama, dağıtım veya kullanım yasaktır.

---

⭐ **Eğer bu projeyi beğendiyseniz GitHub'da yıldız atın — bu, devam etmem için en büyük motivasyon.**

🚀 **Marketing Studio sadece bir araç değil — pazarlama düşünce sürecinize yeni bir lens.**
