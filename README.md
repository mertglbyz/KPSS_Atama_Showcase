<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F3D3E,100:1F6F6B&height=170&section=header&text=KPSS%20Atama%20%F0%9F%8F%9B%EF%B8%8F&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Kamu%20ilanlar%C4%B1%2C%20senin%20profiline%20g%C3%B6re&descAlignY=58&descSize=18" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1300&color=1F6F6B&center=true&vCenter=true&width=620&lines=%F0%9F%93%A2+5+resmi+kaynaktan+ilan+toplar;%F0%9F%A4%96+Gemini+ile+kadro+%C5%9Fartlar%C4%B1n%C4%B1+ay%C4%B1r%C4%B1r;%F0%9F%8E%AF+Profiline+uyan+kadrolar%C4%B1+e%C5%9Fle%C5%9Ftirir;%F0%9F%94%94+Yeni+ilan+%C3%A7%C4%B1k%C4%B1nca+bildirim+g%C3%B6nderir" alt="Typing SVG" />

<br/>

![React Native](https://img.shields.io/badge/React_Native_0.88-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo_SDK_58-000020?style=for-the-badge&logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![RevenueCat](https://img.shields.io/badge/RevenueCat-F25A5A?style=for-the-badge)
![Firebase](https://img.shields.io/badge/Firebase_FCM-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=apple&logoColor=white)
![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=googleplay&logoColor=white)

> 🔒 Kaynak kod private. Bu repo uygulamanın vitrini: ne yaptığı, nasıl kurulduğu ve hangi teknik problemleri çözdüğü. Mülakatlarda kod üzerinden anlatmaktan memnuniyet duyarım.

</div>

---

## 🎬 Uygulama Turu

<div align="center">

<img src="assets/gifs/uygulama-turu.gif" width="280" alt="KPSS Atama uygulama turu" />

</div>

---

## 💡 Problem → Çözüm

😵‍💫 **Problem:** Kamu personel ilanları Kariyer Kapısı, ilan.gov.tr, Resmî Gazete ve onlarca belediye sitesine dağılmış durumda. Her ilanın içinde farklı şartlara sahip onlarca kadro var. Aday hepsini tek tek açıp *"bölümüm, puan türüm, yaşım, ehliyetim tutuyor mu?"* diye bakmak zorunda.

✅ **Çözüm:** Profilini bir kez gir. KPSS Atama her gün ilanları toplar, yapay zekâyla kadro satırlarına ayırır ve sadece **şartlarını karşıladığın** kadroları önüne getirir.

---

## 📱 Ekranlar

<div align="center">

| 🏠 Ana sayfa | 🎯 Bana uygun | 📄 Kadro detayı | 🔔 Bildirimler |
|:-:|:-:|:-:|:-:|
| <img src="assets/screenshots/1-ana-sayfa.jpg" width="190" /> | <img src="assets/screenshots/2-bana-uygun.jpg" width="190" /> | <img src="assets/screenshots/3-ilan-detayi.jpg" width="190" /> | <img src="assets/screenshots/4-bildirimler.jpg" width="190" /> |
| Canlı eşleşme durumu, son 48 saat, bölüm içi sıralama | Uygun kadrolar, kaydet / gizle | Şart karşılaştırması ve resmi ilan | Aktif ve geçmiş eşleşmeler |

| 📋 Tüm ilanlar | 👤 Profil | 🎓 Eğitim |
|:-:|:-:|:-:|
| <img src="assets/screenshots/5-tum-ilanlar.jpg" width="190" /> | <img src="assets/screenshots/6-profil.jpg" width="190" /> | <img src="assets/screenshots/7-egitim.jpg" width="190" /> |
| Başvuru tarihi ve yöntemi | Eşleştirme kriterleri | Ortaöğretim / önlisans / lisans + bölüm |

</div>

---

## ✨ Özellikler

| | Özellik | Ayrıntı |
|:-:|---|---|
| 📢 | **5 kaynaktan ilan toplama** | Kariyer Kapısı, ilan.gov.tr, Kamu İlan Portalı, Resmî Gazete, Yerel Yönetimler — HTML, PDF ve DOCX |
| 🤖 | **Yapay zekâ ile ayrıştırma** | Gemini, ilanı yapılandırılmış JSON şemasıyla kadro satırlarına böler: unvan, bölümler, KPSS türü ve tabanı, yaş, boy, ehliyet, sertifika, SGK günü |
| 🎯 | **Kadro bazında eşleştirme** | 10+ şart aynı anda: eğitim, bölüm/grup, KPSS–EKPSS, YDS, ALES, yaş/boy/kilo, ehliyet hiyerarşisi, sertifika kapsamı, SGK günü |
| 📊 | **Bölüm içi sıralama** | "X aday arasından Y. sıradasın" kartı ve puan dağılım grafiği — kimlik göstermeden |
| ⏰ | **Son 48 saat uyarısı** | Uygun ilanın başvurusu bitmeden hatırlatma |
| 🔔 | **Özet push bildirimi** | Yeni ilan, son 48 saat, düzeltme/iptal — kişi başına tek özet |
| 👤 | **Hesapsız giriş** | E-posta/şifre yok, cihaz başına anonim Supabase oturumu |
| 💎 | **Pro abonelik** | Aylık, 3 aylık, yıllık (3 gün deneme) — RevenueCat |
| 🗑️ | **KVKK uyumlu silme** | Tek dokunuşla profil, eşleşme ve bildirim kayıtlarını silen Edge Function |

---

## 🏗️ Sistem Mimarisi

```mermaid
flowchart LR
    subgraph SRC["🏛️ Resmi kaynaklar"]
        K[Kariyer Kapısı]
        I[ilan.gov.tr API]
        P[Kamu İlan Portalı]
        R[Resmî Gazete]
        Y[Yerel Yönetimler]
    end

    subgraph VPS["🖥️ Türkiye VPS · systemd timer"]
        S[scraper-worker<br/>Node 22 · cheerio · unpdf]
        G[🤖 Gemini API<br/>JSON şema]
        S <--> G
    end

    subgraph SB["🗄️ Supabase"]
        DB[(PostgreSQL + RLS<br/>SQL eşleştirme fonksiyonları)]
        EF[⚡ Edge Functions<br/>Deno]
        ST[📁 Storage<br/>resmi ilan PDF'leri]
    end

    APP[📱 React Native<br/>Expo Router]
    RC[💳 RevenueCat]
    PUSH[🔔 Expo Push<br/>APNs · FCM]

    SRC -->|HTML · PDF · DOCX| S
    S -->|ilan + kadro + eşleşme| DB
    S --> ST
    S --> PUSH --> APP
    APP <-->|anonim oturum| DB
    APP -->|satın alma| RC -->|webhook| EF --> DB
```

### 🔄 Bir tarama turu

1. ⏱️ **Zamanlama** — Türkiye'deki VPS'te systemd timer, Pzt–Cmt 12:00; 18:00'de yedek tur
2. 🕸️ **Toplama** — 5 sitenin okuyucusu; metni değişmemiş ilanlar `body_hash` ile atlanır
3. 🧹 **Filtreleme** — personel alımı olmayan ve akademik ilanlar elenir
4. 🤖 **Ayrıştırma** — Gemini, PDF/DOCX dahil ilanı kadrolara böler; KPSS türleri ÖSYM kodlarına (`P3`, `P93`, `P39,P40`) normalize edilir
5. 🧬 **Tekilleştirme** — aynı ilan farklı sitelerde varsa kurum adı normalizasyonuyla bir kez kaydedilir
6. 🎯 **Eşleştirme** — her kadro için SQL fonksiyonu uygun profilleri `user_matches` tablosuna yazar
7. 🔔 **Bildirim** — Pro kullanıcılara tek özet push; APNs/FCM teslim raporları okunur
8. 📝 **Kayıt** — tur sonucu, Gemini token kullanımı ve hatalar `scraper_runs` tablosuna yazılır
9. 🩺 **Sağlık kontrolü** — GitHub Actions her akşam turu denetler, sorun varsa e-posta ile uyarır

---

## 🧰 Teknoloji

<div align="center">

| Katman | Teknoloji |
|---|---|
| 📱 Mobil | React Native 0.88 · Expo SDK 58 · Expo Router · TypeScript |
| 🎨 Arayüz | NativeWind (Tailwind) · Reanimated · Lucide |
| 🧠 Durum | Zustand (kalıcı profil) · TanStack Query (önbellek) |
| 🗄️ Veritabanı | Supabase PostgreSQL · Row Level Security · 29 migration · SQL fonksiyonları |
| ⚡ Sunucu | Supabase Edge Functions (Deno): `revenuecat-webhook`, `sync-premium`, `delete-account` |
| 🕸️ Scraper | Node 22 · cheerio · unpdf · JSZip · LibreOffice (DOCX → PDF) |
| 🤖 Yapay zekâ | Google Gemini API, yapılandırılmış çıktı (response schema) |
| 🔔 Bildirim | Expo Push · APNs · Firebase Cloud Messaging |
| 💳 Ödeme | RevenueCat · App Store / Google Play abonelikleri |
| 🚀 DevOps | EAS Build · EAS Update (OTA) · GitHub Actions CI · self-hosted runner · systemd |

</div>

---

## 🧠 Çözülen Teknik Problemler

<details>
<summary>🌍 <b>Kamu siteleri yurt dışı IP'lerini engelliyor</b></summary>

<br/>

GitHub Actions sunucularından yapılan istekler 403 alıyordu. Tarama Türkiye'deki bir VPS'e taşındı; zamanlamayı systemd timer belirliyor. GitHub Actions, aynı VPS'i **self-hosted runner** olarak kullanan yedek görev olarak kaldı. İki turun üst üste binmemesi için `flock` kilidi kullanılıyor.
</details>

<details>
<summary>📄 <b>Serbest metin ilanları karşılaştırılabilir veriye çevirmek</b></summary>

<br/>

Her kurum şartları farklı yazıyor: "en az (C) düzeyinde YDS", "3 yıl tecrübe", "E veya yeni tip D sınıfı". Gemini'ye **response schema** ile tip güvenli JSON ürettiriliyor; ardından deterministik normalizasyon katmanı devreye giriyor: YDS harf düzeyi → puan, yıl × 360 → SGK günü, seçenekli ehliyette en düşük sınıf, ilandaki program adı → katalogdaki bölüm (816 bölüm). Model uzun ilanlarda kadroları eksik okursa, metindeki kadro başlığı sayısıyla karşılaştırılıp ilan tam metinle ikinci kez okunuyor. Yarım kalan JSON cevabı ayrı bir hata tipiyle yakalanıyor ve ilan her turda tekrar gönderilmesin diye genel kadro olarak kaydediliyor. Son olarak çıkan şartlar ilan metniyle tekrar denetleniyor.
</details>

<details>
<summary>⚖️ <b>İstemci ve sunucu aynı kuralla eşleştirmeli</b></summary>

<br/>

Eşleştirme hem sunucuda (PostgreSQL fonksiyonu) hem uygulamada (`lib/match.ts`) çalışıyor. İkisinin ayrışmaması için parite testleri yazıldı: katalogdaki her bölüm için bir aday üretilip (824 persona) gerçek ilanlar üzerinde iki tarafın aynı sonucu verdiği doğrulanıyor. Testler CI'da her push'ta koşuyor.
</details>

<details>
<summary>🔐 <b>Pro durumunu istemciye bırakmamak</b></summary>

<br/>

`is_premium` alanını kullanıcı değiştiremez; RLS ve açık `GRANT`'larla korunuyor. RevenueCat webhook'u Edge Function'a geliyor, fonksiyon güncel durumu RevenueCat API'sinden doğrulayıp yazıyor. Liste, eşleşme, sıralama ve bildirim fonksiyonlarının hepsi sunucudaki tek `has_active_pro()` kontrolünü kullanıyor.
</details>

<details>
<summary>🔁 <b>Aynı bildirimin iki kez gitmemesi</b></summary>

<br/>

Her bildirim `dedupe_key` ile kaydediliyor. Uygulama yeniden kurulduğunda yeni anonim hesap push jetonunu `claim_push_token` ile devralıyor; böylece eski hesaba bağlı jeton çift bildirim üretmiyor. Bir turdaki tüm eşleşmeler kişi başına tek özet bildirimde toplanıyor.
</details>

<details>
<summary>💸 <b>Yapay zekâ kotasında veri kaybetmemek</b></summary>

<br/>

Gemini günlük kotası dolduğunda tur güvenli şekilde duruyor; işlenmemiş ilanlar bir sonraki turda alınıyor. Tur başına üst sınır (150 yeni ilan) ve token kullanımı `scraper_runs` kaydına yazılıyor. Toplam altyapı maliyeti ayda birkaç dolar.
</details>

---

## 🔐 Gizlilik

- 🙈 Başka bir adayın kimliği hiçbir ekranda gösterilmez; sıralama yalnızca sayı olarak görünür
- 🧾 Aday profili Gemini'ye **gönderilmez**; yapay zekâ yalnızca kamuya açık ilan metnini işler
- 🚫 Reklam, reklam kimliği, konum ve çerez yok
- ⚖️ 6698 sayılı KVKK kapsamında erişim ve silme talepleri desteklenir
- 📄 [Gizlilik politikası](https://mertglbyz.github.io/KPSS_Atama_Support/privacy-policy/) · [Kullanım koşulları](https://mertglbyz.github.io/KPSS_Atama_Support/terms/)

> ⚠️ KPSS Atama bir kamu kurumu uygulaması değildir. Listede yer almak başvuru veya atama hakkı doğurmaz; başvurudan önce ilanın resmi metni kontrol edilmelidir.

---

## 👨‍💻 Geliştirici

<div align="center">

**Mert Gülbeyaz** — Mobile App Developer | AI/ML Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mertglbyz/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mertglbyz)
[![E-posta](https://img.shields.io/badge/E--posta-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gulbeyazm6@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6F6B,100:0F3D3E&height=100&section=footer" width="100%" />

</div>
