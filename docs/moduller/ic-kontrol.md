# İç Kontrol

Kamu iç kontrol standartlarına uyum eylem planlarının ve iç kontrol faaliyetlerinin (İKF) yürütüldüğü modüldür.

!!! warning "Not"
    Bu modül SGDB sorumluluğundadır; içeriği SGDB ile birlikte güncellenecektir.

## Bu sayfayı kimler kullanır

| Rol | Yapacağı işler |
|-----|----------------|
| Admin, SGDB Admini | [İç kontrol tanımlama](#ic-kontrol-tanimlama) |
| Admin | [İKF oluşturma](#ikf-olusturma), [İKF onayı](#ikf-onayi) |
| İç Kontrol Sorumlusu | [İKF oluşturma](#ikf-olusturma), [Faaliyet adımlarını tamamlama](#faaliyet-adimlarini-tamamlama) |
| İç Kontrol Onay Yetkilisi | [İKF onayı](#ikf-onayi) |

## İç kontrol tanımlama {#ic-kontrol-tanimlama}

!!! note "Rol"
    Admin, SGDB Admini

1. **İç Kontrol** > **İç Kontrol Yönetimi** menüsüne girin.
2. **Yeni İç Kontrol** butonuna tıklayın.
3. **İsim**, **Açıklama** ve **Durum** alanlarını doldurun. Birime özel bir iç kontrol için **İlgili Birimler** alanından
   birimleri seçin; boş bırakılırsa genel iç kontrol olur.
4. **Oluştur** butonuna tıklayın.
5. İç kontrolün sayfasında **Yeni Bileşen** butonuyla bileşenleri ekleyin.
6. Her bileşenin sayfasında **Yeni Standart**, her standardın sayfasında **Yeni Genel Şart** butonunu kullanın.
7. Genel şartın sayfasında **Yeni Eylem** butonuna tıklayın. **Kod No**, **Öngörülen Eylem veya Eylemler**,
   **Sorumlu Birimler**, **İşbirliği Yapılacak Birim**, **Çıktı/Sonuç**, **Tamamlanma Tarihi** ve **Açıklama**
   alanlarını doldurun ve **Oluştur** butonuna tıklayın.

İç kontrolün tamamını indirmek için iç kontrolün sayfasında **Excel İndir** butonuna tıklayın.

## İKF oluşturma {#ikf-olusturma}

!!! note "Rol"
    Admin, İç Kontrol Sorumlusu

1. **İç Kontrol** > **İdare Kamu İç Kontrol Standartlarına Uyum Eylem Planı** (birime özel plan için
   **Birim İç Kontrol Standartlarına Uyum Eylem Planı**) menüsüne girin.
2. Plan listesi açılırsa ilgili planın satırında **Detay** butonuna tıklayın.
3. İlgili eylemin satırında **İç Kontrol Faaliyeti (İKF) Oluştur** butonuna tıklayın.
4. **Birim** alanını kontrol edin (**İç Kontrol Eylemi** seçtiğiniz eylemle hazır gelir) ve **Uygulanması Planlanan
   Faaliyet** alanını doldurun.
5. **Faaliyet Adımı Ekle** butonuyla adımları ekleyin. Her adım için **Faaliyet Adımı** ve **Tamamlanma Tarihi**
   alanlarını doldurun.
6. **Oluştur** butonuna tıklayın.

Oluşturulan İKF'ler **İç Kontrol** > **İç Kontrol Faaliyetleri (İKF)** menüsünde listelenir.

## İKF onayı {#ikf-onayi}

!!! note "Rol"
    İç Kontrol Onay Yetkilisi, Admin

1. **İç Kontrol** > **İç Kontrol Faaliyetleri (İKF)** menüsüne girin.
2. İlgili İKF'nin satırında **Göster** butonuna tıklayın.
3. **İKF'yi Onayla/Reddet** butonuna tıklayın.
4. **İKF'yi Onaylıyor Musunuz?** alanından **Evet** ya da **Hayır** seçin, **Değerlendirme** alanını doldurun ve
   **Oluştur** butonuna tıklayın.

## Faaliyet adımlarını tamamlama {#faaliyet-adimlarini-tamamlama}

!!! note "Rol"
    İç Kontrol Sorumlusu

1. **İç Kontrol** > **İç Kontrol Faaliyetleri (İKF)** menüsünden onaylanmış İKF'nin sayfasını açın.
2. İlgili adımın satırında **Tamamla** butonuna tıklayın.
3. **Faaliyet Adımı Tamamlandı Mı?** alanını seçin, **Açıklama** alanını doldurun, gerekiyorsa **Kanıt** yükleyin ve
   **Oluştur** butonuna tıklayın.

Yapılan tamamlamayı geri almak için **Tamamlamayı Sil** butonunu kullanın.

İç kontrol raporları için [Raporlar](raporlar.md) sayfasına bakın.
