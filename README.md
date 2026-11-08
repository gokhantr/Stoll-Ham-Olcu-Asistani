# 📏 Stoll Ham Ölçü Asistanı

[![Sürüm](https://img.shields.io/badge/S%C3%BCr%C3%BCm-v1.2-0284C7.svg?style=for-the-badge&logo=github)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(x86%20%2F%20x64)-1E293B.svg?style=for-the-badge&logo=windows)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
[![M1plus](https://img.shields.io/badge/Stoll%20M1plus-v7.x%20%2F%20v8.x%20Uyumlu-6366F1.svg?style=for-the-badge)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)
[![Lisans](https://img.shields.io/badge/Lisans-%C3%9ccretsiz%20%2F%20Sekt%C3%B6r-16A34A.svg?style=for-the-badge)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)

**Stoll Ham Ölçü Asistanı**, triko desinatörleri ve teknik ekiplerin ham ölçü iş akışlarını hızlandırmak amacıyla **Gökhan Yücel** tarafından geliştirilmiş bağımsız bir masaüstü yazılımıdır; triko sektörünün **ücretsiz ve sınırsız** kullanımına sunulmuştur.

Stoll M1plus Fully Fashion örgü desenlerindeki (`.mdv`) ve makineye yüklenen desen paketlerindeki (`.zip`) ham ölçüleri (**Setup2** `_COMMENT-DATA_`) milisaniyeler içinde okur, model matrisinde düzenlemenizi sağlar, örgü makinelerinin ekranında görünecek resmi formatta işler ve M1plus motoru üzerinden **Sintral (F11)** derlemesini otomatik tamamlar.

---

## 🚀 Doğrudan İndirme

En son güncel ve kararlı sürümü aşağıdaki bağlantıdan hemen indirebilirsiniz:

👉 **[Stoll Ham Ölçü Asistanı v1.2 - Son Sürümü İndir](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)**

> 💡 **Kurulum Gerektirmez:** İndirdiğiniz `Stoll Ham Ölçü Asistanı.exe` dosyasını doğrudan masaüstünüze veya flash diskinize alıp çalıştırabilirsiniz. Bağımsız ve taşınabilir (portable) mimariye sahiptir.

---

## 🌟 v1.2 Sürümü ile Gelen Yenilikler

* 🎯 **Yenilenen Hizalı Matris Tasarımı:** Değer kutuları üzerindeki gereksiz ölçü isimleri kaldırılarak sadeleştirildi. Soldaki parça kontrol kartı ile sağdaki beden değer kutuları piksel piksel aynı yüksekliğe hizalandı.
* 🏷️ **Kaymayan "Eski Değer" Rozeti:** Hücre değeri değiştirildiğinde `Eski: X` etiketi kutunun sağ üst köşesinde zarifçe yer alır; kutu yüksekliğini bozmaz ve satır kayması yaşatmaz.
* ⚡ **Kompakt Parça Araç Çubuğu:** `+ Yeni Ölçü Ekle` ve `🗑️ Temizle` aksiyonları parça başlığının hemen sağına şık ikon butonlar olarak entegre edildi.
* ⌨️ **Hızlı Veri Girişi & Enter Desteği:** Yeni ölçü ekleme ve adlandırma pencerelerinde `Enter` tuşuna basıldığında anında ekleme/kaydetme yapılır; metin kutusu tertemiz ve odağı hazır açılır.
* 🖱️ **Ergonomik Sağ Tık Menüsü:** Değer kutularında sağ tık menüsü yeniden düzenlendi. En üste **"➡️ Bu Değeri Tüm Bedenlere Uygula (Ctrl+Enter)"** ve **"🔒 Bu Ölçüyü Sabitle"** taşındı; kopyala/yapıştır seçenekleri menünün alt kısmına alındı.
* 📦 **İşlem Sonrası Otomatik Extract Tercihi:** Ayarlar menüsüne ve işlem onay penceresine *"İşle / Derle Sonrası Extract Yap (Makine Paketi Üret)"* seçeneği eklendi. M1plus derlemesi biter bitmez otomatik makine paketi (`.zip`) oluşturulabilir.
* 🖨️ **Kusursuz A4 Föy Yazdırma & Vektörel PDF:** Yazdırma önizlemesi yukarıya hizalandı, sayfa taşmaları giderildi. Föyün en altına resmi ve ortalı `Stoll Ham Ölçü Asistanı programı tarafından hazırlanmıştır.` bilgilendirme dipnotu eklendi.
* 📜 **MDV Klasörüne Otomatik Rapor Dosyası:** İşlem tamamlandığında hem merkezi sistem loguna hem de MDV'lerin bulunduğu dizine otomatik olarak `[Model]_Ham_Olcu_Raporu.log` dosyası yazılır. Değiştirilen desenler `[DEĞİŞTİRİLDİ]`, dokunulmayanlar `[AYNI BIRAKILDI]` ibaresiyle net şekilde listelenir.
* 🖥️ **Pencere Boyutu ve Tam Ekran Hafızası:** Programın tam ekran açılıp kapatılması veya küçültülmesi durumunda son pencere boyutları ve koordinatları (`RestoreBounds`) güvenle saklanır.

---

## ✨ Temel Yetenekler

### 🎛️ 1. Dinamik Model ve Beden Matrisi
- **Akıllı Beden Tanıma:** Bebek/çocuk yaşları (`0-1`, `1-2` ... `15-16`), konfeksiyon bedenleri (`34`, `36`, `38` ... `60`), harf bedenler (`XS`, `S`, `M`, `L`, `XL`, `2XL`, `3XL`) ve `T1`–`T10` serisini kusursuz şekilde sıralar.
- **Çoklu Beden ve Ortak Parça Bağlantısı:** Tek kalıptan üretilen çoklu bedenli parçaları (`YAKA 36-38-40` veya `38-40`) ana beden sütunlarıyla zekice eşleştirir.
- **Hızlı Gezinme & Güvenlik:** Hücreler arasında `Enter` veya `Yön Tuşları` ile seri gezinebilirsiniz. Mouse tekerleğiyle sayfa kaydırırken yanlışlıkla sayıların değişmesi engellenmiştir.

### 🔒 2. Akıllı Sabitleme (Kilit) & Eşitleme
- Bir ölçünün (örneğin Kol Lastiği veya Yaka Eni) tüm bedenlerde aynı kalması gerekiyorsa tek tıkla kilitleyin (`🔒 Sabitle`).
- Kilitli ölçülerde bir bedeni güncellediğinizde veya `+` / `−` butonlarıyla 0.5 cm adımladığınızda tüm bedenler otomatik eşitlenir.
- Yüklenen desenlerde zaten tüm bedenleri aynı olan ölçüler sistem tarafından otomatik kilitli algılanır.

### 💬 3. Özelleştirilebilir Makine Yorum Şablonu
- Örgü makinelerinin ekranında (`CMS / ADF / TC`) görünen ham ölçü metnini serbestçe tasarlayın.
- `{DESEN_ADI}`, `{TARIH}`, `{BOY}`, `{LASTİK}` ve `{OLCULER}` etiketleri ile tek satır veya çok satırlı düzen kurabilirsiniz.
- Düzenleme penceresindeki canlı makine ekranı simülatöründe metnin makinede tam olarak nasıl çıkacağını anında görün.

### ⚙️ 4. Otonom M1plus & Sintral (F11) Derleme
- Yapılan değişiklikleri hem `.mdv` hem de `.zip` içindeki Setup2 XML akışlarına güvenle enjekte eder.
- M1plus GUI oturumunu otonom yönetir; deseni açar, `F11` tuşuyla Sintral derlemesini başlatır ve tamamlanınca kaydeder.
- **HWND Koruması:** Kullanıcının M1plus'ta açık olan şahsi diğer çalışmalarına dokunmaz; yalnızca işlenen deseni güvenle derleyip kapatır.

### 📄 5. Ham Ölçü Föyü Yazdırma & PDF Raporu
- Atölye, kesimhane ve kalite kontrol ekipleri için standart A4 ham ölçü föyü çıktısı verir.
- Tek tıkla doğrudan yazıcıya gönderebilir (`Yazdır`) veya bilgisayarınıza yüksek kaliteli vektörel PDF olarak kaydedebilirsiniz (`PDF İndir`).

### 🛡️ 6. Çift Taraflı Senkronizasyon (ZIP & MDV)
- Makineden USB ile alınan ZIP paketi yüklendiğinde, bilgisayarınızdaki arşiv MDV desenleri toplu seçtirilir; hem flash bellekteki makine paketi hem de arşiviniz aynı anda güncellenir.

---

## 📖 Hızlı Kullanım (3 Adımda)

```
1. SÜRÜKLE & BIRAK  ──>  2. ÖLÇÜLERİ GİR / KİLİTLE  ──>  3. İŞLE VE DERLE (F11)
  (.mdv veya .zip)         (Yeşil Vurgulu Takip)             (M1plus Otonom Derleme)
```

1. **Desenleri Yükleyin:** Tek tek dosyaları veya desenlerin bulunduğu klasörü doğrudan programa sürükleyin.
2. **Ölçüleri Kontrol Edin / Güncelleyin:** Matristeki kutucuklara değerleri yazın. Değeri değişen kutular yeşil renkle vurgulanır ve `Eski: X` değeri gösterilir.
3. **Föy Alın veya Derleyin:**
   - İsterseniz atölye için `📄 Föy / PDF Yazdır` butonuna basın.
   - `Ham Ölçüleri İşle ve Sintral Derle (F11)` butonuna tıklayın; M1plus arkada derlemeyi otomatik tamamlayacaktır.

---

## 🛠️ Sistem Gereksinimleri

* **İşletim Sistemi:** Windows 10, Windows 11 (32-bit & 64-bit)
* **Stoll Yazılımı:** Stoll M1plus (M1plus 7.x ve 8.x sürümleriyle tam uyumlu)
* **Web Motoru:** Microsoft Edge WebView2 (Windows 10 ve 11 ile yerleşik gelir)
* **Ek Yazılım:** Python veya başka bir kütüphane kurulumu gerektirmez.

---

## 📝 Sürüm Geçmişi

### 🔹 v1.2 (Güncel Sürüm)
- **Tasarım İyileştirmeleri:** Değer kutuları üzerindeki isimler sadeleştirildi; sol parça kutusu ile değer hücreleri eşit hizalandı.
- **Kompakt Parça Araç Çubuğu:** Yeni ölçü ekleme ve parça temizleme aksiyonları parça başlığına şık ikonlar olarak eklendi.
- **Klavye & Modal Ergonomisi:** Yeni ölçü ekleme ve düzenleme modallarında `Enter` tuşuyla anında kaydetme; boş açılan metin kutusu.
- **Sağ Tık Menü Optimizasyonu:** "Tüm Bedenlere Uygula" ve "Sabitle" en üste taşındı.
- **Yazdırma İyileştirmesi:** Föy sayfası yukarıya hizalandı; dipnot bilgisi eklendi; taşmalar önlendi.
- **Otomatik Extract Ayarı:** Ayarlar'a ve işlem onay modalına *"İşle Sonrası Extract Yap"* seçeneği eklendi.
- **Klasör İçi Model Logu:** MDV dizinine `[Model]_Ham_Olcu_Raporu.log` dosyası üretimi ve satır sonu durum etiketleri.
- **Pencere Hafızası:** Normal/Tam ekran modları ve küçültülmüş pencere sınırları (`RestoreBounds`) korundu.

### 🔹 v1.1
- İki dilli arayüz altyapısı (Türkçe / English).
- Çocuk, bebek ve konfeksiyon bedenleri için gelişmiş akıllı sıralama kuralları.
- HWND korumalı M1plus otomasyonu ve büyük desenlerde geciken onay pencerelerini otonom karşılama.

### 🔹 v1.0
- İlk kararlı sürüm; PyWebView + Edge Chromium tabanlı taşınabilir mimari.
- Setup2 XML ham ölçü ayrıştırma ve enjeksiyon motoru.
- Canlı önizlemeli yorum şablonu yöneticisi.

---

## 👨‍💻 Geliştirici & Lisans

* **Geliştirici:** Gökhan Yücel
* **GitHub Repository:** [https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)
* **Destek & İletişim:** GitHub Issues üzerinden soru, öneri ve hata bildirimlerinizi iletebilirsiniz.
* **Lisans:** Triko sektörünün ve desinatörlerin ücretsiz ve sınırsız kullanımına sunulmuştur.
