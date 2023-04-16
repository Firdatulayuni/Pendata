Nama: Firdatul A'yuni

NIM: 210411100144

Kelas: Penambangan Data A



Mengumpulkan Data Dari Berbagai Sumber

Aplikasi yang dibutuhkan:

1. PostgreSQL
2. Xammp
3. Power BI
4. Membuat akun elephant

Tahapan-tahapan pengumpulan data dari beberapa sumber:

**Langkah 1**

1. Membuat akun elephant, 

2. Kemudian membuat instance dengan nama pendatab yang akan digunakan untuk server cloud![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1392).png)



**Langkah 2**

**Menghubungkan server dari elephant ke postgresql**

1. Buka pgadmin

2. Klik kanan server lalu pilih register kemudian pilih server

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1397).png)

3. Pada general isi dengan nama pendatab 

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1395).png)

4. Pada connection isi sesuai dengan yang ada di instance elephant, kemudian save

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1396).png)

5. Jika sudah berhasil, buka database dan pilih yang namanya sesuai dengan yang ada di elephant

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1399).png)

6. kemudian pilih schema dan klik kanan table dan pilih query tool

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1401).png)

7. Salin data di github kemudian tempel di query tool

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1402).png)

8. Jika berhasil maka setelah di execute akan tertera successfully

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1404).png)

9. Kemudian refresh table untuk melihat data iris yang sudah sukses di import

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1406).png)





**Langkah 3**

**Membuat server local postgres**

1. Buat server kembali

2. Beri nama localpendatab

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1407).png)

3. Pada connection atur seperti dibawah ini, dan menggunakan password pgadmin

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1408).png)

4. Buat database![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1409).png)

5. Kemudian buat tabel di query tool dengan cara yang sama

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1411).png)



**Langkah 3**

**Import data iris yang terdapat pada database localhost ke power BI**

1. Buka power BI

2. Kemudian klik dapatkan data dan pilin teks/csv

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1412).png)

3. Pilih data yang telah di export dari postgres

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1413).png)

4. Ini data yang sudah berhasil 

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1414).png)

5. Klik iris dan centang semua 

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1415).png)

6. Klik gambar chart untuk menampilkan diagram data

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1417).png)



**Import data iris yang terdapat pada database cloud postgres**

1. Klik dapatkan data > lainnya> cari database postgre lalu sambungkan

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1419).png)

2. Isi server dengan nama server di elephant dan nama databasenya di postgre

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1420).png)

3. Isi dengan username dan sandi elephant

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1421).png)

4. Data sudah berhasil di import

   ![](C:\Users\Firdatul Ayuni\Downloads\WhatsApp Image 2023-03-03 at 9.39.25 PM.jpeg)

   ![](C:\Users\Firdatul Ayuni\Downloads\WhatsApp Image 2023-03-03 at 9.39.26 PM.jpeg)

   

**Import data iris.csv ke phpMyAdmin**

1. Buka phpMyAdmin

2. Buat database baru dengan nama irispendata

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1422).png)

3.Klik impor, kemudian pilih data yang sudah diekspor dari postgre

![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1423).png)

4. Jika sudah sukses akan muncul bacaan seperti gambar dibawah ini

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1424).png)

**Import data iris dari phpMyAdmin ke power BI**

1. Buka dapatkan data>  lainnya> database MySql

2. Isi sesuai dengan nama database

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1429).png)

3. Kemudian isi username root

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1430).png)

4. Import sudah  berhasil

   ![](C:\Users\Firdatul Ayuni\Pictures\Screenshots\Screenshot (1431).png)

**Import data iris dari postgresql ke power BI**

1. 