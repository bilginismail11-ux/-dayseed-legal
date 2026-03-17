# DaySeed — Gizlilik Politikası

**Son güncelleme:** 16 Mart 2026

## 1. Giriş

DaySeed ("uygulama", "biz", "hizmet") olarak kişisel verilerinizin korunmasına büyük önem veriyoruz. Bu gizlilik politikası, 6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) ve ilgili mevzuat kapsamında, uygulamamızı kullanırken hangi verilerinizin toplandığını, nasıl işlendiğini, saklandığını ve korunduğunu açıklamaktadır.

**Veri Sorumlusu:** DaySeed
**İletişim:** destek@dayseed.app

## 2. Toplanan Veriler

### 2.1 Cihazda Yerel Olarak Saklanan Veriler
Aşağıdaki veriler yalnızca cihazınızda (SQLite veritabanında) saklanır:
- Rutin adları, açıklamaları ve ayarları
- Günlük tamamlama geçmişi
- Ruh hali (mood) ve enerji seviyesi kayıtları
- Rutin notları
- Uygulama ayarları (tema, bildirim tercihleri, dil)

### 2.2 Firebase Hizmetleri Üzerinden Toplanan Veriler
Uygulamamız Google Firebase altyapısını kullanmaktadır:

**Firebase Authentication (Hesap oluşturulduğunda):**
- E-posta adresi
- Görünen ad
- Profil fotoğrafı URL'si (Google ile giriş yapılırsa)
- Benzersiz kullanıcı kimliği (UID)

**Firebase Cloud Firestore (Bulut senkronizasyon etkinleştirildiğinde):**
- Rutin verileri ve tamamlama geçmişi
- Ruh hali ve enerji kayıtları
- Uygulama ayarları
- Son senkronizasyon zamanı

**Firebase Analytics (Anonim kullanım verileri):**
- Uygulama açılma sıklığı
- Kullanılan özellikler (hangi ekranlar ziyaret ediliyor)
- Uygulama performans metrikleri
- Cihaz türü ve işletim sistemi versiyonu
- Çökme raporları (Firebase Crashlytics)

Bu anonim veriler, uygulamanın performansını iyileştirmek ve hataları tespit etmek amacıyla toplanır. Bu veriler bireysel kullanıcılarla ilişkilendirilmez.

### 2.3 Toplanmayan Veriler
- Konum bilgisi
- Rehber/kişi listesi
- Fotoğraf veya medya dosyaları
- Diğer uygulama verileri
- Sağlık verileri (Apple Health, Google Fit vb. ile entegrasyon yoktur)

## 3. Verilerin Kullanım Amaçları

Toplanan veriler aşağıdaki amaçlarla işlenir:
- Rutin takibi hizmetinin sunulması
- Bildirim ve hatırlatmaların gönderilmesi
- Bulut senkronizasyonu ile cihazlar arası veri aktarımı
- İstatistik ve içgörülerin hesaplanması
- Uygulama performansının iyileştirilmesi
- Hataların tespit edilmesi ve düzeltilmesi
- Abonelik yönetimi

## 4. Verilerin Paylaşımı

Kişisel verilerinizi **üçüncü taraflarla paylaşmayız, satmayız veya kiralamayız.**

Verilerinize erişimi olan hizmet sağlayıcılar:
- **Google Firebase:** Kimlik doğrulama, bulut depolama ve analitik hizmetleri için. Google'ın gizlilik politikası: https://policies.google.com/privacy
- **Google Play Billing:** Abonelik işlemleri için. Ödeme bilgileri doğrudan Google tarafından işlenir; biz ödeme bilgilerinize erişemeyiz.

## 5. Verilerin Saklanması ve Güvenliği

- **Yerel veriler:** Cihazınızdaki SQLite veritabanında saklanır.
- **Bulut verileri:** Google Firebase sunucularında şifreli bağlantı (TLS) üzerinden saklanır. Firebase, ISO 27001 ve SOC 2 sertifikalarına sahiptir.
- **Hesap silindiğinde:** Tüm bulut verileri kalıcı olarak silinir.

## 6. KVKK Kapsamında Haklarınız

6698 sayılı Kişisel Verilerin Korunması Kanunu'nun 11. maddesi kapsamında aşağıdaki haklara sahipsiniz:

### 6.1 Bilgi Edinme Hakkı
Kişisel verilerinizin işlenip işlenmediğini, işlenmişse buna ilişkin bilgi talep etme hakkınız vardır.

### 6.2 Verilerinize Erişim Hakkı
Uygulama içinden tüm rutin verilerinizi, tamamlama geçmişinizi ve ruh hali kayıtlarınızı görüntüleyebilirsiniz.

### 6.3 Düzeltme Hakkı
Kişisel verilerinizin eksik veya yanlış işlenmiş olması halinde bunların düzeltilmesini isteme hakkınız vardır. Rutin verilerinizi uygulama içinden düzenleyebilirsiniz.

### 6.4 Silme Hakkı
- Uygulama içinden tek tek rutinlerinizi ve verilerinizi silebilirsiniz.
- Hesabınızı tamamen silme seçeneği Profil > Hesap ekranında mevcuttur. Hesap silindiğinde tüm bulut verileri kalıcı olarak kaldırılır.
- Uygulamayı kaldırdığınızda yerel veriler cihazınızdan silinir.

### 6.5 Veri Taşınabilirliği Hakkı
Verilerinizi JSON ve CSV formatlarında dışa aktarabilirsiniz. Bu özellik Profil > Yedekleme ekranından erişilebilir.

### 6.6 İtiraz Hakkı
Kişisel verilerinizin işlenmesine itiraz etme hakkınız vardır. Talebinizi destek@dayseed.app adresine iletebilirsiniz.

## 7. Çocukların Gizliliği

DaySeed, 13 yaşın altındaki çocuklara yönelik değildir ve bu yaş grubundan bilerek kişisel veri toplamaz. 13 yaşın altındaki bir çocuğun veri paylaştığını fark ederseniz, lütfen bizimle iletişime geçin; ilgili verileri derhal sileceğiz.

## 8. Abonelik Bilgileri

### 8.1 Abonelik Türleri
DaySeed, ücretsiz ve premium olmak üzere iki kullanım modeli sunar. Premium abonelik aylık veya yıllık olarak sunulabilir.

### 8.2 Otomatik Yenileme
Premium abonelikler, iptal edilmediği sürece dönem sonunda otomatik olarak yenilenir. Yenileme işlemi, mevcut dönemin bitiminden 24 saat önce Google Play hesabınızdan tahsil edilir.

### 8.3 İptal
Aboneliğinizi istediğiniz zaman Google Play Store > Abonelikler bölümünden iptal edebilirsiniz. İptal işlemi mevcut dönemin sonunda geçerli olur; kalan süre boyunca premium özellikleri kullanmaya devam edersiniz.

### 8.4 İade
İade talepleri Google Play Store politikalarına tabidir.

## 9. Çerezler ve İzleme Teknolojileri

DaySeed mobil uygulaması çerez kullanmaz. Firebase Analytics, uygulama kullanım verilerini anonim olarak toplamak için cihaz tanımlayıcıları kullanabilir. Cihaz ayarlarından reklam izlemeyi devre dışı bırakarak bu veri toplamayı sınırlandırabilirsiniz.

## 10. Politika Değişiklikleri

Bu gizlilik politikasını zaman zaman güncelleyebiliriz. Önemli değişiklikler uygulama içi bildirim ile duyurulacaktır. Güncel politikayı her zaman uygulama içinden ve https://dayseed.app/privacy adresinden inceleyebilirsiniz.

## 11. İletişim

Gizlilik politikamız veya kişisel verileriniz hakkında sorularınız için:

**E-posta:** destek@dayseed.app
**Konu:** Gizlilik / KVKK Talebi

KVKK kapsamındaki başvurularınız en geç 30 gün içinde cevaplanacaktır.
