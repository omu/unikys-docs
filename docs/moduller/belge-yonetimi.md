# Belge Yönetimi

Bu modül, kurumsal belgelerin ve dokümanların yönetimini sağlar.

!!! info "Erişim"
    - **Belge Talepleri**: Admin, Üniversite Yönetimi, Süreç Rolleri
    - **Belge Kategorileri**: Tüm kullanıcılar (giriş yapmadan da erişilebilir)

## Alt Menüler

### Belge Talepleri

Yeni belge oluşturma, belge güncelleme veya belge iptal taleplerinin yönetildiği bölüm.

**Belge Talebi Oluşturma:**

1. **Belge Yönetimi > Belge Talepleri** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Talep türünü seçin:
   - Yeni belge
   - Belge güncelleme
   - Belge iptali
4. İlgili bilgileri doldurun
5. Destekleyici dokümanları ekleyin
6. **Kaydet** butonuna tıklayın

**Talep Durumları:**

| Durum | Açıklama |
|-------|----------|
| Taslak | Henüz gönderilmemiş |
| Onay Bekliyor | Onay sürecinde |
| Onaylandı | Kabul edildi |
| Reddedildi | Talep reddedildi |
| Tamamlandı | Süreç tamamlandı |

---

### Belge Kategorileri

Kurumsal belgelerin kategorize edildiği ve erişilebildiği bölüm.

**Kategori Yapısı:**

```
Belge Kategorileri
├── Prosedürler
│   ├── Eğitim Prosedürleri
│   └── İdari Prosedürler
├── Talimatlar
├── Formlar
└── Politikalar
```

**Kategori Oluşturma (Admin):**

1. **Belge Yönetimi > Belge Kategorileri** menüsüne gidin
2. **Yeni Kategori** butonuna tıklayın
3. Kategori adını girin
4. Üst kategoriyi seçin (varsa)
5. **Kaydet** butonuna tıklayın

**Belge Ekleme:**

1. İlgili kategoriye gidin
2. **Belge Ekle** butonuna tıklayın
3. Belge bilgilerini girin
4. Dosyayı yükleyin
5. **Kaydet** butonuna tıklayın

---

## Belge Özellikleri

Her belge için aşağıdaki bilgiler tanımlanır:

| Alan | Açıklama |
|------|----------|
| Belge Adı | Belgenin başlığı |
| Belge Kodu | Benzersiz tanımlayıcı |
| Revizyon No | Versiyon numarası |
| Hazırlayan | Belgeyi hazırlayan kişi |
| Onaylayan | Belgeyi onaylayan kişi |
| Yürürlük Tarihi | Geçerlilik başlangıcı |
| Durum | Aktif/Pasif |

---

## Versiyon Kontrolü

Belgeler güncellendiğinde versiyon kontrolü yapılır:

- Orijinal belge arşivlenir
- Yeni versiyon aktif olur
- Değişiklik geçmişi tutulur

**Versiyon Geçmişini Görüntüleme:**

1. Belge detay sayfasına gidin
2. **Versiyon Geçmişi** sekmesine tıklayın
3. Önceki versiyonları görüntüleyin

---

## Belge Arama

Belgeleri aramak için:

1. Belge kategorileri sayfasına gidin
2. Arama kutusuna belge adı veya kodunu yazın
3. Sonuçlar filtrelenir

!!! tip "Etkili Arama"
    Belge kodunu biliyorsanız, kod ile arama yapmanız daha hızlı sonuç verir.

---

## İndirme ve Yazdırma

- Belgeleri PDF formatında indirebilirsiniz
- Doğrudan yazdırma özelliği mevcuttur
- Toplu indirme yapılabilir

---

## Birim Belge Kategorileri

Her birim kendi özel belgelerini yönetebilir:

1. **Birimim > Birim Belge Kategorileri** menüsüne gidin
2. Birime özel belgeleri görüntüleyin
3. Yeni belge ekleyin (yetkili ise)

!!! note "Birim Belgeleri"
    Birim belgeleri sadece o birim yetkilileri tarafından yönetilebilir. Diğer kullanıcılar sadece görüntüleyebilir.
