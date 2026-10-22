# İç Değerlendirme

Bu modülde iç değerlendirme tanımlanır, birimler Birim İç Değerlendirme Raporu (BİDR) için metin ve kanıt girer,
komisyon üyeleri Kurum İç Değerlendirme Raporu (KİDR) için kendi metinlerini ve kanıtlarını yükler.

## Bu sayfayı kimler kullanır

| Rol | Yapacağı işler |
|-----|----------------|
| Admin | [İç Değerlendirme Oluşturma](#ic-degerlendirme-olusturma), [Başlıklar](#basliklar), [Ölçütler](#olcutler) |
| Süreç Yöneticisi | [Birim İç Değerlendirme (BİDR)](#bidr) |
| Komisyon Üyesi | [Kurum İç Değerlendirme (KİDR)](#kidr) |
| Üniversite Yöneticisi | Admin ekranlarını görüntüleme |
| Modüle erişen tüm roller | [Gözlem](#gozlem) |

!!! info "Dönemler"
    BİDR ve KİDR girişleri, **Ayarlar** > **Dönemler** menüsünde tanımlanan dönemlerde yapılır. Dönem tanımlama
    [Ayarlar](ayarlar.md) sayfasında anlatılmıştır.

---

## İç Değerlendirme Oluşturma {#ic-degerlendirme-olusturma}

!!! note "Rol"
    Admin

1. **İç Değerlendirme** > **İç Değerlendirmeler** menüsüne girin.
2. **İç Değerlendirme Oluştur** butonuna tıklayın.
3. Şu alanları doldurun: **İç Değerlendirme Adı**, **Yıl**, **Durumu**, **BİDR Giriş Dönemleri**,
   **KİDR Giriş Dönemleri**.
4. **Oluştur** butonuna tıklayın.

!!! warning "DİF formu ile ilişkisi"
    DİF formundaki **İlişkili YÖKAK Ölçütü** listesinin dolu gelmesi için sistemde durumu **Aktif** olan bir iç
    değerlendirme bulunmalıdır.

## Başlıklar {#basliklar}

!!! note "Rol"
    Admin

1. **İç Değerlendirme** > **İç Değerlendirmeler** menüsünde ilgili iç değerlendirmenin satırında **Göster** butonuna
   tıklayın.
2. **Başlık Oluştur** butonuna tıklayın.
3. Şu alanları doldurun: **Başlık**, **Kod**, **Grup**, **Sıra**, **Sorumlu Komisyon Üyeleri**, **Sorumlu Birimler**.
4. **Oluştur** butonuna tıklayın.

**Sorumlu Komisyon Üyeleri** alanında seçilen kullanıcılar, o başlık için komisyon üyesi olarak yetkilendirilir.

!!! tip "Önceki iç değerlendirmeden kopyalama"
    1. İç değerlendirmenin sayfasında **Eksik Başlıkları Diğerlerinden Kopyala (Son iki yıl)** panelinde kaynak iç
       değerlendirmeyi seçin.
    2. **Kopyala** butonuna tıklayın.

## Ölçütler {#olcutler}

!!! note "Rol"
    Admin

### 1. Düzey Ölçüt

1. İç değerlendirmenin sayfasında ilgili başlığın satırında **Göster** butonuna tıklayın.
2. **1. Düzey Ölçüt Oluştur** butonuna tıklayın.
3. **Kod**, **Ölçüt Adı** ve **Açıklama** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın.

### 2. Düzey Ölçüt

1. Başlığın sayfasında ilgili 1. düzey ölçütün satırında **Göster** butonuna tıklayın.
2. **2. Düzey Ölçüt Oluştur** butonuna tıklayın.
3. Şu alanları doldurun:
   - **Kod**, **Ölçüt Adı**, **Açıklama**
   - **İlgili Kurumsal Göstergeler**, **Örnek Kanıtlar**, **Olgunluk Düzeyi Açıklaması**
   - **Kanıt Zorunlu**, **Birimler**
4. **Oluştur** butonuna tıklayın.

---

## Birim İç Değerlendirme (BİDR) {#bidr}

!!! note "Rol"
    Süreç Yöneticisi

BİDR giriş dönemi açıkken:

1. **İç Değerlendirme** > **Birim İç Değerlendirme** menüsüne girin.
2. **Birim** ve **Başlık** seçin.
3. **1. Düzey Ölçütler** panelinde ölçütün satırındaki **Giriş Yap** butonuna tıklayın.
   **Değerlendirme Metni** alanını doldurup **Oluştur** butonuna tıklayın.
4. İlgili 1. düzey ölçütün adını taşıyan panelde, 2. düzey ölçütün satırındaki **Giriş Yap** butonuna tıklayın.
5. **Değerlendirme Metni**, **Olgunluk Düzeyi** ve **Kanıt** alanlarını doldurun.
6. **Oluştur** butonuna tıklayın.

Girilen kayıtlar aynı ekrandaki **Düzenle** butonuyla güncellenir.

## Kurum İç Değerlendirme (KİDR) {#kidr}

!!! note "Rol"
    Komisyon Üyesi

KİDR giriş dönemi açıkken:

1. **İç Değerlendirme** > **Kurum İç Değerlendirme** menüsüne girin ve **Başlık** seçin.
2. Birimlerin girişlerini incelemek için **1. Düzey Ölçütler** panelinde ölçütün satırındaki **BİDR İncele** butonuna
   tıklayın.
   - İncelemek istediğiniz birim girişini **Göster** ile açın.
   - Puanlamak için **Değerlendir** butonuna tıklayın.
   - **Metin Yeterliliği**, **Kanıt Yeterliliği** ve **Komisyon Görüşü / Eksik Bildirimi** alanlarını doldurun.
   - **Puanlamayı Kaydet** butonuna tıklayın.
3. Kendi metninizi yazmak için ilgili ölçütün (1. ya da 2. düzey) satırındaki **Değerlendirme Yaz** butonuna tıklayın. **Değerlendirme Metni** alanını
   (ekranda varsa **Olgunluk Düzeyi** alanını da) doldurup **Oluştur** butonuna tıklayın.
4. Kanıt eklemek için 2. düzey ölçütün satırındaki **Kanıt Yükle** butonuna tıklayın, dosyayı seçip **Oluştur** butonuna
   tıklayın.

Kayıtlar **Değerlendirmeyi Düzenle** ve **Kanıt Düzenle** butonlarıyla güncellenir.

## Gözlem {#gozlem}

1. **İç Değerlendirme** > **Gözlem** menüsüne girin.
2. Görüntülemek istediğiniz gözlem türünün bağlantısına tıklayın:
   - **Birim 1. Düzey Ölçüt Değerlendirme Metinleri (BİDR)**
   - **Birim 2. Düzey Ölçüt Değerlendirme Metinleri (BİDR)**
   - **Komisyon Üyesi Değerlendirme Metinleri (KİDR)**
   - **2. Düzey Ölçüt Kanıtları (KİDR)**

İlgili raporlar için [Raporlar](raporlar.md) sayfasına bakınız.
