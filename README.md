# 🎮 Arkanoid

Taito'nun 1986 yılında çıkardığı klasik Arkanoid oyununun, HTML5 Canvas ve JavaScript ile yapılmış modern bir uyarlaması. Hem masaüstü hem de mobil cihazlarda oynanabilir.

---

## 🕹️ Nasıl Oynanır?

- Paddle'ı hareket ettirerek topun düşmesini engelle
- Topu üstteki tuğlalara çarptırarak hepsini kır
- Tüm tuğlaları kırınca bir sonraki raunda geçersin
- 3 canın biter → Game Over

### Kontroller

| Platform | Hareket | Topu Fırlat |
|----------|---------|-------------|
| 🖥️ Masaüstü | Mouse ile kaydır | Tıkla |
| 📱 Mobil | Parmakla kaydır | Dokun |

---

## ⚡ Power-Up'lar

| İkon | İsim | Etki | Süre |
|------|------|------|------|
| 🔵 | Geniş Paddle | Paddle geçici olarak genişler | 10sn |
| 🔴 | Lazer | Paddle'dan lazer ateşlenir | 8sn |
| 🟡 | Çok Top | Top 3'e katlanır | — |
| 🟢 | Yavaş Top | Top yavaşlar, kontrol kolaylaşır | 7sn |
| 💗 | Ekstra Can | Bir can kazanırsın | — |
| 🟦 | Bariyer | Ekran altında koruma çizgisi, top düşmez | 12sn |
| 🔥 | Ateş Topu | Top tuğlalardan sekmiyor, delerek geçiyor | 8sn |
| 🧲 | Mıknatıs | Top paddle'a yapışır, istediğinde fırlat | 8sn |
| 💣 | Bomba | En yakın 9 tuğlayı anında kırar | — |

---

## 🧱 Tuğla Tipleri

- **Normal tuğlalar** — bir vuruşta kırılır
- **Sağlam tuğlalar** (kırmızı & mor) — iki vuruş gerekir, hasar aldığında solar

---

## 🎮 Özellikler

- ⏸️ **Duraklat / Devam** — oyunu istediğin zaman durdur
- 🎵 **8-bit arka plan müziği** — ayarlardan açılıp kapatılabilir
- 🔊 **Ses efektleri** — her çarpışma ve power-up için ayrı ses
- 📊 **İstatistikler** — en yüksek skor, en yüksek round, toplam oynama süresi, kırılan tuğla sayısı (tarayıcıya kaydedilir)
- ⚙️ **Ayarlar** — top hızı (Kolay / Orta / Zor), müzik ve ses kontrolü
- ❓ **Yardım sayfası** — tüm power-up açıklamaları oyun içinde
- 🌙 **NES tarzı** görsel tasarım ve renk paleti

---

## 🛠️ Teknolojiler

- HTML5 Canvas API
- Vanilla JavaScript
- Web Audio API (ses efektleri ve 8-bit müzik)
- localStorage (istatistik kaydı)
- CSS3

Hiçbir harici kütüphane veya framework kullanılmamıştır. Tek `.html` dosyasıdır.

---

## 🚀 Kurulum

Herhangi bir kurulum gerekmez. Dosyayı indirip tarayıcıda aç:

```bash
git clone https://github.com/kurtayfun/arkanoid.git
cd arkanoid
# index.html dosyasını tarayıcıda aç
```

Ya da GitHub Pages üzerinden direkt oyna:

```
https://KULLANICIADIN.github.io/arkanoid/
```

---

## 👤 Geliştirici

**Çınar Kurt**

---

## 📜 Lisans

Bu proje eğitim ve eğlence amaçlı yapılmıştır. Orijinal Arkanoid © 1986 Taito Corporation.
