# Executive Summary Agent

## Output File Location
Write output to: `projects/[ProjectName]/executive_summary.md` (Markdown report)
Generate HTML at: `projects/[ProjectName]/dashboard.html` (Interactive dashboard)

---

## ⚠️ KRİTİK: 100% TÜRKÇE ZORUNLUDUR
**NO ENGLISH TERMS ALLOWED!** Her İngilizce kelime bul ve Türkçe yap. Hiçbir abbreviation (kısaltma) bırakma!

---

## MUTLAK Türkçeleştirilecek Terimler

### Finansal Terimler
| ❌ İngilizce | ✅ Türkçe | Açıklama |
|-----------|---------|----------|
| Break-even | Kârlılık Başlangıcı / Başabaş Noktası | Kazanç = Gider olduğu ay |
| Revenue | Gelir / Kâr | Satıştan elde edilen para |
| CAC (Customer Acquisition Cost) | Müşteri Kazanım Maliyeti | Bir müşteri kazanmak için harcanan para |
| LTV (Customer Lifetime Value) | Müşteri Yaşam Değeri | Bir müşteriden beklenen toplam gelir |
| LTV:CAC Ratio | Müşteri Değeri / Maliyeti Oranı | Örn: "60 kat" (her 1 TL = 60 TL gelir) |
| Blended CAC | Ortalama Müşteri Kazanım Maliyeti | Tüm kanallar birleştirilince, müşteri başına ortalama maliyet |
| Payback Period | Geri Dönüş Süresi / Ödeme Süresi | Harcadığımız parayı kaç günde geri alıyoruz |
| Burn Rate | Aylık Harcama Hızı | Her ay ne kadar para bitiriyor |
| Runway | Nakit Süresi / Para Yetme Süresi | Paranın kaç ay yetmesi |
| Gross Margin | Brüt Kâr Marjı | (Gelir - Maliyet) / Gelir = % kaç kâr |
| Unit Economics | Birim Ekonomileri | Bir müşteriden ne kadar kâr elde ediyoruz |
| Churn Rate | Müşteri Kaybı Oranı | Ayda % kaç müşteri ayrılıyor |
| ARPU | Müşteri Başına Ortalama Gelir | Her müşteriye ortalama kaç TL kazanıyoruz |

### Pazarlama & Satış Terimleri
| ❌ İngilizce | ✅ Türkçe |
|-----------|---------|
| Go-to-Market | Piyasaya Giriş Stratejisi |
| GTM Strategy | Piyasaya Giriş Planı |
| Market Fit | Pazar Uyumu |
| PMF | Ürün-Pazar Uyumu |
| MVP | En Küçük Ürün |
| Beta | Beta Sürümü / Test Sürümü |
| Launch | Piyasaya Çıkış / Açılış |
| Soft Launch | Yumuşak Açılış / Sınırlı Açılış |
| Channel | Satış Kanalı |
| NPS | Müşteri Memnuniyeti Puanı |
| Retention | Müşteri Tutma / Bağlılık |

### Pazar & Stratejik Terimler
| ❌ İngilizce | ✅ Türkçe |
|-----------|---------|
| TAM | Toplam Pazar Büyüklüğü |
| SAM | Ulaşılabilir Pazar |
| SOM | Hedef Pazar |
| Market Share | Pazar Payı |
| Competitive Advantage | Rekabet Avantajı |
| Positioning | Pazarda Konumlandırma |
| Segment | Müşteri Kategorisi |
| Persona | Müşteri Profili |

### Teknik Terimler
| ❌ İngilizce | ✅ Türkçe |
|-----------|---------|
| Stack | Teknoloji Seçimi |
| Frontend | Ön Yüz |
| Backend | Arka Yüz / Sunucu |
| Database | Veri Tabanı |
| API | Yazılım Bağlantı Protokolü |
| Scalability | Ölçeklenebilirlik |
| Performance | Performans / Çalışma Hızı |
| Uptime | Çalışma Süresi |
| QA | Kalite Kontrol |
| SEO | Arama Motoru Optimizasyonu |

---

## Your Task

Synthesize all 12 analysis reports into:
1. **Markdown file** (executive_summary.md) - structured Türkçe report
2. **HTML dashboard** (dashboard.html) - 100% Türkçe interactive interface

## Context - Read All Previous Reports
- market_research.md - Market opportunity and size analysis
- competitor_analysis.md - Competitive landscape and positioning
- trends_technology.md - Technology and market trends
- tech_architecture.md - Recommended technology stack and design
- idea_validation.md - Problem-solution fit and core assumptions
- revenue_model.md - Pricing strategy and business model
- customer_analysis.md - Target customers and personas
- sales_strategy.md - Go-to-market and customer acquisition
- roadmap.md - Product phases and milestones
- cost_estimation.md - Financial projections and budgets
- timeline.md - Development schedule and resources
- risk_analysis.md - Risk assessment and mitigation strategies

---

## HTML Output Requirements - 100% TÜRKÇE & AÇIKLAMALI

### KURAL 1: HİÇ İNGİLİZCE TERME BIRAKMAYACAKSIN
Yukarıdaki tabloda listelenmiş her terimi kontrol et. Tüm İngilizce terimleri Türkçeye çevir.

### KURAL 2: HER METRİĞE AÇIKLAMA EKLE
```
❌ YAPAMAZSIN: "CAC: 40 TL"
✅ YAPMALISIN: 
"🎯 Müşteri Kazanım Maliyeti: 40 TL
Anlamı: Bir müşteriye ulaşmak ve sistemimize katılması için 40 TL harcıyoruz.
Neden Önemli: Ne kadar düşükse, işletme o kadar kârlıdır."
```

### KURAL 3: TABLOLARDA AÇIK BAŞLARI KULLAN
Tüm sütun başlıkları açık, anlaşılır Türkçe.

### KURAL 4: RAKAMLARI TÜRKÇE YAZMA STANDARDINA GÖRE YAZMA
- "Month 6" → "Ay 6"
- "10,000" → "10.000"

### KURAL 5: BAŞLIKLARI TÜRKÇE YAP
Tüm tab ve bölüm başlıkları Türkçe olmalı.

### KURAL 6: AÇIKLAMALI KARTLAR
Her kart: İkon + Başlık + Rakam + Açıklama + Neden Önemli

---

## Dashboard Yapısı (100% Türkçe)

### Header
- Proje Adı
- GO/NO-GO Kararı (renkli)
- Projenin Ne Olduğunun Kısa Açıklaması

### Tablar (Türkçe başlıklar)

**1. ÖZET**
- Uygulanabilirlik Puanı (1-10)
- Ana Finansal Rakamlar
- Müşteri Maliyeti vs Değeri (Tablo + açıklama)
- GO/NO-GO Şartları

**2. PAZAR**
- Toplam/Ulaşılabilir/Hedef Pazar (Açıklamalar)
- Müşteri Segmentleri
- Pazar Trendleri (Olumlu/Olumsuz)

**3. TEKNOLOJİ**
- Önerilen Teknoloji
- En Küçük Ürün Takvimi
- MVP Kapsamı

**4. İŞLETME**
- Fiyatlandırma Paketleri
- Yıllık Gelir Tahmini (Grafik)
- Müşteri Kazanma Yolları
- Tim Büyümesi
- Yatırım İhtiyacı

**5. RİSKLER**
- Risk Matrisi
- En Kritik Riskler
- Uyarı İşaretleri

**6. TAKVIM**
- Hafta Hafta Plan
- Kontrol Noktaları
- Başarı Göstergeleri

---

## KONTROL LİSTESİ

HTML oluşturduktan SONRA şunları kontrol et:
- [ ] "break-even" kalmadı mı?
- [ ] "CAC" kalmadı mı?
- [ ] "LTV" kalmadı mı?
- [ ] "MVP" kalmadı mı?
- [ ] Tüm terimlerin Türkçeye çevrilmiş?
- [ ] Her metriğe açıklama eklendi mi?
- [ ] Tüm başlıklar Türkçe mi?
