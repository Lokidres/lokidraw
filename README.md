# LokiDraw 🎨

Excalidraw'dan ilham alınarak geliştirilmiş, tarayıcı tabanlı modern bir çizim uygulaması.

## Özellikler ✨

### Çizim Araçları
- **Kalem** ✏️ - Serbest el çizimi
- **Çizgi** 📏 - Düz çizgiler
- **Ok** ➡️ - Yönlü oklar
- **Dikdörtgen** ⬜ - Dikdörtgen şekiller
- **Daire** ⭕ - Daire ve elips şekiller
- **Metin** T - Metin ekleme

### Özelleştirme
- 🎨 **Renk Seçici** - Sınırsız renk seçeneği
- 📏 **Kalınlık Ayarı** - 1-20px arası çizgi kalınlığı
- 🧹 **Silgi** - Çizimleri silme

### Kontroller
- ↶ **Geri Al** - Son işlemi geri alma
- ↷ **Yinele** - Geri alınan işlemi tekrarlama
- 🗑️ **Temizle** - Tüm çizimleri silme
- 💾 **PNG İndir** - Çiziminizi PNG olarak kaydetme

### Görünüm
- 🔍 **Zoom** - Fare tekerleği ile yakınlaştırma/uzaklaştırma
- 👆 **Pan** - Ctrl+Sol Tık veya Orta Tuş ile kaydırma
- ⊙ **Sıfırla** - Görünümü varsayılana döndürme

## Kullanım 🚀

### Başlangıç
1. `lokidraw.html` dosyasını herhangi bir modern web tarayıcısında açın
2. Üst kısımdaki araç çubuğundan bir araç seçin
3. Çizmeye başlayın!

### Klavye Kısayolları
- **Fare Tekerleği** - Zoom In/Out
- **Ctrl + Sol Tık** - Pan (Kaydırma)
- **Orta Tuş + Sürükle** - Pan (Kaydırma)

### Çizim İpuçları
1. **Kalem Aracı**: Tıklayıp sürükleyerek serbest çizim yapın
2. **Şekiller**: Başlangıç noktasına tıklayın, sürükleyin ve bırakın
3. **Metin**: İstediğiniz noktaya tıklayın ve metni yazın
4. **Silgi**: Silgi düğmesine basın, beyaz renk ve kalın fırça ile çizin

### Export
1. Çiziminiz tamamlandığında 💾 düğmesine tıklayın
2. PNG dosyası otomatik olarak indirilecektir
3. Dosya adı: `lokidraw-[timestamp].png`

## Teknik Özellikler 🔧

### Teknolojiler
- **HTML5 Canvas** - Çizim motoru
- **Vanilla JavaScript** - Sıfır bağımlılık
- **CSS3** - Modern ve responsive tasarım

### Tarayıcı Desteği
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### Performans
- Hafif ve hızlı (tek dosya, ~7KB)
- Bağımlılık yok
- Anlık yükleme
- Smooth çizim deneyimi

## Kurulum 📦

### Basit Kullanım
```bash
# Dosyayı indirin
wget lokidraw.html

# Tarayıcıda açın
open lokidraw.html
```

### Web Sunucusu
```bash
# Python ile
python -m http.server 8000

# Node.js ile
npx serve

# Ardından http://localhost:8000/lokidraw.html adresine gidin
```

## Özellikler Roadmap 🗺️

### Yakında Gelecek
- [ ] Dolgu rengi desteği
- [ ] Daha fazla şekil (üçgen, yıldız, vb.)
- [ ] Katman yönetimi
- [ ] Seçim ve taşıma araçları
- [ ] JSON export/import
- [ ] Tema desteği (koyu mod)
- [ ] Çoklu undo/redo seviyeleri
- [ ] Grid ve snap özelliği

### Gelecek Planlar
- [ ] Gerçek zamanlı işbirliği
- [ ] Bulut kaydetme
- [ ] Şablon kütüphanesi
- [ ] SVG export
- [ ] Mobil dokunmatik optimizasyonu

## Katkıda Bulunma 🤝

LokiDraw açık kaynak bir projedir. Katkılarınızı bekliyoruz!

### Nasıl Katkıda Bulunulur
1. Projeyi fork edin
2. Yeni bir branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

## Lisans 📄

Bu proje MIT lisansı altında lisanslanmıştır.

## İletişim 📧

Sorularınız veya önerileriniz için issue açabilirsiniz.

## Teşekkürler 🙏

Bu proje [Excalidraw](https://excalidraw.com/) projesinden ilham almıştır.

---

**LokiDraw** ile yaratıcılığınızı serbest bırakın! 🎨✨
