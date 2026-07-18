# Bab 10: Merespons Hasil Ulasan (Editorial Decision)

Bab ini merupakan tahap krusial dalam alur kerja editorial, di mana editor menafsirkan rekomendasi dari para peninjau (*reviewer*) dan menetapkan keputusan editorial resmi yang menentukan kelayakan suatu naskah.

## 10.1 Pentingnya Tahap Pengambilan Keputusan

Setelah proses penelaahan sejawat (*peer review*) selesai dilakukan oleh mitra bestari, tugas editor bukan sekadar meneruskan komentar dari mitra bestari kepada penulis. Editor memiliki tanggung jawab akademik untuk:

1. Mengevaluasi kualitas ulasan dan melihat rekam jejak aktivitas peninjauan.
2. Menetapkan keputusan editorial resmi: diterima, memerlukan revisi, atau ditolak.
3. Mengomunikasikan hasil ulasan kepada penulis dengan tetap menjamin integritas penelaahan nirnama (*blind review*).

## 10.2 Melihat dan Mengevaluasi Hasil Ulasan

### Prosedur Melihat Ulasan

1. Masuk ke dasbor dan buka naskah yang sedang dalam tahap review.
2. Klik tab **"Review"** pada halaman naskah.
3. Periksa panel **Reviewers** dan identifikasi ulasan yang sudah selesai (status: *completed*).

Catatan Teknis: Sebelum membaca ulasan, klik tombol **Activity Log** di pojok kanan atas. Periksa apakah mitra bestari menyerahkan ulasan tepat waktu atau apakah terdapat catatan khusus selama proses komunikasi. Informasi ini memberikan konteks penting mengenai keandalan suatu ulasan.

4. Klik tautan ulasan untuk melihat detail komentar.

![Panel reviewer dengan status ulasan selesai](../img/elementor-placeholder-image.png)

### Dua Kategori Komentar Reviewer

| Kategori | Pihak yang Membaca | Fungsi |
|----------|-------------------|--------|
| **Komentar untuk Penulis & Editor** | Penulis dan Editor | Masukan teknis yang akan dikirim kepada penulis sebagai panduan untuk melakukan revisi. |
| **Komentar Khusus untuk Editor** | Editor saja | Catatan rahasia dan direktif tentang kelayakan naskah. Penulis tidak memiliki akses ke bagian ini. |

## 10.3 Opsi Keputusan Editorial

Mitra bestari bertugas memberikan rekomendasi, namun keputusan final tetap berada di tangan editor. Editor mengeksekusi salah satu opsi keputusan berikut:

| Keputusan | Deskripsi dan Konsekuensi |
|-----------|------------------------|
| **Accept Submission** | Naskah diterima tanpa perubahan. Naskah langsung bertransisi ke tahap **Copyediting**. |
| **Revisions Required** | Diperlukan revisi minor. Editor memeriksa revisi sendiri tanpa melibatkan mitra bestari kembali. |
| **Resubmit for Review** | Diperlukan revisi mayor. Naskah masuk ke putaran kedua (*Review Round 2*). |
| **Resubmit Elsewhere** | Naskah berkualitas namun tidak sesuai dengan fokus dan ruang lingkup jurnal. Disarankan untuk dikirim ke jurnal lain. |
| **Decline Submission** | Naskah ditolak karena tidak memenuhi standar kualitas atau terdapat kelemahan metodologi yang mendasar. |

Catatan Penting: Keputusan **"Accept Submission"** harus diambil dengan sangat hati-hati. Setelah keputusan dicatat melalui tombol **"Record Editorial Decision"**, sistem akan mengunci status naskah. Pembatalan keputusan kembali ke status "Request Revisions" memerlukan intervensi administratif yang kompleks. Pastikan naskah benar-benar siap sebelum mengkonfirmasi.

## 10.4 Menangani Ulasan yang Saling Bertentangan

Dalam proses editorial, sangat umum ditemui situasi di mana rekomendasi dari dua mitra bestari saling bertentangan (misalnya, satu merekomendasikan *Accept* sedangkan yang lain merekomendasikan *Decline*). Dalam situasi ini, editor dapat mengambil langkah-langkah sesuai panduan Committee on Publication Ethics (COPE):

1. **Evaluasi kualitas ulasan**: Editor harus menilai argumen mana yang didukung oleh bukti ilmiah yang lebih kuat. Ulasan yang lebih mendetail dan konstruktif umumnya lebih dapat diandalkan.
2. **Mengundang peninjau ketiga**: Jika editor merasa tidak memiliki kepakaran yang cukup untuk menimbang kedua ulasan yang bertentangan, editor harus mengundang mitra bestari ketiga sebagai penengah (*adjudicator*).
3. **Mengambil keputusan mandiri**: Jika editor adalah pakar di bidang terkait, editor berhak mengambil keputusan akhir dengan menyertakan alasan penolakan atau penerimaan yang jelas kepada penulis.

Editor dapat merujuk pada diagram alir COPE untuk penanganan proses editorial yang lebih kompleks terkait sengketa peninjauan.

## 10.5 Mengomunikasikan Keputusan kepada Penulis

Setelah menentukan keputusan, klik tombol aksi yang sesuai (misalnya **"Request Revisions"**). Jendela surel (*email*) otomatis akan muncul.

### Prosedur Kritis: Menjaga Integritas Blind Review

Salah satu kesalahan umum adalah membiarkan identitas mitra bestari bocor melalui dokumen ulasan yang dilampirkan.

Perhatian: OJS tidak secara otomatis menghapus metadata personal dari dokumen Word yang diunggah oleh mitra bestari. Sebelum mengirimkan berkas ulasan ke penulis, editor harus:
1. Mengunduh berkas ulasan dari sistem.
2. Menghapus identitas personal secara manual. Di MS Word, klik **File**, pilih **Info**, kemudian **Check for Issues**, lalu **Inspect Document**, dan klik **Remove All** pada bagian properti dokumen.
3. Di jendela notifikasi OJS, pastikan untuk mengunggah dan hanya mencentang berkas yang telah dianomimkan. Berkas asli yang masih memuat metadata tidak boleh dikirimkan ke penulis.

![Jendela pengiriman notifikasi keputusan ke penulis](../img/elementor-placeholder-image.png)

## 10.6 Mengelola Revisi dan Putaran Ulasan Baru

### Jika Keputusan: Revisions Required

- Penulis akan mendapat notifikasi dan mengunggah berkas hasil perbaikan.
- Berkas terbaru akan muncul di panel ulasan pada kolom **Revisions**.
- Editor memeriksa revisi secara langsung, umumnya tanpa mengirim naskah kembali ke mitra bestari.

### Jika Keputusan: Resubmit for Review (Putaran Kedua)

1. Naskah hasil revisi penulis tersedia di kolom **Revisions**.
2. Klik opsi **"New Review Round"** untuk memulai putaran kedua.
3. Pada putaran kedua, editor memiliki keleluasaan untuk mengundang kembali mitra bestari yang sama untuk mengecek perbaikan, atau menambahkan mitra bestari baru jika ulasan pada putaran pertama dirasa kurang memadai.

![Antarmuka memulai New Review Round](../img/elementor-placeholder-image.png)

## 10.7 Mencatat Keputusan Akhir dan Transisi ke Copyediting

Setelah seluruh proses revisi selesai dan editor memutuskan naskah layak terbit, langkah akhir pada tahap ini adalah:

1. Klik **"Record Editorial Decision"** dengan memilih **Accept Submission**.
2. Pilih berkas versi final yang paling bersih dari panel revisi.
3. Sistem secara otomatis memindahkan naskah dari tahap **Review** ke tahap **Copyediting**.
4. Berkas yang dipilih akan menjadi naskah sumber utama bagi tim penyunting di tahap selanjutnya.

![Transisi naskah dari Review ke Copyediting](../img/elementor-placeholder-image.png)

## Checklist Bab 10

- [ ] Status dan komentar semua mitra bestari telah dievaluasi.
- [ ] Keputusan editorial telah ditetapkan dengan mempertimbangkan seluruh ulasan yang masuk.
- [ ] Dokumen ulasan yang akan dikirimkan kepada penulis telah dianomimkan dari metadata personal.
- [ ] Pemberitahuan keputusan telah dikirimkan kepada penulis melalui sistem.
- [ ] Batas waktu revisi (jika ada) telah disampaikan secara jelas kepada penulis.
- [ ] Pada naskah yang memerlukan putaran kedua (*Review Round 2*), mitra bestari lanjutan telah diundang.
- [ ] Naskah yang telah direvisi dan disetujui telah dicatat sebagai *Accept Submission* dan dipindahkan ke tahap Copyediting.

## Ringkasan Bab

| Langkah | Aksi Editor |
|---------|-------------|
| 1 | Periksa status penelaahan di panel *Reviewers*. |
| 2 | Buka dan baca komentar secara menyeluruh. |
| 3 | Timbang rekomendasi mitra bestari dan tentukan keputusan editorial. |
| 4 | Anonimkan berkas ulasan sebelum dikirimkan kepada penulis. |
| 5 | Kirimkan notifikasi keputusan kepada penulis melalui sistem. |
| 6 | Jika diperlukan revisi mayor, buka *New Review Round* setelah perbaikan diunggah. |
| 7 | Catat keputusan akhir (*Accept*) dan pilih berkas final untuk transisi ke Copyediting. |
