# Halil Samed ÖZLÜ - Portföy Web Sitesi

Bu proje, Halil Samed ÖZLÜ'nün kişisel portföy web sitesidir. Python Flask framework'ü kullanılarak geliştirilmiştir ve modern, responsive tasarıma sahiptir.

## Özellikler

- **Modern ve Responsive Tasarım**: Tüm cihazlarda mükemmel görünüm
- **Türkçe İçerik**: Tamamen Türkçe arayüz ve içerik
- **İnteraktif Animasyonlar**: Smooth scrolling ve hover efektleri
- **Mobil Uyumlu**: Hamburger menü ile mobil navigasyon
- **İletişim Formu**: Çalışan iletişim formu
- **SEO Dostu**: Arama motorları için optimize edilmiş

## Bölümler

1. **Ana Sayfa**: Hero section ve genel tanıtım
2. **Hakkımda**: Kişisel bilgiler ve profil
3. **Deneyim**: İş deneyimleri timeline formatında
4. **Projeler**: Geliştirilen projeler ve açıklamaları
5. **Eğitim**: Eğitim geçmişi ve sertifikalar
6. **Yetenekler**: Teknik yetenekler kategorize edilmiş
7. **İletişim**: İletişim bilgileri ve form

## Kurulum

### Gereksinimler

- Python 3.7+
- pip (Python paket yöneticisi)

### Adımlar

1. Projeyi klonlayın veya indirin:
```bash
git clone <repository-url>
cd portfoy
```

2. Sanal ortam oluşturun (önerilen):
```bash
python -m venv venv
```

3. Sanal ortamı aktifleştirin:
```bash
# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate
```

4. Gereksinimleri yükleyin:
```bash
pip install -r requirements.txt
```

5. Uygulamayı çalıştırın:
```bash
python app.py
```

6. Tarayıcınızda `http://localhost:5000` adresine gidin.

## Proje Yapısı

```
portfoy/
├── app.py                 # Ana Flask uygulaması
├── requirements.txt       # Python bağımlılıkları
├── README.md             # Proje dokümantasyonu
├── templates/
│   └── index.html        # Ana HTML template
└── static/
    ├── css/
    │   └── style.css     # CSS stilleri
    ├── js/
    │   └── script.js     # JavaScript kodları
    └── images/           # Resim dosyaları
```

## Teknolojiler

- **Backend**: Python Flask
- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Custom CSS (Flexbox, Grid)
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)

## Özelleştirme

### Profil Resmi Ekleme
`static/images/` klasörüne `profile.jpg` adında bir profil resmi ekleyin.

### İçerik Güncelleme
`templates/index.html` dosyasındaki ilgili bölümleri düzenleyerek içerikleri güncelleyebilirsiniz.

### Stil Değişiklikleri
`static/css/style.css` dosyasını düzenleyerek renkler, fontlar ve diğer stil özelliklerini değiştirebilirsiniz.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## İletişim

- **E-posta**: samedozlu@icloud.com
- **LinkedIn**: [linkedin.com/in/halil-samed-özlü/](https://linkedin.com/in/halil-samed-özlü/)
- **Telefon**: 0546 580 95 35
