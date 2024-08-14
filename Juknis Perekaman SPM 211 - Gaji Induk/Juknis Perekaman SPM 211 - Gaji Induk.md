

![0_image_0.png](0_image_0.png)

![0_image_1.png](0_image_1.png)

�
Petunjuk Teknis Aplikasi SAKTI
♦ PEREKAMAN SPM
GAJI INDUK
�
�
�

## I. Informasi Umum A. Deskripsi Transaksi

Jenis SPM:211-Gaji Induk digunakan untuk Pembayaran atas Gaji Induk Pegawai

| Modul                  | PEM                                                                                                                                                                 |
|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Role User              | OPR, VAL, APP                                                                                                                                                       |
| Modul Lain yang        | KOM                                                                                                                                                                 |
| Terkait Transaksi yang | KOM - Pembuatan supplier tipe 3                                                                                                                                     |
| Tekait                 | KOM - Import GPP Terpusat                                                                                                                                           |
| Dokumen Input          | SPP SPM 211-Gaji Induk                                                                                                                                              |
| Output                 | SP2D Gaji Induk                                                                                                                                                     |
| Validasi               | User harus memastikan data supplier tipe 3 sebagai penerima pembayaran atas  Gaji Induk telah direkam sebelumnya di pencatatan data supplier dalam Modul  Komitmen. |

Beberapa hal yang perlu diperhatikan oleh satker (pengguna SAKTI): User harus **memastikan** data supplier tipe 3 sebagai penerima pembayaran atas Gaji Induk telah benar dan telah direkam sebelumnya di pencatatan data supplier dalam Modul Komitmen. Satuan kerja harus sudah selesai melakukan rekonsiliasi Gaji dengan KPPN sebelum melakukan perekaman pada aplikasi SAKTI.

## Ii. Alur Proses

![1_Image_0.Png](1_Image_0.Png) A. Diagram Alur Proses B. Penjelasan Diagram Alur Proses 0) Pembuatan Data Gaji

Proses perekaman data gaji pada aplikasi gaji yang dilakukan diluar Aplikasi SAKTI. Satuan kerja diwajibkan menyelesaikan rekonsiliasi data gaji ke KPPN terlebih dahulu, sebelum melakukan perekaman pada aplikasi SAKTI.

## 1) Input Supplier

Input Supplier mengacu pada Petunjuk Teknis tentang Perekaman Supplier.

## 2) Pencatatan Spp-Spm Gaji Induk Pada Aplikasi Sakti Data Gaji

Pada Aplikasi Sakti Pilih Modul Komitmen - Import GPP Terpusat Login sebagai pengguna dengan kewenangan operator pada Modul Komitmen.

![2_image_0.png](2_image_0.png)

![2_image_1.png](2_image_1.png)

1. Masuk ke Modul Komitmen →ADK→IMPORT GPP TERPUSAT
2. Pilih jenis pegawai.

![2_image_2.png](2_image_2.png)

3. Pilih jenis data: Data Gaji 4. Input informasi:
a. Tahun bulan gaji b. Nomor gaji c. Kode anak satker (otomatis terisi)
d. Kode jenis gaji (otomatis terisi)
5. Klik import

## Pencatatan Spp

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

![3_image_0.png](3_image_0.png)

![3_image_1.png](3_image_1.png)

1. Masuk ke Modul Pembayaran → RUH SPP → Catat/Ubah SPP
2. Pilih Jenis SPP 211 - Gaji Induk 3. Klik tombol Tambah

![3_image_2.png](3_image_2.png)

## 1.  Pilih Jenis Pegawai.

![4_image_0.png](4_image_0.png)

2.  Input informasi: Bulan, Tahun dan No. Gaji

## 3.  Klik Rekam Spp

![4_image_1.png](4_image_1.png)

Setelah itu akan muncul halaman perekaman (Catat/Ubah) SPP.

0. **Untuk perekaman SPP Gaji Bulan Januari**, harap pastikan kembali bahwa tanggal proses telah sesuai dengan **hari kerja pertama di bulan Januari** atau **sesuai dengan yang diatur pada** langkah - **langkah akhir tahun anggaran**.

1. Pilih Dasar Pembayaran.

2. Uraian pembayaran diisi sesuai dengan ketentuan uraian SPP/SPM yang berlaku.

3. Pilih RPD yang telah dibuat sebelumnya, apabila nilai SPM melebihi 1 M (sesuai dengan Peraturan Menteri Keuangan Nomor 197/PMK.05/2017 tentang Rencana Penarikan Dana, Rencana Penerimaan Dana, dan Perencanaan Kas) dan lewati proses ini, apabila nilai SPM 
kurang dari 1 M.

4. Klik tombol "Cari Supplier" untuk memilih supplier tipe:3-pegawai sebagai penerima atas pembayaran Gaji Induk.

5. Klik tombol 'RUH Akun' untuk melakukan perekaman pendetailan segmen 15/16 atas COA yang ada (Distribusi COA secara otomatis terisi dari hasil import ADK GPP, namun pendetailan segmen tetap perlu dilakukan). 

1. Pilih akun yang hendak dilakukan pendetailan.

![5_image_1.png](5_image_1.png) 2. Klik tombol 'Ubah'

![5_image_0.png](5_image_0.png)

![5_image_2.png](5_image_2.png)

## 3. Klik Tombol 'Detail Coa'

![6_image_0.png](6_image_0.png)

4. Klik tombol "Tambah" untuk melakukan perekaman pendetailan.

![6_image_1.png](6_image_1.png) 6. Pilih detail segmen yang akan digunakan. 7. Klik tombol 'OK'.

![7_image_0.png](7_image_0.png)

8. Nilai pendetailan akan terisi secara otomatis. Namun apabila perlu disesuaikan, silakan disesuaikan dengan nilai per masing-masing segmen 15/16 nya.

9. Klik Tombol "Simpan".

![7_image_1.png](7_image_1.png)

![8_image_0.png](8_image_0.png)

12. Klik tombol "Lihat Detail" untuk melihat nilai pendetailan atas Akun yang digunakan tersebut.

![8_image_1.png](8_image_1.png)

Pada tampilan berikutnya, nilai pendetailan akan terisi apabila pendetailan segmen 15/16 telah terisi dengan benar. Apabila kosong, maka pendetailan atas akun tersebut belum tersimpan / belum dilakukan.

![9_image_0.png](9_image_0.png)

13. Ulangi kembali langkah 1-12 perekaman detail segmen 15/16 untuk seluruh akun gaji yang lainnya. 

14. Jika sudah selesai, klik tombol "Keluar" untuk melanjutkan perekaman SPP.

![9_image_1.png](9_image_1.png)

15. Klik tab "Akun Potongan/Penerimaan" untuk merekam potongan SPM. *(Apabila tidak terdapat* potongan SPM, bisa langsung menyimpan *SPP tersebut dengan klik tombol "Simpan")*
16. Klik tombol "RUH Akun".

![9_image_2.png](9_image_2.png)

17. Klik Tombol "Tambah" untuk menambah akun potongan/penerimaan.

18. Cari akun yang akan digunakan. Apabila akun yang ingin direkam diawali dengan angka 4xx dan 8xx, maka silakan klik tombol "4xx & 8xx ". Namun apabila akun yang hendak direkam merupakan akun dengan awalan 5xx, maka silakan cari akun tersebut dengan klik tombol "5xx".

19. Apabila menggunakan akun 4xx atau 8xx, maka silakan isikan nilai potongan SPM atas akun tersebut di kolom Nilai.

Apabila menggunakan akun 5xx, maka silakan klik tombol "Detail COA" untuk merekam nilai potongan SPM atas akun tersebut.

20. Jika sudah selesai, klik tombol "Simpan". Apabila hendak menambahkan akun lainnya, silakan ulangi langkah nomor 18-20.

21. Klik tombol "Keluar" apabila perekaman potongan telah selesai dilakukan, untuk melanjutkan perekaman SPM tersebut.

![10_image_0.png](10_image_0.png)

## 1) Cetak Spp

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

![10_image_1.png](10_image_1.png)

1. Masuk ke Modul Pembayaran →Cetak→Mencetak SPP
2. Pilih SPP yang ingin dicetak 3. Pilih PPK
4. Pastikan Tempat dan Tanggal telah sesuai 5. Klik tombol "Unduh" untuk mencetak SPP.

6. Klik tombol "SSP" apabila ingin mencetak SSP

## 2) Setuju Spp

Login sebagai pengguna PPK selaku *validator* pada Modul Pembayaran.

![11_image_0.png](11_image_0.png)

1. Masuk ke Modul Pembayaran →Validasi→Validasi SPP.

2. Pilih SPP yang ingin divalidasi.

3. Klik tombol "Unduh Pra Cetak" untuk mencetak SPP yang akan divalidasi. 4. Klik tombol "Setuju".

5. Klik tombol "Batal" apabila ingin membatalkan validasi atas SPP yang sudah dilakukan proses validasi SPP.

## 3) Buat Adk Spp

![11_image_1.png](11_image_1.png)

Login sebagai pengguna PPK selaku *validator* pada Modul Pembayaran.

1. Masuk ke Modul Pembayaran →ADK→ADK SPP OTP
2. Pilih SPP yang ingin dibuat ADK SPP dengan melakukan ceklis pada kolom pilih. Dapat memilih lebih dari 1 SPP sekaligus apabila diperlukan.

3. Klik tombol "Proses". 4. Klik tombol 'Req OTP via SMS' untuk meminta kode OTP. 

5. Setelah menerima kode OTP, silakan input pada kolom 'Input OTP'.

6. Klik tombol "Proses".

## 4) Cetak Spm

![12_image_0.png](12_image_0.png)

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

1. Masuk ke Modul Pembayaran →Cetak→Mencetak SPM
2. Pilih SPM yang ingin dicetak 3. Klik tombol "Unduh"

## 5) Upload Dokumen Pendukung

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

![12_image_1.png](12_image_1.png)

1. Masuk ke Modul Pembayaran →Catat/Upload→Upload Dokumen Pendukung.

2. Pilih SPM yang akan diupload dokumen pendukungnya.

3. Pilih jenis dokumen pendukung. 4. Klik tombol "Pilih" untuk memilih file yang akan diupload.

5. Klik tombol "Upload".

6. File yang akan diupload akan muncul.

7. Klik tombol "View" apabila ingin melihat file yang telah diupload.

8. Klik tombol "Hapus" apabila ingin menghapus file yang telah diupload sebelumnya.

## 6) Setuju Spm

Login sebagai pengguna PPSPM selaku *approver* pada Modul Pembayaran.

![13_image_0.png](13_image_0.png)

1. Masuk ke Modul Pembayaran →Validasi→Validasi SPM
2. Pilih SPM yang ingin divalidasi 3. Klik tombol "Unduh Pra Cetak" untuk mencetak SPM yang akan divalidasi 4. Klik tombol "Setuju" 5. Klik tombol "Batal SPM" apabila ingin membatalkan validasi atas SPM yang sudah divalidasi. 

Klik tombol "Batal Dokumen Pendukung" apabila ingin membatalkan dokumen pendukung yang telah di upload sebelumnya.

## 7) Buat Adk Spm

![13_image_1.png](13_image_1.png)

Login sebagai pengguna PPSPM selaku *approver* pada Modul Pembayaran.

1. Masuk ke Modul Pembayaran →ADK→ADK SPM OTP
2. Pilih SPM yang ingin dibuat ADK SPM. Dapat memilih lebih dari 1 sekaligus apabila diperlukan.

3. Klik tombol "Proses ADK SPM" 4. Klik tombol "Req OTP via SMS" untuk untuk meminta kode OTP. 

5. Setelah menerima kode OTP, silakan input pada kolom 'Input OTP'.

6. Klik tombol "Proses"

## 8) Proses Kppn

Proses di KPPN Mengacu pada Standar Operasional Prosedur Pemrosesan SPM menjadi SP2D 
pada KPPN.

## 9) Catat Sp2D

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

![14_image_0.png](14_image_0.png)

1. Masuk ke Modul Pembayaran →Catat/Upload→ Catat/Upload SP2D
2. Pilih SPM yang ingin dicatat No. SP2D
3. Klik tombol "Catat SP2D Otomatis".