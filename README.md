# Laravel
adalah framework di PHP untuk membuat Web atau API.

# Laravel
adalah framework yang open source dan gratis, sehingga bisa digunakan tanpa biaya dan bisa berkontribusi pada projek.

# Sebelum Membuat Proyek Laravel
harus dipastikan sudah menginstal PHP dan Composer. disarankan juga untuk menginstal Node dan NPM.

# Perintah Composer untuk Membuat Proyek Laravel 
composer create-project laravel/laravel example-app

# Atau dapat membuat proyek Laravel baru dengan menginstal penginstal Laravel secara global melalui Composer :
composer global require laravel/installer
 
laravel new example-app

# Setelah proyek dibuat, mulai server pengembangan lokal Laravel menggunakan perintah CLI Artisan Laravel

cd example-app
 
php artisan serve

# Laravel & Docker
Ada berbagai opsi untuk mengembangkan dan menjalankan proyek Laravel, Laravel menyediakan sail, solusi bawaan untuk menjalankan proyek Laravel menggunakan Docker.
  
# Docker 
adalah alat untuk menjalankan aplikasi dan layanan dalam "wadah" kecil dan ringan yang tidak mengganggu perangkat lunak atau konfigurasi yang diinstal mesin lokal Anda.

# Laravel Sail
adalah antarmuka baris perintah yang ringan untuk berinteraksi dengan konfigurasi Docker default Laravel. Sail menyediakan titik awal yang bagus untuk membangun aplikasi Laravel menggunakan PHP, MySQL, dan Redis tanpa memerlukan pengalaman Docker sebelumnya.

