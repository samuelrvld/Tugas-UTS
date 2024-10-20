1. Instalasi Laravel 11:
   Pastikan sudah terinstal PHP, Composer, dan MySQL.
   Instal Laravel:
   ![Gambar](image.png)

   ![Gambar](image-1.png)

   ![Gambar](image-2.png)

2. Konfigurasi Database:
   Buat database MySQL baru bernama 'tokobuku_db'.
   Sesuaikan file .env dengan informasi berikut:

   ![Gambar](image-3.png)

3. Migrasi Awal:
   Jalankan perintah berikut untuk membuat tabel default:

   ![Gambar](image-4.png)

4. Membuat Migration dan Model
   Buat migration dan model untuk Kategori dan Buku:

   ![Gambar](image-5.png)

    Edit file migration `create_kategoris_table.php`:

   ![Gambar](image-6.png)

    Edit file migration `create_bukus_table.php`
   ![Gambar](image-7.png)

 5. Membuat Controller API untuk Kategori dan Buku
  Buat controller untuk Kategori dan Buku:
  ![gambar](image-8.png)

  Isi file `KategoriController.php`:
  ![Gambar](image-9.png)

  Testing API dengan Postman
  Jalankan server Laravel:
  ![Gambar](image-10.png)

  

