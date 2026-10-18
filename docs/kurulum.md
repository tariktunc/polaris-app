# 🛠️ Polaris — Detaylı Kurulum ve İzin Kılavuzu

Bu kılavuz, Polaris'in Windows ve macOS üzerinde ilk kurulumunda işletim sistemi güvenlik onaylarını nasıl yapılandıracağınızı adım adım açıklar.

---

## 🪟 Windows 10 & 11 Kurulumu

1. [Polaris-Setup-0.1.0.exe](https://github.com/tariktunc/polaris-app/releases/download/v0.1.0-beta/Polaris-Setup-0.1.0.exe) dosyasını indirin ve çift tıklayın.
2. Karşınıza **Windows Defender SmartScreen** penceresi gelirse:
   - Penceredeki **"Ek bilgi" (More info)** bağlantısına tıklayın.
   - Sağ altta beliren **"Yine de çalıştır" (Run anyway)** butonuna basın.
   *(Polaris henüz ticari Microsoft EV sertifikasıyla imzalanmadığı için açık kaynak projelerde bu onay istenir; yazılım tamamen güvenli ve yereldir).*
3. Kurulum sessizce tamamlanacak ve Polaris masaüstünüze eklenecektir.

---

## 🍏 macOS Kurulumu (Apple Silicon & Intel)

1. [Polaris-0.1.0-universal.dmg](https://github.com/tariktunc/polaris-app/releases/download/v0.1.0-beta/Polaris-0.1.0-universal.dmg) dosyasını açın.
2. `Polaris.app` simgesini `Applications` (Uygulamalar) klasörüne sürükleyin.
3. İlk açılışta *"Geliştirici doğrulanamadı"* veya *"Hasarlı"* uyarısı alırsanız:
   - **Sistem Ayarları > Gizlilik ve Güvenlik** sekmesine gidin.
   - Sayfanın en altındaki Güvenlik bölümünde **"Yine de Aç" (Open Anyway)** butonuna tıklayın.
   - Veya Terminal'de şu komutu çalıştırabilirsiniz:
     ```bash
     xattr -cr /Applications/Polaris.app
     ```

### 🔒 macOS Gerekli İzinler
Polaris'in ekranı ve sesi kaydedebilmesi için macOS şu izinleri talep eder:
* **Ekran ve Sistem Sesi Kaydı**: Ekran görüntüsü ve bilgisayar içi sesleri yakalamak için.
* **Kamera**: Web kameranızı baloncuk olarak kaydetmek için.
* **Mikrofon**: Sesli anlatımınızı kaydetmek için.

Bu izinleri **Sistem Ayarları > Gizlilik ve Güvenlik** menüsünden dilediğiniz zaman yönetebilirsiniz.
