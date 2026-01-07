# Eylem Planı

Bu modül, kurumsal eylem planlarının oluşturulması ve takibini sağlar.

!!! info "Erişim"
    Bu modüle herhangi bir role sahip tüm kullanıcılar erişebilir. Ancak **Eylem Planları** ve **Eylem Alanları** alt menüleri sadece Admin/Üniversite Yönetimi tarafından yönetilebilir.

## Alt Menüler

### Eylem Planları

Kurumsal düzeyde eylem planlarının tanımlandığı bölüm.

!!! note "Erişim"
    Sadece **Admin** ve **Üniversite Yönetimi** tarafından yönetilebilir.

**Eylem Planı Oluşturma:**

1. **Eylem Planı > Eylem Planları** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Plan adını ve yılını girin
4. Açıklama ekleyin
5. **Kaydet** butonuna tıklayın

---

### Eylem Alanları

Eylem planlarının kategorize edildiği alanların tanımı.

!!! note "Erişim"
    Sadece **Admin** ve **Üniversite Yönetimi** tarafından yönetilebilir.

**Eylem Alanı Oluşturma:**

1. **Eylem Planı > Eylem Alanları** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Alan adını girin
4. İlgili eylem planını seçin
5. **Kaydet** butonuna tıklayın

---

### Yıllık Eylem Planları

Yıl bazında eylem planlarının görüntülendiği ve takip edildiği bölüm.

**İşlevler:**

- Yıllık eylem planını görüntüleme
- Eylem detaylarına erişim
- İlerleme takibi
- Raporlama

---

## Eylem Planı Yapısı

```
Eylem Planı (2024)
├── Eylem Alanı 1: Eğitim Kalitesi
│   ├── Eylem 1.1: Müfredat güncelleme
│   └── Eylem 1.2: Öğretim yöntemleri geliştirme
├── Eylem Alanı 2: Araştırma
│   └── Eylem 2.1: Proje sayısını artırma
└── Eylem Alanı 3: Toplumsal Katkı
    └── Eylem 3.1: Toplum hizmeti projeleri
```

---

## Eylem Detayları

Her eylem için aşağıdaki bilgiler tanımlanır:

| Alan | Açıklama |
|------|----------|
| Eylem Adı | Yapılacak işin kısa tanımı |
| Açıklama | Detaylı açıklama |
| Sorumlu Birim | Eylemi yürütecek birim |
| Başlangıç Tarihi | Planlanan başlangıç |
| Bitiş Tarihi | Hedeflenen tamamlanma |
| Durum | Mevcut durum |
| İlerleme | Yüzde olarak ilerleme |

---

## Eylem Durumları

| Durum | Açıklama |
|-------|----------|
| Planlandı | Henüz başlanmamış |
| Devam Ediyor | Aktif olarak çalışılıyor |
| Tamamlandı | Başarıyla tamamlandı |
| Ertelendi | İleri tarihe ertelendi |
| İptal Edildi | Uygulamadan vazgeçildi |

---

## İlerleme Takibi

Eylem ilerlemesi düzenli olarak güncellenmelidir:

1. İlgili eylemin detay sayfasına gidin
2. **İlerleme Güncelle** butonuna tıklayın
3. İlerleme yüzdesini girin
4. Açıklama ekleyin (opsiyonel)
5. **Kaydet** butonuna tıklayın

!!! warning "Düzenli Güncelleme"
    Eylem ilerlemelerini en az ayda bir güncelleyin. Bu, yönetimin karar alma süreçlerini destekler.

---

## Raporlama

Eylem planları için çeşitli raporlar oluşturulabilir:

- Yıllık eylem planı raporu
- Birim bazlı ilerleme raporu
- Geciken eylemler raporu
- Tamamlanma oranı analizi

Raporlara **Raporlar** menüsünden erişebilirsiniz.
