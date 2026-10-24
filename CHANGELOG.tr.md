# Sürüm geçmişi

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

