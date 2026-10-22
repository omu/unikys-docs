# Risk ve Fırsat Yönetimi

Kurumsal ve birim risklerinin, fırsatların, hususların ve ilgili tarafların tanımlandığı modüldür.

!!! warning "Not"
    2027 yılından itibaren bu modülün işlemleri SGDB tarafından yürütülecektir; bu bölüm SGDB tarafından güncellenecektir.

## Bu sayfayı kimler kullanır

| Rol | Yapacağı işler |
|-----|----------------|
| Admin | [Risk seviyeleri](#risk-seviyeleri), [Fırsatlar](#firsatlar), [Hususlar ve ilgili taraflar](#hususlar-ve-ilgili-taraflar), [Kurumsal risk oluşturma](#risk-olusturma), [Risk onayı](#risk-onayi), [Risk işlemlerini izleme](#risk-islemlerini-izleme) |
| Kalite Sorumlusu, Süreç Yöneticisi | [Birim riski oluşturma](#risk-olusturma), [Riskten DİF oluşturma](#riskten-dif-olusturma), [Riski güncelleme](#riski-guncelleme) |
| Süreç Yöneticisi | [Risk onayı](#risk-onayi) |
| Kalite Sorumlusu, Süreç Yöneticisi, Süreç Koordinatörü | [Fırsatlarım](#firsatlar) |

!!! info "Seçili yıl"
    **Risk Seviyeleri** ekranındaki kopyalama, oluşturma, düzenleme ve silme butonları, **Eksik Fırsatları Önceki
    Yıldan Kopyala** ve **Riskler** ekranındaki
    **Risk Oluştur** butonu yalnızca üst çubuktaki **Seçili Yıl** aktif yıl olduğunda görünür.

## Risk seviyeleri {#risk-seviyeleri}

!!! note "Rol"
    Admin

1. **Risk ve Fırsat Yönetimi** > **Risk Seviyeleri** menüsüne girin.
2. Önceki yılın seviyelerini almak için **Eksik Risk Seviyelerini Önceki Yıldan Kopyala** butonuna tıklayın.
3. Yeni seviye eklemek için **Risk Seviyesi Oluştur** butonuna tıklayın.
4. **Risk Seviyesi**, **Başlangıç**, **Bitiş**, **Renk** ve **Açıklama** alanlarını doldurun ve **Oluştur** butonuna tıklayın.

Seviyelerin tablo görünümü için **Risk Matrisi** butonuna tıklayın.

## Fırsatlar {#firsatlar}

!!! note "Rol"
    Admin

1. **Risk ve Fırsat Yönetimi** > **Fırsatlar** menüsüne girin.
2. Önceki yılın fırsatlarını almak için **Eksik Fırsatları Önceki Yıldan Kopyala** butonuna tıklayın.
3. Yeni fırsat eklemek için **Fırsat Oluştur** butonuna tıklayın.
4. **Fırsat**, **Süreç**, **Süreç Faaliyeti** ve **Birimler** alanlarını doldurun ve **Oluştur** butonuna tıklayın.

Bir fırsatı pasif yapmak için fırsatın sayfasında **Durumunu Güncelle** butonunu kullanın.

Kalite Sorumlusu, Süreç Yöneticisi ve Süreç Koordinatörü, kendileriyle ilgili fırsatları **Risk ve Fırsat Yönetimi** >
**Fırsatlarım** menüsünden görüntüler.

## Hususlar ve ilgili taraflar {#hususlar-ve-ilgili-taraflar}

!!! note "Rol"
    Admin

**Husus:**

1. **Risk ve Fırsat Yönetimi** > **Hususlar** menüsüne girin.
2. **Husus Oluştur** butonuna tıklayın.
3. **Husus** alanını doldurun, **Husus Türü** alanından **İç Husus** veya **Dış Husus** seçin ve **Oluştur** butonuna
   tıklayın.

**İlgili taraf:**

1. **Risk ve Fırsat Yönetimi** > **İlgili Taraflar** menüsüne girin.
2. **İlgili Taraf Oluştur** butonuna tıklayın.
3. **İlgili Taraf** alanını doldurun, **İlgili Taraf Türü** alanından **Etkileyen** veya **Etkilenen** seçin ve
   **Oluştur** butonuna tıklayın.

## Risk oluşturma {#risk-olusturma}

Kurumsal riskleri admin, birim risklerini Kalite Sorumlusu veya Süreç Yöneticisi oluşturur.

!!! note "Rol"
    Admin (**Riskler** menüsünden), Kalite Sorumlusu ve Süreç Yöneticisi (**Risklerim** menüsünden)

1. **Risk ve Fırsat Yönetimi** > **Riskler** (birim riski için **Risklerim**) menüsüne girin.
2. **Risk Oluştur** butonuna tıklayın.
3. **Risk**, **Risk Türü**, **Süreç** ve **Süreç Faaliyeti** alanlarını doldurun.
4. **İç Husus**, **Dış Husus**, **Etkileyen Taraf** ve **Etkilenen Taraf** alanlarından ilgili olanları seçin.
5. **Birim İçin Olasılık ve Etki Ekle** butonuna tıklayın; **Birim**, **Olasılık** ve **Etki** alanlarını doldurun.
   Birden çok birim için bu adımı tekrarlayın.
6. **Oluştur** butonuna tıklayın.

## Risk onayı {#risk-onayi}

Kalite Sorumlusu'nun oluşturduğu birim riskleri önce birimin Süreç Yöneticisi, ardından Admin tarafından onaylanır.

!!! note "Rol"
    Süreç Yöneticisi, Admin

1. Riskin sayfasını açın (**Risklerim** veya **Riskler** listesinde **Göster**).
2. **Risk'i Onayla** butonuna tıklayın.
3. **Risk'i Onaylıyor Musunuz?** alanından **Evet** veya **Hayır** seçin ve **Değerlendirme** alanını doldurun.
4. Admin ayrıca **Süreç Kartında Görünsün Mü?** alanını seçer.
5. **Oluştur** butonuna tıklayın.

Admin, onaylanmış bir riskin süreç kartında görünürlüğünü **Onayı Düzenle** butonuyla değiştirebilir.

## Riskten DİF oluşturma {#riskten-dif-olusturma}

!!! note "Rol"
    Kalite Sorumlusu, Süreç Yöneticisi

1. **Risk ve Fırsat Yönetimi** > **Risklerim** menüsüne girin.
2. İlgili riskin satırında **DİF Oluştur** butonuna tıklayın.
3. Formu doldurun ve **Oluştur** butonuna tıklayın. DİF formu [İyileştirme Yönetimi](iyilestirme.md) sayfasında
   anlatılır.

## Riski güncelleme {#riski-guncelleme}

Riskten açılan DİF tamamlandıktan sonra **Risklerim** ekranında **Riski Güncelle** butonu görünür.

!!! note "Rol"
    Kalite Sorumlusu, Süreç Yöneticisi

1. **Risk ve Fırsat Yönetimi** > **Risklerim** menüsüne girin.
2. İlgili riskin satırında **Riski Güncelle** butonuna tıklayın.
3. **Risk Güncelleme Açıklaması** alanını doldurun.
4. **Bildirim Türü** alanından **Güncelle** veya **Pasifleştir** seçin. **Güncelle** seçildiyse yeni **Olasılık** ve
   **Etki** değerlerini girin.
5. **DİF** alanını seçin ve **Oluştur** butonuna tıklayın.

Pasifleştirilen riskler **Risk ve Fırsat Yönetimi** > **Pasif Riskler** menüsünde listelenir.

## Risk işlemlerini izleme {#risk-islemlerini-izleme}

!!! note "Rol"
    Admin

- **Risk ve Fırsat Yönetimi** > **Risk Aktiviteleri**: risklerle ilgili tüm işlemler listelenir.
- **Risk ve Fırsat Yönetimi** > **Risk Güncelleme Formları**: DİF sonrasında yapılan risk güncellemeleri listelenir.
- **Risk ve Fırsat Yönetimi** > **Riskler**: tüm riskler listelenir. **Özel Filtreler** alanıyla liste daraltılabilir.
  Birimlerin puanlarını görmek için riskin sayfasında **Birim Puanları** butonuna tıklayın.

Risk raporu için [Raporlar](raporlar.md) sayfasındaki **Risk Raporu** bölümüne bakın.
