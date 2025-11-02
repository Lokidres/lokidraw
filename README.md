# LokiDraw 🎨

Excalidraw'dan ilham alınarak geliştirilmiş, tarayıcı tabanlı modern bir çizim uygulaması.

## Özellikler ✨

### Çizim Araçları
- **Kalem** ✏️ - Serbest el çizimi
- **Çizgi** 📏 - Düz çizgiler
- **Ok** ➡️ - Yönlü oklar
- **Dikdörtgen** ⬜ - Dikdörtgen şekiller
- **Daire** ⭕ - Daire ve elips şekiller
- **Metin** T - Gelişmiş inline metin editörü (Excalidraw tarzı)
  - Doğrudan canvas üzerinde yazma
  - Resize handle ile boyut ayarlama
  - Otomatik kontrast renk seçimi

### Özelleştirme
- 🎨 **Renk Seçici** - Sınırsız çizgi rengi seçeneği
- 🖼️ **Arkaplan Rengi** - Canvas arka plan rengini değiştirme
- 📏 **Kalınlık Ayarı** - 1-20px arası çizgi kalınlığı
- 🧹 **Silgi** - Çizimleri silme

### Kontroller
- ↶ **Geri Al** - Son işlemi geri alma
- ↷ **Yinele** - Geri alınan işlemi tekrarlama
- 🗑️ **Temizle** - Tüm çizimleri silme (kaydedilen çizim de silinir)
- 💾 **PNG İndir** - Çiziminizi PNG olarak kaydetme
- 💿 **Otomatik Kayıt** - Tüm çizimler otomatik olarak tarayıcıda saklanır

### Mobil Özellikler 📱
- ✨ **Touch-Optimized** - Parmak dostu büyük butonlar
- 🤏 **Pinch to Zoom** - İki parmakla yakınlaştırma
- 👆 **Two-Finger Pan** - İki parmakla kaydırma
- 🎯 **Touch Events** - Hassas dokunmatik kontrol
- 📐 **Responsive Design** - Her ekran boyutuna uyum
- 💿 **Auto-Save** - Çizimleriniz cihazınızda otomatik kaydedilir

### Görünüm
- 🔍 **Zoom** - Fare tekerleği ile yakınlaştırma/uzaklaştırma (Mobilde: 2 parmakla pinch)
- 👆 **Pan** - Ctrl+Sol Tık veya Orta Tuş ile kaydırma (Mobilde: 2 parmakla sürükleme)
- ⊙ **Sıfırla** - Görünümü varsayılana döndürme
- 📱 **Mobil Destek** - Touch event desteği ile tam mobil uyumluluk

## Kullanım 🚀

### Başlangıç
1. `lokidraw.html` dosyasını herhangi bir modern web tarayıcısında açın
2. Üst kısımdaki araç çubuğundan bir araç seçin
3. Çizmeye başlayın!
4. Çizimleriniz otomatik olarak tarayıcınızda kaydedilir
5. Sayfayı kapatıp tekrar açtığınızda çizimleriniz hala orada olacak!

### Klavye Kısayolları
- **Fare Tekerleği** - Zoom In/Out
- **Ctrl + Sol Tık** - Pan (Kaydırma)
- **Orta Tuş + Sürükle** - Pan (Kaydırma)
- **Ctrl + Enter** (Metin modunda) - Metni kaydet
- **Esc** (Metin modunda) - Metni iptal et

### Mobil Kullanım 📱
- **Tek Parmak** - Çizim yapma
- **İki Parmak Pinch** - Zoom In/Out
- **İki Parmak Sürükleme** - Pan (Kaydırma)
- **Metin Modu**: 
  - Tıklayıp doğrudan yazma
  - Mavi noktaya dokunup sürükleyerek boyut ayarlama
  - Dışarı tıklayarak kaydetme

### Çizim İpuçları
1. **Kalem Aracı**: Tıklayıp sürükleyerek serbest çizim yapın
2. **Şekiller**: Başlangıç noktasına tıklayın, sürükleyin ve bırakın
3. **Metin**: 
   - İstediğiniz noktaya tıklayın
   - Doğrudan yazmaya başlayın
   - Sağ alt köşedeki mavi noktayı sürükleyerek boyutu ayarlayın
   - Ctrl+Enter veya tıklama dışına çıkarak kaydedin
   - Metin rengi arka plana göre otomatik ayarlanır (kontrast)
4. **Silgi**: Silgi düğmesine basın, beyaz renk ve kalın fırça ile çizin
5. **Arkaplan**: Arkaplan rengi seçiciyle canvas rengini değiştirin (undo/redo ile geri alınabilir)
6. **Otomatik Kayıt**: Her değişiklik anında kaydedilir, endişelenmeyin! Sayfayı kapatabilirsiniz

### Export
1. Çiziminiz tamamlandığında 💾 düğmesine tıklayın
2. PNG dosyası otomatik olarak indirilecektir
3. Dosya adı: `lokidraw-[timestamp].png`

## Teknik Özellikler 🔧

### Teknolojiler
- **HTML5 Canvas** - Çizim motoru
- **Vanilla JavaScript** - Sıfır bağımlılık
- **CSS3** - Modern ve responsive tasarım
- **Local Storage** - Otomatik çizim kaydetme

### Tarayıcı Desteği
#### Masaüstü
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

#### Mobil
- ✅ iOS Safari 14+
- ✅ Chrome Mobile 90+
- ✅ Samsung Internet
- ✅ Firefox Mobile

### Performans
- Hafif ve hızlı (tek dosya, ~10KB)
- Bağımlılık yok
- Anlık yükleme
- Smooth çizim deneyimi
- Mobil cihazlarda optimize edilmiş touch performansı
- 60 FPS çizim desteği
- Otomatik kayıt (hiçbir çizim kaybolmaz)

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
- [ ] Şekil dolgu rengi (fill color)
- [ ] Daha fazla şekil (üçgen, yıldız, vb.)
- [ ] Katman yönetimi
- [ ] Seçim ve taşıma araçları
- [ ] JSON export/import
- [ ] Tema desteği (koyu mod)
- [ ] Grid ve snap özelliği

### Gelecek Planlar
- [ ] Gerçek zamanlı işbirliği
- [ ] Bulut kaydetme (Google Drive entegrasyonu)
- [ ] Şablon kütüphanesi
- [ ] SVG export
- [ ] Gelişmiş mobil jestler (3 parmak işlemleri vb.)
- [ ] Çoklu çizim sayfaları

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
