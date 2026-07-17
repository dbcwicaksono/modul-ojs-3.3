# Bab 7: Menugaskan Peninjau (Assigning Reviewer)

Setelah naskah lolos desk review dan similarity check, tahap selanjutnya adalah **mengirimkan naskah ke proses peer review**. Bab ini memandu editor dalam memilih reviewer yang tepat, mengatur parameter penugasan, dan memantau jalannya proses review.

---

## 7.1 Memindahkan Naskah ke Tahap Review

Sebelum menugaskan reviewer, pastikan naskah sudah siap secara teknis dan substantif untuk ditinjau.

### Prosedur Teknis

1. **Evaluasi pra-review:** Periksa file kiriman dan gunakan *Pre-review Discussions* jika ada hal yang perlu diklarifikasi dengan penulis.
2. Klik tombol **"Send to Review"** di panel kanan halaman naskah.
3. Sistem menampilkan daftar semua komponen naskah. Editor memilih file mana yang akan dikirim ke reviewer.

> **⚠️ Peringatan Kritis (Double Blind Review):**  
> Sebelum mengklik konfirmasi, pastikan file yang dipilih sudah melalui proses **"Blinding" (Anonimisasi)**. Hapus identitas penulis dari properti file dan badan naskah. Jangan kirimkan file yang masih mengandung nama atau afiliasi penulis kepada reviewer.

4. Setelah dikonfirmasi, status naskah secara otomatis berpindah dari *Submission* ke **Review (Round 1)**.

![Jendela pemilihan file untuk Send to Review](../img/elementor-placeholder-image.png)

---

## 7.2 Antarmuka Section Editor vs. Editor-in-Chief

OJS 3.3 menerapkan pembagian tampilan yang spesifik untuk mencegah *information overload*:

| Peran | Tampilan Dasbor | Tab yang Tersedia |
|-------|----------------|-------------------|
| **Editor-in-Chief** | Kontrol penuh | My Queue, **Unassigned**, **All Active**, Archives |
| **Section Editor** | Lebih ramping dan terfokus | Hanya **My Queue** (naskah yang ditugaskan kepadanya) |

Ini memungkinkan Section Editor fokus sepenuhnya pada beban kerja yang relevan tanpa terganggu data naskah lain.

---

## 7.3 Memilih Reviewer yang Tepat

Klik tombol **"Add Reviewer"** di panel *Reviewers* untuk mengakses basis data reviewer. OJS 3.3 menyediakan parameter pencarian mendalam untuk membantu pengambilan keputusan berbasis data:

| Parameter Pencarian | Keterangan |
|---------------------|-----------|
| **Jumlah Tinjauan** | Total riwayat penugasan yang pernah diselesaikan reviewer di jurnal ini. |
| **Rata-rata Waktu** | Kecepatan reviewer menyelesaikan tugas (dalam hitungan hari/minggu). |
| **Tinjauan Aktif** | Jumlah naskah yang sedang ditangani reviewer saat ini — hindari *reviewer fatigue*. |
| **Waktu Sejak Tinjauan Terakhir** | Kapan terakhir kali reviewer berkontribusi, berguna untuk menilai keaktifan. |
| **Minat Meninjau** | Bidang keahlian reviewer (dari kolom *reviewing interests* saat mendaftar). Cocokkan dengan topik naskah. |

![Panel pemilihan reviewer dengan parameter pencarian](../img/elementor-placeholder-image.png)

### Tips Memilih Reviewer

- Pilih reviewer dengan keahlian yang **sesuai dengan topik naskah**.
- Hindari reviewer dengan **terlalu banyak penugasan aktif** untuk mencegah keterlambatan.
- Pilih reviewer yang memiliki **rekam jejak waktu penyelesaian yang baik**.
- Pastikan tidak ada **konflik kepentingan** antara reviewer dan penulis (institusi yang sama, kolaborator sebelumnya, dll.).

---

## 7.4 Mengatur Parameter Penugasan Reviewer

Setelah memilih reviewer, sistem menampilkan formulir penugasan untuk mengatur detail evaluasi:

### Template Email Undangan

OJS menyediakan draf email undangan otomatis yang menggunakan **Placeholders** yang menarik data metadata naskah secara otomatis:

| Placeholder | Data yang Diambil |
|-------------|-------------------|
| `{$reviewerName}` | Nama reviewer |
| `{$submissionTitle}` | Judul naskah |
| `{$abstract}` | Abstrak naskah |
| `{$reviewDueDate}` | Tanggal batas ulasan |
| `{$journalName}` | Nama jurnal |

Anda dapat menyesuaikan isi email sebelum dikirimkan.

### Tanggal Penting

| Tanggal | Keterangan |
|---------|-----------|
| **Response Due Date** | Batas waktu bagi reviewer untuk konfirmasi kesediaan (menerima atau menolak undangan). |
| **Review Due Date** | Batas waktu akhir untuk reviewer mengunggah hasil evaluasi lengkap. |

> **Tips:** Tetapkan *Response Due Date* sekitar 3–5 hari, dan *Review Due Date* sekitar 2–4 minggu dari tanggal penugasan, tergantung kebijakan jurnal.

### Tipe Review

Secara standar OJS menggunakan **Double Blind Review** (identitas penulis dan reviewer bersifat anonim). Pilih sesuai kebijakan jurnal.

### Formulir Penilaian

Jika bagian jurnal memerlukan kriteria evaluasi spesifik, pilih **formulir penilaian** yang sesuai dari menu *drop-down*. Formulir khusus ini dapat dibuat oleh Journal Manager melalui menu **Settings → Workflow → Review**.

![Formulir penugasan reviewer dengan parameter lengkap](../img/elementor-placeholder-image.png)

---

## 7.5 Konfirmasi dan Pemantauan Penugasan

Setelah semua parameter diatur dan tombol **"Add Reviewer"** diklik, sistem otomatis:

1. Mengirimkan **email undangan formal** kepada reviewer.
2. Memasukkan nama reviewer ke dalam **daftar pantau** di panel *Reviewers*.

Anda kini berada dalam posisi **pemantauan**. Melalui dasbor, Anda dapat melacak:

- Apakah reviewer sudah **membaca email** undangan.
- Apakah reviewer sudah **menerima** atau **menolak** undangan.
- Apakah reviewer sudah **mengunggah hasil ulasan**.
- Apakah reviewer memerlukan **pengingat** (*reminder*).

![Panel pemantauan reviewer — status dan tanggal](../img/elementor-placeholder-image.png)

### Mengirim Pengingat (Reminder)

Jika reviewer belum memberikan respons mendekati *Response Due Date*, gunakan:
- Tombol **"Send Reminder"** di sebelah nama reviewer di panel *Reviewers*, ATAU
- Fitur **email templat** melalui tombol Notify/Discussion untuk mengirim pesan personal.

---

## 7.6 Mengelola Beberapa Reviewer

Jurnal biasanya membutuhkan minimal **2 (dua) reviewer** per naskah. Ulangi proses **"Add Reviewer"** untuk menambahkan reviewer kedua dan seterusnya.

**Strategi:**
- Tugaskan reviewer dari **institusi atau negara berbeda** untuk perspektif yang beragam.
- Jika satu reviewer menolak undangan, segera cari pengganti agar proses tidak terhambat.
- Pertimbangkan untuk menambahkan reviewer **cadangan** di awal jika memungkinkan.

---

## Ringkasan Bab

Manajemen penugasan reviewer yang disiplin adalah kunci dalam menjaga reputasi akademik jurnal. Dengan memanfaatkan parameter pencarian berbasis data dan template email yang efisien, editor dapat memastikan proses *peer review* berjalan sesuai jadwal.

**Checklist Penugasan Reviewer:**

- [ ] File naskah sudah dianonimkan (identitas penulis dihapus).
- [ ] Status naskah sudah berpindah ke Review Stage.
- [ ] Reviewer dipilih berdasarkan keahlian yang sesuai topik naskah.
- [ ] Tidak ada konflik kepentingan antara reviewer dan penulis.
- [ ] *Response Due Date* dan *Review Due Date* sudah ditetapkan.
- [ ] Email undangan sudah dikirimkan (otomatis saat klik Add Reviewer).
- [ ] Pemantauan status reviewer dilakukan secara berkala.
