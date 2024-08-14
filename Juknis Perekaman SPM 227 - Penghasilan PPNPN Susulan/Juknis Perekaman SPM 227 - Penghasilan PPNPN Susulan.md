

![0_image_0.png](0_image_0.png)

![0_image_1.png](0_image_1.png)

→
→
.

Petunjuk Teknis Aplikasi SAKTI)
♦
♦ PEREKAMAN SPM
PENGHASILAN PPNPN SUSULAN
→
�

## I. Informasi Umum A. Deskripsi Transaksi

1. SPM Penghasilan PPNPN Susulan (227) digunakan untuk membayar pembayaran belanja pegawai bagi Pegawai Pemerintah Non Pegawai Negeri (PPNPN), yang penyampaian SPM dari satker ke KPPN tidak sesuai ketentuan penyampaian SPM. Sesuai Peraturan Direktur Jenderal Perbendaharan Nomor Per-8/PB/2019 tentang Perubahan Peraturan Direktur Jenderal Perbendaharaan Nomor PER-31/PB/2016 tentang Tata Cara Pembayaran Penghasilan Bagi PPNPN Yang Dibebankan Pada APBN, bahwa satker menyampaikan SPM ke KPPN pada tanggal 21 s.d. 26 bulan berkenaan, agar SPM atas pembayaran penghasilan PPNPN dapat dibayar pada hari pertama.

| Modul                  | PEM                                                                                                                                                                                                                                                                                                                                                                            |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Role User              | OPR, VAL, APP                                                                                                                                                                                                                                                                                                                                                                  |
| Modul Lain yang        | KOM                                                                                                                                                                                                                                                                                                                                                                            |
| Terkait Transaksi yang | KOM - Pembuatan supplier tipe 6                                                                                                                                                                                                                                                                                                                                                |
| Tekait Dokumen Input   | SPP SPM Penghasilan PPNPN Susulan                                                                                                                                                                                                                                                                                                                                              |
| Output                 | SP2D Penghasilan PPNPN Susulan                                                                                                                                                                                                                                                                                                                                                 |
| Validasi               | User harus memastikan data supplier tipe 6 sebagai penerima pembayaran atas  Penghasilan PPNPN Susulantelah direkam sebelumnya di pencatatan data  supplier dalam Modul Komitmen. User harus memilih Header Supplier atas data supplier tipe 6 sebelum  melakukan input penerima pembayaran atas Penghasilan PPNPN Susulanpada  kolom informasi supplier dalam form catat SPP. |

## B. Informasi Penting Lainnya

Beberapa hal yang perlu diperhatikan oleh satker (pengguna SAKTI):
1) User harus memastikan data supplier tipe 6 sebagai penerima pembayaran atas Penghasilan PPNPN Susulan telah direkam sebelumnya di pencatatan data supplier dalam Modul Komitmen.

2) User harus memilih Header Supplier atas data supplier tipe 6 sebelum melakukan input penerima pembayaran atas Penghasilan PPNPN Susulan pada kolom informasi supplier dalam form catat SPP.

3) Input penerima pembayaran atas Penghasilan PPNPN Susulan pada kolom informasi supplier dalam form catat SPP, dapat dilakukan dengan 2 (dua) mekanisme, antara lain:
a) Upload file perhitungan pembayaran atas Penghasilan PPNPN Susulan dengan format .csv yang dihasilkan dari Aplikasi SAS, atau b) Tambah manual penerima dan nilai bersih pembayaran atas Penghasilan PPNPN 
Susulan.

## Ii. Alur Proses

![2_Image_0.Png](2_Image_0.Png)

A. **DIAGRAM ALUR PROSES**

## B. Penjelasan Diagram Alur Proses

1) **Input Supplier**
Input Supplier mengacu pada Petunjuk Teknis tentang Perekaman Supplier.

2) **Input SPP** Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

![2_image_1.png](2_image_1.png)

1. Masuk ke Modul Pembayaran → RUH SPP → Catat/Ubah SPP.

2. Pilih Jenis SPP 227 SPM Penghasilan PPNPN Susulan.

3. Klik tombol tambah.

![3_image_0.png](3_image_0.png)

![3_image_1.png](3_image_1.png)

![3_image_3.png](3_image_3.png)

![3_image_2.png](3_image_2.png)

1. Pilih Dasar Pembayaran.

2. Uraian pembayaran diisi sesuai jenis SPP-SPM yang telah dipilih. 3. Pilih RPD yang telah dibuat sebelumnya, apabila nilai SPM melebihi 1 M (sesuai dengan Peraturan Menteri Keuangan Nomor 197/PMK.05/2017 tentang Rencana Penarikan Dana, Rencana Penerimaan Dana, dan Perencanaan Kas) dan lewati proses ini, apabila nilai SPM 
kurang dari 1 M.

4. Klik tombol "Supplier Header" untuk memilih supplier header. Pilih data supplier tipe 6, atas Supplier Header untuk pembayaran atas Penghasilan PPNPN Susulan, dengan deskripsi "Para PPNPN XXXXXX".

5. Klik tombol "Tambah", untuk input secara manual penerima dan nilai bersih pembayaran atas Penghasilan PPNPN Susulan. Apabila satuan kerja hendak memanfaatkan fitur upload file CSV, maka langkah ini dapat dilewati.

6. Klik tombol "Upload File CSV" untuk *upload* file ADK CSV yang berisi data nama penerima dan perhitungan pembayaran atas Penghasilan PPNPN Susulan dengan format .csv yang dihasilkan dari Aplikasi SAS. (Perhatian: pastikan nama supplier header dalam file ADK CSV sama dengan supplier header yang dipilih). Apabila melakukan perekaman penerima pembayaran secara manual, maka langkah ini dapat dilewati.

Kolom nilai bersih pada informasi supplier, baik yang diperoleh dari hasil upload file CSV 
maupun yang diinput secara manual, diisi dengan *nilai bersih yang diterima oleh penerima* pembayaran/PPNPN (Nilai tersebut merupakan nilai setelah dikurangi potongan 811141 -
Penerimaan PFK Iuran Jaminan Kesehatan Pegawai Pemerintah Non PNS dari APBN).

7. Klik tombol "RUH Akun" untuk menginput Akun Pengeluaran dan Akun Potongan.

![4_image_0.png](4_image_0.png)

8. Klik Tombol "Rekam" untuk menambah Akun.

9. Pilih Akun yang akan digunakan.

10. Klik Tombol "Detail Coa"

![4_image_1.png](4_image_1.png)

11. Klik tombol "Tambah". 12. Klik tombol "Kaca Pembesar" untuk mencari Segmen 15/16nya. Pilih Segmen tersebut.

13. Masukkan nilai per detail segmen tersebut.

14. Klik tombol "Simpan". Apabila dalam akun yang sama terdapat lebih dari satu segmen 15/16, maka silakan ulangi langkah nomor 11-14.

15. Klik tombol "Keluar" untuk kembali ke halaman sebelumnya.

![5_image_0.png](5_image_0.png)

16. Klik tombol "Simpan" untuk menyimpan nilai akun yang digunakan. Apabila terdapat lebih dari satu akun, silakan ulangi langkah nomor 8-16.

17. Klik tombol "Keluar" untuk kembali ke perekaman SPP.

![5_image_1.png](5_image_1.png)

18. Klik tab "Akun Potongan/Penerimaan" untuk merekam potongan SPM.

19. Klik tombol "RUH Akun".

![6_image_0.png](6_image_0.png)

20. Klik Tombol "Tambah" untuk menambah akun potongan/penerimaan. 21. Cari akun yang akan digunakan. Apabila akun yang ingin direkam diawali dengan angka 4xx dan 8xx, maka silakan klik tombol "4xx & 8xx ". Namun apabila akun yang hendak direkam merupakan akun dengan awalan 5xx, maka silakan cari akun tersebut dengan klik tombol 
"5xx".

22. Apabila menggunakan akun 4xx atau 8xx, maka silakan isikan nilai potongan SPM atas akun tersebut di kolom Nilai.

Apabila menggunakan akun 5xx, maka silakan klik tombol "Detail COA" untuk merekam nilai potongan SPM atas akun tersebut.

23. Jika sudah selesai, klik tombol "Simpan". Apabila hendak menambahkan akun lainnya, silakan ulangi langkah nomor 20-22.

24. Klik tombol "Keluar" apabila perekaman potongan telah selesai dilakukan, untuk melanjutkan perekaman SPM tersebut.

![6_image_1.png](6_image_1.png)

## 3) Cetak Spp

![7_image_0.png](7_image_0.png)

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

1. Masuk ke Modul Pembayaran →Cetak→Mencetak SPP
2. Pilih SPP yang ingin dicetak 3. Pilih PPK
4. Pastikan Tempat dan Tanggal telah sesuai 5. Klik tombol "Unduh" untuk mencetak SPP.

6. Klik tombol "SSP" apabila ingin mencetak SSP

## 4) Setuju Spp

Login sebagai pengguna PPK selaku *validator* pada Modul Pembayaran.

![7_image_1.png](7_image_1.png)

1. Masuk ke Modul Pembayaran →Validasi→Validasi SPP
2. Pilih SPP yang ingin divalidasi 3. Klik tombol "Unduh Pra Cetak" untuk mencetak SPP yang akan divalidasi 4. Klik tombol "Setuju" untuk menyetujui SPP.

5. Klik tombol "Batal" apabila ingin membatalkan validasi atas SPP yang sudah divalidasi

## 5) Buat Adk Spp

Login sebagai pengguna PPK selaku *validator* pada Modul Pembayaran.

![8_image_0.png](8_image_0.png)

![8_image_1.png](8_image_1.png)

1. Masuk ke Modul Pembayaran →ADK→ADK SPP OTP
2. Pilih SPP yang ingin dibuat ADK SPP dengan melakukan ceklis pada kolom pilih. Dapat memilih lebih dari 1 SPP sekaligus apabila diperlukan.

3. Klik tombol "Proses" 4. Klik tombol 'Req OTP via SMS' untuk meminta kode OTP. 

5. Setelah menerima kode OTP, silakan input pada kolom 'Input OTP'.

6. Klik tombol "Proses"

## 6) Cetak Spm

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

![8_image_2.png](8_image_2.png)

![8_image_3.png](8_image_3.png)

1. Masuk ke Modul Pembayaran →Cetak→Mencetak SPM
2. Pilih SPM yang ingin dicetak 3. Klik tombol "Unduh"

## 7) Upload Dokumen Pendukung

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

![9_image_0.png](9_image_0.png)

1. Masuk ke Modul Pembayaran →Catat/Upload→Upload Dokumen Pendukung.

2. Pilih SPM yang akan diupload dokumen pendukungnya.

3. Pilih jenis dokumen pendukung.

4. Klik tombol "Pilih" untuk memilih file yang akan diupload.

5. Klik tombol "Upload".

6. File yang akan diupload akan muncul.

7. Klik tombol "View" apabila ingin melihat file yang telah diupload. 8. Klik tombol "Hapus" apabila ingin menghapus file yang telah diupload sebelumnya.

## 8) Setuju Spm

![9_image_1.png](9_image_1.png)

Login sebagai pengguna PPSPM selaku *approver* pada Modul Pembayaran.

1. Masuk ke Modul Pembayaran →Validasi→Validasi SPM
2. Pilih SPM yang ingin divalidasi 3. Klik tombol "Unduh Pra Cetak" untuk mencetak SPM yang akan divalidasi 4. Klik tombol "Setuju" 5. Klik tombol "Batal SPM" apabila ingin membatalkan validasi atas SPM yang sudah divalidasi. 

Klik tombol "Batal Dokumen Pendukung" apabila ingin membatalkan dokumen pendukung yang telah di upload sebelumnya.

## 9) Buat Adk Spm

Login sebagai pengguna PPSPM selaku *approver* pada Modul Pembayaran.

![10_image_0.png](10_image_0.png)

1. Masuk ke Modul Pembayaran →ADK→ADK SPM OTP
2. Pilih SPM yang ingin dibuat ADK SPM. Dapat memilih lebih dari 1 sekaligus apabila diperlukan.

3. Klik tombol "Proses ADK SPM"
4. Klik tombol "Req OTP via SMS" untuk untuk meminta kode OTP. 

5. Setelah menerima kode OTP, silakan input pada kolom 'Input OTP'. 6. Klik tombol "Proses"

## 10) Proses Kppn

Proses di KPPN Mengacu pada Standar Operasional Prosedur Pemrosesan SPM menjadi SP2D 
pada KPPN.

## 11) Catat Sp2D

Login sebagai pengguna dengan kewenangan operator pada Modul Pembayaran.

![11_image_0.png](11_image_0.png)

1.

2.

Pilih SPM yang ingin dicatat No. SP2D Klik tombol "Catat SP2D Otomatis".

3.