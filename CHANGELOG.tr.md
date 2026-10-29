# Sürüm geçmişi

<!-- release:1.2.0 -->
## 1.2.0 — 2026-10-29

macOS ARM64 · Windows x64

### Yenilikler ve düzeltmeler

- macOS ARM64 / Windows x64: DNS kontrolleri tarama zaman aşımına uyar; IP hedeflerinde yalnız domainlere uygun kayıt sorguları atlanır ve yavaş çözümleyicilerin taramayı bekletmesi önlenir.

- macOS ARM64 / Windows x64: AI istemcileri mevcut veya yeni domainler için izinli taramalar başlatabilir, izleyebilir ve iptal edebilir. İşler istemci bağlantısı kesildiğinde korunur ve uygulama penceresinden bağımsız çalışır.
- macOS ARM64 / Windows x64: AI değerlendirmeleri Markdown olarak, revizyon geçmişi ve eski tarama/notlara kesin kaynak bağlantılarıyla kaydedilebilir; sonraki oturumlar bu bağlama yeniden erişebilir. Raporlar yerel JSON, Markdown, HTML veya CSV olarak dışa aktarılabilir.

- macOS ARM64 / Windows x64: tarama raporlarına Markdown önizleme, revizyon geçmişi, kaynak bağlantıları ve Markdown indirme içeren AI notları bölümü eklendi; tarama ve not yazma izinleri salt okunur paylaşımdan ayrı yönetilir.

- macOS ARM64 / Windows x64: AI istemcileri temizlenmiş modül/bulgu ayrıntılarını inceleyebilir, paylaşılan geçmişte arama yapabilir, eğilim ve portföy özetlerini okuyabilir ve kapsam sınırlarını gözeterek bulguları karşılaştırabilir. Kayıtlı raporlar MCP kaynakları ve hazır inceleme promptlarıyla erişilebilir.

- macOS ARM64 / Windows x64: Claude Desktop eklentisinin yerleşik Node ortamındaki giriş noktası ve veri aktarımı düzeltildi; macOS kullanıcıları SiteMoth.app dosyasını doğrudan seçebilir.

### Yükseltme ve dağıtım notları

- macOS ARM64 paketleri Developer ID imzalı ve notarize edilmiştir. Mevcut dağıtım politikası kapsamında Windows x64 installer Authenticode bakımından imzasız kalır; güncelleme paketleri ayrıca imzayla doğrulanır.

- Mevcut salt okunur paylaşım salt okunur kalır. AI connections bölümünde tarama/not yazma izinlerini ayrıca açın; yeni araçları keşfetmesi için AI istemcinizi yeniden bağlayın.
- Notlar için geçmiş şeması yükseltilir. Bu adayı denemeden önce domain geçmişini dışa aktararak yedekleyin; eski uygulama sürümleri yükseltilmiş geçmişi açamaz.
- Model erişimini seçtiğiniz AI istemcisi sağlar. Yalnız herkese açık ağlara izinli güvenlik taramaları HTTP şablonları kullanır; desteklenmeyen veya başarısız kontroller başarılı sonuç sayılmaz.

[GitHub Release](https://github.com/erayturan/sitemoth-releases/releases/tag/v1.2.0)
<!-- /release:1.2.0 -->

<!-- release:1.1.0 -->
## 1.1.0 — 2026-10-24

macOS ARM64 · Windows x64

### Yeni özellikler

- macOS ARM64 / Windows x64: uyumlu yapay zekâ istemcileri, isteğe bağlı yerel ve salt okunur MCP bağlantısıyla yalnızca açıkça seçilen alan adlarının kayıtlı raporlarını okuyabilir. Alan adı seçmek erişim verir; son seçimi kaldırmak erişimi kapatır. Değişiklikler anında kaydedilir.
- macOS ARM64 / Windows x64: Ayarlar’a marka ikonu ve izin açıklamalarıyla Claude Desktop bağlantı düğmesi eklendi.
- macOS ARM64 / Windows x64: elle güncelleme kontrolü ve isteğe bağlı günlük otomatik kontrol eklendi. Güncelleme paketlerinin imzası doğrulanır; kurulum ve yeniden başlatma onay gerektirir, aktif taramalar ve yerel AI oturumları bitene kadar bekler.

- Windows x64: AI istemcilerinin yerel tarama geçmişini okurken kullandığı sürücü harfli dosya yolları düzeltildi.

### Arayüz iyileştirmeleri

- macOS ARM64 / Windows x64: Manrope fontu lisansıyla yerel olarak eklendi; transparan açılış ikonu ve logotip hizalandı, AI ayarları çalışma ortamı bilgilerinin üstüne taşındı.
- Web sitesi: İngilizce kök adreste, Türkçe `/tr` altında sunulur; hukuki bağlantılar, sitemap ve metadata aynı dil düzenini izler. İndirme bağlantıları her platformun yayımlanmış sürümünü ayrı takip eder.

### Yükseltme ve dağıtım

- Güncelleyici içeren bu ilk sürümü elle kurun. Daha yeni kararlı sürüm yayımlandığında sonraki güncellemeler Ayarlar üzerinden sunulacaktır.
- AI erişimi ve otomatik güncelleme kontrolü varsayılan olarak kapalıdır. Güncelleme kontrolleri rapor veya alan adı listesi göndermeden GitHub’a bağlanır. Güncellenen gizlilik bildirimini inceleyin.
- macOS Developer ID imzası ve notarizasyon kullanır. Windows Authenticode bakımından imzasız dağıtılmaya devam eder; güncelleme paketlerinin imzaları ayrıca doğrulanır.
- Tarayıcı tabanlı denetimler için Chrome veya Edge kurulu olmalıdır.

[GitHub Release](https://github.com/erayturan/sitemoth-releases/releases/tag/v1.1.0)
<!-- /release:1.1.0 -->

<!-- release:1.0.3 -->
## 1.0.3 — 2026-10-24

macOS ARM64 · Windows x64

### Düzeltmeler

- Yeni Windows kurulumları 64 bit Program Files klasörünü kullanır. Mevcut kurulumlar önceki kurulum klasörünü koruyabilir.

### Dağıtım notları

- Windows imzasız dağıtılır. macOS dağıtımında Developer ID imzası ve notarization kullanılır.
- Tarayıcı tabanlı denetimler için Chrome veya Edge kurulu olmalıdır.

[GitHub Release](https://github.com/erayturan/sitemoth-releases/releases/tag/v1.0.3)
<!-- /release:1.0.3 -->

