# 📏 Stoll Ham Ölçü Asistanı

[![Sürüm](https://img.shields.io/badge/S%C3%BCr%C3%BCm-v1.1-0284C7.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%20(x86%20%2F%20x64)-1E293B.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
[![Dil](https://img.shields.io/badge/Dil-T%C3%BCrk%C3%A7e%20%2F%20English-F59E0B.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)
[![Lisans](https://img.shields.io/badge/Lisans-%C3%9ccretsiz%20%2F%20Sekt%C3%B6r-16A34A.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)

**Stoll Ham Ölçü Asistanı**, triko desinatörleri ve teknik ekipler için geliştirilmiş, Stoll M1plus Fully Fashion desenlerinde (`.mdv`) ve makine paketlerinde (`.zip`) ham ölçü yönetimini otomatikleştiren bağımsız masaüstü yazılımıdır.

---

## 🚀 Doğrudan İndirme

En güncel sürümü aşağıdaki bağlantıdan hemen indirebilirsiniz:

👉 **[Stoll Ham Ölçü Asistanı - En Son Sürümü İndir (v1.1)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)**

*Kurulum gerektirmez. İndirdiğiniz `Stoll Ham Ölçü Asistanı.exe` dosyasını doğrudan çalıştırabilirsiniz.*

---

## ⚡ Temel Yetenekler (Özet)

* 🎛️ **Dinamik Beden & Model Matrisi:**
  * Bebek/çocuk yaş aralıkları (`0-1` ... `15-16`), tekil rakamlar (`0`...`20`), formatlı yaşlar (`1Y`...`15Y`), `T1`...`T10` serisi, konfeksiyon numaraları (`34`...`60`) ve standart harf bedenleri (`XS`...`3XL`) otomatik tanır ve sıralar.
  * Çoklu bedenli (`38-40`, `S-M`) veya ortak parçalı (`YAKA`) desenleri matriste akıllıca bağlar.

* 🧩 **Akıllı Parça Ayrıştırma:**
  * `SOL-BANT` / `SAG-BANT` gibi birleşik parçaları yutmadan ayrı satırlara açar.
  * Bitişik yazılan parçaları (`SAGKOL`, `SOLON`, `SOLBANT`), `BAND` eklerini ve aksesuar parçalarını (`TIKTAK`, `CEPKAP`, `TUPBIYE`, `ASTAR`) standartlaştırır.
  * İplik katı (`2KAT`), renk (`BEYAZ`) ve numune (`PPS`, `DNM`) notlarını operatör notuna aktarır.

* ⚙️ **Otonom M1plus Enjeksiyonu & F11 Sintral Derleme:**
  * Ham ölçüleri doğrudan Setup2 XML içine yazar.
  * M1plus oturumunda F11 ile Sintral programını derler; büyük çizimli desenlerde geç çıkan onay pencerelerini otonom yanıtlar.
  * **HWND Koruması:** Kullanıcının M1plus'ta açık olan diğer şahsi desenlerine dokunmaz, yalnızca işlenen pencereyi güvenle kapatır.

* 📄 **Ölçü Föyü & PDF Çıktısı:**
  * Triko ustası, kesimhane ve kalite kontrol için resmi A4 ham ölçü föyü baskısı ve PDF oluşturur.

* 🌐 **İki Dilli Arayüz & Kısayollar:**
  * Türkçe ve İngilizce dil desteği, pratik klavye gezinimi (`Enter`, yön tuşları) ve `F1` hızlı yardım.

---

## 🚀 Hızlı Kullanım (3 Adım)

1. **Sürükle & Bırak:** `.mdv` veya makine `.zip` dosyalarını pencereye bırakın.
2. **Ölçüleri Girin:** Beden matrisindeki ölçüleri kontrol edin veya güncelleyin (seri kilit ile tek tıkla eşitleyin).
3. **İşleyin:** **"Ham Ölçüleri İşle ve Sintral Derle"** butonuna basarak Setup2 güncellemelerini ve F11 derlemesini tamamlayın (veya doğrudan föy yazdırın).

---

## 💻 Sistem Gereksinimleri

* **İşletim Sistemi:** Windows 10 / Windows 11 (32-bit & 64-bit)
* **Stoll Uyumluluğu:** Stoll M1plus (v7.x, v8.x)

---

## 👨‍💻 Geliştirici & Lisans

* **Geliştirici:** Gökhan Yücel
* **İndirme & Kaynak:** [GitHub Releases](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
* **Lisans:** Triko sektörünün ücretsiz ve sınırsız kullanımına sunulmuştur.
