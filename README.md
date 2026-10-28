# 📏 Stoll Ham Ölçü Asistanı

[![Sürüm](https://img.shields.io/badge/S%C3%BCr%C3%BCm-v1.0-0284C7.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%20(x86%20%2F%20x64)-1E293B.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)
[![Lisans](https://img.shields.io/badge/Lisans-%C3%9ccretsiz%20%2F%20Sekt%C3%B6r-16A34A.svg)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)

**Stoll Ham Ölçü Asistanı**, triko desinatörleri ve teknisyenlerinin ham ölçü iş akışlarını hızlandırmak amacıyla **Gökhan Yücel** tarafından geliştirilmiş olup, sektörün ücretsiz ve sınırsız kullanımına sunulmuştur.

Stoll M1plus Fully Fashion örgü desenlerinde (`.mdv`) ve makineye yüklenen desen paketlerinde (`.zip`) bulunan ham ölçüleri (**Setup2** `_COMMENT-DATA_`) milisaniyeler içinde okur, dinamik bir model matrisinde düzenlemenize imkân tanır, makinede deseni açan örgücünün doğrudan göreceği formatta işler ve M1plus motoru ile **Sintral (F11)** derlemesini otomatik tamamlar.

---

## 🚀 Doğrudan İndirme

En son güncel sürümü aşağıdaki bağlantıdan hemen indirebilirsiniz:

👉 **[Stoll Ham Ölçü Asistanı - En Son Sürümü İndir (v1.0)](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani/releases/latest)**

*Kurulum gerektirmez. İndirdiğiniz `Stoll_Ham_Olcu_Isleyici.exe` dosyasını doğrudan çalıştırabilirsiniz.*

---

## ✨ Temel Özellikler

- ⚡ **Otomatik Parça, Beden ve Ölçü Tespiti:**
  - Tek tek dosya veya klasör sürükleyip bırakarak desenleri anında yükleyin.
  - Ön, Arka, Kol, Yaka, Biye gibi parçaları ve tüm bedenleri (36, 38, 40, S, M, L vb.) akıllı hiyerarşik sıralamayla matrise yerleştirir.
  - Setup2 XML dosyasındaki kayıtlı yorum satırlarından ham ölçüleri (Boy, Lastik, En vb.) regex ile otomatik ayrıştırır.

- 🎛️ **Gelişmiş Model Ham Ölçü Matrisi:**
  - Enine taşma yapmayan, dikey akışlı, yüksek okunabilirliğe sahip kutu tasarımı.
  - **Değişiklik Vurgusu (Eski Değer Takibi):** Sadece değeri değiştirilen hücrelerde `Eski: X` etiketi ve yeşil renk vurgusu gösterilir; dokunulmayan değerler sade kalır.
  - **Hızlı Gezinme:** Hücreler arasında `Enter` veya `Ok Tuşları` ile zahmetsizce dolaşın.
  - **Tekerlek Koruması:** Mouse scroll tekerleğiyle gezinirken yanlışlıkla sayıların değişmesi kesinlikle engellenmiştir.

- 🔒 **Akıllı Sabitleme (Kilit) & Eşitleme:**
  - Bir ölçünün (örneğin Kol Lastiği) tüm bedenlerde aynı kalması gerekiyorsa tek tıkla kilitleyin (`🔒 Sabit`).
  - Herhangi bir bedeni değiştirdiğinizde veya `+` / `−` butonlarına bastığınızda tüm bedenler otomatik senkronize olur.
  - Desen ilk açıldığında tüm bedenlerde aynı değere sahip ölçüler otomatik kilitli olarak algılanır.

- ✏️ **Dinamik Ölçü Yönetimi (Ekle, Düzenle, Sil):**
  - Parçaya özel yeni ölçü ekleyin (En, Yaka Düşüklüğü, Reglan Boyu vb.).
  - Kalem (`✏️`) butonuyla ölçü isimlerini doğrudan yeniden adlandırın.
  - `+` ve `−` butonlarıyla mevcut tablodaki değerleri 0.5 cm hassasiyetle toplu artırıp azaltın.

- 💬 **Özelleştirilebilir Makine Yorum Şablonu:**
  - Örgü makinelerinin ekranında görünen ham ölçü metninin formatını serbestçe belirleyin.
  - `{DESEN_ADI}`, `{TARIH}`, `{OLCULER}` değişkenlerinin yanı sıra `{BOY}`, `{LASTİK}` veya `{OLCU_1}`, `{OLCU_2}` gibi özel etiketleri kullanarak yan yana veya satır satır yerleşim oluşturun.
  - Canlı önizleme kutusunda makine ekranında nasıl görüneceğini anında izleyin.

- ⚙️ **M1plus Otomasyonu & Sintral (F11) Derleme:**
  - Güncellenen ham ölçüleri hem MDV hem de ZIP içindeki Setup dosyalarına yazar.
  - M1plus GUI oturumu üzerinden deseni açar, `F11` Sintral derlemesini çalıştırır ve desen parametrelerini kaydeder.
  - Süreç boyunca detaylı konsol terminali ve ilerleme çubuğu ile her adım raporlanır.

- 📄 **Ham Ölçü Föyü Yazdırma & Vektörel PDF İndirme:**
  - Model adına göre hazırlanan şık teknik ham ölçü föyünü anında görüntüleyin.
  - Tabloya girilen en güncel değerleri yansıtır.
  - Tek tıkla doğrudan yazıcıya gönderin (`Yazdır`) veya bilgisayarınıza PDF olarak kaydedin (`PDF İndir`).

- 🛡️ **ZIP & MDV Ayrımı ve Güvenlik Koruması:**
  - Makineden alınan ZIP desenlerinin orijinal makine ayarları korunur; ZIP kaynaklı dosyalarda `ExtractSendTo` çalıştırılarak ayarların ezilmesi önlenir.
  - ZIP yüklendiğinde bilgisayardaki orijinal MDV dosyaları toplu olarak seçtirilir; hem flash diskteki ZIP hem de arşivdeki MDV senkronize güncellenir.

- 💾 **Ayar Yedekleme (İçe / Dışa Aktarma):**
  - M1plus dizin yolu ve makine yorum şablonunu tek tıkla `.json` dosyası olarak yedekleyin veya başka bilgisayarlara aktarın.

- 🔄 **Entegre GitHub Sürüm Denetimi:**
  - Yeni bir sürüm çıktığında üst bantta bildirim rozeti çıkar ve tek tıkla indirme bağlantısını açar.

---

## 🛠️ Sistem Gereksinimleri

- **İşletim Sistemi:** Windows 10, Windows 11 (32-bit & 64-bit)
- **Stoll Yazılımı:** Stoll M1plus (M1plus 7.x, 8.x sürümleriyle tam uyumlu)
- **Çalışma Zamanı:** Ekstra kurulum veya Python ortamı gerektirmez (Tek parça taşınabilir `.exe`)

---

## 📖 Kullanım Kılavuzu

1. **Desenleri Yükleyin:**
   - `.mdv` veya makine `.zip` dosyalarını pencereye sürükleyip bırakın.
   - Program otomatik olarak model adını, parçaları (Ön, Arka vb.) ve bedenleri matrise döker.
2. **Ham Ölçüleri Düzenleyin:**
   - Hücrelere güncel ham ölçüleri yazın. Değeri değişen kutular yeşil yanar ve eski değerleri gösterir.
   - Tüm bedenleri senkronize etmek için `🔒` butonunu kullanın.
   - İhtiyaca göre `+` / `−` adımlama butonlarıyla hızlıca 0.5 cm ayarlama yapın.
3. **Föy Alın veya İşleyin:**
   - İsterseniz `Föy / PDF Yazdır` butonuna basarak atölye için ham ölçü tablosunu yazdırın veya PDF olarak indirin.
   - `Ham Ölçüleri İşle ve Sintral Derle (F11)` butonuna basın.
   - Onay kutusundan sonra işlem başlar; Setup dosyaları yazılır, M1plus açılarak F11 derlemesi yapılır ve desenler kullanıma hazır hale gelir.

---

## 📝 Sürüm Geçmişi

### v1.0 (İlk Kararlı Sürüm - Official Release)
- Tek parça portable `.exe` mimarisi (PyWebView + Edge Chromium motoru).
- Dinamik parça ve beden matrisi, akıllı sıralama (Ön, Arka, Kol, Yaka, Aksesuarlar).
- Otomatik kilit algılama ve senkronize beden eşitleme.
- Canlı önizlemeli yorum şablonu düzenleyicisi (Özel değişken etiketleri desteği).
- İstemci taraflı vektörel PDF dışa aktarma (`html2canvas` + `jsPDF`).
- Ayarları İçe / Dışa Aktarma (`.json`).
- GitHub API entegrasyonlu canlı sürüm güncelleme denetimi.

---

## 👨‍💻 Geliştirici & Lisans

- **Geliştirici:** Gökhan Yücel
- **GitHub Reposu:** [https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani](https://github.com/gokhantr/Stoll-Ham-Olcu-Asistani)
- **Lisans:** Triko sektörünün ücretsiz ve sınırsız kullanımına sunulmuştur.

