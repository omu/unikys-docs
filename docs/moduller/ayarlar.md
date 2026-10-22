# Ayarlar

Bu menüde takvimler, yıllar, dönemler, kullanıcı rolleri, rol tanımları ve birimler yönetilir.

## Bu sayfayı kimler kullanır

| Rol | Yapacağı işler |
|-----|----------------|
| Admin | [Takvimler](#takvimler), [Yıllar](#yillar), [Dönemler](#donemler), [Kullanıcılar](#kullanicilar), [Rol Tanımları](#rol-tanimlari), [Birimler](#birimler), [Birim Sorumluları](#birim-sorumlulari), [Aktiviteler](#aktiviteler), [Önceki yıldan kopyalama](#onceki-yildan-kopyalama) |
| Süper Admin | [Global rol atama](#global-roller) |
| Veri ve Göstergeler Admini | [Dönemler](#donemler) |

## Takvimler {#takvimler}

!!! note "Rol"
    Admin

### Takvim oluşturma

1. **Ayarlar** > **Takvimler** menüsüne girin.
2. **Takvim Oluştur** butonuna tıklayın.
3. **Takvim Adı** alanını doldurun ve **Gizlilik** alanından **Herkese Açık** ya da **Gizli** seçeneğini seçin.
4. **Oluştur** butonuna tıklayın.

### Takvime etkinlik ekleme

1. **Ayarlar** > **Takvimler** menüsünde takvimin satırındaki **Göster** butonuna tıklayın.
2. **Takvim Etkinlikleri** panelinde **Takvim Etkinliği Oluştur** butonuna tıklayın.
3. **Etkinlik Adı**, **Açıklama**, **Başlangıç Tarihi** ve **Bitiş Tarihi** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın.

**Herkese Açık** takvimlerin etkinlikleri **Anasayfa**daki takvimde görünür.

## Yıllar {#yillar}

!!! note "Rol"
    Admin

1. **Ayarlar** > **Yıllar** menüsüne girin.
2. Aktif yapmak istediğiniz yılın satırındaki **Aktif et** butonuna tıklayın.

Üst çubuktaki **Seçili Yıl** listesi yalnızca görüntülenen yılı değiştirir; aktif yılı bu ekrandan değiştirirsiniz.

## Dönemler {#donemler}

!!! note "Rol"
    Admin, Veri ve Göstergeler Admini

### Dönem oluşturma

1. **Ayarlar** > **Dönemler** menüsüne girin.
2. **Yeni Dönem Oluştur** butonuna tıklayın.
3. **Dönem** alanını doldurun.
4. **Oluştur** butonuna tıklayın.

### Döneme tarih verme

1. **Ayarlar** > **Dönemler** menüsünde dönemin satırındaki **Göster** butonuna tıklayın.
2. **Dönem Tarihleri** panelinde **Dönem Tarihlerini Oluştur** butonuna tıklayın.
3. **Başlangıç Tarihi** ve **Bitiş Tarihi** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın.

Dönemler; gösterge etiketlerinde (**Kurumsal Veri Dönemleri**, **Hedef Dönemleri**, **Üst Hedef Dönemleri**),
kurumsal göstergelerde ve iç değerlendirmede (**BİDR Giriş Dönemleri**, **KİDR Giriş Dönemleri**) seçilir. Veri ve hedef
girişinin yapılabilmesi için seçilen döneme o yıl için tarih verilmiş olmalıdır.

## Kullanıcılar {#kullanicilar}

!!! note "Rol"
    Admin

### Kullanıcı arama

1. **Ayarlar** > **Kullanıcılar** menüsüne girin.
2. **E-posta**, **Rol** ya da **Birim** alanlarını doldurun ve **Arama Yap** butonuna tıklayın.
3. Listeyi Excel olarak almak için **Kullanıcıları İndir** butonuna tıklayın.

**E-posta** sütununda kullanıcının adına ya da e-posta adresine tıklayınca **Kullanıcı** sayfası açılır. Bu sayfada **Kullanıcı Bilgileri**,
**Birim Rolleri**, **Diğer Roller**, **Süreç Rolleri** ve **Sorumlu Olduğu Etiketler** görüntülenir.

!!! info
    Bu ekranda kullanıcı ekleme ve parola sıfırlama yoktur (bkz. [Sisteme Giriş](../giris/sisteme-giris.md)). Birim rolleri
    [Birim Sorumluları](#birim-sorumlulari) ekranından atanır.

### Tanımlı rol atama {#tanimli-rol-atama}

!!! note "Rol"
    Admin

1. **Ayarlar** > **Kullanıcılar** menüsünde **E-posta** sütunundaki kullanıcı adına ya da e-posta adresine tıklayın.
2. **Tanımlı Roller** panelinde atanacak rolleri seçin.
3. **Kaydet** butonuna tıklayın.

Seçilebilen roller **Rol Tanımları** ekranında oluşturulan rollerdir (bkz. [Rol Tanımları](#rol-tanimlari)).

### Global rol atama {#global-roller}

!!! note "Rol"
    Süper Admin

1. **Ayarlar** > **Kullanıcılar** menüsünde **E-posta** sütunundaki kullanıcı adına ya da e-posta adresine tıklayın.
2. **Global Roller** panelinde rolleri seçin: Admin, Üniversite Yöneticisi, SGDB Admini, Veri ve Göstergeler Admini.
3. **Kaydet** butonuna tıklayın.

## Rol Tanımları {#rol-tanimlari}

!!! note "Rol"
    Admin

### Rol tanımı oluşturma

1. **Ayarlar** > **Rol Tanımları** menüsüne girin.
2. **Yeni Rol Tanımı** butonuna tıklayın.
3. **Rol Adı** ve **Açıklama** alanlarını doldurun. Rolün kullanılabilmesi için **Aktif** kutusu işaretli olmalıdır.
4. **Menü Yetkileri** tablosunda her alt menü için **Okuma**, **Yazma** ve gerekirse **Rapor** kutularını işaretleyin.
   Yalnızca okunabilen sayfalarda **Yazma** kutusu yoktur.
   - Bir menünün tüm alt menülerini işaretlemek için üst menü satırındaki kutuyu işaretleyin (kutunun üzerine gelince
     **Tümünü seç** yazar).
   - **Yazma** işaretlendiğinde **Okuma** da işaretlenir.
   - **Rapor** kutusunun üzerine gelince açılacak raporların adları görünür.
5. **Oluştur** butonuna tıklayın.

### Rol tanımını düzenleme ve silme

1. **Ayarlar** > **Rol Tanımları** menüsüne girin.
2. Rolün satırındaki **Düzenle** butonuna tıklayın, değişiklikleri yapın ve **Kaydet** butonuna tıklayın.
3. Rolü silmek için satırdaki **Sil** butonuna tıklayın ve onaylayın. Silinen rol, atandığı kullanıcılardan da kaldırılır.

Rolün yetkilerini ve atandığı kullanıcıları görmek için satırdaki **Göster** butonuna tıklayın (**Menü Yetkileri** ve
**Atanmış Kullanıcılar** panelleri).

Rolü kullanıcılara atamak için bkz. [Tanımlı rol atama](#tanimli-rol-atama).

## Birimler {#birimler}

!!! note "Rol"
    Admin

**Birimler** ekranında üç sekme bulunur:

| Sekme | İçerik |
|-------|--------|
| **Tüm Birimler** | Sistemdeki tüm birimler (YÖKSİS'ten gelenler ve elle eklenenler) |
| **Oluşturulan Birimler** | Admin'in elle eklediği birimler |
| **Gruplar** | Birim grupları |

### Birim arama ve indirme

1. **Ayarlar** > **Birimler** menüsüne girin.
2. **Tüm Birimler** sekmesinde **Birim Adı**, **Birim Türü** ya da **Aktiflik Durumu** alanlarını doldurup
   **Arama Yap** butonuna tıklayın.
3. Listeyi Excel olarak almak için **Excel Dosyası Olarak İndir** butonuna tıklayın, açılan pencerede filtreleri seçip
   indirin.

### Birim ekleme

YÖKSİS'ten gelmeyen birimler (ör. idari birimler) bu adımlarla eklenir.

1. **Ayarlar** > **Birimler** menüsünde **Oluşturulan Birimler** sekmesine geçin.
2. **Yeni Birim Ekle** butonuna tıklayın.
3. **Adı**, **İngilizce Adı**, **Yöksis Üst Birim Id**, **Eğitim Türü**, **Birim Türü** ve **Aktif** alanlarını
   doldurun.
4. **Oluştur** butonuna tıklayın.

YÖKSİS'ten gelen birimler düzenlenemez; yalnızca **Oluşturulan Birimler** sekmesindeki birimler düzenlenip silinebilir.

### Birim grubu oluşturma

1. **Ayarlar** > **Birimler** menüsünde **Gruplar** sekmesine geçin.
2. **Yeni Grup Ekle** butonuna tıklayın.
3. **Grup Adı** alanını doldurun ve **Birimler** alanından birimleri seçin.
4. **Oluştur** butonuna tıklayın.

Mevcut bir grubu çoğaltmak için satırdaki **Kopyala**, gruptaki birimleri görmek için **Birimleri Göster** butonunu
kullanın.

## Birim Sorumluları {#birim-sorumlulari}

!!! note "Rol"
    Admin

1. **Ayarlar** > **Birim Sorumluları** menüsüne girin.
2. **Birimler ve Sorumluları** panelinde açılır listeden birimi seçin.
3. Açılan **Sorumlular** panelinde ilgili alanlardan kullanıcıları seçin:
   - **Veri Giriş Yetkilileri**
   - **Süreç Yöneticisi** (birimde bir kişi)
   - **Kalite Sorumluları**
   - **Rapor Yetkilileri**
   - **Paydaş İletişim Görevlileri**
   - **İç Kontrol Onay Yetkilileri**
   - **İç Kontrol Sorumluları**
4. **Kaydet** butonuna tıklayın.

## Aktiviteler {#aktiviteler}

!!! note "Rol"
    Admin

1. **Ayarlar** > **Aktiviteler** menüsüne girin.
2. Arama alanlarını (ör. **Açıklama**, **Kullanıcı**, **Başlangıç Tarihi**, **Bitiş Tarihi**) doldurup
   **Arama Yap** butonuna tıklayın.
3. Bir kaydın ayrıntısını görmek için **Detaylar** sütunundaki simgeye tıklayın.

## Önceki yıldan kopyalama {#onceki-yildan-kopyalama}

!!! note "Rol"
    Admin

Yeni yıl aktif edildikten sonra yıllık tanımlar ilgili ekranlardaki kopyalama butonlarıyla önceki yıldan aktarılır.
İlk beş satırdaki butonlar aktif yıl seçiliyken görünür.

| Ekran | Buton |
|-------|-------|
| **Süreç Yönetimi** > **Süreç Kartları** | **Eksik Süreçleri Önceki Yıldan Kopyala** |
| **Risk ve Fırsat Yönetimi** > **Risk Seviyeleri** | **Eksik Risk Seviyelerini Önceki Yıldan Kopyala** |
| **Risk ve Fırsat Yönetimi** > **Fırsatlar** | **Eksik Fırsatları Önceki Yıldan Kopyala** |
| **Geri Bildirimler** > **Geri Bildirim Konuları** | **Eksik Konuları Önceki Yıldan Kopyala** |
| **Eylem Planı** > **Eylem Alanları** | **Eksik Eylem Alanlarını Önceki Yıldan Kopyala** |
| **İç Değerlendirme** > **İç Değerlendirmeler** > iç değerlendirme > **Başlıklar** | **Eksik Başlıkları Diğerlerinden Kopyala (Son iki yıl)** paneli |
| **İç Tetkik** > **İç Tetkikler** | **Önceki İç Tetkikten Aktar** |
