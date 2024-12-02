# labpy06

Nama: Mahfuz Fauzi

NIM: 312410412

Kelas: TI.24.A.3

# Tugas Praktikum 6

### Buat program sederhana dengan mengaplikasikan penggunaan fungsi yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:
## CODE PROGRAM DAFTAR NILAI

### Step 1: Inisialisasi Data
Tambahkan variabel data_mahasiswa sebagai list kosong yang digunakan untuk menyimpan data mahasiswa, setiap elemen dalam list adalah dictionary yang berisi informasi mahasiswa berupa Nilai Mahasiswa untuk kasus ini :

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/step1.png">

### Step 2: Fungsi Tambah ()
Fungsi ini untuk menambahkan data mahasiswa baru yang akan diproses sebagai :

* Meminta pengguna memasukkan nama dan nilai mahasiswa.
* Data yang dimasukkan disimpan dalam bentuk dictionary {"nama": nama, "nilai": nilai}.
* Dictionary ini ditambahkan ke dalam list data_mahasiswa menggunakan .append().

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/step2.png">

### step 3: Fungsi Tampilkan ()
Fungsi ini digunakan untuk menampilkan data nilai mahasiswa ke dalam data_mahasiswa. Tujuan dapat menampilkan seluruh data mahasiswa. Menu ini mampu mengecek apakah data_mahasiswa kosong, Jika tidak kosong data ditampilkan dalam bentuk tabel sesuai data yang telah ditambahkan, Menggunakan enumerate untuk memberikan nomor pada setiap mahasiswa dalam daftar :

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/step3.png">

### Step 4: Fungsi Hapus (nama)
Menghapus data mahasiswa berdasarkan nama yang dimasukan/input, sebagai proses menggunakan list comprehension untuk membuat daftar baru yang tidak berisi mahasiswa dengan nama yang dimasukkan, variabel data_mahasiswa diperbarui dengan daftar baru ini :

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/step4.png">

### Step 5: Fungsi Ubah (nama)
Fungsi yang akan mengubah nilai mahasiswa berdasarkan nama yang dimasukan/input, mencari data mahasiswa dengan nama tertentu di dalam data_mahasiswa. Jika data ditemukan, maka nilai mahasiswa tersebut diperbarui sesuai input pengguna :

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/step5.png">

### Step 6: Fungsi Menu ()
Menyediakan Tampilan menu sebagai opsi pengguna, menggunakan perulangan while untuk terus menampilkan menu namun untuk menghentikan program masukan break sebagai perhentian :

Pilihan menu:

* 1: Memanggil fungsi tambah().
* 2: Memanggil fungsi tampilkan().
* 3: Memanggil fungsi hapus(nama).
* 4: Memanggil fungsi ubah(nama).
* 5: Menghentikan program.

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/step6.1.png">

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/step6.2.png">

### Step 7: Closed Program
Pakai menu() untuk memulai sebuah program ketika dirun :

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/step7.png">

### Step 8: Run Program
Tahap akhir adalah uji coba code program yang sudah dibuat.

# CONTOH OUTPUT

### 1. Tambah Data
Pertama saya mencoba menambahkan data mahasiswa pada tabel, dengan menginputkan '1' untuk menambahkan data mahasiswa.

* Untuk perawalan, mencoba memasukan satu data mahasiswa :
  * Nama : Mahfuz Fauzi
  * Nilai : 89

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/output%201.png">

### 2. Tampilkan Data
Selanjutnya, kondisi kedua menginputkan '2' untuk melihat daftar data mahasiswa pada tabel, namun dari kondisi sebelumnya yang sudah menambahkan data mahasiswa saya coba tambahkan 4 data mahasiswa lagi. maka akan terlihat pada isi tabel :

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/output%202.0.png">

### 3. Hapus Data
Kondisi ketiga, kita mencoba menghapus sebuah data mahasiswa dengan menginputkan '3' untuk menghapuskan data mahasiswa lalu user diminta memasukan nama mahasiswa yang akan dihapus :

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/output%203.png">

### 4. Ubah Data
Masuk kondisi keempat saya akan coba mengubah data, ada data yang salah diinputkan pada Nilai Mahasiswa 81 diubah menjadi 88, sebelum itu inputkan '4' untuk mengubah maka akan ditampilkan daftar nilai tabel dan diminta untuk memasukan nama mahasiswa yang ingin diubah data nilai -nya. User diminta memasukan kembali data valid yang akan diubah.

* Coba memasukan data mahasiswa berikut :
  * Nama : Rakha Ghani Ghani Ghani
  * Nilai : 88

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/output%204.png">

### 5. Keluar
Jika semua data atau program input sudah selesai semua, user dapat menginputkan 5 untuk keluar dari progam :

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/output%205.png">

# FLOWCHART DAFTAR NILAI

<img src="https://github.com/Mahfuz311/labpy06/blob/main/labpy06/screenshot/flowchart.png">

### Step 1 :
Titik mulai sebuah program atau alur.

### Step 2 :
lalu lakukan inisialisasi dengan menampilkan menu yang tersedia.

### Step 3 :
Inputkan code menu yang ingin dilakukan, setiap code berisi :

1. Tambah,
2. Tampilkan,
3. Hapus,
4. Ubah,
5. Keluar.

### Step 4 :
Dalam kasus ini semua kemgkinan dapat terjadi, kondisi yang diperlukan sesuai apa yang akan diinoutkan user.

* Jika Tampilkan, maka user akan di tampilkan sebuah tabel dari daftar nilai, namun jika tabel belum ada isi/kosong maka akan tampil Belum ada data, jika ada maka ditampilkan sebuah data nilai mahasiswa. Setelah tampilkan data maka akan kembali menuju inisialisasi menu.

* Jika Tambah, user diminta memasukan sebuah data yang berupa :

  * Nama
  * Nilai
Lalu User akan diarahkan kembali ke inisialiasi menu.

* Jika Ubah, sama dengan Tampilkan jika tidak ada data nilai maka akan tampil tidak ada data nilai namun Ubah kalau ada data nilai user diminta menginputkan Nama Mahasiswa yang akan diubah, setelah itu diminta untuk mengisi atau menginputkan data valid yang diubah. Setelah itu user kembali ke inisialisasi menu.

* Jika Hapus, user akan ditampilkan daftar nilai lalu diminta memasukan sebuah Nama yang ingin dihapus dari daftar. Setelah itu kembali ke inisialisasi menu.

* jika Keluar, User akan keluar program dan program akan berhenti.

# KESIMPULAN
Program yang telah dibuat adalah aplikasi sederhana untuk mengelola data nilai mahasiswa dengan menggunakan fungsi dalam Python. Program ini memiliki empat fitur utama yang dapat dijalankan melalui menu interaktif:
