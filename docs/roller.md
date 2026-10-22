# Roller ve Yetkiler

Ünikys'te 16 sabit rol vardır. Ayrıca Admin, **Ayarlar** > **Rol Tanımları** ekranında menü bazlı roller oluşturup
kullanıcılara atayabilir. Rolünüze göre hangi bölümleri okumanız gerektiği için bkz.
[Rolüme Göre Kılavuz](rolume-gore.md).

## Roller nereden atanır {#rol-atama}

| Rol | Atayan | Atandığı yer |
|-----|--------|--------------|
| Admin, Üniversite Yöneticisi, SGDB Admini, Veri ve Göstergeler Admini | Süper Admin | **Ayarlar** > **Kullanıcılar** > kullanıcı > **Global Roller** |
| Veri Giriş Yetkilisi, Süreç Yöneticisi, Kalite Sorumlusu, Rapor Yetkilisi, Paydaş İletişim Görevlisi, İç Kontrol Onay Yetkilisi, İç Kontrol Sorumlusu | Admin | **Ayarlar** > **Birim Sorumluları** |
| Süreç Koordinatörü | Admin | Süreç formundaki **Süreç Koordinatörü** alanı ([Süreç Yönetimi](moduller/surec-yonetimi.md)) |
| Etiket Sorumlusu | Admin, Veri ve Göstergeler Admini | Gösterge etiketi formundaki **Etiket Sorumluları** alanı ([Veri ve Göstergeler](moduller/veri-gostergeler.md)) |
| Komisyon Üyesi | Admin | İç değerlendirme başlığındaki **Sorumlu Komisyon Üyeleri** alanı ([İç Değerlendirme](moduller/ic-degerlendirme.md)) |
| İç Tetkikçi | Admin | İç tetkikçi başvurusunun onaylanması ya da **İç Tetkikçiler** ekranından ekleme; ekip lideri ve tetkikçi görevleri **İç Tetkikçi Birim Eşleştirmeleri** ekranında verilir ([İç Tetkik](moduller/ic-tetkik.md)) |
| Rol Tanımları ile oluşturulan roller | Admin | **Ayarlar** > **Kullanıcılar** > kullanıcı > **Tanımlı Roller** |

Atama adımları: [Ayarlar](moduller/ayarlar.md).

## Genel roller

### Süper Admin
- Admin'in yapabildiği tüm işlemleri yapar.
- Kullanıcılara **Global Roller** atar: Admin, Üniversite Yöneticisi, SGDB Admini, Veri ve Göstergeler Admini.

### Admin
- Tüm modüllerde tanımlama, düzenleme ve silme işlemlerini yapar.
- Birim rollerini (**Birim Sorumluları**) ve **Tanımlı Roller**i atar; **Rol Tanımları** oluşturur.
- İç Değerlendirme ve İç Tetkik gibi dönemsel çalışmalarda kullanıcıları görevlendirir.
- Duyuru, takvim, dönem, birim ve birim grubu ekler; aktif yılı belirler ve modüllerde önceki yıldan kopyalama yapar.
- Raporlara ve **Aktiviteler** ekranına erişir.
- Admin global rol atayamaz; bu işlemi Süper Admin yapar.

### Üniversite Yöneticisi
- Modüllerin içeriklerini görüntüler.
- Birimlere yönetim görevi verir ([İyileştirme Yönetimi](moduller/iyilestirme.md)).

### Veri ve Göstergeler Admini
- **Veri ve Göstergeler** modülünde gösterge etiketi, kurumsal veri ve kurumsal gösterge tanımlar, düzenler ve siler.
- Birimlerin kurumsal veri ve hedef değerlerini ekler, düzenler ve siler.
- **Ayarlar** > **Dönemler** ekranını yönetir.
- Gösterge etiketlerine Etiket Sorumlusu atar.

### SGDB Admini
- **İç Kontrol** modülünde tanımlama, düzenleme ve silme işlemlerini yapar.

## Birim rolleri

### Süreç Yöneticisi
Birimde süreçlerle ilgili işlemleri yürüten kullanıcıdır. Bir birime en fazla bir Süreç Yöneticisi atanır.

- Birimin kurumsal veri ve hedeflerini onaylar (**Veri ve Hedef Onayı**).
- Birime özel risk tanımlar ve onaylar; riskten DİF oluşturur.
- Birime gelen geri bildirimler için işlem yapar.
- Birim İç Değerlendirme Raporu'nu (BİDR) yazar ve kanıtlarını yükler.
- İç tetkik raporunu onaylar, birime gelen iç tetkikçileri değerlendirir.
- Düzeltme ve DİF oluşturur; DİF onay işlemlerini yapar.
- Yönetim görevleri ve yıllık eylem planı üzerinden DİF oluşturur.
- Toplantı ve karar kayıtlarını girer.
- Doküman talebi oluşturur ve biriminin doküman taleplerini onaylar.
- Biriminin raporlarına erişir.

### Kalite Sorumlusu
Birimde süreçlerle ilgili işlemleri görüntüleyen ve işlem başlatan kullanıcıdır.

- Birime özel risk tanımlayıp Süreç Yöneticisi'nin onayına gönderir; riskten DİF oluşturur.
- Birime gelen geri bildirimler için işlem yapar.
- Düzeltme ve DİF oluşturur.
- Yönetim görevleri ve yıllık eylem planı üzerinden DİF oluşturur.
- Toplantı ve karar kayıtlarını girer.
- Doküman talebi oluşturur.
- Biriminin raporlarına erişir.

### Veri Giriş Yetkilisi
- Birimin kurumsal veri ve hedef girişlerini yapar, kanıt dosyalarını yükler ve onaya gönderir.

### Rapor Yetkilisi
- **Birim** > **Birimim** ekranında birimin personel listesini düzenler.
- **Birim Dokümanları** ekranında birime ait kategori ve dokümanları yönetir.
- Biriminin raporlarına erişir.

### Paydaş İletişim Görevlisi
- Farklı kaynaklardan gelen geri bildirimleri sisteme kaydeder ve kaydettiği geri bildirimleri düzenler.

### İç Kontrol Sorumlusu
- Birimi için iç kontrol faaliyeti (İKF) oluşturur ve adımlarını tamamlar.

### İç Kontrol Onay Yetkilisi
- Birimin iç kontrol faaliyetlerini (İKF) onaylar ya da reddeder.

## Görevlendirmeyle verilen roller

### Süreç Koordinatörü
- Sorumlu olduğu süreçle ilgili tüm faaliyetleri görüntüler.
- Süreciyle ilgili açılan DİF'lerin son onayını verir.

### Etiket Sorumlusu
- Sorumlu olduğu gösterge etiketi için üniversite adına üst hedef girer (**Üst Hedef Girişi**).
- Birimlere yönetim görevi verir.

### İç Tetkikçi
- İç tetkik için görevlendirildiği birimlerde ekip lideri ya da tetkikçi olarak çalışır.
- **İç Tetkikçi Birim Eşleştirmeleri** ekranında **Ekip Lideri** olarak atanan iç tetkikçi, ön hazırlık kontrol
  listesini ve birim değerlendirmesini yanıtlar.
- Tetkik sorularını yanıtlar, iç tetkik raporunu oluşturur ve onaylar.
- Görevlendirildiği birimlerin raporlarına erişir.

### Komisyon Üyesi
- Birimlerin BİDR'lerini ve kanıtlarını görüntüler.
- Sorumlu olduğu başlıklar için Kurum İç Değerlendirme Raporu (KİDR) metnini ve kanıtlarını girer.
- KİDR giriş dönemi süresince raporlara erişir.

## Rol Tanımları {#rol-tanimlari}

Admin, **Ayarlar** > **Rol Tanımları** ekranında yeni bir rol oluşturur ve bu role menü bazında **Okuma**, **Yazma**
ve **Rapor** yetkileri verir. Oluşturulan rol, kullanıcının sayfasındaki **Tanımlı Roller** alanından atanır. Rolü
atanan kullanıcı, rol tanımında yetki verilen menüleri görür.

Adım adım anlatım: [Ayarlar](moduller/ayarlar.md).
