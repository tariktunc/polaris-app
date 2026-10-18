# 🌟 Polaris — Akıllı Ekran Kaydı & Video Kurgu Stüdyosu


<p align="center">
  <a href="https://tariktunc.github.io/polaris-app/"><img src="https://img.shields.io/badge/🌐_Canlı_Web_Sitesi-tariktunc.github.io%2Fpolaris--app-6366f1?style=for-the-badge" alt="Web Sitesi"/></a>
  <a href="https://github.com/tariktunc/polaris-app/releases/tag/v0.1.0-beta"><img src="https://img.shields.io/badge/Sürüm-v0.1.0--beta-38bdf8?style=for-the-badge" alt="Sürüm"/></a>
  <a href="#lisans"><img src="https://img.shields.io/badge/Lisans-MIT-a855f7?style=for-the-badge" alt="Lisans"/></a>
  <img src="https://img.shields.io/badge/Platform-Windows_%7C_macOS-emerald?style=for-the-badge" alt="Platform"/>
</p>

---

## ⚡ Hızlı İndirme Bağlantıları (v0.1.0-beta)

En son kararlı beta sürümünü doğrudan aşağıdaki bağlantılardan indirebilirsiniz:

| Platform | Kurulum Dosyası | Mimari | Gereksinim | İndirme Bağlantısı |
|---|---|---|---|---|
| **Windows** | `.exe` (Installer) | 64-bit (x64) | Windows 10 (1903+) / Windows 11 | [📥 **Polaris-Setup-0.1.0.exe İndir**](https://github.com/tariktunc/polaris-app/releases/download/v0.1.0-beta/Polaris-Setup-0.1.0.exe) |
| **macOS** | `.dmg` (Universal) | Apple Silicon & Intel | macOS 13.0 (Ventura) veya üstü | [📥 **Polaris-0.1.0-universal.dmg İndir**](https://github.com/tariktunc/polaris-app/releases/download/v0.1.0-beta/Polaris-0.1.0-universal.dmg) |

> 🌐 **Resmi Tanıtım ve İndirme Sayfası**: [https://tariktunc.github.io/polaris-app/](https://tariktunc.github.io/polaris-app/)  
> 📦 **Tüm Sürümler ve Değişiklik Notları**: [GitHub Releases Sayfası](https://github.com/tariktunc/polaris-app/releases)

---

## 📖 Kullanım Kılavuzu & Dokümantasyon (Docs)

### 1. Kurulum ve İlk Çalıştırma

#### 🪟 Windows Kurulumu:
1. `Polaris-Setup-0.1.0.exe` dosyasını indirin ve çift tıklayın.
2. *Windows Defender SmartScreen* "Windows kişisel bilgisayarınızı korudu" uyarısı verirse:
   - **Ek bilgi (More info)** bağlantısına tıklayın.
   - **Yine de çalıştır (Run anyway)** butonuna basın. (Uygulama henüz ticari sertifikayla imzalanmadığı için ilk kurulumda bu onay istenir).
3. Polaris otomatik olarak kurulup açılacaktır.

#### 🍏 macOS Kurulumu:
1. `Polaris-0.1.0-universal.dmg` dosyasını açın ve `Polaris` uygulamasını `Applications` (Uygulamalar) klasörüne sürükleyin.
2. İlk açılışta *"Geliştirici doğrulanamadı"* uyarısı alırsanız:
   - **Sistem Ayarları > Gizlilik ve Güvenlik** sekmesine gidin.
   - En altta **"Yine de Aç" (Open Anyway)** butonuna tıklayın.
3. Ekran kaydı ve sistem sesi için macOS'un istediği izinleri onaylayın.

---

### 2. Kayıt Başlatma (Record Setup)

1. **Ekran Seçimi**: Birden fazla monitörünüz varsa kaydetmek istediğiniz ekranı seçin.
2. **Sistem Sesi**: Bilgisayardan gelen seslerin videoya dahil edilmesi için *Sistem Sesi* kutusunu işaretleyin (WASAPI Loopback).
3. **Kamera & Mikrofon**: Web kameranızı ve konuşma mikrofonunuzu açabilirsiniz.
4. **Kayıt Tuşu**: **● Kaydı Başlat** butonuna basın veya klavyeden `Ctrl+Shift+R` (macOS'ta `Cmd+Shift+R`) kısayolunu kullanın.
5. **Kaydı Bitirme**: Menü çubuğundaki / görev çubuğundaki Polaris simgesine tıklayıp **Durdur** deyin veya açılan küçük HUD panelinden kaydı sonlandırın.

---

### 3. Zaman Çizelgesi ve Düzenleme (Timeline Editing)

Kayıt bittiğinde Polaris projenizi otomatik olarak analiz eder ve düzenleyici penceresini açar:

* **🎯 Otomatik Tıklama Zoom'u (Auto-Zoom)**:
  - Tıkladığınız pencereler ve form alanları otomatik olarak 2.0x oranında odaklanır.
  - Zoom kutularının kenarlarından tutarak süresini uzatabilir/kısaltabilir, sürükleyerek yerini değiştirebilirsiniz.
* **✂️ Kırpma ve Bölme**:
  - Oynatma çizgisini kesmek istediğiniz noktaya getirin ve klavyeden `S` tuşuna basın. Klip ikiye bölünür.
  - İstenmeyen kısımları seçip `Delete` tuşuyla silebilirsiniz; aradaki boşluk otomatik kapanır.
* **⏩ Hız Ayarı**:
  - Seçtiğiniz klibin hızını sağdaki Denetçi panelinden `0.5x`, `1.0x`, `2.0x` veya `4.0x` olarak ayarlayabilirsiniz.
* **🎥 Dinamik Kamera Balonu**:
  - Konuşmacı kamerasını köşelerde küçük baloncuk veya tam ekran olarak konumlandırabilirsiniz (`K` tuşu).
* **🔍 Büyüteç (Magnifier) Efekti**:
  - Ekranın belirli bir piksel alanını dairesel mercek altına almak için `B` tuşuna basarak büyüteç ekleyin.
* **🔇 Durgun Anları Toplu Temizleme**:
  - Konuşmadığınız veya ekranda hiçbir hareketin olmadığı ölü zamanları tek tıkla bulup videodan çıkarmak için üst menüdeki **"Durgun Anları Sil"** seçeneğini kullanın.

---

### 4. Dışa Aktarma (Export)

Videonuz hazır olduğunda sağ üstteki **"Dışa Aktar"** butonuna tıklayın:

| Çıktı Biçimi | Kullanım Alanı | Çözünürlük & Detay |
|---|---|---|
| **MP4 (H.264 / HEVC)** | YouTube, Sunumlar, Masaüstü | 1080p, 2K veya 4K (60 FPS) |
| **Dikey Video (9:16)** | TikTok, Instagram Reels, YouTube Shorts | Mobil cihazlar için optimize edilmiş dikey tuval |
| **Hareketli GIF** | GitHub README, Dokümantasyon, Blog | Düşük dosya boyutlu, optimize renk paletli döngü |
| **WebM** | Web siteleri ve HTML5 video gömmeleri | Yüksek sıkıştırma, açık kaynak standart |

---

### 5. Klavye Kısayolları Tablosu

| Kısayol | İşlem |
|---|---|
| `Space` (Boşluk) | Oynat / Duraklat |
| `S` | Oynatma çizgisinde klibi böl (Split) |
| `Z` | Seçili alana manuel Zoom ekle |
| `K` | Kamera bölümü / geçişi ekle |
| `B` | Büyüteç (Lens) efekti ekle |
| `Delete` / `Backspace` | Seçili klibi veya zoom aralığını sil |
| `Ctrl + Z` / `Cmd + Z` | Geri Al (Undo) |
| `Ctrl + Shift + Z` | Yinele (Redo) |
| `Ctrl + E` / `Cmd + E` | Dışa Aktarma penceresini aç |

---

## 🛡️ Güvenlik & Gizlilik İlkeleri

- **%100 Yerel İşleme**: Polaris hiçbir ses, görüntü veya imleç verisini sunuculara göndermez. Tüm render ve analiz işlemleri yerel donanımınızda (CPU / GPU) gerçekleşir.
- **Ağ İstemez**: Çevrimdışı (offline) olarak tam verimle çalışır.
- **Gizli Kaynak Kodu**: Polaris'in çekirdek kaynak kodları özel geliştirme reposunda saklanır; dağıtım reposu yalnızca son kullanıcı kurulum paketlerini barındırır.

---

## ⚖️ Lisans

Bu yazılım [MIT Lisansı](https://github.com/tariktunc/polaris/blob/main/LICENSE) şartları altında korunmaktadır.  
Telif Hakkı © 2026 **Tarık Tunç** (<info@blakfy.com>). Tüm hakları saklıdır.
