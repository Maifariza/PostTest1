# POST-TEST 1 PRAKTIKUM PBO

### **Disusun Oleh**

============================================================================================

                                                                

**Maifariza Aulia Dyas - 2409116032**                         

                                                                

   Sistem Informasi - A - 2024                                  

                                                               

============================================================================================
 
### **SISTEM MANAJEMEN KOLEKSI BARANG ANTIK**

  <h1 align="center">AntikAesthetic 🔎⏳</h1>
    
 ----------------------------------------------------------------------------------------
 

   AntikAesthetic adalah program untuk menyimpan koleksi barang antik yang dibuat menggunakan bahasa pemrograman Java.   Program ini dirancang untuk membantu pengguna dalam mengelola data koleksi barang antik agar lebih teratur, rapi, dan mudah diakses. Dengan adanya program ini, proses pencatatan barang antik tidak lagi dilakukan secara manual, tetapi sudah terkomputerisasi sehingga lebih efisien dan minim kesalahan.
   
   Program ini menyediakan fitur utama berupa CRUD (Create, Read, Update, Delete) dan pencarian. Melalui fitur tersebut, pengguna dapat menambahkan barang baru ke dalam koleksi, menampilkan seluruh data barang dalam bentuk tabel, memperbarui data tertentu berdasarkan ID, hingga menghapus barang yang sudah tidak diperlukan. Selain itu, tersedia juga fitur pencarian untuk memudahkan pengguna menemukan barang tertentu hanya dengan memasukkan kata kunci, baik dari nama, kategori, maupun asal barang. 

   Setiap barang antik yang disimpan dalam sistem digambarkan sebagai sebuah objek dengan atribut yang cukup lengkap, mulai dari ID unik, nama barang, kategori, asal, tahun pembuatan, material, kondisi, sumber perolehan, hingga harga perolehan. Seluruh data ini dikelola menggunakan struktur ArrayList, sehingga penyimpanan menjadi lebih fleksibel dan juga memudahkan proses manipulasi data seperti menambah, menampilkan, memperbarui, maupun menghapus.

# Menu Utama AntikAesthetic

<img width="643" height="266" alt="Screenshot 2025-09-08 112358" src="https://github.com/user-attachments/assets/f495068e-a9ea-4d29-bec4-bccf41e6b200" />

Pada awal program, pengguna akan langsung diarahkan ke Menu Utama AntikAesthetic. Menu ini berfungsi sebagai menu utama untuk mengakses seluruh fitur yang tersedia. Terdapat enam pilihan utama yang bisa dipilih sesuai kebutuhan.

   1. Tambah Barang, digunakan untuk menambahkan data barang antik baru dengan mengisi atribut seperti nama, kategori, asal, tahun pembuatan, material, kondisi, sumber perolehan, dan harga perolehan.

   2. Tampilkan Semua Barang, menampilkan seluruh koleksi barang antik yang tersimpan dalam bentuk tabel agar mudah dibaca.

   3. Perbarui Barang, memungkinkan pengguna memperbarui data barang tertentu dengan memasukkan ID barang yang ingin diubah.

   4. Hapus Barang, menghapus data barang dari koleksi berdasarkan ID barang yang ingin dihapus.

   5. Cari Barang, memudahkan pengguna menemukan data barang tertentu dengan memasukkan kata kunci pencarian seperti nama/kategori/asal barang yang ingin dicari.

   6. Keluar, digunakan untuk menutup program. Sebelum benar-benar keluar, sistem akan menampilkan konfirmasi agar tidak terjadi kesalahan.

# Jika memilih opsi 1 maka akan diarahkan ke Tambah Barang

<img width="543" height="218" alt="Screenshot 2025-09-08 133146" src="https://github.com/user-attachments/assets/3c28606b-1806-4aa2-a829-413c76e1bfce" />


<img width="336" height="47" alt="Screenshot 2025-09-08 133343" src="https://github.com/user-attachments/assets/bf6b9c29-6fe7-4225-842f-4d8fcfea9c58" />


<img width="1007" height="546" alt="Screenshot 2025-09-08 133435" src="https://github.com/user-attachments/assets/0ea1f0c7-7433-4deb-96a7-1b9fb458d17d" />


# Jika memilih opsi 2 maka akan diarahkan ke Tampilkan Barang

<img width="1266" height="583" alt="Screenshot 2025-09-08 125848" src="https://github.com/user-attachments/assets/91e9b339-ada3-40bd-9990-b05a013449d8" />

  Jika pengguna memilih opsi 2 pada menu utama, maka program akan diarahkan ke fitur Tampilkan Semua Barang. Pada bagian ini, sistem akan menampilkan seluruh koleksi barang dari AntikAesthetic yang sudah tersimpan dalam database program. Data ditampilkan dalam bentuk tabel agar lebih terstruktur dan mudah dipahami.

  Tabel tersebut berisi informasi penting yang dibagi ke dalam beberapa kolom, yaitu ID, Nama, Kategori, Asal, Tahun Pembuatan, Material, Kondisi, Sumber Perolehan, dan Harga. Setiap baris dalam tabel mewakili satu objek barang antik, sementara ID berfungsi sebagai penanda unik sehingga data dapat dengan mudah diidentifikasi saat ingin diperbarui atau dihapus.

  Melalui tampilan ini, pengguna dapat dengan mudah melihat keseluruhan koleksi barang antik hanya dalam satu layar. Format tabel yang rapi membuat data lebih mudah dibaca, dipahami, dan dibandingkan antar barang. Hal ini membantu pengguna ketika ingin menilai kondisi, harga, atau asal-usul barang tertentu secara cepat.

  Setelah seluruh data ditampilkan, program akan memberikan instruksi kepada pengguna untuk menekan tombol Enter agar dapat melanjutkan ke langkah berikutnya. Tekanan tombol Enter ini akan mengembalikan pengguna ke menu utama, sehingga pengguna dapat memilih kembali menu yang lain sesuai kebutuhan, misalnya menambah barang, memperbarui, menghapus, atau keluar dari program.
  

# Jika memilih opsi 3 maka akan diarahkan ke Update Barang


<img width="552" height="311" alt="Screenshot 2025-09-08 134932" src="https://github.com/user-attachments/assets/e332eafe-cdc4-4199-9ef0-b3d102827924" />

### Pengecekan Ulang

<img width="1012" height="448" alt="Screenshot 2025-09-08 135110" src="https://github.com/user-attachments/assets/4fd7c124-d5a7-4b33-a555-667234657b95" />


### Jika Input ID yang tidak terdaftar

<img width="455" height="77" alt="Screenshot 2025-09-08 135329" src="https://github.com/user-attachments/assets/9308cac3-af87-40fb-91da-8614c6de7dc4" />


# Jika memilih opsi 4 maka akan diarahkan ke Hapus Barang

<img width="349" height="147" alt="Screenshot 2025-09-08 133548" src="https://github.com/user-attachments/assets/8dd8b23b-c93c-4a12-9064-c874454be095" />


<img width="336" height="138" alt="Screenshot 2025-09-08 133604" src="https://github.com/user-attachments/assets/90911f05-750a-45dc-865a-bf06fb226e9f" />


<img width="326" height="192" alt="Screenshot 2025-09-08 133622" src="https://github.com/user-attachments/assets/46f0c34a-7f09-476b-a2ca-face02704ecc" />


<img width="359" height="168" alt="Screenshot 2025-09-08 133649" src="https://github.com/user-attachments/assets/70f77aae-ba2d-493c-9a63-7b00666220d7" />

### Jika Input ID yang tidak terdaftar

<img width="329" height="130" alt="Screenshot 2025-09-08 133959" src="https://github.com/user-attachments/assets/280c8281-eecf-4156-ba4f-b9b1d97c000b" />

### Jika Input ID selain angka


<img width="334" height="183" alt="Screenshot 2025-09-08 134318" src="https://github.com/user-attachments/assets/c5db5fce-efd5-487f-a161-bdeacda6c84b" />


# Jika memilih opsi 5 maka akan diarahkan ke Cari Barang

# Jika memilih opsi 6 maka akan diarahkan Keluar Program AntikAesthetic

# Jika user input selain opsi 1-6


