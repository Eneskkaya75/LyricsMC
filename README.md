# LyricsMC

Minecraft 1.21.4 · Fabric · Java 21 · Enws75

Resmî dağıtım: https://github.com/Eneskkaya75/LyricsMC

Bu depo derlenmiş LyricsMC sürümlerini ve sürüm notlarını dağıtır. Java kaynakları ve yayıncı imza anahtarı bu depoda paylaşılmaz.

## Kurulum

Releases bölümünden `LyricsMC-1.21.4-Enws75-v3.5.jar` veya daha yeni uyumlu sürümü indirin. Fabric Loader ve Fabric API gerekir. Aynı anda yalnızca tek LyricsMC sürümü yükleyin.

## Otomatik güncellemeler

Güncelleme kanalı modun içinde sabittir; oyuncu depo, URL veya JAR seçemez. Güncelleyici yalnızca yayıncının Ed25519 imzasıyla onaylanan dosyayı kabul eder. Minecraft/Fabric/Java uyumluluğu, sürüm, dosya boyutu ve SHA-256 ayrıca kontrol edilir. İndirme arka planda, kurulum oyun kapandıktan sonra gerçekleşir; önceki JAR yedeklenir.

Açılışta kontrol, otomatik indirme ve erteleme kişisel tercihlerdir. Kaynak seçimi bu tercihler arasında değildir. Yerel bilgisayarda JAR'ı elle değiştirme tamamen engellenemez; imza doğrulaması resmî güncelleme yolunu korur.

## 3.5 değişiklikleri

- Spiky Hair ve benzer saçların alpha kabuklarındaki eksik iç yüzler tamamlandı.
- Kitsune Tails hacimlerinin içten görünen yüzleri düzeltildi; özgün kürk saçakları korundu.
- Döngü, tek sefer ve son karede bekleyen animasyonlar ayrıldı.
- Paketler ön/arka görünümle sunuluyor; kamera sınırları bakış açısına göre doğru hesaplanıyor.
- Oyuncunun güncelleme kaynağı/JAR seçimi kaldırıldı; sabit kanal ve Ed25519 imzalı bildirim eklendi.

Sürümlerdeki JSON ve SIG dosyaları otomatik güncelleyici içindir. Normal kurulumda yalnız JAR gerekir. Varlık ve üçüncü taraf bildirimleri JAR içindeki NOTICE.txt dosyasındadır.
