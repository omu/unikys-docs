# İç Kontrol

Bu modül, iç kontrol standartlarının ve faaliyetlerinin yönetimini sağlar. Kamu iç kontrol standartlarına uyum bu modül üzerinden takip edilir.

!!! info "Erişim"
    Bu modüle **Admin**, **SGDB Admin**, **Üniversite Yönetimi**, **İç Kontrol Sorumlusu** ve **İç Kontrol Onay Yetkisi** rolleri erişebilir.

## Alt Menüler

### İç Kontrol Faaliyetleri

İç kontrol kapsamında yürütülen faaliyetlerin takip edildiği bölüm.

**İşlevler:**

- Faaliyet listesini görüntüleme
- Faaliyet durumunu güncelleme
- Kanıt dokümanları ekleme
- İlerleme takibi

---

### İç Kontrol Yönetimi

İç kontrol standartlarının tanımlandığı ve yönetildiği bölüm.

!!! note "Erişim"
    Sadece **Admin** ve **SGDB Admin** tarafından yönetilebilir.

**İç Kontrol Yapısı:**

```
İç Kontrol Sistemi
├── Kontrol Ortamı
│   ├── Standart 1: Etik Değerler ve Dürüstlük
│   ├── Standart 2: Misyon, Organizasyon Yapısı
│   └── ...
├── Risk Değerlendirme
│   └── ...
├── Kontrol Faaliyetleri
│   └── ...
├── Bilgi ve İletişim
│   └── ...
└── İzleme
    └── ...
```

**İç Kontrol Standardı Oluşturma:**

1. **İç Kontrol > İç Kontrol Yönetimi** menüsüne gidin
2. İlgili bileşene tıklayın
3. **Yeni Standart Ekle** butonuna tıklayın
4. Standart bilgilerini girin
5. Alt maddeleri tanımlayın
6. **Kaydet** butonuna tıklayın

---

### İç Kontrol Eylem Planları

İç kontrol kapsamında planlanan eylemlerin yönetildiği bölüm.

**Eylem Planı Görüntüleme:**

1. **İç Kontrol > İç Kontrol Eylem Planları** menüsüne gidin
2. İlgili yılı seçin
3. Eylem planını görüntüleyin
4. İlerleme durumunu takip edin

---

### Birime Özel İç Kontrol Eylem Planları

Birim bazında atanmış iç kontrol faaliyetlerinin görüntülendiği bölüm.

!!! note "Erişim"
    Bu menü sadece birime özel iç kontrol faaliyeti atanmış kullanıcılar tarafından görülebilir.

---

## İç Kontrol Bileşenleri

| Bileşen | Açıklama |
|---------|----------|
| **Kontrol Ortamı** | Kurumun iç kontrol kültürü ve ortamı |
| **Risk Değerlendirme** | Risklerin tanımlanması ve analizi |
| **Kontrol Faaliyetleri** | Risklere karşı alınan önlemler |
| **Bilgi ve İletişim** | Bilgi akışı ve iletişim kanalları |
| **İzleme** | Sistemin etkinliğinin değerlendirilmesi |

---

## Faaliyet Durumları

| Durum | Açıklama |
|-------|----------|
| Planlandı | Henüz başlanmamış |
| Devam Ediyor | Aktif çalışma var |
| Tamamlandı | Faaliyet tamamlandı |
| Onay Bekliyor | Onay sürecinde |
| Onaylandı | Onay verildi |

---

## Faaliyet Güncelleme

1. İlgili faaliyetin detay sayfasına gidin
2. **Güncelle** butonuna tıklayın
3. İlerleme durumunu girin
4. Kanıt dokümanlarını ekleyin
5. **Kaydet** butonuna tıklayın

!!! warning "Kanıt Önemi"
    Her faaliyet için destekleyici kanıt dokümanları eklenmelidir. Kanıtsız faaliyetler tamamlanmış sayılmaz.

---

## Onay Süreci

```
1. Sorumlu faaliyeti tamamlar
   ↓
2. Kanıt dokümanlarını yükler
   ↓
3. Onaya sunar
   ↓
4. Onay yetkisi değerlendirir
   ↓
5. Onay/Red kararı verilir
```

---

## Raporlama

İç kontrol ile ilgili raporlara **Raporlar** menüsünden erişebilirsiniz:

- İç kontrol genel durum raporu
- Bileşen bazlı ilerleme raporu
- Birim bazlı faaliyet raporu
