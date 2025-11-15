1) Kullanıcı Akışı (User Flow)
1. Kayıt / Giriş

Kullanıcı e-posta + şifre ile hesap oluşturur.

Daha önce hesabı varsa giriş yapar.

Başarılı giriş → ana sayfaya yönlendirilir.

2. Pet Ekleme

Kullanıcı “Pet Ekle” ekranına geçer.

Fotoğraf yükler, isim, yaş, tür (cat/dog/other) girer.

Kaydeder → Pet profili oluşur.

3. AI Giydirme

Kullanıcı pet fotoğrafını seçer.

Stil/shablon seçer → AI sonucu üretir.

Sonuç kaydedilebilir veya toplulukta paylaşılabilir.

4. Topluluk Paylaşımı

Kullanıcı oluşturduğu AI giydirmeyi topluluk akışında paylaşır.

Diğer kullanıcılar postu beğenebilir ve yorum yapabilir.

5. Mağaza Görüntüleme

Kullanıcı ürünleri listede görür.

Ürün detayı → sepete ekleme (henüz demo için opsiyonel).
2) Admin Akışı
1. Vet Onaylama

Admin → “Veteriner Başvuruları” ekranına girer.

Başvuran vet bilgilerini inceler.

Onayla veya Reddet aksiyonunu yapar.

Onaylanan vet hesabı → sistemde aktifleşir.

2. Ürün Ekleme

Admin → “Mağaza Yönetimi” bölümüne girer.

Ürün adı, fiyat, açıklama, fotoğraf ekler.

Ürün mağazada görünür hale gelir.

3. Post Silme

Topluluk akışında uygunsuz bir içerik fark edilirse admin kaldırabilir.

Post silindiğinde içerik kullanıcılardan görünmez.

4. İstatistik Görme

Admin panelinde:

Toplam kullanıcı

Günlük aktif kullanıcı

Toplam post

Toplam ürün

Vet başvuru sayısı
gibi özet metrikler görüntülenir.
Takip Edilecek Event’ler
Kullanıcı:

user_signup → kullanıcı kayıt olur

user_login → kullanıcı giriş yapar

pet_add → yeni pet eklenir

pet_edit → pet bilgileri düzenlenir

ai_outfit_generate → AI giydirme çalıştırılır

post_create → toplulukta post oluşturulur

store_view → mağaza sekmesi açılır

product_click → ürün detayına girilir

Admin:

vet_approve → veteriner başvurusu onaylanır

vet_reject → veteriner reddedilir

product_add → yeni ürün eklenir

post_delete → admin post siler

stats_view → admin istatistik panelini görüntüler
