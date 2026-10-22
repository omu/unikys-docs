# Doküman Yönetimi

Bu modülde kurum dokümanları yayınlanır, birimler doküman ekleme, güncelleme ve iptal talebinde bulunur.

## Bu sayfayı kimler kullanır

| Rol | Yapacağı işler |
|-----|----------------|
| Admin | [Doküman Türü Oluşturma](#dokuman-turu-olusturma), [Doküman Oluşturma](#dokuman-olusturma), [Doküman Talebini Değerlendirme](#dokuman-talebini-degerlendirme), [Onaylanan Talebi Sonuçlandırma](#onaylanan-talebi-sonuclandirma) |
| Süreç Yöneticisi | [Doküman Talebi Oluşturma](#dokuman-talebi-olusturma), [Doküman Talebini Değerlendirme](#dokuman-talebini-degerlendirme), [Dokümanlara Erişim](#dokumanlara-erisim) |
| Kalite Sorumlusu | [Doküman Talebi Oluşturma](#dokuman-talebi-olusturma), [Dokümanlara Erişim](#dokumanlara-erisim) |
| Tüm kullanıcılar | [Dokümanlara Erişim](#dokumanlara-erisim) |

Birime özel dokümanlar için [Birim](birim.md) sayfasına bakınız.

## Dokümanlara Erişim {#dokumanlara-erisim}

!!! note "Rol"
    Tüm kullanıcılar

1. **Doküman Yönetimi** > **Dokümanlar** menüsüne girin.
2. **Doküman Türleri** listesinde doküman türünün adına tıklayın.
3. Gerekirse **Dokümanlar** panelinin üstündeki arama alanlarını doldurup **Arama Yap** butonuna tıklayın.
4. Dokümanın satırındaki **Dosyalar** butonuna tıklayın. Dosyalar **Doküman Versiyonları** panelinde listelenir.

## Doküman Türü Oluşturma {#dokuman-turu-olusturma}

!!! note "Rol"
    Admin

1. **Doküman Yönetimi** > **Dokümanlar** menüsüne girin.
2. **Doküman Türü Oluştur** butonuna tıklayın.
3. **Doküman Türü** alanını doldurun; gerekiyorsa **Kanıt Zorunlu** ve **Görünsün mü?** kutularını işaretleyin.
4. **Oluştur** butonuna tıklayın.

## Doküman Oluşturma {#dokuman-olusturma}

!!! note "Rol"
    Admin

1. **Doküman Yönetimi** > **Dokümanlar** menüsüne girin ve doküman türünün adına tıklayın.
2. **Dokümanlar** panelinde **Doküman Oluştur** butonuna tıklayın.
3. **Doküman**, **Süreç**, **Süreç Faaliyeti**, **Birim** ve **Durum** alanlarını doldurun.
4. Doküman mevzuat sisteminde yayınlanıyorsa bağlantısını **Url** alanına yazın ve **Revizyon Numarası** alanını
   doldurun.
5. **Oluştur** butonuna tıklayın.

### Dosya yükleme

Doküman dosya olarak yayınlanacaksa doküman oluşturulduktan sonra dosya eklenir.

1. Dokümanın satırındaki **Dosyalar** butonuna tıklayın.
2. **Doküman Versiyonları** panelinde **Dosya Ekle** butonuna tıklayın.
3. **Dosya**, **Doküman Numarası** ve **Revizyon Numarası** alanlarını doldurun. Dosya bir talebe bağlıysa
   **Gerekçe** ve **Doküman Talebi** alanlarını da doldurun.
4. **Oluştur** butonuna tıklayın.

## Doküman Talebi Oluşturma {#dokuman-talebi-olusturma}

!!! note "Rol"
    Süreç Yöneticisi, Kalite Sorumlusu

1. **Doküman Yönetimi** > **Doküman Talepleri** menüsüne girin.
2. **Doküman Talebi Oluştur** butonuna tıklayın.
3. **Talep Eden Birim** alanını seçin.
4. **Talep Türü** alanından birini seçin: **Doküman Ekle**, **Doküman Güncelle** ya da **Doküman İptali**.
   Güncelleme ve iptal taleplerinde **Doküman Kodu** alanını doldurun.
5. **Doküman Adı**, **Doküman Türü**, **Süreç**, **Süreç Faaliyeti**, **Gerekçe** ve gerekiyorsa **Öneri** alanlarını
   doldurun.
6. **Doküman** alanına doküman dosyasını yükleyin. Seçilen doküman türü kanıt istiyorsa **Kanıt** alanı görünür;
   kanıt dosyalarını buraya yükleyin.
7. Formun altında onay kutusu varsa işaretleyin.
8. **Oluştur** butonuna tıklayın.

## Doküman Talebini Değerlendirme {#dokuman-talebini-degerlendirme}

Talep sırasıyla şu kişilerin onayına gelir: talep eden birimin Süreç Yöneticisi, sürecin sorumlu biriminin Süreç
Yöneticisi, Admin.

!!! note "Rol"
    Süreç Yöneticisi, Admin

1. **Doküman Yönetimi** > **Doküman Talepleri** menüsüne girin.
2. Gerekirse **Özel Filtreler** alanından **Onay Bekleyen Talepler** seçeneğini seçip **Arama Yap** butonuna tıklayın.
3. Talebin satırındaki **Göster** butonuna tıklayın.
4. **Doküman Talebini Değerlendir** butonuna tıklayın.
5. **Doküman Talebini Onaylıyor Musunuz?** alanından **Evet** ya da **Hayır** seçin, **Değerlendirme** alanını doldurun.
6. **Oluştur** butonuna tıklayın.

Verilen kararlar talep sayfasındaki **Doküman Talebinin Değerlendirilmesi** panelinde listelenir.

## Onaylanan Talebi Sonuçlandırma {#onaylanan-talebi-sonuclandirma}

!!! note "Rol"
    Admin

1. Talebi sonuçlandırın:
    - **Doküman Ekle** / **Doküman Güncelle** talepleri: gerekiyorsa dokümanı [oluşturun](#dokuman-olusturma), ardından
      dokümana **Dosya Ekle** ile dosyayı ekleyin ve bu formdaki **Doküman Talebi** alanından talebi seçin.
    - **Doküman İptali** talepleri: dokümanı **Düzenle** ile açın, **Durum** alanını **Pasif** yapın; açılan **Gerekçe**
      ve **Doküman Talebi** alanlarını doldurun.
2. **Doküman Talepleri** listesinde talebin satırındaki **Göster** butonuna tıklayın.
3. **Durumunu Güncelle** butonundan **Tamamlandı** seçin.

Talep listesini indirmek için **Doküman Talepleri** sayfasında **Excel Dosyası Olarak İndir** butonuna tıklayın.
