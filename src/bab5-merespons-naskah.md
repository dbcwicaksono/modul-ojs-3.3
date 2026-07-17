# Bab 5: Merespons Kiriman Naskah Baru

Bab ini membahas peran editor dalam mengelola naskah yang masuk ke sistem OJS 3.3, mulai dari navigasi dasbor editorial, pemeriksaan awal naskah, penugasan editor bagian, hingga pengambilan keputusan editorial pertama. Untuk pembahasan tentang proses pengiriman naskah dari sudut pandang penulis, lihat **Bab 4: Panduan Mengirimkan Artikel**.

## Tinjauan Awal Meja (Desk Review)

Sebelum sebuah naskah dikirimkan ke proses penelaahan sejawat (*peer review*), editor terlebih dahulu melakukan tinjauan awal meja (*desk review*). Tinjauan ini adalah penilaian administratif dan kesesuaian ruang lingkup yang dilakukan oleh editor sebelum melibatkan reviewer. Tujuannya adalah menyaring naskah yang tidak memenuhi syarat minimum sehingga beban reviewer dapat dikelola secara efisien.

Menurut panduan Directory of Open Access Journals (DOAJ), jurnal yang memenuhi syarat untuk terindeks harus memiliki proses editorial yang terdokumentasi dan dapat diverifikasi, termasuk proses tinjauan awal sebelum peer review (DOAJ, 2024, https://doaj.org/apply/guide/).

Tinjauan awal meja umumnya mencakup:
1. Pemeriksaan kesesuaian topik dengan fokus dan ruang lingkup jurnal.
2. Pemeriksaan kepatuhan terhadap panduan penulisan (*author guidelines*).
3. Pemeriksaan kelengkapan administratif (jumlah penulis, afiliasi, pernyataan etika jika diperlukan).
4. Pemeriksaan awal kemiripan naskah menggunakan perangkat lunak deteksi plagiasi (lihat **Bab 6: Pemeriksaan Plagiasi**).

---

## 5.1 Peran Editor dalam Tahap Submission

Editor di OJS 3.3 tidak hanya memantau naskah, tetapi memiliki kemampuan teknis untuk:
- Mengelola akun pengguna.
- Masuk sebagai pengguna lain jika diperlukan (*login as*).
- Mengambil keputusan editorial di setiap tahap alur kerja.

OJS 3.3 bersifat fleksibel. Jurnal dapat dikelola oleh editor tunggal yang menangani seluruh proses, atau oleh tim yang terdiri dari Editor Kepala (*Editor-in-Chief*), beberapa Section Editor, hingga staf pendukung.

---

## 5.2 Navigasi Dasbor Editorial

Dasbor editorial adalah antarmuka utama bagi editor untuk memantau seluruh aktivitas naskah. Terdapat empat tab utama yang perlu dipahami:

| Tab | Fungsi | Catatan |
|-----|--------|---------|
| **My Queue** | Naskah yang menjadi tanggung jawab langsung editor yang sedang login. | Periksa setiap hari untuk menjaga akuntabilitas kerja. |
| **Unassigned** | Naskah masuk yang belum ditugaskan ke editor mana pun. | Area berisiko tinggi. Pantau secara rutin untuk mencegah naskah tidak tertangani. |
| **All Active** | Seluruh naskah yang sedang diproses di semua tahap. | Digunakan Editor Kepala untuk memantau beban kerja tim secara keseluruhan. |
| **Archives** | Naskah yang telah dipublikasikan atau ditolak. | Berfungsi sebagai rekam jejak permanen seluruh aktivitas editorial. |

**Fitur Filter dan Pencarian:**

OJS 3.3 menyediakan filter untuk navigasi yang lebih efisien:
- Pencarian berdasarkan nama penulis atau kata kunci judul.
- Filter berdasarkan status terlambat (*overdue*).
- Filter berdasarkan naskah belum lengkap (*incomplete*).
- Filter berdasarkan tahap proses, bagian jurnal, atau jumlah hari sejak aktivitas terakhir (*Days since last activity*). Filter terakhir ini berguna untuk mengidentifikasi naskah yang tidak berkembang dalam waktu lama.

![Tampilan dasbor editorial OJS dengan empat tab utama](../img/elementor-placeholder-image.png)

---

## 5.3 Membuka dan Memahami Rekam Naskah

Klik tombol **"View"** pada naskah untuk masuk ke halaman rekam naskah (*submission record*). Halaman ini berisi seluruh informasi dan aktivitas terkait naskah tersebut.

### Informasi di Header Rekam Naskah

- **ID Naskah**: Pengenal unik setiap naskah dalam sistem.
- **Nama Belakang Penulis**: Informasi cepat untuk identifikasi.
- **Judul Naskah**: Judul lengkap artikel.

### Activity Log dan Internal Notes

Penting untuk membedakan dua fitur ini:

| Fitur | Fungsi | Sifat |
|-------|--------|-------|
| **Activity Log** | Rekaman otomatis setiap tindakan sistem: unggah file, keputusan editor, pengiriman email, dan lainnya. | Tidak dapat diubah (*immutable*). Berfungsi sebagai jejak audit (*audit trail*) seluruh aktivitas sistem. |
| **Notes** (tab internal) | Catatan manual antar-editor untuk hal-hal strategis terkait naskah yang tidak perlu diketahui penulis. | Dapat ditambah dan diedit oleh editor. |

*Jejak audit* (*audit trail*) adalah rekaman kronologis yang tidak dapat diubah dari seluruh aktivitas yang terjadi dalam sistem. Fungsinya adalah memastikan akuntabilitas dan transparansi proses editorial.

### Submission Library

Submission Library adalah tempat berbagi dokumen pendukung, seperti formulir etik penelitian atau data tambahan, secara langsung antara editor dan penulis tanpa melalui prosedur unggah formal.

![Halaman detail rekam naskah](../img/elementor-placeholder-image.png)

---

## 5.4 Manajemen File Kiriman

Area **"Submission Files"** menampilkan seluruh berkas digital yang diunggah penulis, beserta keterangan komponen naskahnya (*Article Text*, *Research Materials*, dan lainnya).

Tindakan yang dapat dilakukan editor pada area ini:

1. **Mengunduh**: Klik judul file untuk mengunduhnya ke perangkat lokal.
2. **Expansion Arrow**: Klik panah kecil di sebelah nama file untuk mengakses log aktivitas spesifik file tersebut beserta catatan internal terkait.
3. **Mengedit nama file** atau menghapus file yang tidak relevan.
4. **Upload File**: Menambahkan dokumen baru yang diperlukan untuk proses editorial.
5. **Download All Files**: Mengunduh seluruh paket dokumen sekaligus untuk peninjauan secara *offline*.

![Area Submission Files dengan berbagai opsi manajemen](../img/elementor-placeholder-image.png)

---

## 5.5 Fitur Diskusi Pre-Review

Fitur **Pre-review Discussions** adalah sarana komunikasi editorial yang terpusat dan tercatat dalam sistem. Fitur ini digunakan untuk meminta klarifikasi atau perbaikan administratif dari penulis sebelum naskah dikirimkan ke tahap penelaahan sejawat.

Seluruh komunikasi yang dilakukan melalui fitur ini tersimpan secara permanen di sistem sebagai bagian dari jejak audit. Penggunaan email eksternal untuk komunikasi editorial tidak dianjurkan karena tidak tercatat dalam sistem dan tidak dapat diverifikasi.

**Prosedur penggunaan:**

1. Klik **"Add Discussion"** di panel *Pre-review Discussions*.
2. Pilih partisipan: penulis, editor lain, atau keduanya.
3. Masukkan subjek dan isi pesan. File dapat dilampirkan di sini.
4. Klik **"OK"**.

Editor juga dapat menggunakan fitur **"Notify"** pada daftar *Participants* di panel kanan untuk mengirim pesan menggunakan templat email yang tersedia dalam sistem.

![Fitur Pre-review Discussions di halaman submission](../img/elementor-placeholder-image.png)

---

## 5.6 Tiga Keputusan Editorial pada Tahap Submission

Setelah tinjauan awal meja selesai, editor mengambil satu dari tiga keputusan melalui **Decision Wizard** di panel sebelah kanan:

### A. Send to Review

Naskah dinyatakan memenuhi syarat awal dan dipindahkan ke tahap penelaahan sejawat (*peer review*).

Catatan Penting untuk Proses Double-Blind Review: Saat memilih file yang akan dikirim ke reviewer, pastikan file yang mengandung identitas penulis tidak disertakan (hapus tanda centang). Hal ini menjaga integritas proses *double-blind review* di mana reviewer tidak mengetahui identitas penulis.

![Jendela Send to Review: pemilihan file yang akan dikirim ke reviewer](../img/elementor-placeholder-image.png)

### B. Accept and Skip Review

Digunakan untuk kiriman yang tidak memerlukan proses peer review formal, seperti:
- Komentar editorial
- Pengumuman
- Resensi buku

Naskah langsung masuk ke tahap Copyediting tanpa melalui tahap Review.

### C. Decline Submission

Naskah ditolak karena tidak sesuai standar atau ruang lingkup jurnal.

Pada opsi ini, editor dapat memilih untuk mengirimkan notifikasi kepada penulis atau hanya merekam keputusan secara internal. Jika terjadi kesalahan dalam pengambilan keputusan, gunakan fitur **"Change Decision"** untuk membatalkan status penolakan.

![Panel keputusan editorial](../img/elementor-placeholder-image.png)

---

## 5.7 Penugasan Editor Bagian (Section Editor)

Pada jurnal yang menggunakan model tim editorial, Editor Kepala dapat menugaskan **Section Editor** melalui tombol **"Assign"** di panel *Participants*.

Terdapat tiga tingkat wewenang yang harus ditentukan saat penugasan:

| Tingkat Wewenang | Deskripsi |
|---|---|
| **Hanya Rekomendasi** | Section Editor hanya dapat memberikan saran kepada Editor Kepala, tidak dapat mengambil keputusan final atau menghubungi penulis secara mandiri. |
| **Wewenang Penuh** | Section Editor memiliki kendali penuh atas alur naskah, termasuk pengambilan keputusan editorial. |
| **Pembatasan Metadata** | Hak akses Section Editor untuk mengubah metadata naskah dapat dibatasi. Pembatasan ini penting untuk menjaga integritas data bibliografi. |

Setelah penugasan dikonfirmasi, sistem secara otomatis mengirimkan email pemberitahuan kepada Section Editor yang ditugaskan.

![Jendela penugasan Section Editor dengan pilihan perizinan](../img/elementor-placeholder-image.png)

---

## 5.8 Memindahkan Naskah ke Tahap Review

Setelah keputusan "Send to Review" dikonfirmasi, naskah berpindah dari status *Submission* ke **Review (Round 1)**. File yang dipilih akan tercantum secara otomatis di panel *Review Files* pada tahap Review.

Pada tahap ini, editor juga dapat menggunakan fitur diskusi untuk mengklarifikasi hal-hal kepada penulis sebelum proses review dimulai, serta memeriksa kembali kelengkapan file naskah.

Panduan lengkap tentang proses penugasan reviewer dibahas di **Bab 7: Menugaskan Peninjau**.

---

## Checklist Bab 5

Gunakan daftar berikut sebagai panduan sebelum memindahkan naskah ke tahap berikutnya:

- [ ] Tab **Unassigned** sudah diperiksa dan tidak ada naskah yang terbengkalai.
- [ ] Rekam naskah sudah dibuka dan *Activity Log* sudah dipelajari.
- [ ] File kiriman sudah diunduh dan diperiksa.
- [ ] Pemeriksaan kemiripan (*similarity check*) sudah dilakukan (lihat Bab 6).
- [ ] **Pre-review Discussions** sudah digunakan untuk komunikasi dengan penulis jika diperlukan.
- [ ] Section Editor sudah ditugaskan dengan tingkat wewenang yang tepat (jika menggunakan model tim).
- [ ] Keputusan editorial sudah diambil: *Send to Review*, *Accept and Skip Review*, atau *Decline Submission*.
- [ ] File sudah dipastikan tidak mengandung identitas penulis sebelum dikirim ke reviewer (untuk *double-blind review*).

---

## Ringkasan Bab

| Langkah | Aksi Editor |
|---------|-------------|
| 1 | Pantau tab **Unassigned** secara rutin. |
| 2 | Buka rekam naskah dan pelajari *Activity Log*. |
| 3 | Unduh dan periksa file kiriman. |
| 4 | Gunakan **Pre-review Discussions** untuk komunikasi dengan penulis. |
| 5 | Tugaskan **Section Editor** dengan wewenang yang tepat (jika ada). |
| 6 | Ambil keputusan: *Send to Review*, *Accept and Skip Review*, atau *Decline Submission*. |
| 7 | Pastikan file sudah dianonimkan sebelum dikirim ke reviewer. |
