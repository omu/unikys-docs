# Toplantı Karar Yönetimi

Bu modülde birim toplantıları gündemleriyle kaydedilir, alınan kararlar ve kararların takibi girilir.

## Bu sayfayı kimler kullanır

| Rol | Yapacağı işler |
|-----|----------------|
| Admin | [Toplantı Türleri](#toplanti-turleri), [Stratejik Plan Tanımlama](#stratejik-plan-tanimlama), [Toplantı Oluşturma](#toplanti-olusturma), [Gerçekleşme Bilgilerini Girme](#gerceklesme-bilgilerini-girme), [Aksiyon Oluşturma](#aksiyon-olusturma), [Karar Listesi](#karar-listesi), [Rapor](#rapor) |
| Süreç Yöneticisi, Kalite Sorumlusu | [Toplantı Oluşturma](#toplanti-olusturma), [Gerçekleşme Bilgilerini Girme](#gerceklesme-bilgilerini-girme), [Aksiyon Oluşturma](#aksiyon-olusturma), [Karar Listesi](#karar-listesi), [Rapor](#rapor) |
| Üniversite Yöneticisi | Toplantıları, kararları ve raporu görüntüler. |

!!! tip "İşlem sırası"
    Toplantı oluşturmadan önce Admin tarafından toplantı türleri ve stratejik plan tanımlanmış olmalıdır. Gündem
    maddesindeki **İlgili YÖKAK ölçütü** listesi için durumu **Aktif** bir iç değerlendirme, **İlgili süreç** listesi
    için o yılın süreç kartları tanımlı olmalıdır.

## Toplantı Türleri {#toplanti-turleri}

!!! note "Rol"
    Admin

1. **Toplantı Karar Yönetimi** > **Toplantı Türleri** menüsüne girin.
2. **Yeni Toplantı Türü** butonuna tıklayın.
3. **Adı** alanını doldurun, **Durumu** alanından **Aktif** seçin.
4. **Oluştur** butonuna tıklayın.

Kullanılmayacak bir türü **Düzenle** ile açıp **Durumu** alanını **Pasif** yapabilirsiniz.

## Stratejik Plan Tanımlama {#stratejik-plan-tanimlama}

!!! note "Rol"
    Admin

### Stratejik plan oluşturma

1. **Toplantı Karar Yönetimi** > **Stratejik Plan Tanımlama** menüsüne girin.
2. **Yeni Stratejik Plan Oluştur** butonuna tıklayın.
3. **Stratejik Plan Adı** ve **Başlangıç Yılı** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın.

### Stratejik amaç ekleme

1. Stratejik planın satırındaki **Göster** butonuna tıklayın.
2. **Stratejik Amaçlar** panelinde **Yeni Stratejik Amaç Oluştur** butonuna tıklayın.
3. **Kod** ve **Amaç** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın.

### Stratejik hedef ekleme

1. Stratejik amacın satırındaki **Göster** butonuna tıklayın.
2. **Stratejik Hedefler** panelinde **Yeni Stratejik Hedef Oluştur** butonuna tıklayın.
3. **Kod** ve **Hedef** alanlarını doldurun.
4. **Oluştur** butonuna tıklayın.

## Toplantı Oluşturma {#toplanti-olusturma}

!!! note "Rol"
    Admin, Süreç Yöneticisi, Kalite Sorumlusu

1. **Toplantı Karar Yönetimi** > **Toplantılar** menüsüne girin.
2. **Toplantı Oluştur** butonuna tıklayın.
3. **Toplantı Bilgileri** panelinde **Birim**, **Türü**, **Tarih** ve gerekiyorsa **Oturum** alanlarını doldurun.
   **Sayı** alanı otomatik verilir.
4. **Gündem** bölümündeki ilk gündem maddesinin alanlarını doldurun:
    - **Gündem açıklaması**
    - **İlgili süreç**
    - **İlgili YÖKAK ölçütü**
    - **İlgili Stratejik Plan**, **İlgili SP Amacı**, **İlgili SP Hedefi**
5. Başka gündem maddesi eklemek için **+ Ekle** butonuna tıklayıp aynı alanları doldurun. Yanlış eklenen maddeyi
   **Gündemi Kaldır** ile silebilirsiniz.
6. **Oluştur** butonuna tıklayın.

## Gerçekleşme Bilgilerini Girme {#gerceklesme-bilgilerini-girme}

!!! note "Rol"
    Admin, Süreç Yöneticisi, Kalite Sorumlusu

1. **Toplantı Karar Yönetimi** > **Toplantılar** menüsüne girin.
2. Toplantının satırındaki **Gerçekleşme** butonuna tıklayın. (Toplantı detayında **Gerçekleşme Bilgilerini Gir**
   butonu da aynı ekranı açar.)
3. **Katılımcı sayısı** alanını doldurun ve **Katılımcı listesi** dosyasını yükleyin.
4. Karar bölümündeki ilk kararın alanlarını doldurun:
    - **İlgili gündem**
    - **Karar açıklaması**
    - **Onay durumu**: **Oy birliği** / **Oy çokluğu**
    - **(Varsa) şerh durumu**
    - **Takip durumu**: **Takipli** / **Takipsiz**
5. **Takipli** seçtiyseniz **Takip görevlisi**, **Sorumlu birim** ve **Termin tarihi** alanlarını doldurun.
6. Başka karar eklemek için **+ Ekle** butonuna tıklayıp 4. ve 5. adımları tekrarlayın. Yanlış eklenen kararı
   **Kararı Kaldır** ile silebilirsiniz.
7. **Toplantı kararlar tutanağı** dosyasını yükleyin.
8. **Kaydet** butonuna tıklayın.

Bilgileri daha sonra toplantı detayındaki **Gerçekleşme Bilgilerini Düzenle** butonuyla güncelleyebilirsiniz.

## Aksiyon Oluşturma {#aksiyon-olusturma}

Aksiyon yalnızca **Takipli** kararlara girilir.

!!! note "Rol"
    Admin, Süreç Yöneticisi, Kalite Sorumlusu

1. **Toplantı Karar Yönetimi** > **Karar Listesi** menüsüne girin. (Toplantı detayındaki **Karar Listesi - Durumu**
   panelini de kullanabilirsiniz.)
2. Kararın satırındaki **Aksiyon Oluştur** butonuna tıklayın.
3. **Açıklama** alanını doldurun, **Gerçekleşme durumu** alanından **Devam Ediyor** ya da **Gerçekleşti** seçin.
4. **Gerçekleşti** seçtiyseniz **Kanıt** dosyasını yükleyin.
5. **Oluştur** butonuna tıklayın.

Kararın girilen aksiyonlarını kararın satırındaki **Göster** butonuyla açılan **Karar Detayı** sayfasında,
**Aksiyonlar** panelinde görebilirsiniz.

## Karar Listesi {#karar-listesi}

!!! note "Rol"
    Admin, Üniversite Yöneticisi, Süreç Yöneticisi, Kalite Sorumlusu

1. **Toplantı Karar Yönetimi** > **Karar Listesi** menüsüne girin.
2. Gerekirse **Birim**, **Sorumlu birim**, **Türü**, **Takip durumu**, **Gerçekleşme durumu** alanlarını seçin,
   **Ara** alanına metin yazın ya da **Termini geçenler** kutusunu işaretleyin.
3. **Ara** butonuna tıklayın. Filtreleri sıfırlamak için **Temizle** butonuna tıklayın.
4. Listeyi indirmek için **Excel'e Aktar** butonuna tıklayın.

## Rapor {#rapor}

!!! note "Rol"
    Admin, Üniversite Yöneticisi, Süreç Yöneticisi, Kalite Sorumlusu

1. **Raporlar** menüsüne girin.
2. **Toplantı Karar İstatistikleri** satırındaki **Göster** butonuna tıklayın.
3. **Birim seç** alanından birim seçin ve **Göster** butonuna tıklayın.
4. Raporu indirmek için **İndir** butonuna tıklayıp **PDF** ya da **Excel** seçin.

Diğer raporlar için [Raporlar](raporlar.md) sayfasına bakınız.
