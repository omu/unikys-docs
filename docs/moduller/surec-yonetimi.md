# Süreç Yönetimi

Bu modül, kurumsal süreçlerin tanımlanması, takibi ve yönetimini sağlar.

!!! info "Erişim"
    Bu modül tüm kullanıcılara açıktır. Ancak **Benim Süreçlerim** alt menüsü sadece süreç rolleri için görünür.

## Alt Menüler

### Ana Süreçler

Kurumun üst düzey süreçlerinin listelendiği bölüm.

**İşlevler:**

- Ana süreç görüntüleme
- Alt süreçlere erişim
- Süreç faaliyetlerini inceleme

**Ana Süreç Yapısı:**

```
Ana Süreç
├── Alt Süreç 1
│   ├── Süreç Faaliyeti 1.1
│   └── Süreç Faaliyeti 1.2
└── Alt Süreç 2
    └── Süreç Faaliyeti 2.1
```

---

### Benim Süreçlerim

Kullanıcının sorumlu olduğu süreçlerin listelendiği bölüm.

!!! note "Kimler Görebilir?"
    Bu menü sadece **Süreç Sorumlusu**, **Süreç Temsilcisi** ve **Süreç Koordinatörü** rollerine sahip kullanıcılar tarafından görülebilir.

**İşlevler:**

- Sorumlu olunan süreçleri görüntüleme
- Süreç faaliyetlerini yönetme
- Süreç dokümanlarına erişim

---

### Görev Tanımları

Süreçlerde yer alan görevlerin tanımlandığı bölüm.

**İşlevler:**

- Görev tanımı oluşturma
- Sorumluluk matriksi belirleme
- Görev dokümanlarını yönetme

**Görev Tanımı Oluşturma:**

1. **Süreç Yönetimi > Görev Tanımları** menüsüne gidin
2. **Yeni Ekle** butonuna tıklayın
3. Görev adı ve açıklamasını girin
4. İlgili süreç faaliyetini seçin
5. Sorumlu birimleri belirleyin
6. **Kaydet** butonuna tıklayın

---

## Süreç Yapısı

### Ana Süreç

En üst düzey süreç kategorisi. Örnek: "Yönetim Süreçleri", "Eğitim Süreçleri"

### Alt Süreç

Ana sürecin altında yer alan detay süreçler. Örnek: "Stratejik Planlama", "Ders Planlaması"

### Süreç Faaliyeti

Alt süreçlerin içerdiği spesifik faaliyetler.

---

## Süreç Sorumlulukları

| Rol | Sorumluluk |
|-----|-----------|
| Süreç Koordinatörü | Süreç genel yönetimi |
| Süreç Sorumlusu | Birim bazlı süreç takibi |
| Süreç Temsilcisi | Süreç faaliyeti yürütme |

---

## Süreç Dokümanları

Her süreç için aşağıdaki dokümanlar tanımlanabilir:

- Süreç akış şeması
- Prosedür dokümanı
- İş talimatları
- Formlar ve şablonlar

Dokümanlar süreç detay sayfasından görüntülenebilir.

---

## İpuçları

!!! tip "Verimli Süreç Yönetimi"
    - Süreç faaliyetlerini düzenli olarak gözden geçirin
    - Sorumlulukları net olarak tanımlayın
    - Süreç akışını görselleştirin
