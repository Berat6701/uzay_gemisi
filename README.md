# 🚀 Uzay Gemisi Kontrol Paneli (Spacecraft Control Panel)

Bu proje, HTML, CSS ve JavaScript kullanılarak geliştirilmiş 3 sayfadan oluşan etkileşimli bir web panelidir. 11. Sınıf Web Tabanlı Uygulama Geliştirme dersi kapsamında temel DOM manipülasyonu, olaylar (events), karar yapıları (if-else, switch-case) ve fonksiyon kullanımını uygulamak amacıyla tasarlanmıştır.

---

## 🛠️ Proje Özellikleri ve Sayfalar

Proje 3 temel modülden oluşmaktadır:

1. **Giriş Ekranı (`index.html`):**
   * Şifre korumalı güvenlik kapısı simülasyonudur.
   * `if-else` yapısı ile şifre (`2025`) kontrolü yapılır.
   * Doğru şifre girildiğinde sistem menüsü dinami olarak görünür hale gelir.

2. **Sistem Kontrolü (`kontrol.html`):**
   * Uzay gemisinin kalkanlarını yönetmeye yarar.
   * Parametreli JavaScript fonksiyonları (`kalkanYonet('ac')` / `kalkanYonet('kapat')`) kullanılarak durum güncellenir.
   * Kalkan durumuna göre CSS sınıfları (`className`) değiştirilerek anlık görsel tepki verilir.

3. **Personel Verileri (`personel.html`):**
   * Gemideki personeller için günlük oksijen tüketimi hesaplayıcısıdır.
   * `switch-case` yapısı kullanılarak rütbeye göre (Kaptan, Mühendis, Bilim İnsanı) farklı matematiksel hesaplamalar gerçekleştirilir.

---

## 📁 Klasör Yapısı

```text
uzay_gemisi/
│
├── css/
│   └── style.css       # Terminal/Hacker temalı özel CSS tasarımları
├── js/
│   └── app.js          # Projenin mantık ve DOM fonksiyonları
├── index.html          # Şifreli Giriş Ekranı
├── kontrol.html        # Kalkan Yönetim Paneli
└── personel.html       # Oksijen Hesaplama Ekranı
