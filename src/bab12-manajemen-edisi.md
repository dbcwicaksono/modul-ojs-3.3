# Bab 12: Manajemen Edisi (Issue) & Pasca Penerbitan

**Manajemen Edisi** adalah tahap puncak dari seluruh rangkaian alur kerja editorial di OJS 3.3. Setelah naskah melewati Submission, Review, Copyediting, dan Production, langkah terakhir adalah **menggabungkan artikel-artikel yang telah siap ke dalam sebuah edisi** dan menerbitkannya kepada publik.

---

## 12.1 Konsep Dasar: Hubungan Naskah dan Edisi

Sebelum memulai, pahami konsep kunci ini:

> Sebuah naskah hanya akan muncul dalam manajemen edisi **setelah** Anda melakukan tindakan **"Scheduling"** (Penjadwalan) pada akhir tahap Production. Tanpa penjadwalan, naskah tidak akan muncul dalam antarmuka manajemen edisi.

---

## 12.2 Navigasi Menu Issues

Untuk mengelola edisi, masuk ke menu navigasi kiri dan pilih **"Issues"**. Halaman ini terbagi menjadi dua tab:

| Tab | Isi | Fungsi |
|-----|-----|--------|
| **Future Issues** | Edisi yang sedang dipersiapkan atau belum diterbitkan. | Tempat berkumpulnya naskah yang telah dijadwalkan dari tahap Production. |
| **Back Issues** | Edisi yang sudah terbit. | Digunakan untuk arsip dan koreksi pasca-publikasi. |

---

## 12.3 Membuat Edisi Baru (Create Issue)

Sebelum naskah dapat dijadwalkan, Anda harus membuat "wadah" edisinya terlebih dahulu.

1. Klik tab **"Future Issues"**.
2. Klik tombol **"Create Issue"**.
3. Isi formulir:

| Komponen | Instruksi |
|----------|-----------|
| **Identifikasi** | Masukkan Volume, Nomor, dan Tahun. Jika jurnal tidak menggunakan salah satunya, biarkan kosong dan **hilangkan centang** (*untick*) pada opsi tersebut. |
| **Deskripsi** | Tambahkan narasi pengantar edisi (opsional). |
| **Cover Image** | Unggah gambar sampul edisi jika diperlukan. |
| **URL Path** | Opsional — untuk alamat URL kustom (mis. `v1n1-2025`). |

4. Klik **"Save"**. Edisi kini siap menerima naskah.

![Formulir Create Issue](../img/elementor-placeholder-image.png)

---

## 12.4 Mengelola Daftar Isi Edisi (Table of Contents)

Setelah naskah dijadwalkan ke dalam edisi, Anda dapat mengelola tampilan edisi:

### Mengakses Pengaturan Edisi

Klik **Expansion Arrow** (panah biru/segitiga) di sebelah judul edisi untuk mengakses opsi:

| Opsi | Fungsi |
|------|--------|
| **View** | Melihat tampilan edisi dari perspektif pembaca. |
| **Table of Contents (TOC)** | Mengelola daftar isi: melihat dan mengatur artikel di dalam edisi. |
| **Order** | Mengaktifkan mode pengurutan. Setelah tombol **Order** aktif, gunakan *drag and drop* untuk mengatur urutan artikel dan bagian. |
| **Issue Data** | Mengedit metadata edisi: tanggal terbit, identifikasi, deskripsi, dan gambar sampul. |
| **Issue Galleys** | Menambahkan satu file PDF gabungan untuk seluruh edisi. |

> **Tips Pakar:** Selalu lakukan pengecekan akhir pada **Issue Data** sebelum publikasi. Memperbaiki metadata edisi setelah artikel terindeks oleh mesin pencari jauh lebih rumit.

![Tampilan pengelolaan Table of Contents edisi](../img/elementor-placeholder-image.png)

---

## 12.5 Menerbitkan Edisi (Publish Issue)

Setelah semua naskah dalam edisi siap dan metadata sudah diverifikasi:

1. Pada tab **Future Issues**, temukan edisi yang dimaksud.
2. Klik **Expansion Arrow** dan pilih **"Publish Issue"**.
3. Jendela konfirmasi muncul. Terdapat opsi penting:
   - **Notify Users** — Centang ini untuk mengirimkan email notifikasi otomatis kepada **seluruh pengguna terdaftar** bahwa edisi terbaru telah terbit. Ini adalah cara efektif untuk meningkatkan jangkauan pembaca.
4. Klik **"Confirm"** untuk menyelesaikan.
5. Edisi berpindah dari tab *Future Issues* ke tab **Back Issues** dan langsung tampil di halaman depan jurnal.

![Jendela konfirmasi Publish Issue dengan opsi Notify Users](../img/elementor-placeholder-image.png)

---

## 12.6 Menetapkan Edisi Terkini (Current Issue)

OJS 3.3 memungkinkan Anda menetapkan edisi mana yang muncul paling awal di halaman depan jurnal:

- Klik **Expansion Arrow** pada edisi yang diinginkan di tab *Back Issues*.
- Pilih **"Set as Current Issue"**.

Fitur ini berguna misalnya jika Anda menerbitkan edisi khusus (*special issue*) dan ingin edisi tersebut menjadi tampilan utama untuk sementara waktu.

---

## 12.7 Fitur Pasca-Penerbitan: Koreksi dan Pengelolaan

### Unpublish Issue

Jika Anda perlu membatalkan publikasi edisi (misalnya ditemukan kesalahan kritis):

1. Di *Back Issues*, klik **Expansion Arrow** pada edisi tersebut.
2. Pilih **"Unpublish Issue"**.
3. Edisi kembali menjadi *Future Issue* dan tidak lagi tampil di halaman publik.

> **⚠️ Peringatan:** Gunakan fitur ini dengan sangat hati-hati. Membatalkan publikasi pada edisi yang sudah lama terbit dapat **memutus tautan eksternal** seperti DOI yang sudah terdaftar di Crossref dan mempengaruhi indeksasi yang sudah ada.

### Menghapus Edisi (Delete)

- Edisi hanya bisa dihapus jika **tidak berisi artikel yang aktif**.
- Klik **Expansion Arrow** → **"Delete"**.

### Mengedit Metadata Artikel yang Sudah Terbit

Jika diperlukan koreksi pada metadata artikel yang sudah terbit (mis. koreksi nama penulis):

1. Masuk ke **Back Issues**, klik nama edisi.
2. Klik **judul artikel** yang ingin diedit.
3. Edit metadata yang diperlukan di tab **Publication**.
4. Klik **"Save"**.

> **Perhatian penting:** Mengubah metadata artikel yang sudah terbit (terutama tanggal terbit) dapat mempengaruhi data di Google Scholar dan mesin pengindeks lain. Selalu konfirmasi kebenaran data sebelum artikel diterbitkan, dan **hindari perubahan metadata pasca-terbit** kecuali benar-benar diperlukan.

---

## 12.8 Aktivitas Pasca-Penerbitan Lainnya

Setelah edisi terbit, beberapa aktivitas penting yang perlu dilakukan:

### Deposit DOI ke Crossref

Jika jurnal sudah terdaftar di Crossref:

1. Login sebagai **Journal Manager**.
2. Buka menu **Tools → Import/Export → Crossref XML Export Plugin**.
3. Pilih artikel yang akan dideposit DOI-nya.
4. Klik **"Export"** untuk menghasilkan file XML.
5. Deposit file XML tersebut ke Crossref melalui plugin atau secara manual.

![Proses deposit DOI ke Crossref](../img/elementor-placeholder-image.png)

### Pengumuman Kepada Pembaca

Selain fitur *Notify Users* saat menerbitkan edisi, Anda dapat membuat pengumuman resmi melalui:

1. Menu **Announcements** di dasbor OJS.
2. Klik **"Add Announcement"**.
3. Isi judul dan konten pengumuman.
4. Atur tanggal kedaluwarsa pengumuman (opsional).
5. Klik **"Save"**.

### Promosi di Media Sosial

Sebaiknya buat strategi promosi konten untuk setiap artikel yang diterbitkan di media sosial institusi atau jurnal, termasuk:
- Ringkasan singkat artikel (untuk Twitter/X, LinkedIn).
- Infografis temuan utama (untuk Instagram).
- Tautan DOI atau URL artikel di jurnal.

---

## Ringkasan Bab

| Langkah | Aksi Editor |
|---------|-------------|
| 1 | Buat edisi baru (*Create Issue*) di tab *Future Issues*. |
| 2 | Jadwalkan naskah ke dalam edisi melalui tab Publication di masing-masing naskah. |
| 3 | Kelola urutan artikel melalui *Table of Contents* (gunakan tombol Order + drag and drop). |
| 4 | Verifikasi metadata edisi di *Issue Data*. |
| 5 | Publikasikan edisi (*Publish Issue*) dan centang *Notify Users*. |
| 6 | Deposit DOI ke Crossref. |
| 7 | Lakukan promosi dan pengumuman pasca-terbit. |
