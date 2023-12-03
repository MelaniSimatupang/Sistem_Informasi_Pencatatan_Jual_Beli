## Sistem_Informasi_Pencatatan_Jual_Beli
Sistem Informasi Pencatatan Jual Beli ini,  dirancang sebagai solusi komprehensif untuk membantu para pelaku bisnis dalam mencatat dan mengelola operasional perusahaan secara efisien. Dengan fokus pada proses jual beli, aplikasi ini menyediakan berbagai fitur yang dirancang untuk memudahkan pengguna dalam mengelola transaksi bisnis.
## Fitur
Dashboard, Jenis Barang, Satuan Barang, Merk Barang, Barang, Customer, Barang Masuk, Barang Keluar, Laporan Barang Masuk, Laporan Barang Keluar, Laporan Stok Barang, Setting Website, Setting Hak Akses user per Role, Setting Menu (bisa tambah menu atau bisa hapus menu)
## Instalasi
1. Clone Project dengan perintah terminal gitbash sebagai berikut:
https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli.git
Atau bisa klik tombol download Zip dan extrak file tersebut
2. Buat Database
Buat Database db_inventoryweb
3. Config ENV
Ubah file dari env.development jadi .env
Setting DB_DATABASE, DB_USERNAME, DB_PASSWORD yang ada di file .env sesuai Nama Database mysql kalian
4. Set Up
Buka Terminal di proyek folder Anda dan jalankan perintah dibawah ini:
composer install atau composer.phar
php artisan storage:link
5. Import Database
Import file database db_inventoryweb.sql yang ada di folder database/db ke phpmyadmin
6. Jalankan Aplikasi
php artisan serve
7. Login Default
username: Melani_Simatupang password: 12345678
username: Cha_Eun_Woo password: 12345678
username: Mark_Lee password: 12345678
username: Han_So_Hee password: 12345678
## Preview
## Tampilan Login ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Login.jpeg?raw=true)
## Tampilan Dashboard ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Dashboard.jpeg?raw=true)
## Tampilan Jenis Barang ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Jenis%20Barang.jpeg?raw=true)
## Tampilan Satuan Barang ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Satuan%20Barang.jpeg?raw=true)
## Tampilan Merk Barang ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Merk%20Barang.jpeg?raw=true)
## Tampilan Fitur Barang![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Barang.jpeg?raw=true)
## Tampilan Untuk Menambahkan Barang ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Menambahkan%20Barang.jpeg?raw=true)
## Tampilan Customer ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Customer.jpeg?raw=true)
## Tampilan Untuk Menambahkan Customer ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Menambahkan%20Customer.jpeg?raw=true)
## Tampilan Fitur Barang Masuk ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Barang%20Masuk.jpeg?raw=true)
## Tampilan Untuk Menambahkan Barang Masuk ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/8a.%20Menambahkan%20%20Barang%20Masuk.jpeg?raw=true)
## Tampilan Fitur Barang Keluar ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/9.%20Barang%20Keluar.jpeg?raw=true)
## Tampilan Untuk Menambahkan Barang Keluar ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/9a.%20Menambahkan%20Barang%20Keluar.jpeg?raw=true)
## Tampilan Laporan Barang Masuk ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/10.%20Lap.%20Barang%20Masuk.jpeg?raw=true)
## Tampilan Laporan Barang Masuk Dalam Bentuk PDF ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/10a.%20Cetak%20Laporan%20Barang%20Masuk.jpeg?raw=true)
## Tampilan Laporan Barang Keluar ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/11.%20Lap.%20Barang%20Keluar.jpeg?raw=true)
## Tampilan Laporan Barang Keluar Dalam Bentuk PDF ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/11a.%20Cetak%20Lap.%20Barang%20Keluar.jpeg?raw=true)
## Tampilan Laporan Stok Barang ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/12.%20Lap.%20Stok%20Barang.jpeg?raw=true)
## Tampilan Laporan Stok Barang Dalam Bentuk PDF ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/12a.%20Cetak%20Lap.%20Stok%20Barang.jpeg?raw=true)
## Tampilan Fitur Menu ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/13.%20Menu.jpeg?raw=true)
## Tampilan Fitur Role ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/14.%20User-Role.jpeg?raw=true)
## Tampilan List User ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/15.%20User-List.jpeg?raw=true)
## Tampilan Menambahkan List User ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/15a.%20User-Menambahkan%20list.jpeg?raw=true)
## Tampilan Fitur User-Akses ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/16.%20User-Akses.jpeg?raw=true)
## Tampilan Fitur Pengaturan Website ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/17.%20Pengaturan%20Website.jpeg?raw=true)
## Tampilan Profile ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/18.%20Profile.jpeg?raw=true)
## Tampilan Tema ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/19.%20TampilanTema.jpeg?raw=true)
## Tampilan Structure PHPmyadmin ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Structure%20PHPmyadmin.jpeg?raw=true)
## Tampilan Designer PHPmyadmin ![alt text](https://github.com/MelaniSimatupang/Sistem_Informasi_Pencatatan_Jual_Beli/blob/main/Camera%20Roll/Designer%20phpmyadmin.jpeg?raw=true)
