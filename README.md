# 📚 EPUB Metadata Editor

Tamamen tarayıcı üzerinde çalışan, sunucusuz ve hafif bir **EPUB Meta Veri ve Kapak Düzenleyicisi**. 

Herhangi bir indirme, kurulum veya sunucu işlemi gerektirmez. Dosyalarınız hiçbir sunucuya yüklenmez; tüm işlemler doğrudan bilgisayarınızdaki tarayıcıda gerçekleşir.

---

## 🚀 Özellikler

- **Temel ve Ekstra Meta Veri Düzenleme:**
  - Kitap Adı, Yazar, Yayıncı, Dil
  - ISBN / Tanımlayıcı, Yayın Tarihi
  - Kategori / Etiketler, Seri Bilgisi (`calibre:series`) ve Açıklama/Özet
- **Gelişmiş Kapak Düzenleyici:**
  - EPUB içerisindeki mevcut kapağı otomatik tespit etme ve görüntüleme.
  - Sürükle-bırak veya dosya seçimi ile kapağı yeni görsellerle (`.jpg`, `.png`, `.webp`) değiştirme.
- **EPUB 2 ➔ EPUB 3 Dönüştürücü:**
  - Eski EPUB 2 formatındaki kitapları tek tıkla EPUB 3 standartlarına yükseltme ve gerekli navigasyon dosyalarını (`nav.xhtml`) entegre etme.
- **Akıllı Dosya Adı Biçimlendirme:**
  - Düzenlenen dosyaları otomatik olarak `Yazar Adı - Kitap Adı.epub` şablonuyla indirme.
- **Güvenli ve İzolasyonlu İçerik:**
  - Kitabın metinleri, bölümleri ve HTML yapısına **kesinlikle dokunmaz**; sadece meta verileri ve kapak dosyalarını günceller.
- **%100 İstemci Taraflı (Client-side):**
  - Güvenli, hızlı ve sıfır sunucu bağımlılığı.

---

## 🛠️ Kullanılan Teknolojiler

- **HTML5 & Vanilla JavaScript (ES6+)**
- **[Tailwind CSS](https://tailwindcss.com/):** Modern ve esnek arayüz tasarımı için.
- **[JSZip](https://stuk.github.io/jszip/):** EPUB/ZIP arşivlerini tarayıcıda açmak, okumak ve yeniden paketlemek için.
- **DOMParser / XMLSerializer:** EPUB `.opf` (XML) dosyalarını ayrıştırmak ve güncellemek için.

---

## 🌐 GitHub Pages Üzerinde Yayınlama

Proje tamamen istemci taraflı olduğu için GitHub Pages üzerinde ücretsiz olarak yayınlanabilir:

1. Bu depoyu (repository) GitHub hesabınıza klonlayın veya yükleyin.
2. Depo ayarlarından **Settings > Pages** sekmesine gidin.
3. **Build and deployment** bölümünde kaynağı (`Source`) **Deploy from a branch** olarak seçin.
4. Dal olarak `main` (veya `master`), klasör olarak `/ (root)` seçip **Save** butonuna tıklayın.
5. Birkaç dakika içinde uygulamanız `https://kullaniciadi.github.io/depo-adi/` adresinde canlıya alınacaktır.

---

## 💻 Yerel Kullanım

Dosyaları bilgisayarınıza indirip `index.html` dosyasına çift tıklayarak doğrudan tarayıcınızda çalıştırabilirsiniz. Herhangi bir yerel sunucu kurulumu gerektirmez.

---

## 📄 Lisans

Bu proje [Apache License 2.0](./LICENSE) altında lisanslanmıştır.
