

![0_image_0.png](0_image_0.png)

![0_image_1.png](0_image_1.png)

''
�
�
Petunjuk Teknis Aplikasi SAKTI)
.

�
PEREKAMAN SPM-IB-PAJAK
(Imbalan Bunga Pajak)
→
�

## I. Informasi Umum A. Deskripsi Transaksi

SPM-IB-PAJAK digunakan untuk membayar tagihan Imbalan Bunga Pajak.

| Modul                  | PEM                                      |
|------------------------|------------------------------------------|
| Role User              | OPR, APP                                 |
| Modul Lain yang        | KOM, PEM                                 |
| Terkait Transaksi yang | KOM - Pembuatan supplier type 2, 6 dan 7 |
| Tekait                 | PEM - Perekaman RPD                      |
| Dokumen Input          | SPP SPM-IB-PAJAK                         |
| Output                 | SP2D SPM-IB-PAJAK                        |
| Validasi               |                                          |

## B. Informasi Penting Lainnya

Beberapa hal yang perlu diperhatikan oleh satker (pengguna SAKTI):
1. SPM-IB-PAJAK menggunakan supplier type 2, 6 dan 7 2. SPM-IB-PAJAK diapprove oleh user KPA

## 1. Alur Proses

DIAGRAM ALUR PROSES

## A. Penjelasan Diagram Alur Proses

![2_Image_0.Png](2_Image_0.Png) 1) Input Supplier

Input Supplier mengacu pada Petunjuk Teknis KOM-00... tentang Input Supplier.

## 2) Input Spp

Login menggunakan user operator SPP/SPM

![2_image_1.png](2_image_1.png)

1. Masuk ke Modul Pembayaran  RUH SPP  Catat/Ubah SPP
2. Pilih Jenis SPP 233 SPM-IB-PAJAK
3. Klik tombol tambah

![3_image_0.png](3_image_0.png)

![3_image_1.png](3_image_1.png)

![3_image_2.png](3_image_2.png)

![3_image_3.png](3_image_3.png)

2. Silahkan memilih RPD yang telah saudara buatsebelumnya, apabila nilai SPM melebihi 1 M (sesuai dengan Peraturan Menteri Keuangan Nomor 197/PMK.05/2017 tentang Rencana Penarikan Dana, Rencana Penerimaan Dana, dan Perencanaan Kas) dan silahkan dilewati saja (tidak perlu pilih RPD) 
apabila nilai SPM kurang dari 1 M
3. Input:
a. Uraian pembayaran b. No. SKPPIB
c. Tanggal SKPPIB
4. Klik tombol "Cari Supplier" untuk memilih supplier 5. Input Informasi Kompensasi Pajak:
a. Tahun Pajak b. Akun Pengeluaran c. Kompensasi Melalui Potongan dan Kompensasi Melalui Transfer (apabila ada)
6. Klik Tombol "Simpan"

## 3) Cetak Spm

Login menggunakan user operator pembayaran

![4_image_0.png](4_image_0.png)

1. Masuk ke Modul Pembayaran CetakMencetak SPM
2. Pilih SPM yang ingin dicetak 3. Klik tombol "Unduh" KEMENTERIAN KEUANGAN REPUBLIK INDONESIA
DIREKTORAT JENDERAL PAJAK
KANTOR PENGAWASAN DAN PELAYANAN BC JAKARTA
SURAT PERINTAH MEMBAYAR IMBALAN BUNGA
Tanggal   04-Feb-2020 Halaman dari 1

| Nomor 00011A                                 |                         |
|----------------------------------------------|-------------------------|
| Berdasarkan SKPPIB Nomor  SKPPIB-001/2020    |                         |
| Kepada: Kuasa Bendahara Umum                 | KPPN JAKARTAII (019)    |
| Agar membayar/memindahbukukan Kr             | bihan Pembayaran Pendap |
| Pada akun 411211 Pendapatan PPN Dalam Negeri |                         |
| sebesa Rp 10.000.00                          |                         |

: SPM-IB-PAJAK
Jenis Jatuh Tempo :  Segera Cara Bayar
: SP20

![5_image_0.png](5_image_0.png)

| JUMLAH UANG        | 10.000,00   |
|--------------------|-------------|
| Jumlah Pengeluaran | 10.000.00   |
| JUMLAH UANG        | 0,00        |
| Jumlah Potong      | 0,00        |
| TOTAL PEMBAYARAN   | 10.000,00   |

| Semua bukti-bukti pengeluaran yang disahkan Pejabat Pembuat     | KOTA JAKARTA PUSAT, 4 Februari 2020   |
|-----------------------------------------------------------------|---------------------------------------|
| telah diuji dan dinyatakan memenuhi persyaratan untuk dilakukan | an Menteri Keuangan                   |
| atas beban APBN, selanjutnya bukti-bukti pengeluaran dimaksud   | Kepala Kantor                         |
| ditatausahakan oleh Pejabat Penandatangan SPM                   |                                       |
| Kebenaran perhitungan dan isi yang tertuang dalam SPM ini       | CHAIRUL SALEH                         |
| tanggung jawab Pejabat Penandatangan SPM                        | NP 196401271988011001                 |

## 4)   Upload Dokumen Pendukung

Login menggunakan user operator pembayaran 1. Masuk ke Modul Pembayaran Catat/UploadUpload Dokumen Pendukung

![6_image_0.png](6_image_0.png)

![6_image_1.png](6_image_1.png)

2. Pilih SPM yang ingin diupload dokumen pendukungnya 3. Pilih jenis dokumen pendukung 4. Klik tombol "Pilih" untuk memilih file yang akan diupload

![6_image_2.png](6_image_2.png)

![6_image_3.png](6_image_3.png)

5. Klik tombol "Upload"
6. File yang akan diupload akan muncul 7. Klik tombol "View" apabila ingin melihat file yang telah diupload 8. Klik tombol ""Hapus" apabila ingin menghapus file yang telah diupload sebelumnya

![7_image_0.png](7_image_0.png)

1.    Masuk ke Modul Pembayaran →Validasi→Validasi SPM
2.

Pilih SPM yang ingin divalidasi 3.

 Klik tombol "Unduh Pra Cetak" untuk mencetak SPM yang akan divalidasi

![8_image_0.png](8_image_0.png)

4.   Klik tombol "Setuju"
5.    Klik tombol "Batal" apabila ingin membatalkan validasi atas SPM yang sudah divalidasi 6.   Klik tombol "Batal Dokumen Pendukung" apabila ingin membatalkan dokumen pendukung yang sudah diupload

## 6)   Create Adk Spm

Login menggunakan user KPA
1. Masuk ke Modul Pembayaran ADKADK SPM OTP

![9_image_0.png](9_image_0.png)

2. Pilih SPP yang ingin dibuat ADK SPM

3. Klik tombol "Proses ADK SPM"

![9_image_1.png](9_image_1.png)

![9_image_2.png](9_image_2.png)

4. Klik tombol "Req OTP via SMS"
5. Input OTP pejabat KPA
6. Klik tombol "Proses"

## 7) Proses Kppn

Proses di KPPN Mengacu pada Standar Operasional Prosedur Pemrosesan SPM menjadi SP2D pada KPPN.

## 8) Catat Sp2D

Login menggunakan user operator pembayaran

![10_image_0.png](10_image_0.png)

1.    Masuk ke Modul Pembayaran →	Catat/Upload → Catat/Upload SP2D
2.    Pilih SPM yang ingin dicatat No. SP2D
Klik tombol "Catat SP2D Otomatis".

3.