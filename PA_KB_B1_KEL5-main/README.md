<b><center><h1>Project Akhir</h1></center></b>
<center><h2>Praktikum Kecerdasan Buatan</h2></center>
<center><h2>Deep Learning - Image Processing</h2></center>

<b><h2>Klasifikasi Jenis Sepatu</h2></b>
<b>Nama Anggota dan Masing-Masing Job Desc Kelompok 5 Kelas B1'20:</b>
1. Muhammad Reyhan Setiawan 2009106052
    - Ketua Kelompok
    - Bagian Collecting
    - Bagian Visualization
    - Bagian Modeling
    - Bagian Evaluasi
        - Model Predict
2. Rahmayanti 2009106078
    - Bagian Collecting
    - Bagian Preprocessing
    - Bagian Evaluasi
        - Visualisasi Akurasi dan Loss
        - Model Test Evaluate
        - Classification Matrix

<b><h2>Penjelasan Dataset</h2></b>
Source Dataset: <a href="https://www.kaggle.com/datasets/noobyogi0100/shoe-dataset">Shoe Dataset - Kaggle</a>

Total gambar keseluruhan setelah dibersihkan dan disamakan ukuran gambarnya secara manual: 900 gambar

Dataset yang digunakan berupa gambar Sepatu dengan 4 Jenis yang berbeda yaitu
1. boots
2. loafers
3. sneakers
4. soccers

Dan sistem akan mengklasifikasi mana gambar Sepatu sesuai dengan jenisnya.


<h4>Berikut adalah visualisasi untuk menampilkan jumlah file seluruh gambar dan tiap folder yang sudah displit

menjadi Data Training(70%), Validation(10%), dan Testing(20%) per jenisnya dengan menggunakan Bar Chart/Grafik Batang</h4>

<b>- Jumlah File Keseluruhan Data</b>

![seluruhfile](https://user-images.githubusercontent.com/74246083/205809395-841f4e07-a8ba-4288-bc65-51cf96683a0d.png)
 - Jumlah File boots = 200 gambar
 - Jumlah File loafers = 200 gambar
 - Jumlah File sneakers = 200 gambar
 - Jumlah File soccers = 200 gambar
 - Jumlah FIle Keseluruhan = 900 gambar
 
<b>- Jumlah File Data Training</b>

![train](https://user-images.githubusercontent.com/74246083/205809611-add10fa7-5d23-4ac6-be96-c4ca6ade6626.png)
 - Jumlah File boots = 155 gambar
 - Jumlah File loafers = 155 gambar
 - Jumlah File sneakers = 159 gambar
 - Jumlah File soccers = 159 gambar
 - Jumlah FIle Keseluruhan = 628 gambar

<b>- Jumlah File Data Validation</b>

![val](https://user-images.githubusercontent.com/74246083/205809722-63b75d69-f284-40f9-b85e-41159783ed17.png)
 - Jumlah File boots = 22 gambar
 - Jumlah File loafers = 22 gambar
 - Jumlah File sneakers = 22 gambar
 - Jumlah File soccers = 22 gambar
 - Jumlah FIle Keseluruhan = 88 gambar
 
<b>- Jumlah File Data Testing</b>

![test](https://user-images.githubusercontent.com/74246083/205809802-92181f30-8e44-4b0a-8b80-19871a650e2b.png)
 - Jumlah File boots = 45 gambar
 - Jumlah File loafers = 45 gambar
 - Jumlah File sneakers = 47 gambar
 - Jumlah File soccers = 47 gambar
 - Jumlah FIle Keseluruhan = 184 gambar

<b><h2>Penjelasan Project</h2></b>
_<h3>Data Preprocessing</h3>_
Setelah melakukan pembagian file/spliting selanjutnya adalah membuat generator untuk melakukan augmentasi pada Data Training, Validation, dan Testing. 

Paramater yang digunakan Data Train adalah _rescale, shear_range, zoom_range, rotation_range,_ dan _horizontal_flip._

Sedangkan Data Val dan Test hanya menggunakan _rescale_

Kemudian data dimasukkan ke dalam generator yang telah dibuat untuk proses Augmentasi dengan parameter yaitu menentukan 

direktorinya _train_path_ untuk train generator, _val_path_ untuk val generator, _test_path_ untuk test generator 

dengan _target_size, batch_size,_ dan _class_modenya_

_<h3>Data Analysis and Visualization</h3>_
Setelah tahap Preprocessing selanjutnya adalah Analisis dan Visualisasi Data 
Dataset yang digunakan pada project ini adalah Gambar Sepatu 

yang akan diklasifikasikan berdasarkan jenisnya yaitu _boots, loafers, sneakers, dan soccers_

Lalu data tersebut akan divisualisasikan menggunakan grafik batang untuk mengetahui berapa jumlah filenya

Kemudian menampilkan beberapa gambar sepatu berdasarkan jenisnya 

dan menampilkan 5 gambar hasil dari preprocessing sesuai dengan ketentuan augmentasi di atas

_<h3>Data Modeling</h3>_

_<h3>Evaluasi</h3>_

<b><h2>Table of Content</h2></b>