# OpenStudy: Kişiselleştirilmiş LGS Hazırlık ve Veri Analiz Platformu

OpenStudy, 8. sınıf öğrencilerinin LGS (Liselere Geçiş Sistemi) hazırlık süreçlerini dijitalleştirmek, akademik verimliliği artırmak ve sınav momentumunu takip etmek amacıyla geliştirilmiş, mobil öncelikli (mobile-first) bir Progressive Web App (PWA) çözümüdür.

Platform, standart görev yönetim araçlarından farklı olarak; odaklanma biyometrisi, akademik veri analitiği ve kullanıcı motivasyonunu tek bir entegre arayüzde birleştirir.

---

## Temel Fonksiyonlar ve Modüller

### Akademik Odaklanma Motoru (Focus Engine)
LGS sınav dinamiklerine uygun olarak kalibre edilmiş 40 dakika ders ve 10 dakika mola (40/10) protokolü üzerine inşa edilmiştir. Görsel geri bildirimli zamanlayıcı, bilişsel yükü optimize ederek dikkat dağınıklığını minimize eder.

### Veri Analitiği ve Performans Takibi
* **Otomatik Net Hesaplama:** 3 yanlışın 1 doğruyu elediği LGS standartlarına uygun algoritma ile ders bazlı net analizi.
* **Momentum Grafikleri:** Chart.js entegrasyonu ile haftalık ve aylık gelişim süreçlerinin görselleştirilmesi.

### Kültürel Entegrasyon ve Motivasyon
Öğrenci psikolojisini desteklemek adına tasarlanan "Günün Sözü" alanı; Duman grubu şarkı sözleri ve edebi alıntılar üzerinden rastgele veri çekerek kullanıcı motivasyonunu dinamik tutar.

### Yerel Veri Güvenliği (Local-First Architecture)
Kullanıcı gizliliği protokolü gereği tüm veriler tarayıcı seviyesinde (LocalStorage API) saklanır. Veriler üçüncü taraf sunuculara iletilmez, tamamen kullanıcının kontrolündeki cihazda barındırılır.

---

## Teknik Spesifikasyonlar

OpenStudy, modern web standartları ve performans odaklı kütüphaneler kullanılarak optimize edilmiştir:

* **Frontend:** HTML5, Modern CSS3
* **UI Framework:** Tailwind CSS (Atomic Design ilkeleriyle)
* **Veri Görselleştirme:** Chart.js
* **İkon Seti:** Lucide React (Web Component mimarisi)
* **Dağıtım:** PWA Standartları (Ana Ekrana Ekleme desteği)

---

## Stratejik Ürün Yol Haritası

1. **Yapay Zeka Entegrasyonu:** TCYZ altyapısı kullanılarak geliştirilen, hatalı soru paternlerine göre konu çalışma önerileri sunan Python tabanlı model desteği.
2. **Bulut Senkronizasyonu:** Cross-platform veri sürekliliği için Google Firestore entegrasyonu.
3. **Deneme Sınavı Simülasyonu:** Gerçek sınav süresi ve tüm dersleri kapsayan bütünleşik test modülü.

---

## Çalıştırma Talimatları

Proje, herhangi bir kurulum bağımlılığı (zero-dependency) gerektirmeyen bir yapıdadır.
1. `index.html` dosyasını tarayıcı üzerinde çalıştırın.
2. Mobil deneyim için tarayıcı ayarlarından "Ana Ekrana Ekle" özelliğini aktif hale getirerek yerel uygulama performansına erişin.

---

**Kurucu:** Doruk KAHRAMAN  
**Proje:** OpenStudy Ecosystem
