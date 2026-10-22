# Eylem Planı

Bu modülde eylem alanları ve eylem planları tanımlanır. Birimler kendilerine verilen uygulama adımları için
**Yıllık Eylem Planı** üzerinden DİF açar.

## Bu sayfayı kimler kullanır

| Rol | Yapacağı işler |
|-----|----------------|
| Admin | [Eylem Alanları](#eylem-alanlari), [Eylem Planı Oluşturma](#eylem-plani-olusturma), [Eylem ve Uygulama Adımları](#eylem-ve-uygulama-adimlari) |
| Üniversite Yöneticisi | Admin ekranlarını görüntüleme |
| Süreç Yöneticisi, Kalite Sorumlusu | [Yıllık Eylem Planından DİF Oluşturma](#yillik-eylem-plani) |
| Rolü olan tüm kullanıcılar | **Yıllık Eylem Planı** ekranını görüntüleme |

İşlemler aşağıdaki sırayla yapılır.

!!! info "Seçili yıl"
    Eylem alanı, eylem planı, eylem ve uygulama adımı oluşturma butonları yalnızca üst çubuktaki **Seçili Yıl** aktif
    yıl olduğunda görünür. Eylem planı aktif yıla oluşturulur.

---

## 1. Eylem Alanları {#eylem-alanlari}

!!! note "Rol"
    Admin

1. **Eylem Planı** > **Eylem Alanları** menüsüne girin.
2. **Yeni Eylem Alanı Oluştur** butonuna tıklayın.
3. **Eylem Alanı** ve **Kodu** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın.

!!! tip "Önceki yıldan kopyalama"
    **Eksik Eylem Alanlarını Önceki Yıldan Kopyala** butonuna tıklayarak önceki yılın eylem alanlarını aktarabilirsiniz.

## 2. Eylem Planı Oluşturma {#eylem-plani-olusturma}

!!! note "Rol"
    Admin

1. Üst çubuktaki **Seçili Yıl** alanında aktif yılın seçili olduğunu kontrol edin.
2. **Eylem Planı** > **Eylem Planları** menüsüne girin.
3. **Yeni Eylem Planı Oluştur** butonuna tıklayın.
4. **Eylem Planı** ve **Kısaltması** alanlarını doldurun.
5. **Oluştur** butonuna tıklayın.

Sistemde birden fazla eylem planı oluşturulabilir.

## 3. Eylem ve Uygulama Adımları {#eylem-ve-uygulama-adimlari}

!!! note "Rol"
    Admin

### Eylem

1. **Eylem Planı** > **Eylem Planları** menüsünde ilgili eylem planının satırında **Göster** butonuna tıklayın.
2. **Yeni Eylem Oluştur** butonuna tıklayın.
3. Şu alanları doldurun: **Eylem**, **Kod**, **Eylem Alanı**, **Süreç**, **Gösterge Etiketi**, **Kurumsal Göstergeler**.
4. **Oluştur** butonuna tıklayın.

### Uygulama Adımı

1. Eylem planının sayfasında ilgili eylemin satırında **Göster** butonuna tıklayın.
2. **Yeni Uygulama Adımı Oluştur** butonuna tıklayın.
3. Şu alanları doldurun:
   - **Uygulama Adımı**, **Sıra**
   - **Süreç Faaliyetleri** (eylemin sürecinde faaliyet varsa görünür)
   - **Ağırlık**
   - **Başlangıç Tarihi**, **Bitiş Tarihi**
   - **Sorumlu Birimler**
4. **Oluştur** butonuna tıklayın.

!!! note "Form uyarısı"
    Bir eylem altındaki uygulama adımlarının **Ağırlık** toplamı en fazla 100 olabilir.

---

## Yıllık Eylem Planından DİF Oluşturma {#yillik-eylem-plani}

!!! note "Rol"
    Süreç Yöneticisi, Kalite Sorumlusu (uygulama adımının sorumlu birimi)

Seçili yıla ait tüm eylem planları **Yıllık Eylem Planı** ekranında listelenir.

1. **Eylem Planı** > **Yıllık Eylem Planı** menüsüne girin.
2. Gerekirse arama alanlarıyla listeyi daraltın.
3. Biriminize verilen uygulama adımının satırındaki **DİF Oluştur** butonuna tıklayın.
4. DİF formunu doldurun ve **Oluştur** butonuna tıklayın. Formun doldurulması [İyileştirme Yönetimi](iyilestirme.md)
   sayfasında anlatılmıştır.

**DİF Oluştur** butonu, uygulama adımının **Başlangıç Tarihi** ile **Bitiş Tarihi** arasında görünür.
