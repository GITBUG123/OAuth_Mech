# OAuth_Mech
Login, register using third-party(Google and GitHub) authenticator.

Installation Guide:
1. composer install
2. composer require laravel/ui
3. php artisan ui vue --auth
4. npm install && npm run dev
5. composer require laravel/socialite
6. mengubah nama file .env.example menjadi .env
7. mengubah nama database
8. php artisan migrate
9. mengisi bagian MAIL yang kosong degan bantuan aplikasi https://mailtrap.io/ untuk proses forget password
10. pada aplikasi mailtrap.io, dilakukan:
- daftar akun
- memasuki bagian https://mailtrap.io/home
- pilih bagian Set Up Inbox
- pada menu SMTP Settings bagain Integrations, pilih Laravel 7+
- memindahkan semua nilai kedalam .env bagain MAIL
Notes: link forget password yang direquest dapat didapatkan pada inbox aplikasi mailtrap.io
11. memasukkan client_id dan client_secret google dan github
12. php artisan serve



