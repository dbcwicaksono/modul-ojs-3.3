# Bab 5: Merespons Kiriman Naskah Baru

Bab ini memandu **editor** dalam mengelola naskah yang masuk ke jurnal — mulai dari navigasi dasbor, pemeriksaan awal naskah, penugasan editor bagian, hingga pengambilan keputusan editorial pertama. Tahap *Submission* adalah gerbang utama di mana editor berperan sebagai kurator awal yang menentukan kelayakan sebuah naskah untuk diproses lebih lanjut.

---

## 5.1 Peran Editor dalam Tahap Submission

Editor di OJS 3.3 tidak hanya memantau naskah, tetapi memiliki kemampuan teknis untuk:
- Mengelola akun pengguna.
- Masuk sebagai pengguna lain jika diperlukan (*login as*).
- Mengambil keputusan krusial di setiap tahap.

OJS 3.3 sangat fleksibel — jurnal dapat dikelola oleh Editor tunggal yang menangani seluruh proses, atau oleh tim besar yang terdiri dari Editor Kepala (*Editor-in-Chief*), beberapa Section Editor, hingga staf pendukung.

---

## 5.2 Navigasi Dasbor Editorial

Dasbor editorial adalah **pusat kendali** bagi editor. Untuk manajemen jurnal yang proaktif, pahami fungsi empat tab utama:

| Tab | Fungsi | Tips Penggunaan |
|-----|--------|-----------------|
| **My Queue** | Naskah yang menjadi tanggung jawab langsung Anda. | Periksa setiap hari untuk akuntabilitas kerja. |
| **Unassigned** | Naskah masuk yang **belum ada editornya**. | ⚠️ Area risiko utama! Pantau rutin untuk mencegah naskah "terlantar". |
| **All Active** | Seluruh naskah yang sedang diproses di semua tahap. | Digunakan Editor Kepala untuk memantau beban kerja tim. |
| **Archives** | Naskah yang telah dipublikasikan atau ditolak. | Rekam jejak permanen. |

**Fitur Filter dan Pencarian:**

Manfaatkan filter canggih OJS 3.3 untuk navigasi efisien:
- Cari berdasarkan **nama penulis** atau **kata kunci judul**.
- Filter berdasarkan status **terlambat** (*overdue*).
- Filter berdasarkan naskah **belum lengkap** (*incomplete*).
- Filter berdasarkan **tahap proses**, bagian jurnal, atau **Days since last activity** (sangat berguna untuk mengidentifikasi naskah yang stagnan).

![Tampilan dasbor editorial OJS dengan empat tab utama](../img/elementor-placeholder-image.png)

---

## 5.3 Membuka dan Memahami Rekam Naskah (Submission Record)

Klik tombol **"View"** pada naskah untuk masuk ke halaman detailnya. Halaman ini berisi:

### Informasi di Header Rekam Naskah

- **ID Naskah** — Pengenal unik setiap naskah dalam sistem.
- **Nama belakang Penulis** — Informasi cepat untuk identifikasi.
- **Judul Naskah** — Judul lengkap artikel.

### Activity Log vs. Internal Notes

Penting untuk membedakan dua fitur ini:

| Fitur | Fungsi | Sifat |
|-------|--------|-------|
| **Activity Log** | Rekaman otomatis setiap tindakan sistem (upload file, keputusan editor, dll.). | Tidak dapat diubah (*immutable*). |
| **Notes** (tab internal) | Catatan manual antar-editor untuk hal strategis terkait naskah. | Dapat ditambah/diedit oleh editor. |

### Submission Library

Tempat berbagi dokumen pendukung (formulir etik, data tambahan) secara efisien dengan penulis dan tim editorial — tanpa melalui prosedur pengiriman formal.

![Halaman detail rekam naskah (Submission Record)](../img/elementor-placeholder-image.png)

---

## 5.4 Manajemen File Kiriman

Area **"Submission Files"** menampilkan seluruh berkas digital yang diunggah penulis, beserta komponen naskahnya (*Article Text, Research Materials*, dll.).

**Tindakan yang dapat dilakukan editor:**

1. **Mengunduh** — Klik judul file untuk mengunduhnya.
2. **Expansion Arrow** *(Pro-Tip)* — Klik panah biru kecil di sebelah file untuk mengakses log aktivitas spesifik file dan catatan internal terkait file tersebut.
3. **Mengedit nama file** atau **menghapus** file yang tidak relevan.
4. **Upload File** — Menambahkan dokumen baru jika diperlukan.
5. **Download All Files** — Mengambil seluruh paket dokumen dalam satu klik untuk peninjauan *offline*.

![Area Submission Files dengan berbagai opsi manajemen](../img/elementor-placeholder-image.png)

---

## 5.5 Menggunakan Fitur Diskusi Pre-Review

Fitur **Pre-review Discussions** adalah alat komunikasi editorial yang terpusat dan terlacak. Gunakan fitur ini secara strategis — misalnya, untuk meminta klarifikasi atau perbaikan administratif dari penulis **sebelum** memutuskan mengirim naskah ke tahap *review*.

**Cara Menggunakan Discussion Wizard:**

1. Klik **"Add Discussion"** di panel *Pre-review Discussions*.
2. **Pilih partisipan** — Penulis, Editor lain, atau keduanya.
3. Masukkan **Subjek** dan **Pesan**. Anda dapat melampirkan file di sini.
4. Klik **"OK"**.

Selain itu, Editor dapat menggunakan fitur **"Notify"** pada daftar *Participants* (panel kanan layar) untuk mengirim pesan menggunakan templat email yang tersedia.

> **Ingat:** Semua diskusi tersimpan permanen di sistem sebagai *audit trail*. Hindari menggunakan email eksternal untuk komunikasi editorial.

![Fitur Pre-review Discussions di halaman submission](../img/elementor-placeholder-image.png)

---

## 5.6 Tiga Keputusan Editorial Utama

Setelah tinjauan awal selesai, editor mengeksekusi keputusan melalui **Decision Wizard** di panel sebelah kanan:

### A. Send to Review

Memindahkan naskah ke tahap peninjauan sejawat.

> **Perhatian Penting (*Double Blind Review*):** Saat memilih file yang akan dikirim ke reviewer, **pastikan** Anda **menghapus centang (uncheck)** pada file yang mengandung identitas penulis. Ini menjaga integritas proses *double-blind review*.

![Jendela Send to Review — pemilihan file yang akan dikirim ke reviewer](../img/elementor-placeholder-image.png)

### B. Accept and Skip Review

Digunakan untuk kiriman yang **tidak memerlukan peer review formal**, seperti:
- Komentar editorial
- Pengumuman
- Resensi buku

Naskah langsung masuk ke tahap Copyediting.

### C. Decline Submission

Menolak naskah yang tidak sesuai standar atau lingkup jurnal.

- Anda dapat memilih untuk mengirim **notifikasi kepada penulis** atau hanya merekam keputusan secara internal.
- Jika terjadi kesalahan, gunakan fitur **"Change Decision"** untuk membatalkan status penolakan.

![Panel keputusan editorial (Decision Wizard)](../img/elementor-placeholder-image.png)

---

## 5.7 Penugasan Editor Bagian (Section Editor)

Jika jurnal menggunakan model tim, Editor Kepala dapat menugaskan **Section Editor** melalui tombol **"Assign"** di panel *Participants*.

**Tiga kontrol perizinan kritis yang harus diatur:**

| Tingkat Wewenang | Deskripsi |
|---|---|
| **Hanya Rekomendasi** | Section Editor hanya dapat memberikan saran, tidak bisa mengambil keputusan final atau menghubungi penulis secara mandiri. |
| **Wewenang Penuh** | Section Editor memiliki kendali penuh atas alur naskah hingga pengambilan keputusan. |
| **Pembatasan Metadata** | Anda dapat membatasi hak akses Section Editor untuk mengubah metadata naskah — fitur krusial untuk menjaga integritas data bibliografi. |

Setelah penugasan dikonfirmasi, sistem otomatis mengirimkan email kepada Section Editor dan memperbarui daftar *Participants* secara *real-time*.

![Jendela penugasan Section Editor dengan pilihan perizinan](../img/elementor-placeholder-image.png)

---

## 5.8 Memindahkan Naskah ke Tahap Review

Setelah keputusan "Send to Review" dikonfirmasi, naskah akan secara otomatis berpindah dari status *Submission* ke **Review (Round 1)**. File yang dipilih akan tercantum di panel *Review Files*.

Pada tahap ini, editor juga dapat:
- Menggunakan **fitur diskusi** untuk mengklarifikasi hal kepada penulis sebelum proses review dimulai.
- Memeriksa kembali kelengkapan file naskah.

> Panduan lengkap tentang proses penugasan reviewer dibahas di **Bab 7: Menugaskan Peninjau**.

---

## Ringkasan Bab

| Langkah | Aksi Editor |
|---------|-------------|
| 1 | Pantau tab **Unassigned** secara rutin. |
| 2 | Buka rekam naskah dan pelajari *Activity Log*. |
| 3 | Unduh dan periksa file kiriman secara *offline* jika perlu. |
| 4 | Gunakan **Pre-review Discussions** untuk komunikasi dengan penulis. |
| 5 | Tugaskan **Section Editor** dengan wewenang yang tepat (jika ada). |
| 6 | Ambil keputusan: *Send to Review*, *Accept and Skip Review*, atau *Decline Submission*. |
| 7 | Pastikan file sudah dianonimkan sebelum dikirim ke reviewer (*Send to Review*). |
