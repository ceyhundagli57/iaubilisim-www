### Veritabanı işlemleri:

- `.env` dosyasını düzenle
- `config/database.php` dosyasını düzenle
- komut gir: `php artisan make:migration posts`
- komut gir: `php artisan make:migration comments`
- `posts` için girilen migration komutuna mukabelen `posts` için tablo oluştur
- `comments` için girilen migration komutuna mukabelen `comments` için tablo oluştur
- kullanıcılar için hazır gelen `database/migrations/2014_10_12_000000_create_users_table.php`
 dosyasını düzenle
- komut gir: `php artisan migrate`

### Routes ve Modals işlemleri:

- `app/Http/routes.php` dosyasını düzenle
- `app` klasöründe `Posts.php` ve `Comments.php` dosyalarını yarat, düzenle
- `app/Users.php` dosyasını düzenle

### Controllers işlemleri:

- Komut gir: `php artisan make:controller UserController`
- Komut gir: `php artisan make:controller PostController`
- Komut gir: `php artisan make:controller CommentController`
- Anasayfada belli sayıda post göstermek için `app/Http/Controllers/PostController.php` dosyasında `index()` fonksiyonunu güncelle
- Bir post yaratmak için `create()` fonksiyonunu güncelle
- `app/Http/Requests/PostFormRequest.php` dosyasını yarat, düzenle
- `app/Http/Controllers/CommentController.php` dosyasını yarat, düzenle

### Frontend işlemleri:

- `resources/views/app.blade.php` dosyasını yarat, düzenle
- `resources/views/home.blade.php` dosyasını yarat, düzenle
- `resources/views/posts/create.blade.php` dosyasını yarat, düzenle
- `resources/views/posts/show.blade.php` dosyasını yarat, düzenle
- `resources/views/posts/edit.blade.php` dosyasını yarat, düzenle

### Kullanıcı Profili işlemleri:

- `tinyMCE` indir ve indirdiğin sıkıştırılmış dosyası `public/js` klasörüne çıkart
- `resources/views/posts/edit.blade.php` dosyasını güncelle
- `resources/views/posts/crate.blade.php` dosyasını güncelle
- `app/controllers/admin/UserController.php` dosyasını güncelle
- `resources/views/admin/profile.blade.php` dosyasını yarat, düzenle

