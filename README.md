# Reservation-Angular-App

## Randevu Uygulaması

Sizden belirtilen Front-end Framework'lerinden biriyle (Vue.js, Angular veya ReactJs) geliştirmiş, bir web uygulaması bekliyoruz. Bu uygulama kişinin randevu listesini tutacak bir uygulama olup, temek fonksiyonları barındıracaktır.

Beklenen fonksiyonlar:

* Kendi için taklit servisler ile çalışması (Mock Api)

* Sayfa yönlendirme (Routing)

* Kimlik doğrulama sistemi (Authentication)

* Ortam değişkenleri barındırması (örn: test, production vs)

* Ekranlar:

    * Giriş

    * Randevular

    * Randevu Ekle

    * Randevu Güncelle

      
#### Projeyi Çalıştırma

Proje angular ile geliştirildi. Projeyi test edebilmek için proje dizininde `npm start` komutunu çalıştırmanız yeterli. Ardından açılan `http://localhost:4200/` adresinden projeyi test edebilirsiniz.

Projede 2 tane ana servis var birisi `AuthenticationService ` diğeri `RandevuService`.  Bu servisler httpclient yardımıyla sunucuyla bağlantı kurarak işlem yapan basit crud servisleri.

Gelen istek urlleri eğer mocklanan servislerin isteklerine ait ise ilgili sonuç sunucuya gitmeden dönüldü.

Randevu verilerinin depolanması için ise yazılan mock servis localstorage kullanıldı.

İlgili sayfalar için gerekli componentler yazıldı.
