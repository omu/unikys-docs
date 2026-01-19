# Roller ve Yetkiler

Ünikys sisteminde farklı yetki seviyelerine sahip kullanıcı rolleri bulunmaktadır. Bu sayfa, tüm rolleri ve erişim haklarını açıklamaktadır.

## Rol Kategorileri

### Yönetim Rolleri

| Rol | Açıklama | Yetki Kapsamı |
|-----|----------|---------------|
| **Admin** | Sistem yöneticisi | Tüm modüllere ve ayarlara tam erişim |
| **Süper Admin** | Gelişmiş sistem yöneticisi | Admin + demo ayarları |
| **Üniversite Yönetimi** | Üst düzey yönetim | Tüm modüllere okuma ve yazma erişimi |
| **SGDB Admin** | İç kontrol sistem yöneticisi | İç kontrol modülü yönetimi |

### Veri ve Gösterge Rolleri

| Rol | Açıklama | Yetki Kapsamı |
|-----|----------|---------------|
| **Veri ve Göstergeler Admin** | Veri modülü yöneticisi | Gösterge etiketleri, kurumsal veriler, dönemler |
| **Kalite Temsilcisi** | Birim kalite sorumlusu | Veri girişi, hedef girişi |
| **Etiket Sorumlusu** | Gösterge etiketi sorumlusu | Üst hedef girişi, yönetim görevleri |

### Süreç Rolleri

| Rol | Açıklama | Yetki Kapsamı |
|-----|----------|---------------|
| **Süreç Koordinatörü** | Süreç koordinasyonu | Süreç yönetimi, fırsatlar |
| **Süreç Sorumlusu** | Birim süreç sorumlusu | Benim süreçlerim, riskler, DİF |
| **Süreç Temsilcisi** | Birim süreç temsilcisi | Benim süreçlerim, belge talepleri |

### Denetim Rolleri

| Rol | Açıklama | Yetki Kapsamı |
|-----|----------|---------------|
| **İç Denetçi** | Denetim yapan kullanıcı | Denetçi görevleri, geri bildirimler |
| **İç Denetim Ekip Lideri** | Denetim ekip lideri | Denetçi görevleri, ekip yönetimi |
| **Komisyon Üyesi** | Değerlendirme komisyonu üyesi | Komisyon değerlendirmeleri |

### İç Kontrol Rolleri

| Rol | Açıklama | Yetki Kapsamı |
|-----|----------|---------------|
| **İç Kontrol Sorumlusu** | Birim iç kontrol sorumlusu | İç kontrol faaliyetleri, eylem planları |
| **İç Kontrol Onay Yetkisi** | İç kontrol onay yapan | İç kontrol onayları |

### Diğer Roller

| Rol | Açıklama | Yetki Kapsamı |
|-----|----------|---------------|
| **Yönetici** | Birim yöneticisi | Birim bilgileri, birim belgeleri |
| **Paydaş İletişim Sorumlusu** | Paydaş iletişimi | Geri bildirimler |

---

## Modül Erişim Matrisi

Aşağıdaki tablo, hangi rollerin hangi modüllere erişebildiğini göstermektedir.

| Modül | Admin | Ünv. Yön. | Süreç Sor. | Süreç Tem. | Kalite Tem. |
|-------|:-----:|:---------:|:----------:|:----------:|:-----------:|
| Veri ve Göstergeler | ✓ | ✓ | - | - | - |
| Veri Girişi | - | - | - | - | ✓ |
| Veri Onayı | - | - | ✓ | - | - |
| Süreç Yönetimi | ✓ | ✓ | ✓ | ✓ | - |
| Risk Yönetimi | ✓ | ✓ | ✓ | ✓ | - |
| Geri Bildirimler | ✓ | ✓ | ✓ | ✓ | - |
| İç Değerlendirme | ✓ | ✓ | ✓ | - | - |
| İç Denetim | ✓ | ✓ | - | - | - |
| İyileştirme | ✓ | ✓ | ✓ | ✓ | - |
| Eylem Planı | ✓ | ✓ | ✓ | ✓ | - |
| İç Kontrol | ✓ | ✓ | - | - | - |
| Belge Yönetimi | ✓ | ✓ | ✓ | ✓ | - |
| Duyurular | ✓ | ✓ | - | - | - |
| Raporlar | ✓ | ✓ | ✓ | ✓ | - |
| Ayarlar | ✓ | ✓ | - | - | - |

!!! note "Not"
    - ✓: Erişim var
    - -: Erişim yok
    - Bazı modüller birim bazlı erişim kontrolüne sahiptir

---

## Birim Bazlı Roller

Bazı roller birim bazında atanır. Kullanıcı, atandığı birimlerdeki verilere erişebilir.

**Birim bazlı roller:**

- Kalite Temsilcisi
- Süreç Sorumlusu
- Süreç Temsilcisi
- İç Kontrol Sorumlusu
- İç Kontrol Onay Yetkisi
- Yönetici

!!! info "Birim Grupları"
    Birimler grup olarak da tanımlanabilir. Bir gruba atanan kullanıcı, o gruptaki tüm birimlerin verilerine erişebilir.

---

## Rol Atama

Kullanıcılara rol atamak için:

1. **Ayarlar > Kullanıcı Yönetimi** menüsüne gidin
2. İlgili kullanıcıyı bulun
3. **Roller** sekmesine tıklayın
4. Atamak istediğiniz rolleri seçin
5. Birim bazlı roller için ilgili birimi de seçin
6. **Kaydet** butonuna tıklayın

!!! warning "Dikkat"
    Rol atamaları sadece Admin tarafından yapılabilir.
