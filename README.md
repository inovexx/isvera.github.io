# Gençİş — Türkiye Esnek İş Gücü Platformu

<div align="center">
  <img src="assets/logo.svg" alt="Gençİş Logo" width="200">
  <br><br>
  <strong>Gençler ve öğrenciler için anlık & kısa süreli iş fırsatları platformu</strong>
  <br><br>
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-e8ff47?style=flat-square&labelColor=0a0a0a">
  <img src="https://img.shields.io/badge/Türkiye-81%20İl-47ffb8?style=flat-square&labelColor=0a0a0a">
  <img src="https://img.shields.io/badge/Lisans-MIT-white?style=flat-square&labelColor=0a0a0a">
</div>

---

## 🚀 Canlı Demo

👉 **[gencis.github.io](https://kullaniciadiniz.github.io/gencis)** *(GitHub Pages URL'nizi buraya yazın)*

---

## 📱 Uygulama Hakkında

**Gençİş**, Türkiye'de faaliyet gösteren, gençler ve öğrenciler için kısa süreli, uzun süreli ve anlık iş fırsatları sunan hibrit bir iş gücü platformudur.

### Temel Amaçlar
- Bireylerin boş zamanlarını ekonomik kazanca dönüştürmesi
- İşletmelerin ve fabrikaların geçici iş gücü ihtiyaçlarını hızlı ve güvenli karşılaması
- Öğrencilerin tecrübe kazanıp staj yapmasına yardımcı olmak
- Engelli bireylere özel, erişilebilir iş fırsatları sunmak

---

## ✨ Özellikler

### Kullanıcı (İş Arayan)
- 📲 Onboarding turu (4 adımlı)
- 👤 Kayıt & Giriş (kullanıcı adı + şifre)
- 🗺️ 81 il seçeneği
- 🔍 Kategori & arama filtresi
- 📋 İş ilanlarını görüntüleme & başvuru yazısı gönderme
- ⭐ Çift taraflı puanlama & değerlendirme sistemi
- 💳 Şeffaf ödeme takibi
- 👤 Profil: tamamlanan işler, alınan puanlar, işveren yorumları
- ⚙️ Ayarlar: şifre, e-posta, telefon değiştirme

### İşveren / İşletme
- 📝 İş ilanı oluşturma (başlık, kategori, şehir, ücret, süre, beceriler)
- 📷 Fotoğraf yükleme
- 🤖 Otomatik eşleştirme (konum, beceri, puan bazlı)
- 📊 Aktif ilan yönetimi
- ✅ Performans değerlendirmesi

### Engelsiz Sayfası ♿
- Uzaktan çalışma pozisyonları
- Esnek saatli iş fırsatları
- Erişilebilir platform standartları

### Admin Paneli 🔐
- Kullanıcı yönetimi & engelleme
- Tüm işlemleri ve ilanları görüntüleme
- Ücret & görev raporlaması

---

## 🛠️ Teknik Stack

| Katman | Teknoloji |
|--------|-----------|
| Frontend | Vanilla HTML5, CSS3, JavaScript (ES6+) |
| Font | [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) |
| Hosting | GitHub Pages |
| Backend | — (Frontend demo; backend için Node.js/Firebase entegrasyonu önerilir) |

---

## 📁 Klasör Yapısı

```
gencis/
├── index.html          # Ana uygulama
├── css/
│   └── style.css       # Tüm stiller (CSS değişkenleri, dark/light mod)
├── js/
│   ├── data.js         # Şehirler, iş ilanları, sabitler
│   └── app.js          # Uygulama mantığı
├── assets/
│   ├── logo.svg        # Platform logosu
│   └── favicon.svg     # Tarayıcı ikonu
└── README.md
```

---

## 🚀 GitHub Pages'e Yükleme

### 1. Repository Oluştur
```bash
git init
git add .
git commit -m "🚀 İlk sürüm: Gençİş platformu"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADINIZ/gencis.git
git push -u origin main
```

### 2. GitHub Pages Aktifleştir
1. Repository → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **(root)**
4. **Save** → Birkaç dakika içinde yayınlanır

### 3. URL
```
https://KULLANICI_ADINIZ.github.io/gencis
```

---

## 🔐 Admin Girişi

| Kullanıcı Adı | Şifre |
|---------------|-------|
| `admin` | `admin123` |

> ⚠️ Canlı kullanım için admin şifresini değiştirin ve backend doğrulaması ekleyin.

---

## 🗺️ Yol Haritası

- [ ] Firebase Authentication entegrasyonu
- [ ] Realtime Database ile canlı ilanlar
- [ ] Push notification desteği
- [ ] Harita bazlı iş görüntüleme
- [ ] Ödeme sistemi entegrasyonu (iyzico / PayTR)
- [ ] PWA (Progressive Web App) desteği
- [ ] Android & iOS native wrapper

---

## 📄 Lisans

MIT © 2026 Gençİş
