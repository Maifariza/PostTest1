# POST-TEST 1 PRAKTIKUM PBO

### **Disusun Oleh**

===========================================================================

                                                                

**Maifariza Aulia Dyas - 2409116032**                         

                                                                

   Sistem Informasi - A - 2024                                  

                                                               

===========================================================================
 
### **SISTEM MANAJEMEN KOLEKSI BARANG ANTIK**

  <h1 align="center">AntikAesthetic 🔎⏳</h1>
    
 -------------------------------------------------------------------------
 

   AntikAesthetic adalah program untuk menyimpan koleksi barang antik yang dibuat menggunakan bahasa pemrograman Java.   Program ini dirancang untuk membantu pengguna dalam mengelola data koleksi barang antik agar lebih teratur, rapi, dan mudah diakses. Dengan adanya program ini, proses pencatatan barang antik tidak lagi dilakukan secara manual, tetapi sudah terkomputerisasi sehingga lebih efisien dan minim kesalahan.
   
   Program ini menyediakan fitur utama berupa CRUD (Create, Read, Update, Delete) dan pencarian. Melalui fitur tersebut, pengguna dapat menambahkan barang baru ke dalam koleksi, menampilkan seluruh data barang dalam bentuk tabel, memperbarui data tertentu berdasarkan ID, hingga menghapus barang yang sudah tidak diperlukan. 
   
   Fitur pencarian tersedia untuk memudahkan pengguna menemukan barang tertentu hanya dengan memasukkan kata kunci, baik dari nama, kategori, maupun asal barang. 

   Setiap barang antik yang disimpan dalam sistem digambarkan sebagai sebuah objek dengan atribut yang cukup lengkap, mulai dari ID unik, nama barang, kategori, asal, tahun pembuatan, material, kondisi, sumber perolehan, hingga harga perolehan. Seluruh data ini dikelola menggunakan struktur ArrayList, sehingga penyimpanan menjadi lebih fleksibel dan juga memudahkan proses manipulasi data seperti menambah, menampilkan, memperbarui, maupun menghapus.

# Menu Utama AntikAesthetic

<img width="468" height="203" alt="Screenshot 2025-09-09 130453" src="https://github.com/user-attachments/assets/d3f33513-9c4f-46f7-b978-f377ab2f1dfd" />

Pada awal program, pengguna akan langsung diarahkan ke Menu Utama AntikAesthetic. Menu ini berfungsi sebagai menu utama untuk mengakses seluruh fitur yang tersedia. Terdapat enam pilihan utama yang bisa dipilih sesuai kebutuhan.

   1. Tambah Barang, digunakan untuk menambahkan data barang antik baru dengan mengisi atribut seperti nama, kategori, asal, tahun pembuatan, material, kondisi, sumber perolehan, dan harga perolehan.

   2. Tampilkan Semua Barang, menampilkan seluruh koleksi barang antik yang tersimpan dalam bentuk tabel agar mudah dibaca.

   3. Perbarui Barang, memungkinkan pengguna memperbarui data barang tertentu dengan memasukkan ID barang yang ingin diubah.

   4. Hapus Barang, menghapus data barang dari koleksi berdasarkan ID barang yang ingin dihapus.

   5. Cari Barang, memudahkan pengguna menemukan data barang tertentu dengan memasukkan kata kunci pencarian seperti nama/kategori/asal barang yang ingin dicari.
   
   6. Keluar, digunakan untuk menutup program. Sebelum benar-benar keluar, sistem akan menampilkan konfirmasi agar tidak terjadi kesalahan.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Jika memilih opsi 1 maka akan diarahkan ke Tambah Barang**

<img width="543" height="218" alt="Screenshot 2025-09-08 133146" src="https://github.com/user-attachments/assets/3c28606b-1806-4aa2-a829-413c76e1bfce" />

Ketika pengguna memilih opsi 1 pada menu utama, maka program akan diarahkan ke fitur Tambah Barang. Pada bagian ini, sistem meminta pengguna untuk mengisi informasi detail mengenai barang antik baru yang ingin ditambahkan ke dalam koleksi AntikAesthetic.

Pada saat pengguna memilih opsi 1 (Tambah Barang), program akan menampilkan form input untuk menambahkan data barang antik baru ke dalam sistem.

Seperti pada gambar, user ingin menambah barang Patung Ganesha. Setelah itu, user diminta mengisi informasi lainnya secara berurutan, mulai dari kategori barang, asal, tahun pembuatan, material, kondisi barang, sumber perolehan, hingga harga perolehan.


### Pemberitahuan Jika Berhasil

<img width="336" height="47" alt="Screenshot 2025-09-08 133343" src="https://github.com/user-attachments/assets/bf6b9c29-6fe7-4225-842f-4d8fcfea9c58" />

Setelah semua data selesai diisi, sistem akan otomatis memberikan ID unik untuk barang baru tersebut dan menambahkannya ke dalam koleksi. 

### Pengecekan Ulang

<img width="1007" height="546" alt="Screenshot 2025-09-08 133435" src="https://github.com/user-attachments/assets/0ea1f0c7-7433-4deb-96a7-1b9fb458d17d" />

Lalu untuk melihat daftar koleksi yang telah ditambahkan, user ketik 2. Di bagian akhir, program menampilkan instruksi “Tekan Enter untuk melanjutkan…” agar pengguna bisa kembali ke menu utama dan melanjutkan ke fitur lain sesuai kebutuhan.

### Jika Inputan Kosng

<img width="292" height="97" alt="Screenshot 2025-09-08 162201" src="https://github.com/user-attachments/assets/9363c488-0979-4736-81bd-35b5cea66035" />

Apabila pengguna mencoba menambahkan barang baru namun tidak mengisi data pada kolom yang diminta, maka program akan menampilkan pesan peringatan. Misalnya, ketika pengguna menekan Enter tanpa mengetikkan nama barang, sistem akan menampilkan pesan “Input tidak boleh kosong”.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Jika memilih opsi 2 maka akan diarahkan ke Tampilkan Barang**

<img width="1266" height="583" alt="Screenshot 2025-09-08 125848" src="https://github.com/user-attachments/assets/91e9b339-ada3-40bd-9990-b05a013449d8" />

  Jika pengguna memilih opsi 2 pada menu utama, maka program akan diarahkan ke fitur Tampilkan Semua Barang. Pada bagian ini, sistem akan menampilkan seluruh koleksi barang dari AntikAesthetic yang sudah tersimpan dalam database program. Data ditampilkan dalam bentuk tabel agar lebih terstruktur dan mudah dipahami.

  Tabel tersebut berisi informasi penting yang dibagi ke dalam beberapa kolom, yaitu ID, Nama, Kategori, Asal, Tahun Pembuatan, Material, Kondisi, Sumber Perolehan, dan Harga. Setiap baris dalam tabel mewakili satu objek barang antik, sementara ID berfungsi sebagai penanda unik sehingga data dapat dengan mudah diidentifikasi saat ingin diperbarui atau dihapus.

  Melalui tampilan ini, pengguna dapat dengan mudah melihat keseluruhan koleksi barang antik hanya dalam satu layar. Format tabel yang rapi membuat data lebih mudah dibaca, dipahami, dan dibandingkan antar barang. Hal ini membantu pengguna ketika ingin menilai kondisi, harga, atau asal-usul barang tertentu secara cepat.

  Setelah seluruh data ditampilkan, program akan memberikan instruksi kepada pengguna untuk menekan tombol Enter agar dapat melanjutkan ke langkah berikutnya. Tekanan tombol Enter ini akan mengembalikan pengguna ke menu utama, sehingga pengguna dapat memilih kembali menu yang lain sesuai kebutuhan, misalnya menambah barang, memperbarui, menghapus, atau keluar dari program.
  
--------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Jika memilih opsi 3 maka akan diarahkan ke Update Barang**


<img width="552" height="311" alt="Screenshot 2025-09-08 134932" src="https://github.com/user-attachments/assets/e332eafe-cdc4-4199-9ef0-b3d102827924" />

Ketika pengguna memilih opsi 3 pada menu utama, maka program akan diarahkan ke fitur Update Barang.
Pada bagian ini, sistem meminta pengguna untuk memasukkan ID dari barang yang ingin diperbarui. ID ini digunakan sebagai penanda unik setiap barang dalam koleksi.

Setelah ID dimasukkan, program akan menampilkan form dengan data lama sebagai referensi. Pengguna dapat mengosongkan input (menekan Enter) jika ingin mempertahankan nilai lama, atau mengetikkan data baru untuk mengganti informasi.

Misalnya, pengguna ingin memperbarui barang dengan ID 1 (Vas Dinasti Ming). Program akan menampilkan data lama seperti nama barang, kategori, asal, tahun pembuatan, material, kondisi, sumber perolehan, dan harga. Pengguna bisa mengubah salah satu atau beberapa data, contohnya kondisi dari “Baik” menjadi “Rusak”. Setelah menekan Enter, program akan menyimpan perubahan tersebut dan menampilkan pesan “Data ID 1 berhasil diperbarui”.

### Pengecekan Ulang

<img width="1012" height="448" alt="Screenshot 2025-09-08 135110" src="https://github.com/user-attachments/assets/4fd7c124-d5a7-4b33-a555-667234657b95" />

Setelah proses update selesai, pengguna dapat melihat daftar koleksi untuk memastikan bahwa data sudah diperbarui sesuai dengan input terbaru dengan ketik opsi 2. Tabel akan menampilkan kondisi data terbaru dengan informasi yang sudah diperbarui.

### Jika Input ID yang tidak terdaftar

<img width="402" height="102" alt="Screenshot 2025-09-09 130728" src="https://github.com/user-attachments/assets/655ae614-a723-4fb4-ad74-ec7dc907345f" />

Apabila pengguna memasukkan ID yang tidak ada di dalam koleksi, maka program akan memberikan pesan peringatan seperti pada gambar diatas. 

Pesan ini berfungsi sebagai validasi agar pengguna mengetahui bahwa ID yang dimasukkan salah atau tidak tersedia.

### Jika Input huruf

<img width="465" height="284" alt="Screenshot 2025-09-09 130620" src="https://github.com/user-attachments/assets/1b0370d6-d9fb-42b0-a154-78e2f6df9f3e" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------
 
# **Jika memilih opsi 4 maka akan diarahkan ke Hapus Barang**

<img width="349" height="147" alt="Screenshot 2025-09-08 133548" src="https://github.com/user-attachments/assets/8dd8b23b-c93c-4a12-9064-c874454be095" />


<img width="336" height="138" alt="Screenshot 2025-09-08 133604" src="https://github.com/user-attachments/assets/90911f05-750a-45dc-865a-bf06fb226e9f" />


<img width="326" height="192" alt="Screenshot 2025-09-08 133622" src="https://github.com/user-attachments/assets/46f0c34a-7f09-476b-a2ca-face02704ecc" />


<img width="359" height="168" alt="Screenshot 2025-09-08 133649" src="https://github.com/user-attachments/assets/70f77aae-ba2d-493c-9a63-7b00666220d7" />

### Jika Input ID yang tidak terdaftar

<img width="329" height="130" alt="Screenshot 2025-09-08 133959" src="https://github.com/user-attachments/assets/280c8281-eecf-4156-ba4f-b9b1d97c000b" />

### Jika Input ID selain angka


<img width="334" height="183" alt="Screenshot 2025-09-08 134318" src="https://github.com/user-attachments/assets/c5db5fce-efd5-487f-a161-bdeacda6c84b" />

--------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Jika memilih opsi 5 maka akan diarahkan ke Cari Barang**

### Cari Berdasarkan Nama Barang

<img width="985" height="160" alt="Screenshot 2025-09-08 135635" src="https://github.com/user-attachments/assets/c4ed5f05-4cb8-4bc5-b222-006758a175b3" />

### Cari Berdasarkan Kategori

<img width="982" height="164" alt="Screenshot 2025-09-08 140013" src="https://github.com/user-attachments/assets/1bf6b9e3-8601-4e41-b86a-86120259a3b4" />

### Cari Berdsarkan Asal

<img width="983" height="160" alt="Screenshot 2025-09-08 140157" src="https://github.com/user-attachments/assets/fd2e8cac-0609-4615-a806-3ff43b1d94de" />

### Input Kata Kunci yang tidak terdaftar

<img width="388" height="119" alt="Screenshot 2025-09-08 140255" src="https://github.com/user-attachments/assets/c3013074-2505-4453-ab92-17a4e1cbfbc2" />

### Inputan Kosong

<img width="341" height="113" alt="Screenshot 2025-09-09 094143" src="https://github.com/user-attachments/assets/a0f53bdb-25e3-42ca-841c-effd5c0cdc83" />


--------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Jika memilih opsi 6 maka akan diarahkan Keluar Program AntikAesthetic**

### Jika memilih "y"

<img width="462" height="294" alt="Screenshot 2025-09-09 130258" src="https://github.com/user-attachments/assets/a97dda3e-362e-4a05-ad42-5d8d46a551bd" />


### Jika memilih "n"

<img width="469" height="283" alt="Screenshot 2025-09-09 130223" src="https://github.com/user-attachments/assets/7b4a8cb2-1fb8-4a97-a604-6ede66c4fb95" />


### Jika memilih selain "y" dan "n"

<img width="470" height="282" alt="Screenshot 2025-09-09 130125" src="https://github.com/user-attachments/assets/85249312-528a-48ab-a541-6b516fda71d6" />


--------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Jika user input selain opsi 1-7**

<img width="457" height="254" alt="Screenshot 2025-09-09 125912" src="https://github.com/user-attachments/assets/67ec9884-670c-462b-8dd6-cbb210c67051" />


--------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Jika user input huruf pada Menu Utama**


<img width="465" height="250" alt="Screenshot 2025-09-09 125746" src="https://github.com/user-attachments/assets/26387c70-961b-4c14-b291-2bef5e6d4572" />
