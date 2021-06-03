# Lab8Web

Nama  : Syukur Yakub

Kelas : TI.19.C1

Nim   : 311910696

# Langkah-langkah Praktikum
# Persiapan
Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah 
database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan 
melalui XAMPP.
# Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Contol.

![1a](https://user-images.githubusercontent.com/56242226/120600595-9296d980-c466-11eb-925f-ef09ed2196f4.PNG)

# Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka 
melalui browser: http://localhost/phpmyadmin/

# Membuat Database dan Membuat Tabel
![1](https://user-images.githubusercontent.com/56242226/120600902-ea354500-c466-11eb-8822-dbe2b3f3c6ea.PNG)

# Menambahkan Data
![2a](https://user-images.githubusercontent.com/56242226/120601190-45ffce00-c467-11eb-8073-cff6e8918689.PNG)

![2b](https://user-images.githubusercontent.com/56242226/120602774-fa4e2400-c468-11eb-8093-d1201f2a0e23.PNG)


![2](https://user-images.githubusercontent.com/56242226/120602588-ca9f1c00-c468-11eb-8f37-bf2ccb1e1800.PNG)

# Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (d:\xampp\htdocs)

![33](https://user-images.githubusercontent.com/56242226/120603165-59139d80-c469-11eb-9b71-f01c63387ae4.PNG)

# Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL: 
http://localhost/lab8_php_database/

# Membuat file koneksi database
Buat file baru dengan nama koneksi.php

![3](https://user-images.githubusercontent.com/56242226/120603343-8ceec300-c469-11eb-9d06-372e34015b50.PNG)

# Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan 
koneksi berhasil, uncomment pada perintah echo “koneksi berhasil”; 

![3a](https://user-images.githubusercontent.com/56242226/120603440-aabc2800-c469-11eb-92a4-9f1b31ddcbc1.PNG)

# Membuat file index untuk menampilkan data (Read)
Buat file baru dengan nama index.php

![4](https://user-images.githubusercontent.com/56242226/120603537-c7586000-c469-11eb-908f-8def7d07e2aa.PNG)
![4aa](https://user-images.githubusercontent.com/56242226/120603588-d4754f00-c469-11eb-8199-ae64142ee4ca.PNG)

Hasilnya 

![4a](https://user-images.githubusercontent.com/56242226/120603698-e820b580-c469-11eb-97cc-8a34e485e079.PNG)

# Menambah Data (Create)
Buat file baru dengan nama tambah.php

![6](https://user-images.githubusercontent.com/56242226/120603818-0981a180-c46a-11eb-8a10-10d320c1de20.PNG)
![6a](https://user-images.githubusercontent.com/56242226/120603878-156d6380-c46a-11eb-979d-fde6448170e6.PNG)
![6b](https://user-images.githubusercontent.com/56242226/120603917-20c08f00-c46a-11eb-8344-a7aca1e5cc8f.PNG)

Hasilnya :

![6c](https://user-images.githubusercontent.com/56242226/120603976-31710500-c46a-11eb-89b6-77315148ad86.PNG)

# Mengubah Data (Update)
Buat file baru dengan nama ubah.php

![7](https://user-images.githubusercontent.com/56242226/120604153-5f564980-c46a-11eb-9932-8f82fadda91c.PNG)
![7a](https://user-images.githubusercontent.com/56242226/120604191-69784800-c46a-11eb-9e17-3857eb444ec3.PNG)
![7b](https://user-images.githubusercontent.com/56242226/120604223-739a4680-c46a-11eb-85fb-5566b6a23f17.PNG)

Data sebelum Di ubah : 

![7c](https://user-images.githubusercontent.com/56242226/120604272-844abc80-c46a-11eb-8962-1f694277fc9e.PNG)

Data setelah Di ubah :

![7d](https://user-images.githubusercontent.com/56242226/120604362-9d536d80-c46a-11eb-8e99-19609772627b.PNG)

# Menghapus Data (Delete)
Buat file baru dengan nama hapus.php

![8](https://user-images.githubusercontent.com/56242226/120604501-c07e1d00-c46a-11eb-947f-4171f2209e9a.PNG)

Data sebelum di hapus :

![8a](https://user-images.githubusercontent.com/56242226/120604692-e7d4ea00-c46a-11eb-9988-c615799bdf7d.PNG)

Data setelah Di Hapus :

![8b](https://user-images.githubusercontent.com/56242226/120604771-fd4a1400-c46a-11eb-9a88-29ee4a667350.PNG)

# Agar Tampilan nya Terlihat Rapih dan Menarik 
# Tambahkan CSS di dalamnya 
![5](https://user-images.githubusercontent.com/56242226/120604928-223e8700-c46b-11eb-9a9b-d492198f1023.PNG)


























