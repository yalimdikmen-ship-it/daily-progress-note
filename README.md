# YB Günlük Vizit v2.13

- Sistem yalnızca içinde bulunulan günün hasta kayıtlarını saklar.
- Uygulama açıldığında önceki günlere ait kayıtlar otomatik silinir.
- Yeni hasta kaydı yapılırken eski gün kayıtları temizlenir.
- TXT çıktısı sadece bugünkü hastaları içerir.
- Böylece localStorage ve TXT çıktısı gereksiz büyümez.
