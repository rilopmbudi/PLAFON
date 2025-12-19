# PLAFON


Project Pemrograman Web – RANCANGAN BASIS DATA SISTEM INFORMASI PENJUALAN PLAFON

# Deskripsi Sistem
SISTEM INFORMASI PENJUALAN PLAFON berbasis web yang dibangun menggunakan PHP dan MySQL dengan konsep multi-role user, yaitu:

- Admin
- Customer
- Manager

Setiap role memiliki hak akses dan menu yang berbeda sesuai dengan fungsinya.

# Akun Login Default 🔐
- Admin
- Username : admin
- Password : admin123
________________________________
- Customer
- Username : nama kamu
- Password : terserah kamu aja 
________________________________
- Manager
- Username : manager
- Password : miko123
________________________________
- Contoh Customer:
- username : rilopmbudi
- Password : rilo123
________________________________
# Teknologi yang Digunakan 🛠️ 
- PHP Native
- MySQL
- HTML, CSS
- Apache (XAMPP / Hosting)

# Diagram Database
<img width="1236" height="668" alt="image" src="https://github.com/user-attachments/assets/862f9ad5-9833-40bb-8e26-27c21e3600f9" />

# Tampilan Aplikasi 📷 
<img width="1920" height="866" alt="image" src="https://github.com/user-attachments/assets/8301f827-7e6f-4baf-b451-d6482946dc8d" />

# Dashboard Admin
<img width="1894" height="856" alt="image" src="https://github.com/user-attachments/assets/f35d470e-d430-47b1-b289-e2c7bd275090" />

# Dashboard Manager
<img width="1920" height="853" alt="image" src="https://github.com/user-attachments/assets/7e10d857-8e3e-464b-bbe2-04924d03b595" />

# Dashboard Customer
<img width="1893" height="854" alt="image" src="https://github.com/user-attachments/assets/28839d93-e411-47ad-b72e-2a907df40733" />

# Cara Menjalankan Aplikasi 🚀
Berikut adalah langkah-langkah untuk menjalankan aplikasi SISTEM INFORMASI PENJUALAN PLAFON pada lingkungan lokal:
- Clone repository project ke komputer lokal.
- Pindahkan folder project ke dalam direktori web server XAMPP, yaitu folder htdocs.
- Jalankan layanan Apache dan MySQL melalui XAMPP Control Panel.
- Buka browser dan akses phpMyAdmin melalui alamat http://localhost/phpmyadmin.
- Buat database baru dengan nama db_plafon.
- Import file database db_plafon.sql yang tersedia pada folder database di dalam project.
- Buka file konfigurasi koneksi database pada folder config (file koneksi.php), kemudian sesuaikan pengaturan koneksi database dengan server lokal.
- Akses aplikasi melalui browser dengan alamat http://localhost/nama-folder-project.
- Login ke sistem menggunakan akun default sesuai dengan role pengguna (admin, manager, customer).

