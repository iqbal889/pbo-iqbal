# Instalasi Git Bash
## 1.download Git pada browser ketik 'git-scm'
![[assets/bal1.jpeg]]
## 2.Lalu klik Git Hub yang telah di instal

## 3.Lalu akan muncul tampilan seperti gambar

![[assets/bal2.jpeg]]

## 4.Maka klik 'next' terus hingga mendapatkan tampilan seperti gambar

![[assets/bal3.jpeg]]

# Login Akun GitHub
1. Buka aplikasi github di browser 
2. Lalu lakukan sign up pada github
[![[0df41373-3ae9-4125-acd8-0d2c03e0224f.jpg]]
3. Jika sudah memiliki akun langsung masukkan password dan username yang ada
![[105f487e-d933-43e5-8438-ab218f6f67b3.jpg]]

4. Jika tidak memiliki akun klik tambahkan akun
![[Pasted image 20240731222938.png]] 

5. Setelah buat akun maka akan tampil seperti gambar
![[Screenshot (12).png]]

# Buat Repositori GitHub Baru:
   - Login ke akun GitHub Anda.
   - Klik tombol "New" untuk membuat repositori baru.
   ![[Screenshot (15).png]]
   - Berikan nama repositori, pilih apakah akan bersifat publik atau privat, lalu klik "Create repository".
   ![[Screenshot (16).png]]

# Konfigurasi Git Bash 

>[!penjelasan]
Berikut adalah penjelasan mendetail mengenai perintah git config --list beserta beberapa contoh output dan artinya
Fungsi Perintah
Perintah git config --list digunakan untuk menampilkan semua konfigurasi Git yang sedang berlaku. Konfigurasi ini mencakup pengaturan global, sistem, dan lokal (spesifik repositori).

progamnya : 
~~~cs
git config --list
~~~
 contohnya : 
 ![[Screenshot (21).png]]

   - Buka git di laptop/komputer anda.
   - Jalankan perintah berikut untuk mengatur identitas Anda:

  ~~~CS
  git config --global user.name "Nama Anda"
  git config --global user.email "email@example.com"
   ~~~
     
     contohnya :

![[Screenshot (2).png]]
![[Screenshot (22).png]]

# Akses Folder Di Git Bash
   - Gunakan perintah cd (change directory) sampai ke folder proyek kalian
![[Screenshot (23).png]]
# Hubungkan Folder Proyek Lokal Github

   1.  Buat direktori baru untuk proyek Anda dan navigasikan ke direktori tersebut menggunakan Git bash. Kemudian, inisialisasi Git di direktori tersebut dengan menjalankan perintah:
   ~~~cs
     git init
~~~
 contohnya :
![[Screenshot (19).png]]

   2. Jalankan perintah berikut untuk menghubungkan repositori lokal Anda ke repositori GitHub yang telah Anda buat sebelumnya:
~~~cs
     git remote add origin https://github.com/username/nama-repository.git
  ~~~ 
  contohnya : 
![[Screenshot (18) 3.png]]
  3. Tampilkan status commit/koneksi file ke github
   ~~~cs
   git status
   ~~~
   contohnya : 
   ![[Screenshot (25).png]]
  
4. Tambahkan file ke repositori: 
   - Perintah ini akan menambahkan semua file di direktori saat ini ke repositori.
   - Tambahkan file yang ingin Anda simpan di repositori Git dengan menjalankan perintah:
   ~~~cs
     git add .
     ~~~
contohnya :
![[Screenshot (20).png]]

5. Tampilkan status commit/koneksi file ke github

contohnya:

1. Tambahkan file ke repositori: 
   - Perintah ini akan menambahkan semua file di direktori saat ini ke repositori.
   - Tambahkan file yang ingin Anda simpan di repositori Git dengan menjalankan perintah:
   ~~~cs
     git add .
     ~~~
contohnya :
![[Screenshot (20).png]]

# ls
>[!penjelasan]
>ls adalah perintah yang digunakan untuk menampilkan daftar file dan direktori dalam direktori saat ini.

Perintah ls ini akan menampilkan daftar file dan direktori yang ada di dalam direktori repositori tersebut.
   ~~~cs
     ls .
     ~~~
 contohnya :
![[Screenshot (26) 1.png]]

# Cd

>[!penjelasan]
>Perintah cd digunakan untuk mengubah direktori kerja saat ini di sistem operasi berbasis Unix (seperti Linux dan macOS) serta Windows.

- Penggunaan dasar :
~~~cs
cd [nama direktori]
~~~
- Pindah ke direktori tertentu : 
~~~cs
cd Documents
~~~
- Kembali ke direktori sebelumnya : 
~~~cs
cd ..
~~~
- Pergi ke direktori Home : 
~~~cs
cd ~
~~~
contohnya : 
![[Screenshot (28).png]]
