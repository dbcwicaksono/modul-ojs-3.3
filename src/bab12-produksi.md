# Bab 12: Produksi, Tata Letak, dan Galley

Tahap **Produksi** adalah fase keempat dan terakhir dalam alur kerja editorial OJS 3.3. Pada tahap ini, naskah yang telah melalui proses penyuntingan dikonversi menjadi format publikasi resmi yang disebut **Galley**, kemudian dijadwalkan ke dalam edisi (*issue*) tertentu.

Tujuan utama tahap produksi bukan lagi untuk menyunting substansi konten, melainkan memastikan presentasi teknis naskah siap diakses oleh pembaca secara global dalam format yang profesional dan akurat.

## 12.1 Peran dalam Tahap Produksi

| Aktor | Tanggung Jawab |
|-------|---------------|
| **Layout Editor** | Mengubah versi naskah hasil *copyediting* menjadi format siap terbit (PDF, HTML, XML, EPUB). |
| **Editor / Section Editor** | Mengelola alur kerja produksi dengan menunjuk staf, mengawasi proses, dan menetapkan jadwal terbit. |
| **Author (Penulis)** | Melakukan pengecekan akhir (*proofreading*) terhadap berkas galley yang telah disiapkan sebelum diterbitkan. |
| **Proofreader** | Melakukan pemeriksaan akhir pada galley untuk memastikan tidak terdapat kesalahan tata letak atau visual visual. |

Catatan Teknis: OJS 3.3 memberikan fleksibilitas peran. Apabila tim pengelola terbatas, seorang editor dapat merangkap peran sebagai Layout Editor dengan cara memberikan akses peran tambahan di dalam sistem.

## 12.2 Penugasan Tim Produksi

Langkah pertama pada tahap produksi adalah menunjuk personel pelaksana:

1. Navigasi ke panel **"Participants"** di halaman naskah pada tab *Production*.
2. Klik tombol **"Assign"**.
3. Pilih peran yang ditugaskan, misalnya *Layout Editor* atau *Proofreader*.
4. Cari dan pilih staf yang tersedia dari daftar pengguna.
5. Sistem akan membuka draf surel notifikasi. Sesuaikan isi surel jika diperlukan, kemudian klik **"OK"**.

![Panel Participants di tahap Production](../img/elementor-placeholder-image.png)

## 12.3 Pembuatan File Galley

Layout Editor akan mengunduh berkas *copyedited* dari tahap sebelumnya, melakukan tata letak menggunakan perangkat lunak eksternal, lalu mengunggahnya kembali sebagai **Galley**.

Pembuatan galley umumnya menggunakan beberapa perangkat lunak, seperti:
- **Microsoft Word atau LibreOffice**: Digunakan untuk menyusun draf akhir sebelum diekspor menjadi format PDF.
- **Pandoc** (https://pandoc.org/): Perangkat lunak baris perintah untuk mengonversi dokumen antar berbagai format, sangat berguna untuk membuat HTML atau EPUB dari dokumen teks.
- **Plugin OJS JATS XML**: Beberapa jurnal menggunakan plugin OJS atau perangkat lunak pihak ketiga seperti Texture untuk menghasilkan dokumen berformat XML JATS secara otomatis.

### Format File Galley yang Didukung OJS

| Format | Kegunaan Utama |
|--------|---------------|
| **PDF** | Format standar untuk cetak digital dan pembacaan luring (*offline*). Paling umum digunakan oleh jurnal ilmiah. |
| **HTML** | Menyediakan tampilan responsif yang dapat dibaca langsung melalui peramban web tanpa perlu mengunduh dokumen. |
| **XML (JATS)** | Format terstruktur yang esensial untuk indeksasi tingkat lanjut dan pertukaran data antar mesin. |
| **EPUB** | Format yang dioptimalkan untuk perangkat pembaca buku elektronik (*e-reader*). |

Pentingnya Format XML JATS: *Journal Article Tag Suite* (JATS) adalah format standar internasional untuk mendeskripsikan konten ilmiah. Penyediaan galley dalam format XML JATS merupakan persyaratan penting bagi jurnal yang ingin terindeks di pangkalan data bergengsi seperti PubMed Central dan sangat direkomendasikan untuk indeksasi Scopus. XML JATS memastikan bahwa metadata dan konten teks artikel terstruktur dengan sempurna sehingga dapat dibaca dan diekstraksi oleh mesin pengindeks.

**Studi Kasus**: Banyak jurnal di Indonesia mengalami peningkatan jumlah pembaca (*readership*) dan sitasi yang signifikan setelah beralih dari sekadar menyajikan PDF menjadi juga menyediakan versi HTML dan XML artikelnya. Versi HTML dan XML membuat artikel jauh lebih mudah ditemukan oleh mesin pencari dan lebih nyaman dibaca di perangkat seluler, sehingga meningkatkan visibilitas secara drastis.

### Cara Mengunggah Galley

1. Di halaman naskah pada tahap *Production*, klik **"Add Galley"** di bagian *Galleys*.
2. Isi label galley (misalnya "PDF" atau "HTML").
3. Pilih bahasa dari dokumen galley tersebut.
4. Klik **"Save"**, lalu unggah berkas galley yang telah disiapkan.

![Tampilan unggah Galley di tahap Production](../img/elementor-placeholder-image.png)

## 12.4 Diskusi Produksi dan Proofreading

Fungsikan fitur **"Production Discussions"** sebagai pusat komunikasi utama selama tahap ini.

Prosedur proofreading oleh penulis dilakukan sebagai berikut:
1. Editor mengunggah berkas galley ke area diskusi produksi.
2. Editor memulai diskusi dengan penulis (*Add Discussion*, dan memilih penulis sebagai partisipan).
3. Penulis akan menerima surel notifikasi.
4. Penulis mengunduh berkas galley dan memeriksa beberapa hal teknis:
   - Apakah tata letak halaman dan tipografi sudah sesuai?
   - Apakah terdapat kesalahan ketik atau pemotongan kata yang tidak tepat?
   - Apakah gambar, grafik, dan tabel disajikan dengan jelas?
5. Penulis menyampaikan konfirmasi atau daftar koreksi melalui fitur diskusi.

Seluruh komunikasi harus dilakukan melalui fitur diskusi produksi OJS, bukan melalui surel eksternal pribadi. Praktik ini memastikan seluruh proses revisi tercatat dalam sistem dan dapat diakses oleh tim editorial lainnya.

![Fitur Production Discussions untuk proofreading](../img/elementor-placeholder-image.png)

## 12.5 Finalisasi Metadata di Tab Publication

Sebelum naskah dijadwalkan untuk terbit, pastikan semua metadata sudah terverifikasi. Masuk ke tab **"Publication"** pada halaman alur kerja naskah dan periksa elemen berikut:

| Bagian | Elemen yang Diverifikasi |
|--------|------------------------|
| **Title & Abstract** | Judul dan abstrak bebas dari kesalahan ketik dan sesuai secara presisi dengan teks di dalam galley. |
| **Contributors** | Daftar penulis, nama institusi afiliasi, dan urutan nama penulis sudah benar. |
| **Metadata** | Kata kunci (*keywords*) telah diinput dengan struktur tag yang tepat. |
| **References** | Daftar pustaka sudah diinput, dengan setiap referensi dipisahkan oleh satu baris kosong. |
| **Identifiers (DOI)** | Nomor DOI (*Digital Object Identifier*) telah ditugaskan (*assigned*) sesuai dengan pola registrasi jurnal. |
| **Permissions & Disclosure** | Informasi pemegang hak cipta, jenis lisensi, dan tahun hak cipta sudah tercatat dengan benar. |
| **Issue & Page Numbers** | Nomor edisi target dan rentang halaman artikel telah ditetapkan. |

![Tab Publication: verifikasi metadata sebelum publikasi](../img/elementor-placeholder-image.png)

## 12.6 Menjadwalkan Naskah ke Dalam Issue

Setelah galley dan metadata siap, naskah siap dijadwalkan:

1. Di tab **Publication**, akses submenu **"Issue"**.
2. Pilih edisi yang telah dibuat sebagai target penerbitan (*Future Issue*).
3. Masukkan nomor halaman artikel pada kolom yang tersedia.
4. Klik **"Schedule for Publication"**.

Naskah kini telah dijadwalkan dan akan dipublikasikan secara daring bersamaan dengan diterbitkannya edisi terkait.

![Penjadwalan naskah ke dalam Future Issue](../img/elementor-placeholder-image.png)

## Checklist Bab 12

Sebelum beralih ke tahap manajemen edisi, pastikan poin-poin berikut telah terselesaikan:

- [ ] Personel tim produksi (seperti Layout Editor) telah ditugaskan di dalam sistem jika menggunakan model tim.
- [ ] Berkas galley (minimal berformat PDF) telah dikonversi dan diunggah menggunakan format tata letak jurnal.
- [ ] Penulis telah melakukan *proofreading* akhir melalui fitur *Production Discussions* dan menyetujui versi galley.
- [ ] Seluruh data metadata di tab *Publication* telah diverifikasi kesesuaiannya dengan teks artikel.
- [ ] Nomor DOI telah ditugaskan (*assigned*).
- [ ] Rentang halaman artikel telah ditentukan.
- [ ] Naskah telah dijadwalkan ke dalam edisi mendatang (*Future Issue*).

## Ringkasan Bab

Tahap produksi menentukan kualitas dan profesionalisme bentuk fisik digital sebuah jurnal. Penyajian tata letak yang bersih, kelengkapan ragam galley (termasuk format berbasis web seperti HTML atau XML JATS), serta kelengkapan metadata, berkontribusi langsung pada visibilitas artikel di berbagai mesin pencari akademik. Komunikasi *proofreading* yang tersentralisasi dalam OJS memastikan proses perbaikan akhir dapat dilacak dan dipertanggungjawabkan sebelum artikel diterbitkan secara publik.
