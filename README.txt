YOĞUN BAKIM GÜNLÜK VİZİT + DAILY GOALS / AKŞAM DEVİR - v2.17 PROTOTİP

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

Ertesi gün tetkik paketleri:
Kısa: Kan sayımı, CRP, Prokalsitonin.
Uzun = Kısa +
- İnflamasyon: Ferritin
- Koagülasyon: Protrombin zamanı (PT), INR, Protrombin aktivitesi, aPTT, Fibrinojen, D-dimer
- Böbrek/metabolik: Üre, Kreatinin, Ürik asit
- Elektrolit/mineral: Sodyum, Potasyum, Klor, Kalsiyum, Magnezyum, Fosfor
- Karaciğer/protein: AST, ALT, Total bilirubin, Direkt bilirubin, Total protein, Albümin
- Doku/kas: LDH, CK, CK-MB

NOT: Bu ilk prototipte veriler cihazın localStorage alanında tutulur. Çok kullanıcılı
telefon/tablet paylaşımı henüz eklenmemiştir; önce klinik iş akışı ve çıktılar test edilmelidir.


v2.14: Üst menüye Kullanım Kılavuzu düğmesi ve uygulama içi kullanım açıklamaları eklendi. Günlük vizit/progres yapısı değiştirilmedi.


v2.15: Günlük Hedefler ve Akşam Devir çıktı ekranlarına “Uygulamaya Dön / Kapat” ve “PDF / Yazdır” düğmeleri eklendi. PWA/standalone modunda çıktıdan uygulamaya dönüş sorunu giderildi.


v2.16: Günlük Hedefler ve Akşam Devir çıktıları artık yeni pencere açmaz. Uygulamanın üzerinde kapatılabilir önizleme katmanı olarak açılır; Kapat düğmesi ana uygulamaya anında döner.


v2.17: Uzun ertesi gün tetkik paketi kurumun yüklenen tetkik listesine göre yeniden sıralandı. Kısa pakette bulunan Kan sayımı, CRP ve Prokalsitonin Uzun listede tekrarlanmaz; “Uzun = Kısa +” olarak gösterilir. Kan gazı çıkarıldı.
