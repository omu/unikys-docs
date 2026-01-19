# Ünikys Kullanım Kılavuzu

Bu repository, Ünikys Kalite Yönetim Sistemi'nin kullanım kılavuzunu içermektedir.

## Canlı Site

[https://omu.github.io/unikys-docs/](https://omu.github.io/unikys-docs/)

## Geliştirme

### Gereksinimler

- Python 3.x
- pip

### Kurulum

```bash
# Bağımlılıkları yükle
pip install mkdocs-material

# Yerel sunucuyu başlat
mkdocs serve
```

Tarayıcıda `http://127.0.0.1:8000` adresini açın.

### Yapı

```
unikys-docs/
├── mkdocs.yml          # MkDocs konfigürasyonu
├── docs/
│   ├── index.md        # Ana sayfa
│   ├── giris/          # Giriş bölümü
│   ├── moduller/       # Modül sayfaları
│   ├── roller.md       # Roller ve yetkiler
│   └── sss.md          # Sık sorulan sorular
└── .github/
    └── workflows/
        └── deploy.yml  # Otomatik deploy
```

### Deploy

`main` branch'e push yapıldığında GitHub Actions otomatik olarak siteyi build edip GitHub Pages'e deploy eder.

## Katkıda Bulunma

1. Değişikliklerinizi yapın
2. `mkdocs serve` ile yerel olarak test edin
3. Pull request oluşturun

## Lisans

Bu dokümantasyon Ondokuz Mayıs Üniversitesi tarafından hazırlanmıştır.
