# Polaris — Detaylı Kullanım ve Düzenleme Kılavuzu

Bu belgede Polaris'in gelişmiş motor özellikleri, kurgu araçları ve dışa aktarma seçenekleri ayrıntılı olarak açıklanmıştır.

---

## 1. Kayıt Öncesi Ayarlar (Record Setup)

* **Monitör Seçimi**: Çoklu ekran kullanıyorsanız hedef ekranı seçin.
* **Sistem Sesi**: Bilgisayarınızdan çıkan müzik, bildirim veya uygulama seslerini kaydetmek için aktifleştirin (WASAPI Loopback).
* **Kamera ve Mikrofon**: Web kameranızı konuşmacı balonu olarak entegre edin. Gürültü engelleme (Noise Suppression) seçeneği mevcuttur.
* **Kısayol ile Başlatma**: `Ctrl+Shift+R` (macOS: `Cmd+Shift+R`).

---

## 2. Zaman Çizelgesi ve Düzenleme (Timeline Ops)

Polaris, kaydınız bittiğinde otomatik olarak projenizi analiz eder ve kurgu arayüzünü açar:

### Akıllı Otomatik Zoom (Auto-Zoom)
* Tıklanan pencereler, form kutuları ve butonlar yapay zeka algoritmasıyla tespit edilir.
* Her tıklamaya yumuşak bir 2.0x yakınlaştırma atanır.
* Zaman çizelgesindeki sarı renkli zoom kutularının kenarından tutarak süresini uzatabilir, sürükleyerek başka saniyeye taşıyabilirsiniz.
* Manuel zoom eklemek için: İmleci getirin ve `Z` tuşuna basın.

### Kırpma, Bölme ve Çoğaltma
* **Bölme (Split)**: Oynatma çizgisini getirin ve `S` tuşuna basın.
* **Silme (Delete)**: İstemediğiniz aralığı seçip `Delete` veya `Backspace` tuşuna basın; zaman çizgisi otomatik olarak toparlanır.
* **Hız Değiştirme (Speed)**: Klibi seçin; sağdaki Denetçi panelinden hızı `0.5x`, `1.0x`, `2.0x` veya `4.0x` yapın.

### Dinamik Kamera Balonu (Picture-in-Picture)
* Kamerayı sağ-alt, sol-alt veya istediğiniz köşeye sabitleyin.
* Belirli anlarda tam ekran konuşmacı moduna geçmek için zaman çizgisine kamera bölümü (`K`) ekleyin.
* Geçişler sinematik yaylanma (easing) ile pürüzsüz gerçekleşir.

### Büyüteç (Magnifier / Lens)
* Kod satırları veya küçük yazıları öne çıkarmak için `B` tuşuna basarak dairesel büyüteç ekleyin.
* Merceğin boyutunu ve yakınlaştırma oranını Denetçi panelinden özelleştirin.

### Durgun Anları Toplu Temizleme
* Üst menüden **"Durgun Anları Sil"** butonuna tıklayın.
* Ekranda hiçbir hareketin veya sesin olmadığı duraklama süreleri listelenir; tek tıkla videodan çıkartılır.

---

## 3. Dışa Aktarma (Export Pipeline)

Sağ üstteki **Dışa Aktar** butonuna basarak istediğiniz çıktı formatını belirleyin:

* **16:9 Yatay MP4 / WebM**: YouTube ve masaüstü sunumları için 1080p, 2K ve 4K 60 FPS.
* **9:16 Dikey Format**: TikTok, Instagram Reels ve YouTube Shorts için özel dikey kırpma.
* **Hareketli GIF**: Bloglar ve dokümantasyonlar için düşük boyutlu, palet optimizasyonlu döngüsel GIF.
