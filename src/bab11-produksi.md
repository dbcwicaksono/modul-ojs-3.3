# Bab 11: Produksi, Tata Letak & Galley

Tahap **Produksi** adalah fase keempat dan terakhir dalam alur kerja editorial OJS 3.3. Di sinilah naskah yang telah melalui penyuntingan dikonversi menjadi **format publikasi resmi** yang disebut **Galley** dan dijadwalkan ke dalam edisi (*issue*) tertentu.

> **Tujuan Tahap Produksi:** Bukan lagi menyunting konten, melainkan memastikan **presentasi teknis** naskah siap untuk dikonsumsi pembaca secara global — dalam format yang profesional dan akurat.

---

## 11.1 Peran dalam Tahap Produksi

| Aktor | Tanggung Jawab |
|-------|---------------|
| **Layout Editor** | Mengubah versi *copyedited* menjadi format siap terbit (PDF, HTML, XML, EPUB). |
| **Editor / Section Editor** | Manajer alur kerja: menunjuk staf, mengawasi proses, dan memegang otoritas keputusan penjadwalan. |
| **Author (Penulis)** | Melakukan *proofreading* akhir terhadap file galley yang telah disiapkan. |
| **Proofreader** | Pemeriksaan akhir pada galley untuk memastikan tidak ada kesalahan tata letak atau visual sebelum publikasi. |

> **Catatan fleksibilitas OJS 3.3:** Jika tim terbatas, seorang Editor dapat merangkap peran sebagai Layout Editor dalam sistem — cukup berikan akses peran yang sesuai.

---

## 11.2 Penugasan Tim Produksi

Langkah pertama adalah menunjuk personel di dalam sistem:

1. Navigasi ke panel **"Participants"** di halaman naskah (tab Production).
2. Klik tombol **"Assign"**.
3. Pilih peran yang sesuai: *Layout Editor*, *Proofreader*, atau lainnya.
4. Cari staf yang tersedia dan pilih.
5. Sistem membuka draf email notifikasi — sesuaikan jika perlu, lalu klik **"OK"**.

![Panel Participants di tahap Production](../img/elementor-placeholder-image.png)

---

## 11.3 Pembuatan File Galley

Layout Editor akan mengunduh file *copyedited* dari tahap sebelumnya, mengerjakannya di luar sistem, lalu mengunggahnya kembali sebagai **Galley**.

### Format File Galley yang Didukung OJS

| Format | Kegunaan Utama |
|--------|---------------|
| **PDF** | Standar utama untuk cetak digital dan pembacaan *offline*. Paling umum digunakan. |
| **HTML** | Tampilan responsif yang dapat dibaca langsung di peramban web. |
| **XML** | Format terstruktur untuk indeksasi otomatis dan pertukaran data antar mesin. |
| **EPUB** | Dioptimalkan untuk perangkat pembaca buku elektronik (*e-reader*). |

### Cara Mengunggah Galley

1. Di halaman naskah tahap Production, klik **"Add Galley"** di bagian *Galleys*.
2. Isi **label galley** (mis. "PDF", "HTML").
3. Pilih bahasa galley.
4. Klik **"Save"**, lalu unggah file galley yang telah dibuat.

![Tampilan unggah Galley di tahap Production](../img/elementor-placeholder-image.png)

---

## 11.4 Diskusi Produksi dan Proofreading

Gunakan fitur **"Production Discussions"** sebagai pusat komunikasi. 

**Prosedur proofreading oleh penulis:**
1. Editor mengunggah file galley di area diskusi.
2. Mulai diskusi dengan penulis (*Add Discussion*, pilih penulis sebagai partisipan).
3. Penulis menerima email notifikasi.
4. Penulis mengunduh file galley dan memeriksa secara menyeluruh:
   - Apakah tata letak sudah benar?
   - Apakah ada kesalahan ketik yang terlewat?
   - Apakah gambar/tabel sudah tampil dengan benar?
5. Penulis memberikan konfirmasi atau catatan koreksi melalui fitur diskusi di sistem.

> **Semua komunikasi harus melalui *Production Discussions*** — bukan email eksternal. Ini memastikan seluruh jejak audit tersimpan di sistem dan dapat diakses oleh tim editorial lain.

![Fitur Production Discussions untuk proofreading](../img/elementor-placeholder-image.png)

---

## 11.5 Finalisasi Metadata di Tab Publication

Sebelum naskah dijadwalkan untuk terbit, pastikan semua metadata sudah benar. Masuk ke tab **"Publication"** pada halaman alur kerja naskah dan verifikasi:

| Bagian | Yang Harus Diverifikasi |
|--------|------------------------|
| **Title & Abstract** | Judul dan abstrak bebas dari kesalahan ketik, sesuai dengan file galley. |
| **Contributors** | Daftar penulis, afiliasi, urutan kontributor sudah benar dan konsisten. |
| **Metadata** | Kata kunci (*keywords*) sudah dimasukkan dengan multi-tag yang benar. |
| **References** | Referensi sudah dimasukkan, pisahkan setiap referensi dengan baris kosong. |
| **Identifiers (DOI)** | Nomor DOI sudah ter-*assign* sesuai pola yang ditetapkan. |
| **Permissions & Disclosure** | Pemegang hak cipta, lisensi, dan tahun copyright sudah benar. |
| **Issue & Page Numbers** | Nomor halaman dan edisi target sudah dipilih. |

![Tab Publication — verifikasi metadata sebelum publikasi](../img/elementor-placeholder-image.png)

---

## 11.6 Menjadwalkan Naskah ke Dalam Issue

Setelah galley dan metadata sudah siap:

1. Di tab **Publication**, masuk ke submenu **"Issue"**.
2. Pilih edisi yang sudah dibuat sebagai target publikasi (*Future Issue*).
3. Isi **nomor halaman** artikel jika diperlukan.
4. Klik **"Schedule for Publication"**.

Naskah kini resmi terjadwalkan dan akan terbit saat edisi tersebut dipublikasikan.

![Penjadwalan naskah ke dalam Future Issue](../img/elementor-placeholder-image.png)

---

## 11.7 Tips untuk Alur Kerja Produksi yang Efisien

> **Sentralisasi Komunikasi:** Pastikan **semua instruksi perubahan layout** dilakukan melalui "Production Discussions". Jangan gunakan email eksternal agar riwayat perubahan file selalu tersimpan dan dapat diakses oleh seluruh tim editorial.

> **Konsistensi Nama File:** Beri nama file galley secara konsisten — misalnya: `[JurnalSingkatan]-[Vol]-[No]-[Tahun]-[ID].pdf`. Ini memudahkan pengelolaan file dalam jangka panjang.

> **Backup:** Simpan salinan file galley final di luar sistem OJS sebagai arsip cadangan.

---

## Checklist Produksi

Sebelum melanjutkan ke tahap manajemen edisi, pastikan semua poin berikut sudah terpenuhi:

- [ ] File galley (minimal PDF) sudah dibuat dan diunggah.
- [ ] Penulis sudah melakukan proofreading dan memberikan persetujuan.
- [ ] Metadata di tab Publication sudah lengkap dan terverifikasi.
- [ ] DOI sudah ter-assign.
- [ ] Naskah sudah dijadwalkan ke dalam *Future Issue* yang sesuai.

---

## Ringkasan Bab

Tahap produksi bukan sekadar urusan teknis — ini adalah penentu kualitas akhir jurnal di mata komunitas akademik global. Keakuratan galley, metadata yang rapi, dan komunikasi yang terdokumentasi dengan baik mencerminkan **kredibilitas dan profesionalisme jurnal**.

Dengan menyelesaikan tahap ini, naskah siap untuk dipublikasikan melalui proses **Manajemen Edisi** yang dibahas pada Bab 12.
