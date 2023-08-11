# Cara Install Project Shopping Yuk
1. Clone  & Extract folder zip nya
2. Buka folder ShoppingYuk pake VS Code
3. Buka Terminal
4. Lakukan perintah cmd ``` composer install```
5. Replace file ```.env.example``` jadi ```.env```
6. Isi  konfigurasi database pada file .env seperti dibawah:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=fashion
DB_USERNAME=root
```
6. Buat database pada laragon dengan nama <b>fashion</b>
7. Buka folder database/migrations
8. Lakukan perintah migration pada terminal dengan cara```php artisan migrate```
9. Lakukan perintah seeder pada terminal dengan cara ```php artisan db:seed```
10. Lakukan perintah server dengan perintah ```php artisan serve```
11. Untuk loginnya pakai akun ini ya:
```
    Admin
    username: admin@gmail.com
    password: password
    User
    username: user@gmail.com  
    password: password

```
12. Selamat Berbelanja!