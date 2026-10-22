# İyileştirme Yönetimi

Bu modülde uygunsuzluklar tanımlanır, düzeltmeler ve DİF (Düzeltici İyileştirici Faaliyet) kayıtları izlenir, yönetim
görevleri verilir.

## Bu sayfayı kimler kullanır

| Rol | Yapacağı işler |
|-----|----------------|
| Admin | [Uygunsuzluklar](#uygunsuzluklar), [Yönetim Görevleri](#yonetim-gorevleri), tüm listeleri görüntüleme |
| Üniversite Yöneticisi | [Yönetim Görevleri](#yonetim-gorevleri), tüm listeleri görüntüleme |
| Etiket Sorumlusu | [Yönetim Görevleri](#yonetim-gorevleri) |
| Süreç Yöneticisi | [Düzeltme Yapma](#duzeltme), [DİF Oluşturma](#dif-olusturma), [DİF Onayı](#dif-onayi), [Faaliyet Adımlarını Tamamlama](#dif-tamamlama), [DİF Değerlendirme](#dif-degerlendirme) |
| Kalite Sorumlusu | [Düzeltme Yapma](#duzeltme), [DİF Oluşturma](#dif-olusturma), [Faaliyet Adımlarını Tamamlama](#dif-tamamlama) |
| Süreç Koordinatörü | [DİF Onayı](#dif-onayi), [DİF Değerlendirme](#dif-degerlendirme) |

**İyileştirme Yönetimi** menüsünde şu alt menüler bulunur: **Uygunsuzluklar**, **Düzeltmeler**, **Düzeltmelerim**,
**DİF**, **Yönetim Görevleri**. Her rol yalnızca kendisine açık olanları görür.

---

## Uygunsuzluklar {#uygunsuzluklar}

!!! note "Rol"
    Admin

1. **İyileştirme Yönetimi** > **Uygunsuzluklar** menüsüne girin.
2. **Yeni Uygunsuzluk Oluştur** butonuna tıklayın.
3. **Uygunsuzluk** ve **Uygunsuzluk Türü** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın.

Tanımlanan uygunsuzluklar düzeltme formundaki **Uygunsuzluk** listesinde çıkar.

## Düzeltme Yapma {#duzeltme}

!!! note "Rol"
    Süreç Yöneticisi, Kalite Sorumlusu

**Düzeltme Yap** butonu şu ekranlarda bulunur:

- **Geri Bildirimler**: geri bildirimin detay sayfası ([Geri Bildirimler](geri-bildirimler.md))
- **Süreç Kartları**: süreç kartındaki faaliyet ([Süreç Yönetimi](surec-yonetimi.md))
- **İç Tetkik Raporları**: iç tetkik bulgusunun sayfası ([İç Tetkik](ic-tetkik.md))

Adımlar:

1. İlgili ekranda **Düzeltme Yap** butonuna tıklayın.
2. **Uygunsuzluk** alanından uygunsuzluğu seçin. Listede yoksa **Diğer** seçili bırakıp **Uygunsuzluğu Tanımlayın**
   alanını doldurun.
3. **Birim** ve **Açıklama / Yapılan İşlem** alanlarını doldurun. Varsa **Kanıtlar (varsa)** alanından dosya yükleyin.
4. **Oluştur** butonuna tıklayın.

Biriminize ve süreçlerinize ait düzeltmeler **İyileştirme Yönetimi** > **Düzeltmelerim** menüsünde listelenir. Admin ve Üniversite Yöneticisi
tüm düzeltmeleri **İyileştirme Yönetimi** > **Düzeltmeler** menüsünde görür.

---

## DİF Oluşturma {#dif-olusturma}

!!! note "Rol"
    Süreç Yöneticisi, Kalite Sorumlusu

**DİF Oluştur** butonu şu ekranlarda bulunur:

| Ekran | Sayfa |
|---|---|
| Geri bildirimin detay sayfası | [Geri Bildirimler](geri-bildirimler.md) |
| **Risklerim** listesi ve risk detay sayfası | [Risk ve Fırsat Yönetimi](risk-ve-firsat-yonetimi.md) |
| Süreç kartındaki faaliyet | [Süreç Yönetimi](surec-yonetimi.md) |
| **Yıllık Eylem Planı** | [Eylem Planı](eylem-plani.md) |
| Yönetim görevinin adımı | [Yönetim Görevleri](#yonetim-gorevleri) |
| İç tetkik bulgusunun sayfası | [İç Tetkik](ic-tetkik.md) |

Adımlar:

1. İlgili ekranda **DİF Oluştur** butonuna tıklayın.
2. Şu alanları doldurun:
   - **Talep Eden Birim**, **DİF Türü**
   - **Uygunsuzluk Tanımı** veya **İyileştirme Tanımı**
   - **Uygunsuzluğun Nedeni (Kök Neden Analizi) ve Yayılma Potansiyeli** (**Düzeltici Faaliyet** seçildiğinde)
   - **Uygulanması Planlanan Faaliyet**
3. **Faaliyet Adımı Ekle** butonuyla her faaliyet adımını ekleyin. Her adımda şunları doldurun: **Faaliyet Adımı**,
   **Sorumlu Kişi**, **Tamamlanma Tarihi**, **Etki Yüzdesi (%)**, **Bütçe**.
4. **Faaliyetin Üst Sorumlusu** ve **İlişkili YÖKAK Ölçütü** alanlarını doldurun. Varsa **Dosyalar** alanından dosya
   yükleyin.
5. **Oluştur** butonuna tıklayın.

DİF kayıtları **İyileştirme Yönetimi** > **DİF** menüsünde listelenir.

!!! note "Form uyarısı"
    Faaliyet adımlarının **Etki Yüzdesi (%)** değerlerinin toplamı 100 olmalıdır. Aksi halde form kaydedilmez.

## DİF Onayı {#dif-onayi}

!!! note "Rol"
    Süreç Yöneticisi, Süreç Koordinatörü

1. **İyileştirme Yönetimi** > **DİF** menüsüne girin.
2. Onayınızı bekleyen DİF'i **Göster** ile açın.
3. **DİF'i Onayla/Reddet** butonuna tıklayın.
4. **DİF'i Onaylıyor Musunuz?** alanında **Evet** veya **Hayır** seçin ve **Değerlendirme** alanını doldurun.
5. **Oluştur** butonuna tıklayın.

DİF sırasıyla talep eden birimin Süreç Yöneticisi, ilgili sürecin Süreç Yöneticisi ve Süreç Koordinatörü tarafından onaylanır.

## Faaliyet Adımlarını Tamamlama {#dif-tamamlama}

!!! note "Rol"
    Süreç Yöneticisi, Kalite Sorumlusu (DİF'i talep eden birim)

DİF onaylanıp başladıktan sonra:

1. **İyileştirme Yönetimi** > **DİF** menüsünde DİF'i **Göster** ile açın.
2. Tamamlanan faaliyet adımının satırındaki **Tamamla** butonuna tıklayın.
3. **Faaliyet Adımı Tamamlandı Mı?**, **Açıklama** ve **Kanıt** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın. Her faaliyet adımı için tekrarlayın.

## DİF Değerlendirme {#dif-degerlendirme}

!!! note "Rol"
    Süreç Yöneticisi, Süreç Koordinatörü

Bütün faaliyet adımları tamamlandıktan sonra:

1. **İyileştirme Yönetimi** > **DİF** menüsünde DİF'i **Göster** ile açın.
2. **Değerlendir** butonuna tıklayın.
3. **DİF etkili mi?** alanında **Etkili** veya **Etkili Değil** seçin ve **Açıklama** alanını doldurun.
4. **Oluştur** butonuna tıklayın.

---

## Yönetim Görevleri {#yonetim-gorevleri}

### Yönetim Görevi Oluşturma

!!! note "Rol"
    Admin, Üniversite Yöneticisi, Etiket Sorumlusu

Admin ve Üniversite Yöneticisi için:

1. **İyileştirme Yönetimi** > **Yönetim Görevleri** menüsüne girin.
2. **Yönetim Görevi Oluştur** butonuna tıklayın.

Etiket Sorumlusu için (Admin ve Üniversite Yöneticisi de bu yolu kullanabilir):

1. **Raporlar** menüsünde **Kurumsal Göstergeler** raporunun satırındaki **Göster** butonuna tıklayın.
2. İlgili kurumsal göstergenin satırında **Yönetim Görevi Oluştur** butonuna tıklayın.

Açılan formda:

1. **Yönetim Görevi Adı**, **Yönetim Görevi Tanımı** ve **Süreç** alanlarını doldurun. Görev bir kurumsal göstergeden
   açıldıysa **Kurumsal Gösterge** alanı dolu gelir.
2. **Görev Adımı Ekle** butonuyla her görev adımını ekleyin. Her adımda şunları doldurun: **Tanım**, **Ağırlık**,
   **Sorumlu Kişi**, **Sorumlu Birimler**, **Başlangıç Tarihi**, **Bitiş Tarihi**.
3. **Oluştur** butonuna tıklayın.

### Yönetim Görevinden DİF Oluşturma

!!! note "Rol"
    Süreç Yöneticisi, Kalite Sorumlusu (görev adımının sorumlu birimi)

1. **İyileştirme Yönetimi** > **Yönetim Görevleri** menüsüne girin.
2. Biriminize verilen görevi **Göster** ile açın.
3. İlgili görev adımının satırındaki **DİF Oluştur** butonuna tıklayın.
4. DİF formunu [DİF Oluşturma](#dif-olusturma) bölümündeki gibi doldurun.
