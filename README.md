# Ünikys Kullanım Kılavuzu

Bu repository, Ünikys Kalite Yönetim Sistemi'nin kullanım kılavuzunu içermektedir.

## Canlı Site

[https://omu.sh/unikys-docs/](https://omu.sh/unikys-docs/)

## Geliştirme

### Gereksinimler

- Python 3.x
- pip

### Kurulum

```bash
# Bağımlılıkları yükle
pip install mkdocs-material mkdocs-redirects

# Yerel sunucuyu başlat
mkdocs serve
```

Tarayıcıda `http://127.0.0.1:8000` adresini açın.

### Yapı

```
unikys-docs/
├── mkdocs.yml          # MkDocs konfigürasyonu (nav, eski adres yönlendirmeleri)
├── overrides/          # Tema eki (arama motorlarına noindex)
├── docs/
│   ├── index.md        # Ana sayfa
│   ├── giris/          # Giriş bölümü
│   ├── moduller/       # Modül sayfaları
│   ├── rolume-gore.md  # Rolüme göre kılavuz
│   ├── assets/img/     # Kırpılmış ekran görüntüleri
│   ├── roller.md       # Roller ve yetkiler
│   └── sss.md          # Sık sorulan sorular
└── .github/
    └── workflows/
        └── deploy.yml  # Otomatik deploy
```

### Deploy

`main` branch'e push yapıldığında GitHub Actions otomatik olarak siteyi build edip GitHub Pages'e deploy eder.

## Güncelleme

Kılavuz, ÜNİKYS (kalem) uygulamasının canlı sürümüne (`origin/main`) göre yazılır. Menü, buton ve alan adları ekranda
göründüğü gibi yazılır; yalnızca tıklama adımları anlatılır. Claude Code'da `unikys-kilavuz` skill'i bu süreci
(değişenleri bulma, yazım kuralları, doğrulama betikleri) yürütür.

## Katkıda Bulunma

1. Değişikliklerinizi yapın
2. `mkdocs serve` ile yerel olarak test edin
3. Pull request oluşturun

## Lisans

Bu dokümantasyon Ondokuz Mayıs Üniversitesi tarafından hazırlanmıştır.
