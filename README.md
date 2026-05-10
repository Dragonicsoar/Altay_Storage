# Altay Storage v1.0.0

## 1. Proje Özeti
Altay Storage; kullanıcıların verilerini tarayıcı tabanlı (Client-side) depolama birimleri üzerinde organize etmelerini sağlayan, modern ve duyarlı (responsive) bir dosya yönetim ve paylaşım simülasyonudur. Proje, hem bireysel kullanım hem de kurumsal veri mimarilerini anlamaya yönelik bir temel teşkil etmektedir.

## 2. Teknik Mimari
Sistem, herhangi bir sunucu tarafı bağımlılığı olmaksızın tamamen **Vanilla JavaScript** ve **HTML5/CSS3** teknolojileri ile inşa edilmiştir. Veri sürekliliği `localStorage` ve `sessionStorage` mekanizmaları aracılığıyla sağlanmaktadır.

### Kullanılan Teknolojiler:
- **Frontend:** HTML5, CSS3 (CSS Variables tabanlı dinamik tema sistemi)
- **Logic:** Vanilla JavaScript (ES6+)
- **Storage:** LocalStorage & SessionStorage API
- **UI/UX:** Adaptif tasarım, Dinamik Karanlık/Aydınlık mod desteği

## 3. Temel Özellikler
- **Esnek Giriş Sistemi:** Kullanıcılar hem e-posta adresleri hem de benzersiz kullanıcı adları ile sisteme erişim sağlayabilirler.
- **Dinamik Veri Yönetimi:** Form otomasyonu sayesinde dosya yükleme ekranlarında otomatik form sıfırlama (state reset) özelliği.
- **Admin Kontrol Paneli:** Sistemdeki tüm kullanıcıları ve yüklenen medyaları denetleme, silme ve istatistik takibi yapabilme yetkisi.
- **Gelişmiş Medya Önizleme:** Görüntü ve video dosyaları için entegre önizleme motoru.
- **Güvenlik ve Gizlilik:** Şifre gizleme/gösterme opsiyonu ve yerel oturum yönetimi.

## 4. Kurulum ve Kullanım
Proje herhangi bir paket yöneticisi (npm, yarn) gerektirmez.

1. Depoyu klonlayın:
   ```bash
   git clone [https://github.com/kullaniciadi/altay-storage.git](https://github.com/kullaniciadi/altay-storage.git)