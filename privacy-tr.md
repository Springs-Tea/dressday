---
title: Bugün Ne Giysem — Gizlilik Politikası
---

# Bugün Ne Giysem Gizlilik Politikası

Son güncelleme: 7 Ekim 2026 · Kapsam: iPhone (iPad'e kurulduğunda da) ve Android için Bugün Ne Giysem, sürüm 1.0.0


Bugün Ne Giysem, Coditive tarafından geliştirilir. Bu politika, uygulamanın bilgilerinle ne yaptığını anlatır. Kısacası: kıyafetlerin, boy fotoğrafın ve dolabın cihazında kalır. Hesap, reklam, analitik ve izleme yoktur. İnternet yalnız iki iş için kullanılır: hava tahmini ve App Store ya da Google Play üzerinden satın alma.

İletişim: kasim@mitrabilisim.com.tr

## 1. Uygulamanın kullandığı bilgiler ve nerede durdukları

Aşağıdakilerin hepsini sen uygulamada oluşturursun ve hepsi yalnız cihazındaki uygulama alanında saklanır. Coditive'in sunucusu yoktur; bunların hiçbiri bize ulaşmaz.

- Kamerayla çektiğin ya da sistem fotoğraf seçicisinde seçtiğin **kıyafet fotoğrafları** ve bunlardan kesilen görseller.
- **Parça etiketleri**: kategori, renk, desen, mevsim, resmiyet, kalınlık ve isteğe bağlı olarak kendin eklediğin fiyat, marka ve not.
- Her parça için uygulamaya gömülü bir görüntü modeliyle cihazında hesaplanan **sayısal görüntü özeti**. Etiket önermek ve çok benzer parçaları fark etmek için kullanılır.
- **Ayna fotoğrafların**: Ayna için çektiğin ya da seçtiğin boy fotoğrafı, ondan hesaplanan poz noktaları ve vücut ana hattı, Ayna'nın çizdiği görseller.
- **Uygulama kullanımın**: kaydettiğin kombinler, ne zaman ne giydiğin, beğendiklerin ve beğenmediklerin, kirli sepeti, haftalık planlar ve seyahatler.
- **Ayarlar**: tarz cevapların, sıcaklık birimi, sabah bildirimi saati, kirli sepeti kuralları, tema, dil ve hava için kullanılan şehir ya da yaklaşık konum.

Arka plan silme ve poz algılama cihazında çalışır: iPhone'da Apple'ın Vision çerçevesiyle, Android'de uygulamanın içinde gelen modellerle. Etiketleme her iki platformda uygulamaya gömülü bir görüntü modeliyle yapılır, kombin önerilerini uygulamanın kendisi hesaplar. Bu işler için hiçbir fotoğraf çevrimiçi bir servise gönderilmez.

## 2. Cihazından ne çıkar ve neden

**Hava tahmini (Open-Meteo).** Havayı göstermek ve kombinleri havaya göre planlamak için uygulama Open-Meteo'dan (api.open-meteo.com) tahmin ister. İstekte yalnız tek ondalığa yuvarlanmış koordinatlar (yaklaşık 10 km) ve tahmin ayarları bulunur. Bir şehir aradığında (örneğin şehrini seçerken ya da seyahat planlarken) iki harften itibaren yazdığın metin ve uygulamanın dil kodu Open-Meteo'nun yer aramasına (geocoding-api.open-meteo.com) gönderilir. İstekler HTTPS ile gider; hesap, cihaz kimliği, çerez ya da tarayıcı kimliği (user-agent) taşımaz; fotoğraf ya da dolap verisi asla içermez. Her internet isteğinde olduğu gibi Open-Meteo cihazının IP adresini görebilir; istekleri nasıl işlediği kendi gizlilik politikasına tabidir. Uygulama son tahmini cihazında 3 saate kadar kullanır, bağlantı yoksa son tahmini "çevrimdışı" işaretiyle gösterir.

Konumun kullanılıp kullanılmayacağına sen karar verirsin. iPhone'da uygulama yalnız yaklaşık konum ister; Android'de yalnız yaklaşık (kaba) konum izni ister. Konuma izin vermezsen şehir seçebilirsin.

**Satın almalar (App Store, Google Play).** Bugün Ne Giysem Plus, App Store ya da Google Play üzerinden satın alınır. Ödemeyi ve mağaza hesabını Apple ya da Google yönetir; Coditive'e ödeme bilgisi, ad ya da e-posta adresi ulaşmaz. Uygulama, mağaza hesabının hangi Plus ürünlerine sahip olduğunu cihazında denetler. Android'de bunun için uygulamanın parçası olan ve Google Play ile iletişim kuran Google Play Billing Library kullanılır; bu işleme Google'ın gizlilik politikası uygulanır. iPhone'da Apple'ın gizlilik politikası geçerlidir.

**Paylaşmayı seçtiklerin.** Verilerini dışa aktardığında, bir Ayna görselini paylaştığında ya da kaydettiğinde veya tanılama metnini kopyaladığında uygulama dosyayı ya da metni cihazının paylaşım sayfasına, Fotoğraflar'a veya panoya verir. Oradan nereye gideceğini sen seçersin; Coditive'e ulaşmaz. Dışa aktarmaya Ayna fotoğrafın, sen açmadıkça dahil edilmez.

Bunların dışında hiçbir şey gönderilmez. Uygulamada analitik, reklam, çökme bildirimi ya da izleme yazılımı yoktur.

## 3. İzinler

Her izin, ona ihtiyaç duyan özelliği ilk kullandığında istenir; uygulama açılırken asla. "Hayır" dersen uygulama çalışmaya devam eder.

- **Kamera**: kıyafetlerini ve Ayna için boy fotoğrafını çekmek için.
- **Fotoğraf kitaplığı**: parça eklemek için istenmez. Sistem fotoğraf seçicisi uygulamaya yalnız seçtiğin fotoğrafları verir. iPhone'da bir Ayna görselini Fotoğraflar'a kaydettiğinde "yalnız ekleme" izni istenir; uygulama kitaplığını okuyamaz.
- **Yaklaşık konum**: yukarıda anlatılan hava tahmini için.
- **Bildirimler**: isteğe bağlı sabah bildirimi için. Bildirim cihazında planlanır; bildirim sunucusu yoktur.
- **Takvim** (Plus; yalnız "Takvimden gün tipi"ni açarsan): önümüzdeki 7 günün etkinlik başlıklarına salt okunur erişim. Başlıklar cihazında iş, davet gibi bir gün tipiyle eşlenir; saklanmaz, hiçbir yere gönderilmez ve takvimine asla bir şey yazılmaz.

Ana ekran widget'ı izin gerektirmez. Widget'ta yalnız parça görselleri, sıcaklık, gün tipi ve bir gerekçe görünür; Ayna fotoğrafın asla. Ana ekranını gören widget'ı da görebilir.

## 4. Cihaz yedekleri

Cihaz yedeklemesi açıksa işletim sistemin uygulama verisini kendi yedeğine (iPhone'da iCloud Yedekleme, Android'de Google hesabına yedekleme) alabilir. Bu yedekleri Coditive değil, senin hesabın altında Apple ya da Google yönetir. Ayna fotoğraflarının bulunduğu klasör cihaz yedeklerine (Android'de cihazdan cihaza aktarıma da) dahil edilmez.

## 5. Saklama süresi ve silme

Verilerin, sen silene kadar cihazında kalır:

- **Tek bir parça, kombin ya da seyahat**: uygulamada sil.
- **Ayna fotoğrafı**: Ayna ekranının menüsünde ya da Ayarlar → Ayna fotoğrafların sayfasında "Ayna fotoğrafımı sil"e dokun (birden çok fotoğrafın varsa "Tüm Ayna fotoğraflarımı sil"e ya da tek bir fotoğrafın altındaki "Fotoğraf 2 sil" gibi düğmeye). Fotoğraf, poz noktaları ve önbellekteki görseller anında silinir.
- **Hepsi**: Ayarlar → Veri → Tüm verileri sil; parçaların, kombinlerin, Ayna fotoğrafların, geçmişin ve ayarların cihazdan silinir. Plus satın alımın mağaza hesabında kalır.
- **Uygulamayı kaldırmak** verilerini cihazdan siler (kendi cihaz yedeklerindeki kopyalar yedekleme ayarlarına göre kalır).

Coditive verilerinin kopyasını tutmadığı için bizim tarafımızda silinecek bir şey yoktur. Aboneliğini durdurmak ya da iptal etmek için App Store veya Google Play hesap ayarlarını kullan.

## 6. Çocuklar

Bugün Ne Giysem 13 yaşından küçük çocuklara yönelik değildir. Uygulama, çocuklar dahil hiç kimseden bilerek bilgi toplamaz.

## 7. Hakların

KVKK ve GDPR gibi kişisel verilerin korunması mevzuatı sana kişisel verilerine erişme, onları düzeltme, alma ve sildirme hakları tanır. Bugün Ne Giysem'de bu hakları doğrudan uygulamada kullanırsın: her şey cihazında görünür ve düzenlenebilir, Ayarlar → Veri → Verileri dışa aktar sana bir kopya verir, Tüm verileri sil hepsini siler. Coditive hiçbir sunucuda senin hakkında kişisel veri tutmaz. Sorun ya da talebin olursa yukarıdaki iletişim adresine yazabilirsin.

## 8. Değişiklikler

Uygulama bilgileri farklı biçimde işlemeye başlarsa bu politika o sürüm yayımlanmadan önce güncellenir ve üstteki tarih değişir.

Değişiklik geçmişi:
- 7 Ekim 2026: ilk sürüm (uygulama sürümü 1.0.0).
