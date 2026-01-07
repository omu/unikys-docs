# Risk Yönetimi

Bu modül, kurumsal risklerin ve fırsatların tanımlanması, değerlendirilmesi ve takibini sağlar.

!!! info "Erişim"
    Bu modüle **Admin**, **Üniversite Yönetimi** ve **Süreç Rolleri** erişebilir.

## Alt Menüler

### Risk Seviyeleri

Risk değerlendirmesinde kullanılan seviye tanımları.

!!! note "Erişim"
    Sadece **Admin** tarafından yönetilebilir.

**Risk Seviyesi Tanımlama:**

1. **Risk Yönetimi > Risk Seviyeleri** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Seviye adı (örn: Düşük, Orta, Yüksek)
4. Renk kodu belirleyin
5. Puan aralığını girin
6. **Kaydet** butonuna tıklayın

---

### Fırsatlar

Kurumsal fırsatların yönetildiği bölüm.

**İşlevler:**

- Fırsat tanımlama
- Fırsat değerlendirme
- Fırsat takibi

**Fırsat Oluşturma:**

1. **Risk Yönetimi > Fırsatlar** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Fırsat başlığı ve açıklamasını girin
4. İlgili birimi seçin
5. Potansiyel etki değerlendirmesi yapın
6. **Kaydet** butonuna tıklayın

---

### Riskler

Kurumsal risklerin tanımlandığı ve değerlendirildiği bölüm.

**Risk Oluşturma:**

1. **Risk Yönetimi > Riskler** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Risk başlığı ve açıklamasını girin
4. İlgili süreç/birimi seçin
5. Olasılık ve etki değerlendirmesi yapın
6. Risk seviyesi otomatik hesaplanır
7. **Kaydet** butonuna tıklayın

---

### Risk Aktiviteleri

Risklere karşı alınacak önlemlerin planlandığı bölüm.

**Aktivite Oluşturma:**

1. İlgili riskin detay sayfasına gidin
2. **Aktivite Ekle** butonuna tıklayın
3. Aktivite tanımını girin
4. Sorumlu kişiyi belirleyin
5. Hedef tarihi seçin
6. **Kaydet** butonuna tıklayın

---

### Risk Bildirimleri

Belirlenen risklerin onay süreçlerinin yönetildiği bölüm.

---

### Sorunlar

Tespit edilen sorunların kaydedildiği ve takip edildiği bölüm.

---

### İlgili Taraflar

Risk yönetimi sürecindeki paydaşların tanımlandığı bölüm.

---

### Benim Risklerim

Kullanıcının sorumlu olduğu risklerin listelendiği bölüm.

!!! note "Kimler Görebilir?"
    Bu menü sadece **Süreç Rolleri** tarafından görülebilir.

---

### Silinen Riskler

Silinen/arşivlenen risklerin görüntülendiği bölüm.

---

## Risk Değerlendirme Matrisi

Risk seviyesi, olasılık ve etki değerlerine göre hesaplanır:

| | Düşük Etki | Orta Etki | Yüksek Etki |
|---|---|---|---|
| **Yüksek Olasılık** | Orta | Yüksek | Kritik |
| **Orta Olasılık** | Düşük | Orta | Yüksek |
| **Düşük Olasılık** | İhmal Edilebilir | Düşük | Orta |

---

## Risk Yönetim Süreci

```
1. Risk Tanımlama
   ↓
2. Risk Analizi (Olasılık × Etki)
   ↓
3. Risk Değerlendirme (Kabul/Azalt/Transfer/Kaçın)
   ↓
4. Risk İşleme (Aktivite Planlama)
   ↓
5. İzleme ve Gözden Geçirme
```

!!! warning "Periyodik Gözden Geçirme"
    Riskler en az yılda bir kez gözden geçirilmelidir.
