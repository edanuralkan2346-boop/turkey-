📺 IPTV Nedir?

IPTV (Internet Protocol Television), televizyon yayınlarını uydu, anten veya kablo yerine internet üzerinden izlemene yarayan bir sistemdir.

Yani:

TRT 1, Show TV, Bein Sports gibi kanalları uydu kablosuna gerek kalmadan — internet bağlantısı üzerinden — canlı olarak izleyebilirsin.

⚙️ IPTV Nasıl Çalışır?

IPTV, sana bir M3U veya M3U8 uzantılı yayın listesi verir.
Bu liste, TV kanallarının yayın adreslerini içerir.

Örneğin:

#EXTM3U
#EXTINF:-1 tvg-name="TRT 1" group-title="Ulusal", TRT 1
https://orneklink.com/trt1/playlist.m3u8


Bu linkleri IPTV oynatıcı bir uygulamaya yüklersin ve kanalları izlersin.

📱💻 IPTV Nasıl Kullanılır?

Kullandığın cihaza göre yöntem değişir 👇

🖥️ Bilgisayarda:

VLC Media Player indir (ücretsiz).

Üst menüden “Ortam > Ağ Akışı Aç” seçeneğine tıkla.

IPTV M3U linkini yapıştır → Oynat → kanallar açılır.

📱 Android Telefon / Tablet:

Google Play’den şu uygulamalardan birini indir:

TiviMate

IPTV Smarters Pro

GSE Smart IPTV

Uygulamayı aç → “M3U URL” kısmına IPTV linkini yapıştır → Kaydet → İzle.

📺 Android TV / Smart TV:

TV’nin uygulama mağazasından (Google Play / App Store):

TiviMate

Smart IPTV

IPTV Smarters Pro
indir.

M3U linkini gir ve kanalları izle.

💡 Örnek M3U Linki:
https://raw.githubusercontent.com/kullaniciadi/iptv/main/turkey.m3u
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔗 GitHub’da M3U dosyası için çalışır bağlantı (RAW link) alma

GitHub’da kendi M3U dosyana git (örnek:
https://github.com/kullaniciadi/myiptvlist/blob/main/playlist.m3u)

Dosya sayfasında sağ üstte “Raw” yazan bir buton göreceksin.
🔹 Ona tıkla.

Tarayıcıda dosya sade metin olarak açılacak.
Adres çubuğundaki link senin gerçek M3U linkindir.

🔹 O genelde şu şekilde olur:

https://raw.githubusercontent.com/kullaniciadi/myiptvlist/main/playlist.m3u


İşte bu linki IPTV uygulamana (örneğin TiviMate, IPTV Smarters Pro vs.) yapıştırırsan,
artık senin GitHub’daki listedeki kanalları gösterir! ✅

💡 Ek ipucu:

Eğer dosyayı güncellersen (örneğin yeni kanal eklersen),
aynı “raw” link otomatik olarak güncellenir.
Yani IPTV uygulamasında linki tekrar değiştirmen gerekmez 💪
