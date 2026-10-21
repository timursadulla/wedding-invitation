# Gullola & Enes – Düğün Davetiyesi

Aydınger zarftan çıkan, kitap gibi açılan dört sayfalık dijital düğün davetiyesi.

Tek bir statik sayfadır, derleme adımı yoktur: `index.html` ve `images/` klasörü yeterlidir.

## Yerelde açmak

`index.html` dosyasını tarayıcıda açın.

## Vercel

Bu depoyu Vercel’e içe aktarın. Framework olarak “Other” seçin, build komutunu ve çıktı klasörünü boş bırakın. Site kök dizindeki `index.html` dosyasından yayınlanır.

## Müzik

Zarf açıldığında `audio/idea-12.mp3` yavaşça yükselerek çalmaya başlar ve döngüde devam eder. Sağ üstteki düğmeyle kapatılıp açılabilir. Dosya yoksa sayfa sessiz çalışır ve düğme görünmez. Başka bir parça kullanmak için dosyayı aynı adla değiştirin.

## Sayfalar

- `images/sayfa-1-kapak.jpg`: kapak
- `images/sayfa-2.jpg`: iç sol sayfa
- `images/sayfa-3.jpg`: iç sağ sayfa (program ve mekân)
- `images/sayfa-4-arka.jpg`: arka kapak

Görsellerde yazı yoktur, yalnızca çiçekler ve zemin vardır. Sayfalardaki bütün metinler (tarih, program, mekân, isimler) `index.html` içindeki `class="pt"` bloklarında gerçek yazı olarak durur; bu yüzden her ekranda keskin görünür ve oradan düzenlenir. Görseli değiştirirseniz yazısız hâlini kullanın. Tüm sayfalar aynı orandadır (yaklaşık 1 : 1,296).
