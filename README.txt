YOĞUN BAKIM GÜNLÜK VİZİT + DAILY GOALS / AKŞAM DEVİR - v2.15 PROTOTİP

Bu prototip v2.11 günlük vizit yapısını korur. Mevcut Değerlendirme, Organ Sistemleri,
Cihazlar, Plan ve Progres bölümleri ile TXT progres çıktısı değiştirilmemiştir.

Yeni bölümler:
1) Günlük Hedefler
   - Vizitte girilen klinik bilgileri otomatik özetler.
   - Hedef, güvenlik, tetkik ve aile bilgilendirme alanlarını toplar.
   - Hasta başına A4 PDF/Yazdır çıktısı verir.
   - Tüm kayıtlı hastaları ayrı A4 sayfalar halinde tek yazdırma işine alabilir.

2) Akşam Devir
   - Kayıtlı hastalar arasından hasta yeniden açılabilir.
   - Gün içi değişiklik, beklenen sonuç, gece yapılacak, sabah tetkiki,
     Risk/Dikkat ve haber verme kriteri girilir.
   - Tüm hastalar için A4 yatay nöbet tablosu üretir.
   - Risk gösterimi renge bağlı değildir: ⚠ Risk, ! Dikkat, ✓ Stabil.

Sabah tetkik paketleri:
Kısa: Kan sayımı, CRP, Prokalsitonin.
Uzun: Kısa + Glukoz, Üre, Kreatinin, Na, K, Cl, Ca, Mg, P, AST, ALT, ALP,
GGT, Total/Direkt bilirubin, Albumin, Total protein, LDH, Ferritin.
Kan gazı ve laktat paket dışındadır.

NOT: Bu ilk prototipte veriler cihazın localStorage alanında tutulur. Çok kullanıcılı
telefon/tablet paylaşımı henüz eklenmemiştir; önce klinik iş akışı ve çıktılar test edilmelidir.


v2.14: Üst menüye Kullanım Kılavuzu düğmesi ve uygulama içi kullanım açıklamaları eklendi. Günlük vizit/progres yapısı değiştirilmedi.


v2.15: Günlük Hedefler ve Akşam Devir çıktı ekranlarına “Uygulamaya Dön / Kapat” ve “PDF / Yazdır” düğmeleri eklendi. PWA/standalone modunda çıktıdan uygulamaya dönüş sorunu giderildi.
