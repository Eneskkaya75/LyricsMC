# LyricsMC

Minecraft 1.21.4 / 1.21.11 · Fabric · Java 21 · Enws75

Resmî dağıtım: https://github.com/Eneskkaya75/LyricsMC

Bu depo derlenmiş LyricsMC sürümlerini ve sürüm notlarını dağıtır. Java kaynakları ve yayıncı imza anahtarı bu depoda paylaşılmaz.

## 3.7.5

Klasik menü daha minimal bir koyu tasarımla yenilendi: kömür grisi yüzeyler, mat arduvaz vurgular ve hafif çerçeveler. Çalan, Sözler ve Stil sol menüde ayrı açılır. Müzik sayfası doğrudan bağlantı ayarlarıyla başlar. 1.21.11 için Fabric API 0.141.3+1.21.11 desteği korunur.

Menü grubu daha küçük ve ortalanmış panellerden oluşur; çevresinde oyun dünyasına geniş alan bırakılır.

## 3.7.4

Minecraft 1.21.11 paketi Fabric API **0.141.3+1.21.11** ile uyumludur; 0.141.4 gereksiniminden kaynaklanan açılış engeli giderildi.

Klasik düzen geri geldi: solda ayrı müzik kartı; sağda dikey menü ve geniş ayar alanı. Antrasit yüzeyler üzerinde turkuaz vurgu kullanılır; kişisel vurgu rengi seçilebilir. Müzik kartında kapak, oynatma, ilerleme ve ses kontrolleri bulunur. Geniş ekranlarda Minecraft GUI ölçeği bu kartı gizlemez; dar ekranlar için içeride oynatıcı görünümü vardır. Kozmetik, prova, emote ve güncelleme ekranlarının renkleri de uyumlu hâle getirildi.

## 3.7.3

Mor arayüz; sabit sol gezinme, geniş kozmetik kartları ve üç sekmeli gökyüzü galerisiyle yenilendi. Daha yumuşak yıldızlar, nebula ayrıntıları ve daha temiz gökyüzü renk geçişleri eklendi. Yeni hareketler: eğilerek selamlama, omuz silkme, dönüş ve kutlama.

Emote ve kozmetikler ortak canlı bağlantıdan alınır. Kombinlerin sekiz saniyelik bekleme aralığı kaldırıldı; hareket komutları önceliklendirildi. Bağlantı yeniden kullanımı ve IPv4/IPv6 yol seçimi eklendi. Karşı oyuncuya ulaşma süresi bağlantıya bağlıdır; iki oyuncunun da 3.7.3 kullanması önerilir. V çarkı ve F ile ikili hareketler kullanılabilir.

## 3.7.2

Uzaktaki oyuncunun emote'unu eski hız bilgisinden dolayı silen çizim kontrolü düzeltildi. Mesaj akışı tamponlandığında yedek aktarım, saat farkı uyarlaması ve uzaktaki modelden gösterim onayı eklendi.

**Beşlik, yumruk tokuşturma ve ikili dans:** V çarkında F ile birlikte hareketleri açın, hareketi ve yakındaki arkadaşınızı seçip davet edin. İkinizde de 3.7.2 ve paylaşım açık olmalı. Mor tasarım korunarak emote stüdyosu ve çalışma alanı yenilendi.

## 3.7.1

Yenilenmiş LyricsMC arayüzü, daha büyük kozmetik önizlemeleri, ayrıntı/tam karakter provası ve sohbet/skor tablosu/boss çubuğuna göre yer değiştiren akıllı HUD.

V'ye basılı tutup fareyle emote seçin. Favorileri çarka yerleştirin; birlikte hareket için yakındaki oyuncuya davet gönderin. İki oyuncuda da 3.7.1, emote paylaşımı ve çevrimiçi bağlantı gerekir. Chat emoji sistemi, Mavi Alev/Warden/Zebani Aesir paketleri, Tris ve Atelier ipek pelerinler kaldırıldı.

## Kurulum

Releases bölümünden kendi Minecraft sürümünüze uygun en yeni JAR dosyasını indirin. 1.21.4 için `LyricsMC-1.21.4-Enws75-v…jar`, 1.21.11 için `LyricsMC-1.21.11-Enws75-v…jar` kullanılır. Fabric Loader ve oyun sürümüne uygun Fabric API gerekir. Aynı anda yalnızca tek LyricsMC sürümü yükleyin.

## Otomatik güncellemeler

Güncelleme kanalı modun içinde sabittir; oyuncu depo, URL veya JAR seçemez. Her istemci yalnızca kendi Minecraft sürümünün en yeni uygun yayınını seçer: 1.21.4 ve 1.21.11 manifestleri/imzaları ayrıdır. Güncelleyici yalnızca yayıncının Ed25519 imzasıyla onaylanan dosyayı kabul eder. Minecraft/Fabric/Java uyumluluğu, sürüm, dosya boyutu ve SHA-256 ayrıca kontrol edilir. İndirme arka planda, kurulum oyun kapandıktan sonra gerçekleşir; önceki JAR yedeklenir.

Açılışta kontrol, otomatik indirme ve erteleme kişisel tercihlerdir. Kaynak seçimi bu tercihler arasında değildir. Yerel bilgisayarda JAR'ı elle değiştirme tamamen engellenemez; imza doğrulaması resmî güncelleme yolunu korur.

Sürümlerdeki JSON ve SIG dosyaları otomatik güncelleyici içindir. Normal kurulumda yalnız JAR gerekir. Varlık ve üçüncü taraf bildirimleri JAR içindeki NOTICE.txt dosyasındadır.

