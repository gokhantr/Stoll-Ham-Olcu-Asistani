# 📏 Stoll Ham Ölçü Asistanı

[![Sürüm](https://img.shields.io/badge/S%C3%BCr%C3%BCm-v1.0-0284C7.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%20(x86%20%2F%20x64)-1E293B.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
[![Dil](https://img.shields.io/badge/Dil-T%C3%BCrk%C3%A7e%20%2F%20English-F59E0B.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)
[![Lisans](https://img.shields.io/badge/Lisans-%C3%9ccretsiz%20%2F%20Sekt%C3%B6r-16A34A.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)

**Stoll Ham Ölçü Asistanı**, triko desinatörleri ve teknisyenlerinin ham ölçü iş akışlarını hızlandırmak amacıyla **Gökhan Yücel** tarafından geliştirilmiş olup, sektörün ücretsiz ve sınırsız kullanımına sunulmuştur.

Stoll M1plus Fully Fashion örgü desenlerinde (`.mdv`) ve makineye yüklenen desen paketlerinde (`.zip`) bulunan ham ölçüleri (**Setup2** `_COMMENT-DATA_`) milisaniyeler içinde okur, akıllı model matrisinde düzenlemenize imkân tanır, makinede deseni açan operatörün doğrudan göreceği resmi formata dönüştürür ve M1plus motoru ile **Sintral (F11)** derlemesini otomatik tamamlar.

---

## 🚀 Doğrudan İndirme

En son güncel sürümü aşağıdaki bağlantıdan hemen indirebilirsiniz:

👉 **[Stoll Ham Ölçü Asistanı - En Son Sürümü İndir (v1.0)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)**

*Kurulum gerektirmez. İndirdiğiniz `Stoll_Ham_Olcu_Isleyici.exe` dosyasını doğrudan çalıştırabilirsiniz.*

---

## ✨ Temel Özellikler

- 🌐 **İki Dilli Arayüz (Türkçe & English):**
  - İşletim sisteminizin dilini otomatik algılar (Türkçe veya İngilizce).
  - Ayarlar menüsünden tek tıkla dil değişimi yapılabilir.

- 🧵 **Makineden Doğrudan Okuma & Akıllı Ayraç Desteği:**
  - Stoll makinesinin Setup ekranında operatörlerin pratikçe yazdığı tüm formatları tanır:
    * `55-5,5` *(Tire)*
    * `55 5,5` *(Boşluk)*
    * `55/5,5` *(Bölü)*
    * `55x5,5` / `55X5,5` *(Çarpı / X)*
    * `55\5,5` *(Ters Slash)*
    * `55=5,5` *(Eşittir)*
    * `55` *(Enter)* `5,5` *(Alt satır)*
    * `BOY 58 LASTİK 5` veya `CEP AÇIKLIĞI 16.5` *(Etiketli)*
  - İşle butonuna basıldığında tüm ölçüler resmi Stoll Setup2 şablonuna otomatik standartlaştırılır.

- 🎛️ **Akıllı Model & Beden Matrisi:**
  - Tek hamlede sürükle-bırak ile ön, arka, kol, yaka parçalarını ve tüm bedenleri (XS, S, M, L, XL vb.) listeler.
  - `L-XL`, `XS_S` gibi ortak bedenli veya `MODEL1-YAKA` gibi bedensiz parçalar fazladan sütun açmaz; ilgili bedenlere otomatik paylaştırılır ve değerleri birbirine bağlanır.

- 🔒 **Kilitli Ölçüler & Canlı Eşitleme:**
  - Kilit (🔒) simgesiyle lastik, en veya ortak parça ölçülerini seriye kilitleyin.
  - Bir bedende yaptığınız değişiklik tüm serideki değerlere anında canlı yansır.
  - Fare tekerleğiyle gezinirken yanlışlıkla sayıların değişmesi kesinlikle engellenmiştir.

- 🖱️ **Sağ Tık Menüsü & Hızlı Gezinme:**
  - Hücreler arasında `Enter` veya `Yön Okları` ile seri gezinebilirsiniz.
  - Sağ tık menüsüyle *"Bu Değeri Tüm Bedenlere Uygula"*, *"Kopyala"* ve *"Yapıştır"* yapabilirsiniz.

- ⚙️ **Hızlı M1plus Enjeksiyonu & F11 Sintral Derleme:**
  - **Hızlı Mod (Varsayılan):** Sadece ölçüsü değişen desenleri derleyerek büyük modellerde maksimum zaman kazandırır.
  - Arka planda güvenli M1plus oturumu yönetimi ve Sintral (F11) derlemesi.

- 📄 **Ham Ölçü Föyü Yazdırma & PDF Çıktısı:**
  - Kesimhane, triko ustası ve kalite kontrol için tertemiz, resmi bir A4 ölçü tablosu çıktısı veya PDF indirme imkânı.

- ❓ **Dahili Kullanım Kılavuzu (F1):**
  - Klavyeden `F1` tuşuyla veya üst bardaki `Yardım` butonuyla açılan pratik kullanım kılavuzu.

---

## 🛠️ Sistem Gereksinimleri

- **İşletim Sistemi:** Windows 10, Windows 11 (32-bit & 64-bit)
- **Stoll Yazılımı:** Stoll M1plus (7.x, 8.x sürümleriyle tam uyumlu)
- **Çalışma Şekli:** Ekstra kurulum veya Python ortamı gerektirmez (Tek parça taşınabilir `.exe`)

---

## 📖 Hızlı Kullanım Adımları

1. **Desenleri Yükleyin:** `.mdv` veya makine `.zip` dosyalarını pencereye sürükleyip bırakın.
2. **Ölçüleri Düzenleyin:** Matristeki kutulara güncel ölçüleri girin. Gerekirse kilit simgesiyle ölçüleri seriye sabitleyin.
3. **Föy Alın veya İşleyin:** 
   - İsterseniz `Föy / PDF Yazdır` butonuyla föy alın.
   - `Ham Ölçüleri İşle ve Sintral Derle (F11)` butonuna basarak M1plus derlemesini başlatın.

---

## 👨‍💻 Geliştirici & Lisans

- **Geliştirici:** Gökhan Yücel
- **GitHub Reposu:** [https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)
- **Lisans:** Triko sektörünün ücretsiz ve sınırsız kullanımına sunulmuştur.
