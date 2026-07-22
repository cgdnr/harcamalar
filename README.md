# PWA Uygulaması Oluşturma Rehberi

Bu belge, PWABuilder kullanarak Android için bir PWA (Progressive Web App) uygulaması oluşturma sürecini adım adım açıklar.

## Adımlar

### 1. PWABuilder'a Gidin
[PWABuilder](https://pwabuilder.com) web sitesine erişin.

### 2. GitHub URL'sini Yapıştırın
Açılan sayfada, GitHub URL'nizi yapıştırın ve "Start" düğmesine tıklayın.

### 3. Platform Seçimi
- "Package for stores" bölümünde **"Android"** seçeneğini seçin.

### 4. Host Ayarları
Aşağıdaki bilgileri girin:
- **Host**: `cgdnr.github.io`
- **Start URL**: `/harcamalar`

### 5. APK Oluşturma
Tüm bilgileri girdikten sonra APK dosyasını oluşturmak için **"Generate"** seçeneğine tıklayın.

### 6. `assetlinks.json` Dosyasını Güncelleyin
- Oluşan `assetlinks.json` dosyasındaki verileri GitHub'daki aynı dosyanın içerisine kopyalayın.

### 7. APK'yı Cihaza Kurun
Oluşturulan APK dosyasını cihazınıza yükleyin ve uygulamayı çalıştırın.

### 8. İkinci Kez APK Oluşturma
- Eğer PWABuilder'da ikinci kez APK oluşturursanız, "Use mine" veya "Import existing key" seçeneğini seçin.
- `signing.keystore` dosyasını yükleyin. Bu adım atlanırsa, her defasında `assetlinks.json` içeriğini güncellemeniz gerekecektir.

## Notlar
- Her aşamada dikkatli olun ve gereken dosyaları yedekleyin.
