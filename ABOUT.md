# Polaris Dağıtım ve İndirme Sayfası (GitHub Pages)

Bu klasör, **Polaris v0.1.0-beta** sürümünün halka açık indirme sayfasını barındırır.
Ana kaynak kodlarınızı (Private Repo) sızdırmadan tamamen güvenli bir indirme kapısı sunar.

---

## Hızlı Kurulum Adımları

### 1. Yeni Bir Genel (Public) GitHub Reposu Açın
- GitHub'da yeni bir repo oluşturun: Örneğin `polaris-app` veya `polaris-download`.
- Repoyu **Public** olarak ayarlayın.

### 2. Dosyaları Repoya Yükleyin
- Bu klasördeki (`distribution-page/`) `index.html` dosyasını yeni açtığınız reponun kök dizinine yükleyin.

### 3. GitHub Pages'i Etkinleştirin
- GitHub reponuzda **Settings > Pages** sekmesine gidin.
- **Build and deployment > Source** kısmını **Deploy from a branch** yapın.
- Branch olarak `main` ve `/ (root)` seçip **Save** butonuna tıklayın.
- Birkaç dakika içinde indirme sayfanız `https://kullaniciadi.github.io/polaris-app/` adresinde canlıya geçecektir.

---

## Sürüm (Release) Dosyalarının Bağlanması

1. Derlediğiniz kurulum dosyalarını (`Polaris-Setup-0.1.0.exe` ve `Polaris-0.1.0-universal.dmg`) oluşturun.
2. Açtığınız public reponun sağındaki **Releases > Create a new release** bölümüne gidin.
3. Etiket (Tag) olarak **`v0.1.0-beta`** yazın.
4. `.exe` ve `.dmg` kurulum dosyalarını buraya sürükleyip bırakarak yayınlayın.
5. `index.html` içindeki indirme bağlantıları otomatik olarak bu sürüm etiketini çekecek şekilde yapılandırılmıştır.

---

## Güvenlik Notu
Ana proje kodlarınız (Electron, Rust, Swift kaynakları) kendi **Private** reponuzda kalır.
Bu indirme reposu tamamen bağımsızdır ve kaynak kod içermez.
