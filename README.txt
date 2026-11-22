EFOTBALL LEAGUE — KURULUM

Bu paket Android ve iPhone'da ana ekrana uygulama gibi eklenebilen bir PWA web uygulamasıdır. Tek bir web sürümü iki platformda da çalışır.

MEVCUT ÖZELLİKLER
- Birden fazla lig oluşturma ve yönetme
- Tek/çift devre fikstür oluşturma
- Takım ekleme ve silme
- Maç skoru kaydetme
- Otomatik puan durumu (3/1/0)
- Gol, averaj, galibiyet, beraberlik ve mağlubiyet istatistikleri
- Mobil arayüz ve çevrimdışı önbellek
- Alt bilgi: producter: 7x HASANOV sunar

WEB'DE YAYINLAMA (GitHub Pages)
1. GitHub'da yeni bir repository oluştur.
2. Bu klasördeki dosyaların tamamını repository'nin ana dizinine yükle.
3. Repository Settings > Pages bölümüne gir.
4. Deploy from a branch seç; branch olarak main ve klasör olarak /(root) seçip kaydet.
5. GitHub'ın verdiği HTTPS adresi açılınca uygulama çalışır.

ANDROID KURULUMU
- Yayındaki HTTPS bağlantısını Chrome'da aç.
- Tarayıcı menüsünden 'Uygulamayı yükle' veya 'Ana ekrana ekle' seç.

IPHONE KURULUMU
- HTTPS bağlantısını Safari'de aç.
- Paylaş > Ana Ekrana Ekle seç.

ÖNEMLİ SINIRLAMALAR
- Bu paket doğrudan APK veya App Store .ipa dosyası değildir; Android ve iPhone'da kurulabilen ortak web uygulamasıdır.
- Gerçek APK ve App Store uygulaması için ayrıca native paketleme gerekir. iOS .ipa/App Store derlemesi Xcode çalışan bir Mac ve Apple geliştirici süreçleri gerektirir.
- Lig verileri şu an cihazın kendi tarayıcı hafızasında tutulur. Farklı telefonlarda ortak lig/veri senkronizasyonu için sunucu ve veritabanı eklenmelidir.
