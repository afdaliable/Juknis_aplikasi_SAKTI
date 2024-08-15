

![0_image_0.png](0_image_0.png)

![0_image_1.png](0_image_1.png)

Petunjuk Teknis Aplikasi SAKTI
MODUL PERSEDIAAN
♦
♦
♦

# Petunjuk Teknis Transaksi Persediaan Juknis Persediaan Dalam Proses

## Deskripsi Singkat Menu

Menu persediaan dalam proses ini, digunakan untuk melakukan perekaman pembelian barang persediaan diserahkan ke masyarakat ( kode barang 10105 XXXXX ) yag diperoleh bukan dari pembelian langsung, melainkan pembeliaanya terdidi dari beberapa termin.

## Contoh Simulasi

Terdapat pembelian Receiver diserahkan ke masyarakat ( kode 10105 XXXXX ), yang diperoleh dari 2 kali pembayaran, ada 2 BAST. Untuk tiap-tiap pembayaran, harus didetilkan dahulu ke kode barang dalam proses ( 10109 XXXXX ) terlebih dahulu. Pendetilan BAST pertama akan didetilkan sebagai Receiver Tahap I dan pendetilan BAST kedua akan didetilkan sebagai Reicever Tahap II. Jika sudah, baru nanti diselesaikan pada menu Penyelesaian persediaan dalam proses untuk dijadikan ke kode barang diserahkan ke masyarakat ( 10105 XXXXX ).

## Langkah Perekaman Bast Di Modul Komitmen

Perekaman pada Modul Komitmen saat membuat BAST. Pada BAST pastikakn kode barng yang dipilih dan jumlah barang disesuaikan dengan proporsi sesuai pembayaran tahap I-nya

![2_image_0.png](2_image_0.png)

Tentukan pengisian jumlah barang dan harga satuan

![3_image_0.png](3_image_0.png)

## Langkah Perekaman Di Modul Persediaan Sakti

Membuat Refrensi Kode Barang Pada user opr satker induk. Silahkan masuk ke menu refrensi, mengelola barang persediaan

![3_image_1.png](3_image_1.png)

Untuk Barang persediaan dalam proses, menggunakan kode barang khusus ( 10109 XXXXX )

![4_image_0.png](4_image_0.png)

Kita buat kode barang dalam proses I ( untuk pembayaran pertama )

![4_image_1.png](4_image_1.png) Buat kode barang dalam proses II ( untuk pembayaran kedua )

![4_image_2.png](4_image_2.png)

Masuk ke menu pembelian untuk mendetilkan masing2 BAST di barang dalam proses

![5_image_0.png](5_image_0.png)

![5_image_1.png](5_image_1.png)

Kita pilih kode barang ( tahap I )

![5_image_2.png](5_image_2.png)

 Lanjut diisikan jumlah barang dan harga satuan, disesuaikan eprrti yang di BAST
Pembelian Men

![6_image_0.png](6_image_0.png)

![6_image_1.png](6_image_1.png)

Pada User Appoval lakukan persetujuan an Transaksi Persediaan Tables Build econ Masuk pada menu pembelian, klik tombol rekam

![7_image_0.png](7_image_0.png)

![7_image_1.png](7_image_1.png)

![7_image_2.png](7_image_2.png)

![7_image_3.png](7_image_3.png)

![7_image_4.png](7_image_4.png)

![7_image_5.png](7_image_5.png)

Lanjut diisikan jumlah barang dan harga satuan, disesuaikan eprrti yang di BAST

![8_image_0.png](8_image_0.png)

![8_image_1.png](8_image_1.png)

Pada User Appoval lakukan persetujuan

![8_image_2.png](8_image_2.png)

## Penyelesaian Persediaan Dalam Proses

Pada tahap ini kita sudah merekam semua termin pembayaran ( BAST I dan BAST II ) dalam bentuk kode barang dalam proses I dan kode barang dalam proses II ( 10109 XXXXX). Sampai di tahap ini, mash berupa barang dalam proses dan perlu lankah selanjutnya untuk memproses menjadi barang di serahkan ke masyarakat ( 10105 XXXXX ). Masuk pada menu Persediaan dalam proses > penyelesaian persediaan dalam proses, klik tombol rekam maka akan muncul form berikut. Silahkan isikan No Bukti dasar transaksi, tanggal dokumen dan tanggal buku

![9_image_0.png](9_image_0.png)

Lalu pilih kode barang dalam proses ( 10109 XXXX ) yang akan dijadikan menjadi barang yang akan diserahkan ke masyarakat, dalam contoh ini, dipilih kode barang Receiver Dalam Proses I. 

Dalam form berikutnya yang muncul ( form input jumlah ) silahakn diisikan jumlah barnag dalam proses yang akan dijadikan menjadi barang diserahkan ke masyarakat. Dalam contoh ini semua kode barang Receiver dalam proses I ( 10 buah ) akan dijadikan menjadi barang diserahkan ke masyarakat ( kode barang 10105XXXXX ), lalu klik simpan.

![9_image_1.png](9_image_1.png)

ii
Berikutnya kita pilih kode barang receiver dalam proses II dan kita isikan jumlahnya yang akan dijadikan barang diserahkan ke masyarakat ( kode 10105 XXXXX ), setelah itu klik simpan

![10_image_0.png](10_image_0.png)

Pada Langkah berikutnya, kita isikan jumlah barang yang diserahkan ke masyarakat ( kode 10105XXXXX ). Dalam contoh ini akan dijadikan kode barang Receiver Diserahkan ke Masyarakat dengan cara klik tombol tambah di sisi kanan dan pilih barangnya dengan cara klik tombol cari 

![10_image_1.png](10_image_1.png)

Pilih kode barang Receiver Diserahkan ke Masyarakat, lalu isikan jumlah yang akan dijadikan menjadi Receiver Diserahkan ke Masyarakat seperti form dibawah ini ( dalam contoh ini Reicever Diserahkan ke Masyarakat ada 20 buah ). SIlahkan isikan kolom keterangan jika dibutuhkan keterangan yang lebih jelas. 

![11_image_0.png](11_image_0.png)

![11_image_1.png](11_image_1.png)

![12_image_2.png](12_image_2.png)

![12_image_0.png](12_image_0.png)

![12_image_1.png](12_image_1.png)

