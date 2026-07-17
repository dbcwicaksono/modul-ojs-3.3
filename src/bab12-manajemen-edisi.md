# Bab 12: Manajemen Edisi dan Pasca Penerbitan

Manajemen edisi adalah tahap puncak dari seluruh rangkaian alur kerja editorial di OJS 3.3. Setelah naskah melewati tahap *Submission*, *Review*, *Copyediting*, dan *Production*, langkah terakhir adalah menggabungkan artikel-artikel yang telah siap ke dalam sebuah edisi dan menerbitkannya kepada publik.

## 12.1 Konsep Dasar: Hubungan Naskah dan Edisi

Sebelum memulai manajemen edisi, pengelola harus memahami satu konsep kunci: sebuah naskah hanya akan muncul dalam sistem manajemen edisi apabila telah dilakukan tindakan penjadwalan (*Scheduling*) pada akhir tahap *Production*. Tanpa proses penjadwalan tersebut, naskah tidak akan tersedia untuk dimasukkan ke dalam edisi mana pun.

## 12.2 Navigasi Menu Issues

Untuk mengelola edisi, navigasikan ke menu sisi kiri dan pilih **"Issues"**. Halaman ini terbagi menjadi dua tab utama:

| Tab | Isi | Fungsi |
|-----|-----|--------|
| **Future Issues** | Edisi yang sedang dipersiapkan atau belum diterbitkan. | Berfungsi sebagai wadah penampungan naskah yang telah dijadwalkan dari tahap *Production*. |
| **Back Issues** | Edisi yang sudah diterbitkan kepada publik. | Berfungsi sebagai arsip dan area untuk melakukan koreksi pascapublikasi jika diperlukan. |

## 12.3 Membuat Edisi Baru (Create Issue)

Sebelum naskah dapat dijadwalkan, editor harus membuat wadah edisi terlebih dahulu.

1. Klik tab **"Future Issues"**.
2. Klik tombol **"Create Issue"**.
3. Isi formulir pembuatan edisi:

| Komponen | Instruksi |
|----------|-----------|
| **Identifikasi** | Masukkan rentang Volume, Nomor, dan Tahun. Jika jurnal tidak menggunakan salah satu komponen ini, biarkan kolom kosong dan hapus centang pada opsi tersebut. |
| **Deskripsi** | Tambahkan narasi pengantar atau editorial edisi (opsional). |
| **Cover Image** | Unggah gambar sampul khusus untuk edisi ini jika diperlukan. |
| **URL Path** | Opsi untuk membuat tautan khusus, misalnya `v1n1-2025`. |

4. Klik **"Save"**. Edisi kini siap untuk menerima naskah yang dijadwalkan.

![Formulir Create Issue](../img/elementor-placeholder-image.png)

## 12.4 Mengelola Daftar Isi Edisi (Table of Contents)

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

## 12.5 Menerbitkan Edisi (Publish Issue)

Setelah seluruh naskah dalam edisi siap dan metadata tervalidasi:

1. Pada tab **Future Issues**, temukan edisi yang dimaksud.
2. Klik ikon panah dan pilih **"Publish Issue"**.
3. Jendela konfirmasi akan muncul dengan opsi **Notify Users**. Centang opsi ini untuk mengirimkan surel pemberitahuan otomatis kepada seluruh pengguna terdaftar bahwa edisi terbaru telah terbit. Ini merupakan strategi dasar untuk meningkatkan jumlah pembaca.
4. Klik **"Confirm"** untuk menyelesaikan proses publikasi.
5. Edisi berpindah dari tab *Future Issues* ke tab **Back Issues** dan seketika tampil di halaman publik jurnal.

![Jendela konfirmasi Publish Issue dengan opsi Notify Users](../img/elementor-placeholder-image.png)

## 12.6 Menetapkan Edisi Terkini (Current Issue)

OJS 3.3 memungkinkan pengelola menetapkan edisi mana yang ditampilkan paling awal di halaman utama beranda jurnal:

- Klik ikon panah pada edisi yang diinginkan di tab *Back Issues*.
- Pilih **"Set as Current Issue"**.

Fitur ini berguna apabila jurnal menerbitkan edisi khusus (*special issue*) dan ingin menampilkan edisi tersebut sebagai sorotan utama untuk sementara waktu.

## 12.7 Fitur Pascapenerbitan: Koreksi dan Pengelolaan

### Unpublish Issue (Membatalkan Publikasi)

Apabila ditemukan kesalahan fatal, editor dapat menarik edisi dari publikasi:

1. Di tab *Back Issues*, klik ikon panah pada edisi terkait.
2. Pilih **"Unpublish Issue"**.
3. Edisi kembali menjadi *Future Issue* dan tidak lagi tampil di halaman publik.

Perhatian: Fitur ini harus digunakan dengan sangat hati-hati. Membatalkan publikasi pada edisi yang sudah terbit lama dapat merusak tautan eksternal seperti *Digital Object Identifier* (DOI) yang sudah didaftarkan dan memengaruhi metrik sitasi.

### Mengedit Metadata Artikel yang Terbit

Jika diperlukan koreksi pada metadata artikel setelah terbit:

1. Masuk ke **Back Issues**, lalu klik judul edisi.
2. Klik judul artikel yang perlu dikoreksi.
3. Lakukan koreksi metadata di tab **Publication**.
4. Klik **"Save"**.

Mengubah metadata artikel pascaterbit (terutama tanggal terbit atau daftar nama penulis) dapat merusak sinkronisasi data dengan pengindeks seperti Google Scholar dan Crossref. Lakukan hanya jika benar-benar mendesak.

## 12.8 Aktivitas Pascapenerbitan dan DOI

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

Catatan: Untuk materi mengenai strategi promosi dan peningkatan visibilitas artikel secara eksternal (melalui media sosial atau repositori), lihat **Bab 14: Diseminasi dan Peningkatan Visibilitas Jurnal**.

## Checklist Bab 12

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
