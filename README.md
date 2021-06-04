# Lab8Web
# Membuat data base  : studi kasus data barang
# CREATE DATABASE latihan1.;

![image](https://user-images.githubusercontent.com/77254428/120841521-cde3f600-c595-11eb-989b-93610d6d3e39.png)

Menambahkan data 

INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok)
VALUES ('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5),
('Elektronik', 'HP Xiaomi Android', 'hp_xiaomi.jpg', 1000000, 1400000, 5),
('Elektronik', 'HP OPPO Android', 'hp_oppo.jpg', 1800000, 2300000, 5);

![image](https://user-images.githubusercontent.com/77254428/120841667-fec42b00-c595-11eb-80ae-6d9c9dbf72ad.png)

# Membuat Program CRUD
Buat folder lab8_php_database pada root directory web server (C:\xampp\htdoct)
![image](https://user-images.githubusercontent.com/77254428/120842190-9590e780-c596-11eb-8dd6-49b018c9fa7d.png)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab8_php_database/

![lab8](https://user-images.githubusercontent.com/77254428/120842292-b6f1d380-c596-11eb-8669-b4749e52e8a2.png)

Membuat file koneksi database
Buat file baru dengan nama koneksi.php

![image](https://user-images.githubusercontent.com/77254428/120842568-0d5f1200-c597-11eb-92bb-60ccca3a46d3.png)

# Membuat file index untuk menampilkan data (Read)
Buat file baru dengan nama index.php

![image](https://user-images.githubusercontent.com/77254428/120842807-69299b00-c597-11eb-9d23-40b4934f8650.png)
![image](https://user-images.githubusercontent.com/77254428/120842963-adb53680-c597-11eb-87dd-4a1112096c78.png)

Menambah Data (Create)
Buat file baru dengan nama tambah.php

![image](https://user-images.githubusercontent.com/77254428/120843070-db9a7b00-c597-11eb-9279-a85f22149590.png)

![tambah barang](https://user-images.githubusercontent.com/77254428/120843114-e9e89700-c597-11eb-889a-cd71555f666f.png)

Mengubah Data (Update)
Buat file baru dengan nama ubah.php
![image](https://user-images.githubusercontent.com/77254428/120843196-0553a200-c598-11eb-939f-df44e0fd6d11.png)

![image](https://user-images.githubusercontent.com/77254428/120843492-5fecfe00-c598-11eb-81a7-80e642d3f20d.png)

Menghapus Data (Delete)
Buat file baru dengan nama hapus.php
![image](https://user-images.githubusercontent.com/77254428/120843580-7b580900-c598-11eb-846e-061193956714.png)


