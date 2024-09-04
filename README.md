# trendyol-microservice

Bu proje, Trendyol API'sinden ürünleri çeken bir mikroservistir.

## Özellikler

- Ürün verilerini Trendyol API'sinden çeker
- Verileri veritabanına kaydeder
- Performans optimizasyonu sağlar

## Kurulum

1. Depoyu klonlayın
2. Gereksinimleri yükleyin
3. `.env` dosyasını oluşturun ve gerekli ayarları yapın
4. `composer install` komutunu çalıştırın
5. Veritabanı migrasyonlarını çalıştırın: `php artisan migrate`

## Kullanım

Uygulamayı çalıştırmak için:
```bash
php artisan serve

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakın.