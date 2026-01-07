# Ayarlar

Bu modül, sistem yapılandırmasının ve yönetiminin yapıldığı bölümdür.

!!! info "Erişim"
    Bu modüle **Admin**, **Üniversite Yönetimi** ve **Veri ve Göstergeler Admin** rolleri erişebilir. Alt menüler role göre farklılık gösterir.

## Alt Menüler

### Takvimler

Akademik ve idari takvimlerin yönetildiği bölüm.

!!! note "Erişim"
    Sadece **Admin** tarafından yönetilebilir.

**Takvim Oluşturma:**

1. **Ayarlar > Takvimler** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Takvim adını girin
4. Dönemleri tanımlayın
5. **Kaydet** butonuna tıklayın

---

### Yıllar

Akademik yılların tanımlandığı bölüm.

!!! note "Erişim"
    Sadece **Admin** tarafından yönetilebilir.

**Yıl Oluşturma:**

1. **Ayarlar > Yıllar** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Yıl adını girin (örn: 2024-2025)
4. Aktif yıl olarak işaretleyin (gerekirse)
5. **Kaydet** butonuna tıklayın

!!! warning "Aktif Yıl"
    Sistemde sadece bir aktif yıl olabilir. Aktif yıl, varsayılan olarak kullanılan yıldır.

---

### Dönemler

Veri giriş dönemlerinin tanımlandığı bölüm.

**Dönem Oluşturma:**

1. **Ayarlar > Dönemler** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Dönem adını girin
4. Başlangıç ve bitiş tarihlerini belirleyin
5. İlgili yılı seçin
6. **Kaydet** butonuna tıklayın

---

### Kullanıcı Yönetimi

Sistem kullanıcılarının yönetildiği bölüm.

!!! note "Erişim"
    Sadece **Admin** tarafından yönetilebilir.

**Kullanıcı İşlemleri:**

- Kullanıcı listesi görüntüleme
- Yeni kullanıcı ekleme
- Kullanıcı düzenleme
- Rol atama
- Hesap kilitleme/açma

**Kullanıcı Ekleme:**

1. **Ayarlar > Kullanıcı Yönetimi** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Kullanıcı bilgilerini girin
4. Rolleri atayın
5. **Kaydet** butonuna tıklayın

---

### Birim Yönetimi

Kurumsal birimlerin tanımlandığı bölüm.

!!! note "Erişim"
    Sadece **Admin** tarafından yönetilebilir.

**Birim Yapısı:**

```
Üniversite
├── Rektörlük
│   ├── Genel Sekreterlik
│   └── ...
├── Fakülteler
│   ├── Mühendislik Fakültesi
│   └── ...
└── Enstitüler
    └── ...
```

**Birim Oluşturma:**

1. **Ayarlar > Birim Yönetimi** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Birim adını girin
4. Üst birimi seçin
5. Birim türünü belirleyin
6. **Kaydet** butonuna tıklayın

---

### Birim Sorumlularını Yönet

Birimlere sorumlu kullanıcı atama işlemlerinin yapıldığı bölüm.

**Sorumlu Atama:**

1. **Ayarlar > Birim Sorumlularını Yönet** menüsüne gidin
2. İlgili birimi bulun
3. Sorumlu türünü seçin (Süreç Sorumlusu, Kalite Temsilcisi, vb.)
4. Kullanıcıyı seçin
5. **Kaydet** butonuna tıklayın

---

### Aktivite Günlüğü

Sistemde yapılan işlemlerin kaydedildiği günlük.

!!! note "Erişim"
    Sadece **Admin** tarafından görüntülenebilir. Demo ortamında gizlidir.

**Günlük İçeriği:**

- Kullanıcı işlemleri
- Kayıt oluşturma/güncelleme/silme
- Giriş/çıkış bilgileri
- Sistem olayları

---

## Sistem Yapılandırması

| Ayar | Açıklama | Varsayılan |
|------|----------|------------|
| Aktif Yıl | Varsayılan çalışma yılı | Son oluşturulan |
| Dil | Sistem dili | Türkçe |
| Zaman Dilimi | Sistem saat dilimi | İstanbul |

---

## Güvenlik Ayarları

!!! warning "Dikkat"
    Güvenlik ayarları sadece yetkili kişiler tarafından değiştirilmelidir.

- Şifre politikaları
- Oturum süreleri
- Erişim kısıtlamaları
