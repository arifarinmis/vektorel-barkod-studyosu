# Vektörel Barkod Stüdyosu (CMYK K:100 Prepress & Ambalaj)

Modern **macOS / SF Pro** estetiğinde tasarlanmış, ambalaj ve baskı profesyonelleri için tek sayfalık, bağımsız **Vektörel Barkod Üretim Stüdyosu**.

## Özellikler

- **Desteklenen Barkod Standartları:**
  - **EAN-13** (12 hane veri girişi → 13. Modulo-10 kontrol hanesi otomatik hesaplanır)
  - **UPC-A** (11 hane veri girişi → 12. Modulo-10 kontrol hanesi otomatik hesaplanır)
  - **ITF-14** (13 hane veri girişi → 14. kontrol hanesi otomatik hesaplanır + Koli Çerçevesi / Bearer Bar desteği)
  - **Code 128** (Tam alfanümerik destek, dahili Mod-103 kontrolü)
  - **QR Code** (ISO/IEC 18004 2D vektörel modül üretimi)
- **Ambalaj ve Baskı (Prepress) Özellikleri:**
  - **CMYK K:100 Saf Siyah:** PDF çıktısında doğrudan `DeviceCMYK (0 0 0 1 k)` operatörleriyle **%0 C, %0 M, %0 Y, %100 K** saf siyah vektör ayrımı.
  - **Quiet Zone (Güvenlik Payı) Koruması:** GS1 standartlarına uygun sol/sağ modül boşlukları ve canlı önizleme kılavuzu.
  - **BWR (Bar Width Reduction / Mürekkep Yayılma Telafisi):** Flekso ve ofset baskı için mikron (`µm`) düzeyinde çubuk inceltme ayarı.
  - **SVG Kopyala (Illustrator):** Adobe Illustrator veya Figma'ya doğrudan `⌘V` ile yapıştırılabilir milimetrik `<rect>` vektör panosu.
  - **SVG İndir & Vektörel PDF İndir:** Kesim işaretleri (Crop Marks) ve gerçek milimetrik ebatlarla hazır çıktı.
- **macOS Safari Web App (PWA) Desteği:**
  - Safari'de **Dosya > Dock'a Ekle (Add to Dock)** seçildiğinde bağımsız masaüstü uygulaması penceresi olarak çalışır (`manifest.json` ve `apple-touch-icon.png` dahildir).

## GitHub Pages ile Yayınlama

1. Bu depoyu GitHub hesabınıza gönderin (`git push -u origin main`).
2. GitHub depo ayarlarından **Settings > Pages** bölümüne gidin.
3. **Build and deployment > Source** altından `Deploy from a branch` seçip `main` dalını ve `/ (root)` klasörünü kaydedin.
