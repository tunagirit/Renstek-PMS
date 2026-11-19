# Değişiklik Günlüğü

## [1.0.2] – 2026-11-19

Uygulama, büyük bir otelin sahibi için tam bir yönetim paneline dönüştü.

### Eklenenler
- **Yönetim paneli** yapısı: genişletilebilir gezinme menüsü, genel arama, rozetli bildirimler
- **Genel bakış:** doluluk, ADR, RevPAR, aylık gelir, 14 günlük doluluk grafiği, oda durumu, bugünkü giriş/çıkış, kanal geliri, son işlemler
- **Büyük otel:** 8 kat, 192 oda, 7 oda tipi ve oda özellikleri (deniz manzarası, balkon, jakuzi, engelli erişimi vb.)
- **Kat planı:** bina kesiti, özellik filtreleri, alttan açılan rezervasyon çubuğu ve rezervasyon penceresi
- **Doluluk takvimi:** oda × gün şerit görünümü, bakım blokları
- **Rezervasyonlar:** arama ve filtreler, tahsilat, tarih/oda değiştirme, iptal, no-show, VIP
- **Odalar:** oda düzenleme, toplu bakım planlama ve tip değiştirme
- **Bakım & arıza:** tarih aralığıyla bakım planlama, kategori/öncelik/sorumlu, çakışma uyarısı, kayıp gelir hesabı, çakışan misafirleri otomatik taşıma
- **Kat hizmetleri:** oda temizlik durumları, kat sorumlusu atama
- **Fiyat & sezon:** taban fiyatlar, sezonlar, hafta sonu farkı, pansiyon fiyatları, 60 günlük önizleme
- **Misafirler:** misafir geçmişi, harcama, VIP
- **Ayarlar:** bina yapısı, personel, animasyon tercihi, veri dışa/içe aktarma
- **Animasyonlar:** sayfa geçişleri, sırayla beliren kartlar, sayarak artan göstergeler, büyüyen grafikler, şekil değiştiren odalar ve butonlar, ripple efekti, açılış göstergesi

### Değişenler
- Simgeler dosyaya gömüldü; internet bağlantısı olmadan da çalışır
- Veri anahtarı değişti; ilk açılışta yeni demo otel yüklenir

## [1.0.1] – 2026-11-17

### Eklenenler
- Ayarlar menüsünde tema seçimi: Açık, Karanlık, Otomatik (cihaz ayarını izler)
- Material 3 karanlık renk paleti
- Ayarlar menüsünde sürüm bilgisi

### Değişenler
- Kat planı ve oda renkleri temaya göre değişen renk değişkenlerine taşındı

## [1.0.0] – 2026-11-17

İlk sürüm.

### Eklenenler
- Çizgisel otel krokisi: merdiven, koridor ve 1 ya da 2 sıra oda
- Tarih aralığına göre oda durumu: müsait, seçili, dolu
- Giriş ve çıkış tarihi, yetişkin ve çocuk sayısı, oda tipi ve pansiyon seçimi
- Çoklu oda rezervasyonu ve anlık fiyat hesabı
- Giriş, çıkış ve iptal işlemleri
- Otel ayarları: kat sayısı, sıra sayısı, sıradaki oda sayısı, oda fiyatları
- Material 3 Expressive arayüz
- Tarayıcıda (`localStorage`) veri saklama ve demo veriler
