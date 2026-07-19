# Bab 13: Manajemen Edisi dan Pasca Penerbitan

> **Pemantik Bab**
> Anda memiliki sepuluh artikel matang yang siap rilis. Namun, sistem OJS tidak bekerja seperti blog biasa di mana setiap artikel diterbitkan satu per satu; OJS menggunakan konsep "wadah" yang disebut Edisi (*Issue*). Menjadwalkan artikel tanpa memasukkannya ke dalam edisi ibarat menumpuk barang di gudang tanpa etalase. Bab ini memandu Anda merakit etalase tersebut, menerbitkannya, hingga menangani krisis jika terjadi kesalahan pascapublikasi yang mengharuskan Anda menarik kembali edisi (*unpublish*).

Manajemen edisi adalah tahap puncak dari seluruh rangkaian alur kerja editorial di OJS 3.3. Setelah naskah melewati tahap *Submission*, *Review*, *Copyediting*, dan *Production*, langkah terakhir adalah menggabungkan artikel-artikel yang telah siap ke dalam sebuah edisi dan menerbitkannya kepada publik.

## 13.1 Konsep Dasar: Hubungan Naskah dan Edisi

Sebelum memulai manajemen edisi, pengelola harus memahami satu konsep kunci: sebuah naskah hanya akan muncul dalam sistem manajemen edisi apabila telah dilakukan tindakan penjadwalan (*Scheduling*) pada akhir tahap *Production*. Tanpa proses penjadwalan tersebut, naskah tidak akan tersedia untuk dimasukkan ke dalam edisi mana pun.

## 13.2 Navigasi Menu Issues

Untuk mengelola edisi, navigasikan ke menu sisi kiri dan pilih **"Issues"**. Halaman ini terbagi menjadi dua tab utama:

| Tab | Isi | Fungsi |
|-----|-----|--------|
| **Future Issues** | Edisi yang sedang dipersiapkan atau belum diterbitkan. | Berfungsi sebagai wadah penampungan naskah yang telah dijadwalkan dari tahap *Production*. |
| **Back Issues** | Edisi yang sudah diterbitkan kepada publik. | Berfungsi sebagai arsip dan area untuk melakukan koreksi pascapublikasi jika diperlukan. |

## 13.3 Membuat Edisi Baru (Create Issue)

Sebelum naskah dapat dijadwalkan, editor harus membuat wadah edisi terlebih dahulu.

**Jalur Eksekusi Cepat: Membuat Edisi**
1. Klik tab **Future Issues**.
2. Klik tombol **Create Issue**.
3. Isi formulir identifikasi (Volume, Nomor, Tahun).
4. (Opsional) Tambahkan judul khusus, deskripsi, atau unggah **Cover Image**.
5. Klik **Save**. Edisi kini siap untuk menerima naskah yang dijadwalkan.

> **Troubleshooting: Penomoran Edisi Tidak Urut**
>
> **Masalah**: Anda secara tidak sengaja membuat dua edisi dengan Volume dan Nomor yang sama (misal: Vol 1 No 1), dan sistem OJS menjadi bingung saat menampilkan edisi berjalan (*Current Issue*).
>
> **Solusi Cepat**: OJS mengizinkan duplikasi penomoran jika tidak menggunakan *URL Path* khusus. Untuk memperbaikinya, masuk ke **Future Issues**, klik ikon panah di edisi yang salah, pilih **Edit**, dan ubah nomornya. Pastikan Anda memeriksa ulang penomoran halaman (*Pages*) di setiap artikel di dalam edisi tersebut.

![Formulir Create Issue](../img/elementor-placeholder-image.png)

## 13.4 Mengelola Daftar Isi Edisi (Table of Contents)

Setelah naskah dijadwalkan ke dalam edisi, editor mengatur tata letak presentasi edisi tersebut. Klik ikon panah di sebelah judul edisi untuk mengakses opsi pengelolaan:

| Opsi | Fungsi |
|------|--------|
| **View** | Meninjau tampilan pratinjau edisi dari perspektif pembaca. |
| **Table of Contents (TOC)** | Mengelola daftar isi dengan melihat dan mengatur posisi artikel di dalam edisi. |
| **Order** | Mengaktifkan mode pengurutan. Setelah tombol diaktifkan, gunakan fungsi seret dan lepas (*drag and drop*) untuk mengatur urutan artikel. |
| **Issue Data** | Mengubah metadata edisi seperti tanggal terbit, identifikasi, deskripsi, dan gambar sampul. |
| **Issue Galleys** | Menambahkan satu berkas gabungan (umumnya PDF) untuk keseluruhan edisi penuh (*full issue*). |

Catatan Penting: Selalu lakukan verifikasi akhir pada metadata edisi sebelum mengklik publikasi. Mengubah metadata edisi setelah artikel terindeks oleh mesin pencari akademik akan menimbulkan inkonsistensi data.

![Tampilan pengelolaan Table of Contents edisi](../img/elementor-placeholder-image.png)

## 13.5 Menerbitkan Edisi (Publish Issue)

Setelah seluruh naskah dalam edisi siap dan metadata tervalidasi:

**Jalur Eksekusi Cepat: Memublikasikan Edisi**
1. Pada tab **Future Issues**, temukan edisi yang dimaksud.
2. Klik ikon panah dan pilih **Publish Issue**.
3. Centang opsi **Notify Users** pada pop-up konfirmasi (wajib untuk visibilitas).
4. Klik **Confirm** untuk menyelesaikan proses publikasi.
5. Edisi otomatis berpindah ke tab **Back Issues** dan langsung tampil di halaman publik jurnal.

![Jendela konfirmasi Publish Issue dengan opsi Notify Users](../img/elementor-placeholder-image.png)

## 13.6 Menetapkan Edisi Terkini (Current Issue)

OJS 3.3 memungkinkan pengelola menetapkan edisi mana yang ditampilkan paling awal di halaman utama beranda jurnal:

- Klik ikon panah pada edisi yang diinginkan di tab *Back Issues*.
- Pilih **"Set as Current Issue"**.

Fitur ini berguna apabila jurnal menerbitkan edisi khusus (*special issue*) dan ingin menampilkan edisi tersebut sebagai sorotan utama untuk sementara waktu.

## 13.7 Fitur Pascapenerbitan: Koreksi dan Pengelolaan

### Unpublish Issue (Membatalkan Publikasi)

Apabila ditemukan kesalahan fatal, editor dapat menarik edisi dari publikasi.

**Jalur Eksekusi Cepat: Membatalkan Publikasi Edisi**
1. Di tab **Back Issues**, klik ikon panah pada edisi terkait.
2. Pilih **Unpublish Issue**.
3. Edisi kembali menjadi *Future Issue* dan tidak lagi tampil di halaman publik.

> **Catatan Kritis**: Fitur *Unpublish* harus digunakan dengan sangat hati-hati. Membatalkan publikasi pada edisi yang sudah terbit lama dapat merusak tautan eksternal (termasuk DOI) dan menghilangkan akses pembaca secara tiba-tiba. Lakukan hanya dalam keadaan darurat absolut (misal: pelanggaran etika publikasi massal).

### Mengedit Metadata Artikel yang Terbit

Jika diperlukan koreksi pada metadata artikel setelah terbit:

1. Masuk ke **Back Issues**, lalu klik judul edisi.
2. Klik judul artikel yang perlu dikoreksi.
3. Lakukan koreksi metadata di tab **Publication**.
4. Klik **"Save"**.

Mengubah metadata artikel pascaterbit (terutama tanggal terbit atau daftar nama penulis) dapat merusak sinkronisasi data dengan pengindeks seperti Google Scholar dan Crossref. Lakukan hanya jika benar-benar mendesak.

## 13.8 Aktivitas Pascapenerbitan dan DOI

Setelah edisi terbit, langkah teknis terpenting berikutnya adalah mendepositkan metadata dan mendaftarkan DOI artikel ke Crossref.

### Apa itu Crossref dan DOI?

Crossref (https://www.crossref.org/) adalah lembaga pendaftaran resmi (*registration agency*) untuk *Digital Object Identifier* (DOI) yang paling banyak digunakan untuk publikasi ilmiah. DOI menyediakan tautan permanen (*persistent link*) ke lokasi artikel di internet. Jika URL jurnal berubah, DOI memastikan artikel tetap dapat ditemukan selama pengelola jurnal memperbarui data URL baru di sistem Crossref.

Standar kelayakan Directory of Open Access Journals (DOAJ) sangat menganjurkan agar setiap artikel ilmiah memiliki DOI yang valid untuk menjamin kelestarian akses jangka panjang artikel.

### Deposit DOI Melalui OJS 3.3

Jika jurnal telah menjadi anggota Crossref, proses registrasi DOI dapat dilakukan secara langsung melalui sistem:

1. Masuk sebagai **Journal Manager**.
2. Navigasi ke menu **Tools**, pilih **Import/Export**, lalu klik **Crossref XML Export Plugin**.
3. Pilih artikel yang akan didepositkan DOI-nya.
4. OJS dapat mendepositkan secara otomatis atau menghasilkan berkas XML.
5. Klik tombol ekspor atau register sesuai konfigurasi sistem jurnal Anda.

![Proses deposit DOI ke Crossref](../img/elementor-placeholder-image.png)

Catatan: Untuk materi mengenai strategi promosi dan peningkatan visibilitas artikel secara eksternal (melalui media sosial atau repositori), lihat **Bab 15: Diseminasi dan Peningkatan Visibilitas Jurnal**.

## Latihan Bab 13

**Skenario Simulasi: Membangun Etalase Publikasi**

Jurnal Anda bersiap untuk menerbitkan edisi perdana. Anda ditugaskan untuk membuat wadah edisinya dan memublikasikannya secara *dummy*.

**Tugas Praktik:**
1. Masuk ke dasbor utama dan navigasikan ke menu **Issues**.
2. Pada tab **Future Issues**, buat edisi baru dengan klik **Create Issue**. Isi dengan Volume 1, Nomor 1, Tahun ini.
3. Setelah tersimpan, jadwalkan satu naskah uji coba dari tahap *Production* ke dalam edisi tersebut.
4. Kembali ke menu **Issues**, klik panah pada edisi tersebut, pilih **Publish Issue**, namun kali ini *jangan* centang opsi notifikasi (karena ini percobaan).
5. Setelah terbit, lihat dampaknya di beranda publik. Terakhir, kembalikan edisi tersebut dengan melakukan **Unpublish Issue** di tab **Back Issues**.

## Checklist Bab 13

Gunakan daftar periksa berikut untuk mengelola edisi jurnal:

- [ ] Wadah edisi baru (*Create Issue*) telah dibuat pada tab *Future Issues*.
- [ ] Naskah-naskah telah dijadwalkan dari tahap *Production* ke dalam edisi yang dituju.
- [ ] Urutan artikel pada daftar isi (*Table of Contents*) telah ditata secara logis.
- [ ] Keseluruhan metadata edisi (volume, nomor, tahun, tanggal terbit) telah diverifikasi kebenarannya.
- [ ] Edisi telah dipublikasikan (*Publish Issue*) dengan mencentang opsi pemberitahuan kepada pengguna (*Notify Users*).
- [ ] Proses deposit DOI ke Crossref telah diselesaikan segera setelah penerbitan.

## Ringkasan Bab

| Langkah | Aksi Editor |
|---------|-------------|
| 1 | Buat edisi baru di tab *Future Issues*. |
| 2 | Jadwalkan naskah ke dalam edisi melalui opsi penjadwalan di tahap *Production*. |
| 3 | Kelola tata letak urutan artikel melalui fitur *Table of Contents*. |
| 4 | Verifikasi seluruh parameter metadata edisi di *Issue Data*. |
| 5 | Publikasikan edisi dan aktifkan fitur pemberitahuan kepada pembaca (*Notify Users*). |
| 6 | Daftarkan tautan permanen artikel dengan mendepositkan DOI ke Crossref. |
