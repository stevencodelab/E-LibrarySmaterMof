# E-LibrarySmaterMof
Merupakan Sistem Informasi Perpustakaan untuk Sekolah Menengah Atas (SMA) Katolik Frateran Maumere guna mendukung kelancaran proses belajar-mengajar serta meningkatkan kualitas pendidikan siswa di SMAK FRATERAN MAUMERE. Perpustakaan SMAK FRATERAN MAUMERE telah menyediakan beragam buku dengan beragam kategori yang dapat dimanfaatkan siswa untuk menbaca serta pihak perpustakaan juga menyediakan sistem peminjaman buku kepada siswa/anggota perpustakaan dengan ketentuan yang telah ditetapkan.

# System Requirements 
1. XAMPP Versi 5.6.40
2. Apache/2.4.34
3. PHPMyadmin 4.8.2

Karena project ini dibangun dengan menggunakan PHP versi di bawah 7 yaitu 5.6.40, maka untuk menjalankannya harus menggunakan Xampp dengan versi yang lebih rendah dan saya menggunakan Xampp Versi 5.6.40 yang bisa di download melalui link berikut ini : 
(https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.40/xampp-windows-x64-5.6.40-1-VC11-installer.exe/download)

# How To Use 
1. Clone project ini dengan menggunakan `git clone` pada folder htdocs di xampp
2. Akses `localhost/phpmyadmin` lalu buat database baru dengan nama `e-library` lalu import `database` yang ada pada folder database pada project, jika ingin merubah nama database harap disesuaikan dengan nama database pada `config db`.
3. Jika sudah berhasil melakukan import database, akses website dengan cara `localhost/E-LibrarySmaterMof/index.php`

# Login Role (Admin Only) 
1. Admin
   -> username : admin
   -> password : admin
