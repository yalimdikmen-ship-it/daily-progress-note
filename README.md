# Yoğun Bakım Günlük Vizit ve Progres Sistemi — v2.6

## GitHub Pages ile deneme

1. GitHub'da yeni bir repository oluşturun.
2. Bu ZIP içindeki dosyaları repository'nin kök dizinine yükleyin:
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
3. Repository > Settings > Pages bölümüne gidin.
4. Source olarak **Deploy from a branch** seçin.
5. Branch: **main**, Folder: **/(root)** seçin ve Save'e basın.
6. GitHub Pages adresi açıldığında uygulamayı test edin.
7. iPhone/iPad Safari'de Paylaş > Ana Ekrana Ekle ile PWA olarak kurabilirsiniz.
8. Android Chrome'da menü > Ana ekrana ekle / Uygulamayı yükle seçeneğini kullanabilirsiniz.

Not: Service worker nedeniyle yeni sürüm yükledikten sonra eski sürüm görünürse sayfayı birkaç kez yenileyin veya site verilerini temizleyin.


## v2.6 yenilikleri
- Organ Sistemleri alt tabları üstte ve altta tekrarlandı.
- Kalp hızı ve sistolik/diyastolik KB alanları eklendi; OAB otomatik hesaplanır.
- Karın İçi Basıncı alanı eklendi; >12 mmHg ise 4 saatte bir takip notu ve yapılacak işi otomatik oluşur.


## v2.6 yenilikleri
- Glasgow Koma Skoru E/V/M bileşenleri ayrı seçilir.
- Sayısal E/V/M mevcutsa toplam otomatik hesaplanır.
- Entübe/trakeostomili hastada verbal yanıt VT olarak gösterilir ve toplam yanlış hesaplanmaz.
- GKS progres notuna otomatik aktarılır.


## v2.6 yenilikleri
- GKS'de kullanıcı yalnızca klinik yanıtı seçer; E/V/M komponent puanları otomatik atanır.
- Toplam GKS otomatik hesaplanır.
- Entübe/trakeostomili hastada verbal komponent VT olarak gösterilir ve yanlış toplam puan üretilmez.
