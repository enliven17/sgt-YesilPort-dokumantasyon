# YeşilPort: İklim Değişikliği ile Mücadele Bağlantısı

## Özet

YeşilPort, binaların iklim değişikliğine karşı dayanıklılığını ölçen dijital bina pasaportu platformudur. Proje, **ana eksen olarak Uyum & Dayanıklılık (Adaptation & Resilience)**, **ikincil katkı olarak Azaltım (Mitigation)** yaklaşımını benimser.

**Ana Eksen Seçimi Gerekçesi:**

Türkiye, iklim değişikliğinin etkilerini şiddetle yaşayan bir coğrafyadadır:
- 2021 Kastamonu-Sinop sel felaketi: 82 can kaybı, 1.500+ bina ağır hasar
- 2021 Manavgat-Marmaris orman yangınları: 9 can kaybı, 270.000 hektar orman
- 2023 Hatay sel felaketi: Altyapı çöküşü, binlerce kişi etkilendi
- Artan kentsel ısı adası etkisi: İstanbul, Ankara, İzmir'de +5°C sıcaklık artışı

YeşilPort, bu acil ihtiyaca yanıt vererek binaların dayanıklılığını ölçer, zayıf noktaları tespit eder ve iyileştirme yol haritası sunar. IFC World Bank Group'un Building Resilience Index (BRI) metodolojisini kullanarak sistematik risk değerlendirmesi yapar. Aynı zamanda, enerji verimliliği ve karbon ayak izi hesaplamaları ile azaltım hedeflerine de katkı sağlar.

---

## 1. Ana Eksen: Uyum & Dayanıklılık (Adaptation & Resilience)

### 1.1 Türkiye'nin İklim Değişikliği Riskleri

```mermaid
graph TB
    A[Türkiye'nin İklim Riskleri<br/>İklim Değişikliği Kaynaklı] --> B[Su Riskleri]
    A --> C[Sıcaklık ve Yangın Riskleri]
    A --> D[Rüzgar Riskleri]
    A --> E[Dolaylı Risk: Deprem]
    
    B --> B1[2021 Kastamonu-Sinop Seli<br/>82 can kaybı<br/>1.500+ bina ağır hasar<br/>10.000+ kişi etkilendi]
    B --> B2[2023 Hatay Sel<br/>Altyapı çöküşü<br/>Binlerce kişi tahliye]
    B --> B3[Karadeniz Bölgesi<br/>Yıllık taşkın riski<br/>%30 artış projeksiyonu]
    B --> B4[Deniz Seviyesi Yükselişi<br/>İstanbul, İzmir kıyıları<br/>2050'de +30cm]
    
    C --> C1[2021 Antalya-Muğla Yangınları<br/>9 can kaybı<br/>270.000 hektar orman<br/>5.000+ kişi tahliye]
    C --> C2[Kentsel Isı Adası<br/>İstanbul +5°C<br/>Ankara +4.5°C<br/>İzmir +5.2°C]
    C --> C3[Kuraklık ve Su Kıtlığı<br/>Yangın riski %40 artış<br/>2050 projeksiyonu]
    
    D --> D1[Ege-Akdeniz Fırtınaları<br/>Artan sıklık ve şiddet<br/>%25 artış son 10 yılda]
    D --> D2[Marmara Hortumları<br/>Yapısal hasarlar<br/>Yıllık 5-10 olay]
    
    E --> E1[Deprem Riski<br/>Türkiye'nin %92'si<br/>deprem bölgesinde<br/>İklim değişikliği ile<br/>doğrudan ilişkili değil<br/>ancak afet dayanıklılığı<br/>için kritik]
    
    B1 --> F[YeşilPort BRI Sistemi<br/>Sistematik Risk Değerlendirmesi]
    B2 --> F
    B3 --> F
    B4 --> F
    C1 --> F
    C2 --> F
    C3 --> F
    D1 --> F
    D2 --> F
    E1 --> F
    
    F --> G[4 Risk Kategorisi<br/>WATER - FIRE - WIND - GEOSEISMIC]
    G --> H[Bina Dayanıklılık Skoru<br/>Risk Yüzdesi<br/>İyileştirme Yol Haritası]
    
    style A fill:#ffebee
    style B fill:#e3f2fd
    style C fill:#fff3e0
    style D fill:#e1f5e1
    style E fill:#f3e5f5
    style F fill:#e8eaf6
    style G fill:#c8e6c9
    style H fill:#4caf50
```

### 1.2 Building Resilience Index (BRI) Metodolojisi

YeşilPort, IFC World Bank Group'un BRI metodolojisini Türkiye'nin iklim gerçeklerine uyarlar. Sistem, dört ana risk kategorisinde değerlendirme yapar ve "Weakest Link Principle" (En Zayıf Halka Prensibi) ile binanın genel dayanıklılığını belirler.

```mermaid
graph LR
    A[BRI Değerlendirme<br/>Sistemi] --> B[WATER<br/>Su Riskleri<br/>İKLİM DEĞİŞİKLİĞİ<br/>DOĞRUDAN ETKİ]
    A --> C[FIRE<br/>Yangın Riskleri<br/>İKLİM DEĞİŞİKLİĞİ<br/>DOĞRUDAN ETKİ]
    A --> D[WIND<br/>Rüzgar Riskleri<br/>İKLİM DEĞİŞİKLİĞİ<br/>DOĞRUDAN ETKİ]
    A --> E[GEOSEISMIC<br/>Jeolojik Riskler<br/>DOLAYLI İLİŞKİ]
    
    B --> B1[Artan yağış şiddeti<br/>Sel ve taşkın sıklığı<br/>Deniz seviyesi yükselişi<br/>Kıyı erozyonu]
    
    C --> C1[Artan sıcaklık<br/>Uzun kuraklık dönemleri<br/>Orman yangını riski<br/>Kentsel ısı adası]
    
    D --> D1[Aşırı hava olayları<br/>Fırtına şiddeti artışı<br/>Hortum sıklığı<br/>Rüzgar hasarları]
    
    E --> E1[Deprem doğrudan<br/>iklim değişikliği<br/>sonucu değil<br/>ancak afet<br/>dayanıklılığı için<br/>kritik öneme sahip]
    
    B1 --> F[Weakest Link Principle<br/>En düşük rating<br/>genel dayanıklılığı belirler]
    C1 --> F
    D1 --> F
    E1 --> F
    
    F --> G[BRI Rating<br/>AA+ / AA / A+ / A / B+ / B / NR]
    G --> H[Risk Yüzdesi<br/>%7 - %60+]
    H --> I[İyileştirme<br/>Yol Haritası]
    
    style A fill:#e8f5e8
    style B fill:#e3f2fd
    style C fill:#ffebee
    style D fill:#e1f5e1
    style E fill:#f3e5f5
    style F fill:#fff3e0
    style G fill:#e8eaf6
    style H fill:#ffcdd2
    style I fill:#c8e6c9
```

**BRI Rating Sistemi ve Risk Seviyeleri:**

| Rating | Risk Yüzdesi | Operasyonel Süreklilik | Anlamı |
|--------|--------------|------------------------|--------|
| **AA+** | %7 | Var | Çok düşük risk, tam hazırlık |
| **AA** | %10 | Yok | Çok düşük risk |
| **A+** | %15 | Var | Düşük risk, iyi hazırlık |
| **A** | %20 | Yok | Düşük risk |
| **B+** | %35 | Var | Orta risk, temel hazırlık |
| **B** | %40 | Yok | Orta risk |
| **NR** | %60+ | Yok | Yüksek risk, acil iyileştirme gerekli |



### 1.3 WATER (Su) Dayanıklılığı - İklim Değişikliğinin Doğrudan Etkisi

**Türkiye'deki Durum ve Projeksiyonlar:**
- 2021 Kastamonu-Sinop seli: 82 can kaybı, 1.500+ bina ağır hasar, 10.000+ kişi etkilendi
- 2023 Hatay sel felaketi: Altyapı çöküşü, binlerce kişi tahliye edildi
- İklim projeksiyonları (2050): Karadeniz ve Akdeniz bölgelerinde %20-30 yağış artışı
- Deniz seviyesi yükselişi: İstanbul ve İzmir kıyılarında 2050'de +30cm bekleniyor

**YeşilPort'un Değerlendirme Sistemi:**

```mermaid
flowchart TD
    A[WATER Rating<br/>Değerlendirmesi] --> B[Su Geçimsizlik<br/>Sistemi]
    A --> C[Drenaj<br/>Kapasitesi]
    A --> D[Taban<br/>Riski]
    A --> E[Coğrafi<br/>Konum]
    
    B --> B1{Su Geçimsizlik<br/>Seviyesi?}
    B1 -->|Tam Koruma| B2[+3 Puan<br/>Bodrum katlar korumalı<br/>Su yalıtımı mevcut<br/>Pompa sistemi]
    B1 -->|Gelişmiş| B3[+2 Puan<br/>Temel su yalıtımı<br/>Kısmi koruma]
    B1 -->|Temel| B4[+1 Puan<br/>Minimal koruma<br/>Standart izolasyon]
    B1 -->|Yok| B5[0 Puan<br/>Risk altında<br/>Korumasız]
    
    C --> C1{Drenaj Sistemi?}
    C1 -->|Akıllı Sistem| C2[+2 Puan<br/>Sensörlü, otomatik<br/>Yağmur suyu yönetimi<br/>Taşkın önleme]
    C1 -->|Gelişmiş| C3[+1.5 Puan<br/>Yeterli kapasite<br/>Bakımlı sistem]
    C1 -->|Temel| C4[+1 Puan<br/>Standart drenaj<br/>Minimal kapasite]
    C1 -->|Yok| C5[0 Puan<br/>Tıkanma riski<br/>Yetersiz]
    
    D --> D1{Taban Riski?}
    D1 -->|Yok| D2[+2 Puan<br/>Yüksek kotta<br/>Güvenli bölge]
    D1 -->|Düşük| D3[+1 Puan<br/>Orta risk<br/>İzleme gerekli]
    D1 -->|Orta| D4[0 Puan<br/>Dikkat gerekli<br/>Önlem alınmalı]
    D1 -->|Yüksek| D5[-1 Puan<br/>Acil önlem gerekli<br/>Yüksek risk]
    
    E --> E1[Denize Uzaklık<br/>Nehire Uzaklık<br/>Denizden Yükseklik]
    E1 --> E2{Risk Faktörleri?}
    E2 -->|Deniz >10km<br/>Nehir >5km<br/>Yükseklik >100m| E3[+3 Puan<br/>Düşük risk<br/>Güvenli konum]
    E2 -->|Orta mesafe| E4[+1 Puan<br/>Orta risk<br/>İzleme gerekli]
    E2 -->|Yakın mesafe| E5[-1 Puan<br/>Yüksek risk<br/>Tsunami/taşkın riski]
    
    B2 --> F[Toplam Skor<br/>Hesaplama]
    B3 --> F
    B4 --> F
    B5 --> F
    C2 --> F
    C3 --> F
    C4 --> F
    C5 --> F
    D2 --> F
    D3 --> F
    D4 --> F
    D5 --> F
    E3 --> F
    E4 --> F
    E5 --> F
    
    F --> G{Skor<br/>Değerlendirmesi}
    G -->|≥7| H1[AA Rating<br/>Risk: %10<br/>Çok düşük risk<br/>Mükemmel hazırlık]
    G -->|≥5| H2[A Rating<br/>Risk: %20<br/>Düşük risk<br/>İyi hazırlık]
    G -->|≥3| H3[B Rating<br/>Risk: %40<br/>Orta risk<br/>Temel hazırlık]
    G -->|<3| H4[NR Rating<br/>Risk: %60+<br/>Yüksek risk<br/>ACİL İYİLEŞTİRME<br/>GEREKLİ]
    
    style A fill:#e3f2fd
    style F fill:#fff3e0
    style H1 fill:#4caf50
    style H2 fill:#8bc34a
    style H3 fill:#ff9800
    style H4 fill:#f44336
```

**Somut Örnek 1: Kastamonu Seli Senaryosu**

2021 Kastamonu selinde hasar gören bir apartman YeşilPort ile değerlendirilseydi:

**Mevcut Durum:**
- **Su Geçimsizlik:** Yok (0 puan) - Bodrum katlar korumasız, su yalıtımı yok
- **Drenaj Sistemi:** Temel (1 puan) - Yetersiz kapasite, tıkanma sorunu
- **Taban Riski:** Yüksek (-1 puan) - Dere yatağına 200m mesafede
- **Coğrafi Konum:** Nehir 500m (-1 puan) - Taşkın riski yüksek
- **Toplam Skor:** -1 puan → **NR Rating (Risk: %60+)**

**Gerçekleşen Hasar:**
- Bodrum ve zemin katlar tamamen su altında
- Elektrik ve ısıtma sistemleri kullanılamaz hale geldi
- 3 gün boyunca bina kullanılamadı
- Tamir maliyeti: 450.000 TL
- Sakinler 2 hafta tahliye edildi

**İyileştirme Önerileri ve Maliyet:**
1. Bodrum katlar için su geçimsizlik sistemi: 80.000 TL (+3 puan)
2. Gelişmiş drenaj sistemi kurulumu: 60.000 TL (+1.5 puan)
3. Tahliye pompası ve erken uyarı sistemi: 40.000 TL (+1 puan)
4. Zemin katta su baskınına dayanıklı malzemeler: 50.000 TL (+0.5 puan)
5. Elektrik panosu yükseltme: 20.000 TL (+0.5 puan)

**Toplam İyileştirme Maliyeti:** 250.000 TL  
**İyileştirme Sonrası Skor:** 5.5 puan → **A Rating (Risk: %20)**  
**Risk Azaltımı:** %67 (Risk %60+ → %20)

**Ekonomik Analiz:**
- Bir sonraki sel olayında beklenen hasar: 90.000 TL (önceki 450.000 TL)
- Sigorta primi indirimi: %12 (yıllık 3.600 TL tasarruf)
- 10 yıllık toplam tasarruf: 396.000 TL (hasar azaltımı + sigorta)
- **ROI:** %58 (10 yıl)
- **Geri ödeme süresi:** 5.2 yıl

**Sosyal Fayda:**
- Sakinler tahliye edilmek zorunda kalmaz
- Yaşlı ve engelli sakinler için güvenlik
- Psikolojik rahatlık ve yaşam kalitesi artışı



### 1.4 FIRE (Yangın) Dayanıklılığı - İklim Değişikliğinin Doğrudan Etkisi

**Türkiye'deki Durum ve Projeksiyonlar:**
- 2021 Manavgat-Marmaris yangınları: 9 can kaybı, 270.000 hektar orman, 5.000+ kişi tahliye
- Artan sıcaklık ve kuraklık: Yangın sezonunun uzaması (Haziran-Ekim)
- İklim projeksiyonları (2050): Akdeniz ve Ege'de %2-3°C sıcaklık artışı
- Yangın riski artışı: %40 (2050 projeksiyonu)
- Kentsel ısı adası etkisi: İstanbul +5°C, Ankara +4.5°C, İzmir +5.2°C

**YeşilPort'un Değerlendirme Sistemi:**

```mermaid
graph TD
    A[FIRE Rating<br/>Değerlendirmesi] --> B[Yangın Algılama<br/>Sistemi]
    A --> C[Yangın Söndürme<br/>Sistemi]
    A --> D[Yangın<br/>Dayanımı]
    A --> E[Kaçış<br/>Yolları]
    A --> F[Orman Yangını<br/>Riski]
    
    B --> B1[Akıllı Sistem: +3 puan<br/>IoT sensörler<br/>AI analiz<br/>Erken tespit]
    B --> B2[Gelişmiş: +2 puan<br/>Isı + Duman algılama<br/>Merkezi izleme]
    B --> B3[Temel: +1 puan<br/>Sadece duman<br/>Lokal alarm]
    B --> B4[Yok: 0 puan<br/>Risk altında<br/>Geç tespit]
    
    C --> C1[Gelişmiş: +3 puan<br/>Sprinkler + Gazlı + Köpük<br/>Otomatik aktivasyon]
    C --> C2[Karma: +2 puan<br/>Sprinkler + Gazlı<br/>Kısmi otomasyon]
    C --> C3[Temel: +1 puan<br/>Sadece sprinkler<br/>Manuel destek gerekli]
    C --> C4[Yok: 0 puan<br/>Manuel müdahale<br/>Yüksek risk]
    
    D --> D1[120dk: +2 puan<br/>Çok yüksek dayanım<br/>Beton/çelik yapı]
    D --> D2[90dk: +1.5 puan<br/>Yüksek dayanım<br/>Yangın kapıları]
    D --> D3[60dk: +1 puan<br/>Orta dayanım<br/>Standart yapı]
    D --> D4[30dk: +0.5 puan<br/>Düşük dayanım<br/>Ahşap yapı]
    
    E --> E1{Kaçış Yolu<br/>Yeterliliği?}
    E1 -->|Kat başına ≥2| E2[+1 puan<br/>Yeterli<br/>Güvenli tahliye]
    E1 -->|Kat başına <2| E3[0 puan<br/>Yetersiz<br/>Tahliye riski]
    
    F --> F1{Orman Uzaklığı?}
    F1 -->|>10km| F2[+1 puan<br/>Düşük risk<br/>Güvenli mesafe]
    F1 -->|5-10km| F3[0 puan<br/>Orta risk<br/>İzleme gerekli]
    F1 -->|<2km| F4[-1 puan<br/>Yüksek risk<br/>İKLİM DEĞİŞİKLİĞİ<br/>RİSK ARTIŞI<br/>Acil önlem gerekli]
    
    B1 --> G[Toplam Skor<br/>Hesaplama]
    B2 --> G
    B3 --> G
    B4 --> G
    C1 --> G
    C2 --> G
    C3 --> G
    C4 --> G
    D1 --> G
    D2 --> G
    D3 --> G
    D4 --> G
    E2 --> G
    E3 --> G
    F2 --> G
    F3 --> G
    F4 --> G
    
    G --> H{Skor<br/>Değerlendirmesi}
    H -->|≥7| I1[AA Rating<br/>Risk: %10<br/>Çok düşük risk<br/>Mükemmel hazırlık]
    H -->|≥5| I2[A Rating<br/>Risk: %20<br/>Düşük risk<br/>İyi hazırlık]
    H -->|≥3| I3[B Rating<br/>Risk: %40<br/>Orta risk<br/>Temel hazırlık]
    H -->|<3| I4[NR Rating<br/>Risk: %60+<br/>Yüksek risk<br/>ACİL İYİLEŞTİRME]
    
    style A fill:#ffebee
    style G fill:#fff3e0
    style F4 fill:#d32f2f
    style I1 fill:#4caf50
    style I2 fill:#8bc34a
    style I3 fill:#ff9800
    style I4 fill:#f44336
```

**Somut Örnek 2: Manavgat Yangını Senaryosu**

2021 Manavgat yangınında zarar gören bir otel YeşilPort ile değerlendirilseydi:

**Mevcut Durum:**
- **Yangın Algılama:** Temel (1 puan) - Sadece duman algılama, geç tespit
- **Yangın Söndürme:** Temel (1 puan) - Sadece sprinkler, yetersiz kapasit e
- **Yangın Dayanımı:** 60dk (1 puan) - Orta dayanım, ahşap detaylar
- **Kaçış Yolları:** Yetersiz (0 puan) - 5 kat, 1 merdiven, dar koridor
- **Orman Uzaklığı:** 800m (-1 puan) - **Yüksek risk, iklim değişikliği ile artan tehlike**
- **Toplam Skor:** 2 puan → **NR Rating (Risk: %60+)**

**Gerçekleşen Hasar:**
- Otel tamamen yandı, kullanılamaz hale geldi
- 120 misafir tahliye edildi, 3 kişi yaralandı
- Toplam hasar: 15 milyon TL
- İşletme 2 yıl kapalı kaldı
- Gelir kaybı: 8 milyon TL

**İyileştirme Önerileri ve Maliyet:**
1. Gelişmiş yangın algılama sistemi (IoT + AI): 250.000 TL (+2 puan)
2. Karma söndürme sistemi (sprinkler + gazlı): 400.000 TL (+2 puan)
3. İkinci kaçış merdiveni ve acil çıkış genişletme: 600.000 TL (+1 puan)
4. Yangına dayanıklı peyzaj (ateş kesici bitki örtüsü): 150.000 TL (+0.5 puan)
5. Erken uyarı sistemi (orman yangını izleme): 100.000 TL (+0.5 puan)
6. Yangın dayanımı artırma (yangın kapıları, bölmeleme): 500.000 TL (+0.5 puan)

**Toplam İyileştirme Maliyeti:** 2.000.000 TL  
**İyileştirme Sonrası Skor:** 8.5 puan → **AA Rating (Risk: %10)**  
**Risk Azaltımı:** %83 (Risk %60+ → %10)

**Ekonomik Analiz:**
- Bir sonraki yangın olayında beklenen hasar: 2.5 milyon TL (önceki 15 milyon TL)
- Sigorta primi indirimi: %15 (yıllık 180.000 TL tasarruf)
- İşletme kesintisi riski: %90 azalma
- 10 yıllık toplam tasarruf: 14.3 milyon TL (hasar azaltımı + sigorta + gelir kaybı önleme)
- **ROI:** %615 (10 yıl)
- **Geri ödeme süresi:** 1.6 yıl

**Sosyal Fayda:**
- 120 misafir ve 40 çalışanın can güvenliği
- Bölge turizmine katkı (süreklilik)
- İstihdam korunması
- Toplumsal güven artışı

**İklim Değişikliği Bağlantısı:**
- Orman yangını riski 2050'de %40 artacak
- Yangın sezonu 2 ay uzayacak (Mayıs-Kasım)
- Sıcaklık artışı ile kuraklık dönemleri uzayacak
- YeşilPort'un erken uyarı sistemi entegrasyonu ile iklim değişikliği risklerine proaktif hazırlık



### 1.5 Sosyal Boyut: Kırılgan Gruplar ve Erişilebilirlik

YeşilPort, iklim değişikliğinin etkilerine karşı en savunmasız grupları özel olarak değerlendirir. Bu yaklaşım, sosyal adalet ve kapsayıcılık prensiplerini iklim uyum stratejilerine entegre eder.

**Kırılgan Gruplar:**
- **Yaşlılar (65+ yaş):** Hareket kısıtlılığı, kronik hastalıklar, ilaç bağımlılığı
- **Engelliler:** Fiziksel engel, görme/işitme engeli, bilişsel engel
- **Çocuklar (0-6 yaş):** Bağımlı grup, tahliye desteği gerekli
- **Kronik Hastalar:** Oksijen bağımlılığı, diyaliz, sürekli ilaç kullanımı
- **Düşük Gelir Grupları:** İyileştirme yatırımı yapamama, sigorta eksikliği

```mermaid
graph TB
    A[Sosyal Dayanıklılık<br/>Değerlendirmesi] --> B[Kırılgan Gruplar<br/>Analizi]
    A --> C[Erişilebilirlik<br/>Altyapısı]
    A --> D[Tahliye<br/>Senaryoları]
    
    B --> B1[Yaşlılar<br/>65+ yaş<br/>Hareket kısıtlılığı<br/>İlaç ihtiyacı]
    B --> B2[Engelliler<br/>Fiziksel engel<br/>Görme/işitme engeli<br/>Özel destek gerekli]
    B --> B3[Çocuklar<br/>0-6 yaş<br/>Bağımlı grup<br/>Yetişkin desteği]
    B --> B4[Kronik Hastalar<br/>Oksijen bağımlılığı<br/>Diyaliz<br/>Sürekli bakım]
    
    C --> C1[Asansör Yedekliliği<br/>Jeneratör desteği<br/>Acil durum asansörü<br/>Manuel çalıştırma]
    C --> C2[Rampa ve Korkuluklar<br/>Tekerlekli sandalye erişimi<br/>Görme engelli yönlendirme<br/>Hissedilebilir yüzey]
    C --> C3[Acil Durum Aydınlatması<br/>Fotolüminesan işaretler<br/>Sesli uyarı sistemleri<br/>Çoklu duyusal uyarı]
    
    D --> D1[Tahliye Planı<br/>Kırılgan grup önceliği<br/>Toplanma noktaları<br/>Yardım ekipleri]
    D --> D2[İletişim Sistemi<br/>Görsel + İşitsel uyarı<br/>Çoklu dil desteği<br/>Basit mesajlar]
    D --> D3[Yardım Ekipleri<br/>Eğitimli personel<br/>Tıbbi destek hazırlığı<br/>Özel ekipman]
    
    B1 --> E[Risk Çarpanı<br/>Hesaplama]
    B2 --> E
    B3 --> E
    B4 --> E
    C1 --> E
    C2 --> E
    C3 --> E
    D1 --> E
    D2 --> E
    D3 --> E
    
    E --> F{Kırılgan Grup<br/>Oranı?}
    F -->|>%30| G1[Yüksek Öncelik<br/>Ek güvenlik önlemleri<br/>Aylık tatbikatlar<br/>7/24 destek ekibi]
    F -->|%15-30| G2[Orta Öncelik<br/>Standart önlemler<br/>3 aylık tatbikatlar<br/>Yardım protokolü]
    F -->|<%15| G3[Düşük Öncelik<br/>Temel önlemler<br/>Yıllık tatbikat<br/>Standart prosedür]
    
    G1 --> H[Sosyal Dayanıklılık<br/>Skoru]
    G2 --> H
    G3 --> H
    
    H --> I[BRI Rating'e<br/>Entegrasyon<br/>Operasyonel Süreklilik<br/>+ Rating Kriteri]
    
    style A fill:#e8f5e8
    style B fill:#ffebee
    style C fill:#e3f2fd
    style D fill:#fff3e0
    style E fill:#f3e5f5
    style G1 fill:#f44336
    style G2 fill:#ff9800
    style G3 fill:#4caf50
    style I fill:#c8e6c9
```

**Somut Örnek 3: Yaşlı Bakım Evi - Sosyal Dayanıklılık Değerlendirmesi**

İstanbul Kadıköy'de bir yaşlı bakım evi (80 sakin, 65-95 yaş arası):

**Mevcut Durum:**
- **Kırılgan Grup Oranı:** %100 (tüm sakinler 65+ yaş, %40'ı hareket kısıtlı)
- **Erişilebilirlik:** Asansör var, ancak jeneratör yok
- **Tahliye Planı:** Mevcut, ancak tatbikat yapılmamış
- **WATER Rating:** B (sel riski orta, Moda kıyısına 500m)
- **FIRE Rating:** A (yangın sistemleri iyi)
- **Operasyonel Süreklilik:** Yok (yedek güç, su depolama yetersiz)

**Risk Analizi:**
- Elektrik kesintisinde asansör çalışmaz → 4. katta 20 yaşlı mahsur kalır
- Tahliye süresi: Normal bina 5 dk, bu bina 25 dk (hareket kısıtlılığı)
- Kronik hastalar: 15 kişi oksijen bağımlı, 8 kişi diyaliz hastası
- **Sosyal Risk Çarpanı:** x2.5 (kırılgan grup yoğunluğu)
- **Genel BRI Rating:** B (Risk: %40) → **Sosyal Risk ile: %100 (Kritik)**

**İyileştirme Önerileri ve Maliyet:**
1. Jeneratör kurulumu (asansör + tıbbi ekipman desteği): 180.000 TL
2. Zemin kat acil barınma alanı (20 kişilik): 120.000 TL
3. Aylık tahliye tatbikatları ve personel eğitimi: 60.000 TL/yıl
4. Tıbbi ekipman yedekleme (oksijen, ilaç, 7 gün): 80.000 TL
5. Erken uyarı sistemi (sel, yangın, deprem): 70.000 TL
6. Tekerlekli sandalye erişimi iyileştirme: 50.000 TL
7. Acil durum iletişim sistemi (görsel + işitsel): 40.000 TL

**Toplam İyileştirme Maliyeti:** 600.000 TL (ilk yıl)  
**İyileştirme Sonrası:**
- **BRI Rating:** A+ (Risk: %15)
- **Sosyal Risk Çarpanı:** x1.2 (iyileştirilmiş hazırlık)
- **Genel Risk:** %18 (önceki %100)
- **Risk Azaltımı:** %82

**Ekonomik ve Sosyal Fayda:**
- Yaşlıların can güvenliği (paha biçilemez)
- Ailelerin psikolojik rahatlığı
- Kurum itibarı ve doluluk oranı artışı (%95 → %100)
- Sigorta primi indirimi: %12 (yıllık 36.000 TL)
- Devlet teşvikleri: Yaşlı bakım tesisleri için %50 hibe desteği (300.000 TL)
- **Net Maliyet:** 300.000 TL
- **Geri ödeme süresi:** 8.3 yıl (sigorta tasarrufu ile)

**İklim Değişikliği Bağlantısı:**
- Aşırı sıcaklık dalgaları: Yaşlılar en riskli grup (kalp krizi, sıcak çarpması)
- Sel ve taşkın: Hareket kısıtlılığı nedeniyle tahliye zorluğu
- Elektrik kesintileri: Tıbbi ekipman bağımlılığı (oksijen, diyaliz)
- YeşilPort'un sosyal dayanıklılık değerlendirmesi, iklim adaletini sağlar



### 1.6 Operasyonel Süreklilik - Afet Sonrası Dayanıklılık

İklim değişikliği kaynaklı aşırı hava olaylarında binaların işlevselliğini sürdürmesi kritiktir. YeşilPort, operasyonel süreklilik önlemlerini değerlendirerek "+" rating verir.

```mermaid
flowchart LR
    A[Operasyonel Süreklilik<br/>+ Rating Kriterleri<br/>Minimum 3 kriter gerekli] --> B[Yedek Güç<br/>Elektrik Sürekliliği]
    A --> C[Su Depolama<br/>Su Sürekliliği]
    A --> D[Haberleşme<br/>İletişim Sürekliliği]
    A --> E[Erişim Yolları<br/>Ulaşım Sürekliliği]
    A --> F[Acil Durum Planı<br/>Organizasyonel Hazırlık]
    
    B --> B1[Tam Sistem: +5 puan<br/>Jeneratör + UPS + Güneş<br/>7+ gün kapasitesi<br/>Otomatik geçiş]
    B --> B2[Karma: +4 puan<br/>Jeneratör + UPS<br/>3-7 gün<br/>Manuel geçiş]
    B --> B3[Jeneratör: +3 puan<br/>1-3 gün<br/>Temel yük]
    B --> B4[UPS: +2 puan<br/>4-8 saat<br/>Kritik yük]
    B --> B5[Yok: 0 puan<br/>Altyapı bağımlı]
    
    C --> C1[7+ Gün: +5 puan<br/>Afet sonrası bağımsızlık<br/>Büyük depo]
    C --> C2[3-7 Gün: +4 puan<br/>Orta süre dayanıklılık<br/>Orta depo]
    C --> C3[1-3 Gün: +3 puan<br/>Kısa süre dayanıklılık<br/>Küçük depo]
    C --> C4[<1 Gün: +1 puan<br/>Minimal yedek]
    C --> C5[Yok: 0 puan<br/>Şebeke bağımlı]
    
    D --> D1[Uydu: +5 puan<br/>Altyapı bağımsız<br/>Her koşulda çalışır]
    D --> D2[Yedekli: +3 puan<br/>Fiber + 4G/5G<br/>Çift hat]
    D --> D3[Temel: +1 puan<br/>Tek hat<br/>Kesinti riski]
    D --> D4[Yok: 0 puan<br/>İletişimsiz]
    
    E --> E1[3+ Yol: +3 puan<br/>Yüksek esneklik<br/>Alternatif rotalar]
    E --> E2[2 Yol: +2 puan<br/>Orta esneklik<br/>Yedek rota]
    E --> E3[1 Yol: 0 puan<br/>Tek nokta arızası<br/>İzolasyon riski]
    
    F --> F1[Kapsamlı Plan: +5 puan<br/>Tatbikat yapılmış<br/>Ekipler eğitimli<br/>Düzenli güncelleme]
    F --> F2[Temel Plan: +2 puan<br/>Dokümante edilmiş<br/>Tatbikat yok]
    F --> F3[Yok: 0 puan<br/>Hazırlıksız]
    
    B1 --> G[Toplam Skor<br/>Hesaplama]
    B2 --> G
    B3 --> G
    B4 --> G
    B5 --> G
    C1 --> G
    C2 --> G
    C3 --> G
    C4 --> G
    C5 --> G
    D1 --> G
    D2 --> G
    D3 --> G
    D4 --> G
    E1 --> G
    E2 --> G
    E3 --> G
    F1 --> G
    F2 --> G
    F3 --> G
    
    G --> H{Skor ≥15?}
    H -->|Evet| I[+ Rating Aktif<br/>AA → AA+<br/>A → A+<br/>B → B+<br/>Operasyonel<br/>Süreklilik Sağlandı]
    H -->|Hayır| J[Temel Rating<br/>İyileştirme gerekli<br/>Operasyonel<br/>Süreklilik Yok]
    
    style A fill:#e8f5e8
    style G fill:#fff3e0
    style I fill:#4caf50
    style J fill:#ff9800
```

**Somut Örnek 4: Hastane - Operasyonel Süreklilik Değerlendirmesi**

İzmir Karşıyaka'da bir devlet hastanesi (200 yatak, günlük 500 hasta):

**Mevcut Durum (2021 İzmir Depremi Sonrası):**
- **Yedek Güç:** Jeneratör (3 puan) - 48 saat kapasitesi, sadece kritik yük
- **Su Depolama:** 2 gün (3 puan) - Yetersiz, ameliyathane öncelikli
- **Haberleşme:** Yedekli (3 puan) - Fiber + 4G, kesinti yaşandı
- **Erişim Yolları:** 2 yol (2 puan) - Ana cadde + servis yolu
- **Acil Durum Planı:** Kapsamlı (5 puan) - Düzenli tatbikat, eğitimli ekip
- **Toplam Skor:** 16 puan → **+ Rating Aktif**

**Temel BRI Rating:** A (Risk: %20)  
**Operasyonel Süreklilik ile:** A+ (Risk: %15)  
**Risk Azaltımı:** %25

**2021 İzmir Depremi Deneyimi:**
- Elektrik kesintisi: 6 saat (jeneratör devreye girdi)
- Su kesintisi: 12 saat (depo yeterli oldu)
- Haberleşme kesintisi: 2 saat (4G'ye geçildi)
- Ameliyatlar kesintisiz devam etti
- Acil servis tam kapasite çalıştı
- **Sonuç:** Hastane işlevselliğini sürdürdü, can kaybı olmadı

**İyileştirme Önerileri ve Maliyet:**
1. Güneş paneli + batarya depolama (7 gün kapasitesi): 2.500.000 TL (+2 puan)
2. Su depolama artırımı (7 gün, 500m³): 800.000 TL (+2 puan)
3. Uydu haberleşme yedekliliği: 300.000 TL (+2 puan)
4. Üçüncü erişim yolu (helikopter pisti): 1.500.000 TL (+1 puan)
5. Acil durum planı güncelleme (iklim senaryoları): 100.000 TL

**Toplam İyileştirme Maliyeti:** 5.200.000 TL  
**İyileştirme Sonrası Skor:** 23 puan  
**İyileştirme Sonrası Rating:** AA+ (Risk: %7)  
**Risk Azaltımı:** %65 (Risk %20 → %7)

**Ekonomik ve Sosyal Fayda:**
- Afet sonrası 7 gün bağımsız çalışma kapasitesi
- Yıllık 182.500 hasta hizmeti kesintisiz
- Ameliyat ve acil servis sürekliliği
- Bölge sağlık güvenliği
- Sigorta primi indirimi: %15 (yıllık 450.000 TL)
- Devlet teşvikleri: Kritik altyapı için %60 hibe (3.120.000 TL)
- **Net Maliyet:** 2.080.000 TL
- **Geri ödeme süresi:** 4.6 yıl

**İklim Değişikliği Bağlantısı:**
- Aşırı hava olayları sıklığı artıyor (sel, fırtına, sıcak dalgası)
- Altyapı kesintileri daha sık ve uzun sürüyor
- Hastanelerin operasyonel sürekliliği can kurtarıcı
- YeşilPort'un değerlendirmesi, kritik altyapıların iklim dayanıklılığını sağlar

---

## 2. İkincil Katkı: Azaltım (Mitigation)

YeşilPort'un ikincil odağı, binaların karbon emisyonlarını azaltmak ve enerji verimliliğini artırmaktır. Bu yaklaşım, dayanıklılık iyileştirmeleriyle sinerjik olarak çalışır.

### 2.1 Karbon Ayak İzi Hesaplama - Nicel Etki Analizi

**Hesaplama Metodolojisi:**

```mermaid
graph LR
    A[Karbon Ayak İzi<br/>Hesaplama] --> B[Yapı Malzemesi<br/>Emisyonu]
    A --> C[Enerji Sistemi<br/>Emisyonu]
    A --> D[Yalıtım<br/>Etkisi]
    A --> E[Yenilenebilir<br/>Enerji Bonusu]
    
    B --> B1[Beton: 45 kg CO₂/m²/yıl<br/>Standart yapı]
    B --> B2[Çelik: 55 kg CO₂/m²/yıl<br/>Yüksek emisyon]
    B --> B3[Ahşap: 15 kg CO₂/m²/yıl<br/>%73 daha düşük<br/>Karbon tutma]
    B --> B4[Tuğla: 35 kg CO₂/m²/yıl<br/>Orta emisyon]
    
    C --> C1[Doğalgaz: +20 kg CO₂/m²/yıl<br/>Fosil yakıt]
    C --> C2[Elektrik: +35 kg CO₂/m²/yıl<br/>Şebeke bağımlı]
    C --> C3[Isı Pompası: +15 kg CO₂/m²/yıl<br/>%57 azaltım<br/>Verimli sistem]
    C --> C4[Güneş: +5 kg CO₂/m²/yıl<br/>%86 azaltım<br/>Yenilenebilir]
    
    D --> D1[Yalıtım Yok: +25 kg CO₂/m²/yıl<br/>Yüksek kayıp]
    D --> D2[Temel Yalıtım: +5 kg CO₂/m²/yıl<br/>Orta verimlilik]
    D --> D3[Maksimum Yalıtım: +3 kg CO₂/m²/yıl<br/>%88 azaltım<br/>Yüksek verimlilik]
    
    E --> E1[Güneş Paneli: -15 kg CO₂/m²/yıl<br/>Temiz enerji üretimi]
    E --> E2[Rüzgar Türbini: -12 kg CO₂/m²/yıl<br/>Yenilenebilir kaynak]
    E --> E3[Jeotermal: -10 kg CO₂/m²/yıl<br/>Sürekli enerji]
    
    B1 --> F[Toplam Karbon<br/>Ayak İzi<br/>kg CO₂/m²/yıl]
    B2 --> F
    B3 --> F
    B4 --> F
    C1 --> F
    C2 --> F
    C3 --> F
    C4 --> F
    D1 --> F
    D2 --> F
    D3 --> F
    E1 --> F
    E2 --> F
    E3 --> F
    
    F --> G[Yıllık Toplam Emisyon<br/>Bina Alanı x Karbon Ayak İzi]
    G --> H[Azaltım Potansiyeli<br/>İyileştirme Senaryoları<br/>Ekonomik Analiz]
    
    style A fill:#e8f5e8
    style F fill:#fff3e0
    style G fill:#ffebee
    style H fill:#c8e6c9
```



**Nicel Azaltım Potansiyeli - Bina Tiplerine Göre:**

| Bina Tipi | Mevcut Durum (kg CO₂/m²/yıl) | İyileştirme Sonrası | Azaltım | Yıllık Tasarruf (100m² için) | Ekonomik Değer (20 yıl) |
|-----------|------------------------------|---------------------|---------|------------------------------|-------------------------|
| **Eski Apartman (1980 öncesi)** | 85 | 35 | **%59** | 5 ton CO₂/yıl | 100 ton CO₂ |
| **Orta Yaş Apartman (1980-2010)** | 65 | 30 | **%54** | 3.5 ton CO₂/yıl | 70 ton CO₂ |
| **Yeni Bina (2010+)** | 45 | 20 | **%56** | 2.5 ton CO₂/yıl | 50 ton CO₂ |
| **Ofis Binası** | 75 | 25 | **%67** | 50 ton CO₂/yıl (1000m²) | 1.000 ton CO₂ |
| **Alışveriş Merkezi** | 95 | 40 | **%58** | 550 ton CO₂/yıl (10.000m²) | 11.000 ton CO₂ |

**Somut Örnek 5: Eski Apartman İyileştirmesi - Ekonomik Motivasyon**

İstanbul Kadıköy'de 1975 yapımı 8 katlı apartman (800m², 16 daire):

**Mevcut Durum:**
- **Yapı:** Beton (45 kg CO₂/m²)
- **Yalıtım:** Yok (+25 kg CO₂/m²)
- **Isıtma:** Doğalgaz kombi (+20 kg CO₂/m²)
- **Pencere:** Tek cam (ek %20 tüketim)
- **Aydınlatma:** Fluoresan (orta verimlilik)
- **Toplam:** 85 kg CO₂/m²/yıl = **68 ton CO₂/yıl**
- **Yıllık Enerji Maliyeti:** 180.000 TL (doğalgaz + elektrik)

**İyileştirme Paketi ve Maliyet:**

1. **Dış Cephe Yalıtımı (Taş Yünü, 10cm):** 120.000 TL
   - Azaltım: -22 kg CO₂/m²
   - Doğalgaz tasarrufu: %60

2. **Çift Cam Pencere (Low-E):** 80.000 TL
   - Azaltım: -8 kg CO₂/m²
   - Isı kaybı azaltımı: %30

3. **Kombi Yenileme (Yoğuşmalı):** 40.000 TL
   - Azaltım: -5 kg CO₂/m²
   - Verimlilik artışı: %25

4. **Çatı Güneş Paneli (20 kW):** 200.000 TL
   - Azaltım: -15 kg CO₂/m²
   - Elektrik üretimi: 30.000 kWh/yıl

5. **LED Aydınlatma (Ortak Alanlar):** 20.000 TL
   - Azaltım: -3 kg CO₂/m²
   - Elektrik tasarrufu: %40

**Toplam Yatırım:** 460.000 TL

**İyileştirme Sonrası:**
- **Toplam:** 32 kg CO₂/m²/yıl = **25.6 ton CO₂/yıl**
- **Azaltım:** %62 (42.4 ton CO₂/yıl)
- **20 Yıllık Etki:** 848 ton CO₂ azaltımı (178 araç/yıl eşdeğeri)
- **Yıllık Enerji Maliyeti:** 70.000 TL (110.000 TL tasarruf)

**Ekonomik Analiz:**

```mermaid
graph TD
    A[İyileştirme Yatırımı<br/>460.000 TL] --> B[Yıllık Tasarruflar]
    
    B --> C[Doğalgaz Tasarrufu<br/>%60 azalma<br/>45.000 TL/yıl]
    B --> D[Elektrik Tasarrufu<br/>%40 azalma<br/>25.000 TL/yıl]
    B --> E[Güneş Enerjisi Üretimi<br/>30.000 kWh/yıl<br/>40.000 TL/yıl]
    
    C --> F[Toplam Yıllık Tasarruf<br/>110.000 TL/yıl]
    D --> F
    E --> F
    
    F --> G[Geri Ödeme Süresi<br/>4.2 yıl]
    
    G --> H[Ek Ekonomik Faydalar]
    
    H --> I[Emlak Değeri Artışı<br/>%15-20<br/>+600.000 TL]
    H --> J[Sigorta Primi İndirimi<br/>%10-15<br/>BRI Rating ile<br/>2.250 TL/yıl]
    H --> K[Yeşil Bina Sertifikası<br/>Prestij ve pazarlama<br/>Kiralama avantajı]
    H --> L[Devlet Teşvikleri<br/>KDV indirimi %8<br/>Hibe desteği<br/>-36.800 TL]
    
    I --> M[20 Yıllık Toplam Fayda<br/>Tasarruf: 2.200.000 TL<br/>Sigorta: 45.000 TL<br/>Emlak değeri: 600.000 TL<br/>Teşvik: 36.800 TL<br/>TOPLAM: 2.881.800 TL]
    J --> M
    K --> M
    L --> M
    
    M --> N[ROI: %527<br/>Net Kazanç: 2.421.800 TL]
    
    style A fill:#ffebee
    style F fill:#fff3e0
    style G fill:#e8f5e8
    style M fill:#c8e6c9
    style N fill:#4caf50
```

**Sigorta ve Kredi Avantajları:**

1. **Sigorta Primi İndirimi (BRI Rating ile):**
   - AA+ Rating: %15 indirim
   - AA/A+ Rating: %12 indirim
   - A/B+ Rating: %8 indirim
   - **Örnek:** 800m² apartman, yıllık 15.000 TL prim → 2.250 TL tasarruf (AA+ ile)

2. **Yeşil Kredi Avantajları:**
   - %0.5-1 puan faiz indirimi
   - Daha yüksek kredi limiti (%20 artış)
   - Uzun vade seçenekleri (10 yıla kadar)
   - **Örnek:** 500.000 TL kredi, 5 yıl, %1 faiz indirimi → 25.000 TL faiz tasarrufu

3. **Emlak Değeri Artışı:**
   - Enerji sınıfı A+: %20 değer artışı
   - BRI Rating AA+: %15 değer artışı
   - **Örnek:** 3.000.000 TL değerli apartman → 1.050.000 TL değer artışı

**Toplam Ekonomik Fayda (20 yıl):**
- Enerji tasarrufu: 2.200.000 TL
- Sigorta indirimi: 45.000 TL
- Kredi faiz tasarrufu: 25.000 TL
- Emlak değeri artışı: 1.050.000 TL
- Devlet teşvikleri: 36.800 TL
- **Toplam:** 3.356.800 TL
- **Yatırım:** 460.000 TL
- **Net Kazanç:** 2.896.800 TL
- **ROI:** %630

**Çevresel Etki:**
- 20 yıllık karbon azaltımı: 848 ton CO₂
- Eşdeğer: 178 araç/yıl emisyonu
- Eşdeğer: 38.000 ağaç dikimi
- Türkiye'nin 2053 net sıfır hedefine katkı

---

## 3. Hizmet Tasarımı Perspektifi

### 3.1 Kullanıcı Deneyimi ve İhtiyaç Analizi

**Hedef Kitle ve İhtiyaçları:**

```mermaid
graph TB
    A[YeşilPort<br/>Hedef Kitlesi] --> B[Bina Sahipleri<br/>ve Yöneticileri]
    A --> C[Yerel Yönetimler<br/>ve Kamu Kurumları]
    A --> D[Sigorta Şirketleri<br/>ve Finansal Kurumlar]
    A --> E[Yatırımcılar<br/>ve Geliştiriciler]
    A --> F[Topluluklar<br/>ve STK'lar]
    
    B --> B1[İhtiyaç:<br/>Bina performansını anlamak<br/>İyileştirme yol haritası<br/>Ekonomik gerekçe]
    B --> B2[Sorun:<br/>Dağınık veriler<br/>Subjektif değerlendirmeler<br/>Yatırım kararı zorluğu]
    
    C --> C1[İhtiyaç:<br/>Toplu veri analizi<br/>Risk haritalama<br/>İyileştirme programları]
    C --> C2[Sorun:<br/>Veri eksikliği<br/>Standart yokluğu<br/>Önceliklendirme zorluğu]
    
    D --> D1[İhtiyaç:<br/>Risk değerlendirmesi<br/>Prim hesaplama<br/>Güvenilir veri]
    D --> D2[Sorun:<br/>Subjektif değerlendirme<br/>Veri güvenilirliği<br/>Güncel bilgi eksikliği]
    
    E --> E1[İhtiyaç:<br/>Sürdürülebilirlik kriterleri<br/>Yatırım değerlendirmesi<br/>ESG raporlama]
    E --> E2[Sorun:<br/>Standart eksikliği<br/>Karşılaştırma zorluğu<br/>Greenwashing riski]
    
    F --> F1[İhtiyaç:<br/>Mahalle dayanıklılığı<br/>Toplumsal farkındalık<br/>Kolektif aksiyon]
    F --> F2[Sorun:<br/>Bilgi asimetrisi<br/>Koordinasyon eksikliği<br/>Kaynak yetersizliği]
    
    B1 --> G[YeşilPort Çözümü]
    C1 --> G
    D1 --> G
    E1 --> G
    F1 --> G
    
    G --> H[Standartlaştırılmış<br/>Değerlendirme]
    G --> I[Blockchain Tabanlı<br/>Güvenilir Veri]
    G --> J[Kullanıcı Dostu<br/>Görselleştirme]
    G --> K[İyileştirme Önerileri<br/>ve Yol Haritası]
    
    style A fill:#e8f5e8
    style G fill:#c8e6c9
    style H fill:#e3f2fd
    style I fill:#fff3e0
    style J fill:#ffebee
    style K fill:#f3e5f5
```

### 3.2 Davranış Değişikliği Mekanizmaları

**1. Bilinçlendirme ve Farkındalık:**
- Görsel skorlar ve rating'ler (BRI, Enerji Sınıfı, Karbon Ayak İzi)
- Karşılaştırmalı analiz imkanı (mahalle, şehir, ülke ortalaması)
- Risk yüzdesi ve kategorik değerlendirmeler
- İnteraktif diyagramlar ve grafikler

**2. Teşvik ve Ödüllendirme:**
- Yüksek BRI rating'leri için dijital rozetler
- İyileştirme önerileri ve sonraki seviye gereksinimleri
- Blockchain'de kalıcı ve doğrulanabilir kayıt
- Sosyal medya paylaşım özellikleri

**3. Ekonomik Motivasyon:**
- Detaylı maliyet-fayda analizi
- Geri ödeme süresi hesaplama
- Sigorta ve kredi avantajları gösterimi
- Emlak değeri artışı projeksiyonu

**4. Sosyal Baskı ve Rekabet:**
- Binalar arası karşılaştırma
- Mahalle dayanıklılık skoru
- Liderlik tablosu (anonim veya açık)
- Toplumsal tanınma ve prestij

**5. Erişilebilirlik ve Kapsayıcılık:**
- Basit ve anlaşılır arayüz
- Mobil uyumlu tasarım
- Çoklu dil desteği (Türkçe, İngilizce, Arapça)
- Ücretsiz temel değerlendirme

### 3.3 Sistemik Dönüşüm Potansiyeli

```mermaid
graph LR
    A[YeşilPort<br/>Platformu] --> B[Veri Toplama<br/>ve Analiz]
    A --> C[Standartlaştırma]
    A --> D[Blockchain<br/>Güvencesi]
    
    B --> B1[Şehir/Bölge Bazlı<br/>Performans Haritaları]
    B --> B2[Trend Analizi<br/>İyileştirme Takibi]
    B --> B3[Politika Geliştirme<br/>Veri Kaynağı]
    
    C --> C1[Ulusal/Uluslararası<br/>Standartlara Uyum<br/>BRI, EU Direktifleri]
    C --> C2[Karşılaştırılabilir<br/>Veri Setleri]
    C --> C3[Sertifikasyon<br/>Sistemleri Altyapısı]
    
    D --> D1[Değiştirilemez<br/>Kayıtlar]
    D --> D2[Güven ve<br/>Şeffaflık]
    D --> D3[Sigorta ve Finansman<br/>Veri Kaynağı]
    
    B1 --> E[Sistemik Etki]
    B2 --> E
    B3 --> E
    C1 --> E
    C2 --> E
    C3 --> E
    D1 --> E
    D2 --> E
    D3 --> E
    
    E --> F[Yerel Yönetim<br/>Politikaları]
    E --> G[Sigorta ve<br/>Finansman Modelleri]
    E --> H[Toplumsal<br/>Farkındalık]
    E --> I[İklim Uyum<br/>Stratejileri]
    
    style A fill:#e8f5e8
    style E fill:#c8e6c9
    style F fill:#e3f2fd
    style G fill:#fff3e0
    style H fill:#ffebee
    style I fill:#f3e5f5
```

---

## 4. Sonuç ve Etki Değerlendirmesi

### 4.1 İklim Değişikliği ile Mücadele Katkısı

**Ana Eksen: Uyum & Dayanıklılık (%70 Odak)**
- BRI metodolojisi ile sistematik risk değerlendirmesi
- İklim değişikliği kaynaklı aşırı hava olaylarına hazırlık (sel, yangın, fırtına)
- Türkiye'ye özgü iklim riskleri ile somut bağlantı (Kastamonu seli, Manavgat yangını)
- Sosyal dayanıklılık: Kırılgan gruplar, erişilebilirlik, tahliye senaryoları
- Operasyonel süreklilik: Afet sonrası işlevsellik
- Toplumsal düzeyde dayanıklılık planlaması için veri kaynağı

**İkincil Katkı: Azaltım (%30 Odak)**
- Karbon ayak izi hesaplama ve izleme ile emisyon farkındalığı
- Nicel azaltım potansiyeli: %54-67 (bina tiplerine göre)
- Enerji verimliliği sınıflandırması ile tüketim azaltımı
- Ekonomik motivasyon: Geri ödeme süresi 4-8 yıl, ROI %527-630
- Sürdürülebilir malzeme seçimlerinin teşviki
- Yenilenebilir enerji yatırımları için veri tabanlı gerekçe

### 4.2 Hizmet Tasarımı Kriterlerine Uyum

**Bireyleri ve Toplulukları Güçlendirme:**
- Bilinçli karar verme için standartlaştırılmış veri
- Erişilebilir ve kullanıcı dostu arayüz
- Toplumsal katılımı artırma (mahalle dayanıklılığı)
- Kırılgan grupları özel olarak değerlendirme

**Davranış Değişikliği:**
- Görsel skorlar ve rating'ler ile farkındalık
- Ekonomik motivasyon (tasarruf, sigorta, emlak değeri)
- İyileştirme önerileri ile harekete geçirme
- Sosyal baskı ve rekabet (binalar arası karşılaştırma)

**Sistemik Dönüşüm:**
- Standartlaştırılmış değerlendirme metodolojisi (BRI, EU)
- Blockchain ile güvenilir veri saklama
- Toplu veri analizi ve politika geliştirme için altyapı
- Sigorta ve finansman modelleri için veri kaynağı

**Uzun Vadeli Etki:**
- Sürdürülebilir yaşam alışkanlıklarının yaygınlaştırılması
- İklim dostu dönüşümün bir parçası olma
- Toplumsal düzeyde uzun vadeli etki yaratma
- Türkiye'nin 2053 net sıfır hedefine katkı

### 4.3 Uygulanabilirlik ve Gerçekçilik

**Teknik Uygulanabilirlik:**
- Mevcut teknolojilerle geliştirilebilir (Next.js, Sui Blockchain)
- Ölçeklenebilir mimari (bulut tabanlı)
- Blockchain entegrasyonu ile güvenilirlik ve şeffaflık

**Ekonomik Uygulanabilirlik:**
- Düşük işletme maliyetleri (blockchain, cloud hosting)
- Ölçek ekonomisi (çok sayıda bina için maliyet düşüşü)
- Finansman modelleri: Yerel yönetim, sigorta, yatırımcı desteği, devlet teşvikleri

**Sosyal Uygulanabilirlik:**
- Kullanıcı dostu arayüz (teknik bilgi gerektirmez)
- Erişilebilir tasarım (mobil uyumlu, çoklu dil)
- Toplumsal katılımı teşvik eden özellikler
- Kırılgan grupları özel olarak değerlendirme

---

## 5. Referanslar ve Metodoloji

**Kullanılan Metodolojiler:**
1. Building Resilience Index (BRI) - IFC World Bank Group
2. EU Energy Performance of Buildings Directive
3. Türkiye Deprem Bölgeleri Haritası
4. İklim Değişikliği Projeksiyonları (IPCC, MGM)

**Blockchain Teknolojisi:**
- Sui Network: Yüksek throughput, düşük maliyet, hızlı finality
- Smart Contract: Move programlama dili
- Değiştirilemez Kayıt: Pasaport verilerinin güvenilir saklanması

**Veri Kaynakları:**
- 2021 Kastamonu-Sinop Seli: AFAD raporları
- 2021 Manavgat-Marmaris Yangınları: Orman Genel Müdürlüğü
- İklim Projeksiyonları: Meteoroloji Genel Müdürlüğü, IPCC AR6

---

**Dokümantasyon Tarihi:** 2025  
**Proje:** YeşilPort - Dijital Bina Pasaportu  
**Yarışma:** Sürdürülebilir Geleceği Tasarla 2025  
**Kategori:** Hizmet Tasarımı  
**Ana Eksen:** Uyum & Dayanıklılık (Adaptation & Resilience)  
**İkincil Katkı:** Azaltım (Mitigation)
