# labpy06

Nama: Mahfuz Fauzi

NIM: 312410412

Kelas: TI.24.A.3

# Tugas Praktikum 6

### Buat program sederhana dengan mengaplikasikan penggunaan fungsi yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:
## CODE PROGRAM DAFTAR NILAI

### Step 1: Inisialisasi Data
Tambahkan variabel data_mahasiswa sebagai list kosong yang digunakan untuk menyimpan data mahasiswa, setiap elemen dalam list adalah dictionary yang berisi informasi mahasiswa berupa Nilai Mahasiswa untuk kasus ini :



### Step 2: Fungsi Tambah ()
Fungsi ini untuk menambahkan data mahasiswa baru yang akan diproses sebagai :

* Meminta pengguna memasukkan nama dan nilai mahasiswa.
* Data yang dimasukkan disimpan dalam bentuk dictionary {"nama": nama, "nilai": nilai}.
* Dictionary ini ditambahkan ke dalam list data_mahasiswa menggunakan .append().

### step 3: Fungsi Tampilkan ()
Fungsi ini digunakan untuk menampilkan data nilai mahasiswa ke dalam data_mahasiswa. Tujuan dapat menampilkan seluruh data mahasiswa. Menu ini mampu mengecek apakah data_mahasiswa kosong, Jika tidak kosong data ditampilkan dalam bentuk tabel sesuai data yang telah ditambahkan, Menggunakan enumerate untuk memberikan nomor pada setiap mahasiswa dalam daftar :


### Step 4: Fungsi Hapus (nama)
Menghapus data mahasiswa berdasarkan nama yang dimasukan/input, sebagai proses menggunakan list comprehension untuk membuat daftar baru yang tidak berisi mahasiswa dengan nama yang dimasukkan, variabel data_mahasiswa diperbarui dengan daftar baru ini :



### Step 5: Fungsi Ubah (nama)
Fungsi yang akan mengubah nilai mahasiswa berdasarkan nama yang dimasukan/input, mencari data mahasiswa dengan nama tertentu di dalam data_mahasiswa. Jika data ditemukan, maka nilai mahasiswa tersebut diperbarui sesuai input pengguna :



### Step 6: Fungsi Menu ()
Menyediakan Tampilan menu sebagai opsi pengguna, menggunakan perulangan while untuk terus menampilkan menu namun untuk menghentikan program masukan break sebagai perhentian :

Pilihan menu:

* 1: Memanggil fungsi tambah().
* 2: Memanggil fungsi tampilkan().
* 3: Memanggil fungsi hapus(nama).
* 4: Memanggil fungsi ubah(nama).
* 5: Menghentikan program.




### Step 7: Closed Program
Pakai menu() untuk memulai sebuah program ketika dirun :



### Step 8: Run Program
Tahap akhir adalah uji coba code program yang sudah dibuat.

# CONTOH OUTPUT

