# Transformasi Modul OJS 3.3 Menjadi Buku Teks/Referensi

## Visi dan Latar Belakang

Modul yang ada saat ini sudah sangat baik secara prosedural: bersih dari gaya bahasa informal, berstruktur, dan bersumber. Namun ia masih berkarakter **panduan teknis** — linear, berbasis langkah, dan terbatas pada pengalaman "di dalam kotak OJS". Transformasi ini bertujuan mengangkatnya menjadi **buku teks referensi** yang:

- **Eksploratif**: membahas "mengapa" di balik "bagaimana" — konteks, standar global, dan konsekuensi pilihan.
- **Inklusif secara level**: bisa dibaca oleh pengelola jurnal baru *maupun* editor berpengalaman yang ingin memahami praktik terbaik global.
- **Kaya studi kasus**: dilengkapi situasi riil (termasuk dari pengalaman penulis) yang menjembatani teori dengan praktik lapangan.
- **Layak sebagai bahan pelatihan/workshop**: struktur tiap bab mendukung fasilitasi sesi belajar kelompok.

---

## Pertanyaan Terbuka untuk Penulis

> [!IMPORTANT]
> Sebelum eksekusi dimulai, ada beberapa hal yang perlu klarifikasi dari Anda. Tidak harus dijawab semua sekarang — bisa dijawab bertahap saat mengerjakan tiap bab.

1. **Identitas pengalaman**: Pengalaman Anda di bidang apa saja yang bisa digali? Misalnya: pernah mengelola jurnal X, pernah menjadi reviewer, pernah mengalami kasus plagiasi yang rumit, pernah mengurus DOAJ/Scopus, pernah pelatih/fasilitator workshop OJS, dll. Ini akan menjadi bahan studi kasus.

2. **Nada buku**: Apakah Anda menginginkan nada *akademis-formal* sepenuhnya, atau boleh ada bagian "catatan dari pengalaman penulis" (*author's note*) yang lebih personal dan reflektif?

3. **Target pembaca utama**: Apakah buku ini lebih condong ke (a) pengelola jurnal kampus yang baru mulai, (b) editor jurnal yang sudah jalan tapi ingin naik kelas ke DOAJ/Scopus, atau (c) fasilitator pelatihan OJS? Ini menentukan kedalaman bab mana yang diprioritaskan.

4. **Judul buku**: Apakah sudah ada judul yang Anda pikirkan? Contoh alternatif:
   - *"Manajemen Jurnal Ilmiah Berbasis OJS 3.3: Panduan Komprehensif dari Naskah hingga Indeksasi"*
   - *"OJS 3.3 untuk Pengelola Jurnal: Praktik, Standar, dan Strategi Visibilitas"*

5. **Bab 14 (Diseminasi)**: Topik ini masih kosong. Apakah Anda punya pengalaman atau preferensi strategi diseminasi tertentu (media sosial, ResearchGate, repository institusional, dll.)?

---

## Diagnosis Kondisi Terkini

| Aspek | Kondisi Sekarang | Target Buku |
|---|---|---|
| Gaya bahasa | Formal, baku ✓ | Tetap formal, tambah narasi reflektif |
| Kedalaman | Prosedural, berbasis langkah | Konseptual + prosedural + kontekstual |
| Studi kasus | Ada di beberapa bab (Bab 7, 11, 13) | Setiap bab wajib punya ≥1 studi kasus |
| Pengalaman penulis | Belum ada | Sisipkan sebagai *"Catatan dari Lapangan"* |
| Elemen latihan | Hanya checklist | Tambah latihan/skenario simulasi per bab |
| Aparatus buku | Glosarium & Daftar Pustaka sudah ada (draft) | Perkaya + tambah Indeks Subjek + Tentang Penulis |
| Pengantar bab | Langsung ke materi | Tambah *vignette* atau situasi pemantik di awal tiap bab |

---

## Kerangka Buku yang Diusulkan

### Aparatus Depan (Front Matter)
- **Halaman Judul dan Hak Cipta** (dalam `book.toml` dan `README.md`)
- **Kata Pengantar** — Ditulis ulang sepenuhnya: lebih personal, menceritakan perjalanan penulis dan mengapa buku ini lahir
- **Cara Menggunakan Buku Ini** — Panduan membaca untuk berbagai jenis pembaca (pemula, editor berpengalaman, fasilitator)
- **Ucapan Terima Kasih**

### Bagian I–VII (Bab 1–14) — Transformasi Per Bab
Setiap bab akan diperkaya dengan:
- **Pemantik Bab** (*Chapter Vignette*): sebuah pertanyaan, skenario, atau kutipan singkat yang membuka bab
- **Catatan dari Lapangan** (*Field Notes*): pengalaman atau observasi penulis yang relevan
- **Sorotan Standar Global**: kotak informasi tentang standar DOAJ, COPE, Crossref, dll.
- **Latihan/Skenario**: tugas reflektif atau simulasi untuk konteks pelatihan
- Checklist yang sudah ada tetap dipertahankan

### Aparatus Belakang (Back Matter)
- **Glosarium** — perkaya dari draft yang ada
- **Daftar Pustaka Terpadu** — konsolidasi semua referensi
- **Indeks Subjek** (*Subject Index*) — [BARU]
- **Tentang Penulis** (*About the Author*) — [BARU]
- **Lampiran**: contoh-contoh formulir, templat surel, checklist pra-indeksasi

---

## Rencana Perubahan Per Bab

### Aparatus Depan

#### [MODIFY] [README.md](file:///d:/opot/antigravity/modul-ojs-3/src/README.md) — Kata Pengantar
- Tulis ulang seluruhnya menjadi narasi personal dan kontekstual
- Ceritakan: mengapa jurnal ilmiah Indonesia penting, perjalanan penulis mengenal OJS, dan visi buku ini
- Tambahkan bagian: **"Untuk Siapa Buku Ini"** dengan panduan membaca per profil pembaca

#### [NEW] `src/cara-menggunakan-buku.md` — Panduan Membaca
- Profil Pembaca 1: Pengelola Jurnal Baru (rute baca linear)
- Profil Pembaca 2: Editor Berpengalaman (rute baca tematik, lompat ke bab relevan)
- Profil Pembaca 3: Fasilitator Pelatihan (rute baca per modul workshop)
- Penjelasan elemen-elemen bab (apa itu "Catatan dari Lapangan", "Sorotan Standar Global", dll.)

---

### Bagian I — Persiapan dan Kemampuan Dasar

#### [MODIFY] [bab1-eresources.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab1-eresources.md)
- Tambah **Pemantik Bab**: "Bayangkan Anda diminta menelusuri 50 referensi dalam 3 hari untuk sebuah artikel review..."
- Tambah subbab: konteks ekosistem informasi ilmiah global (Web of Science, Scopus, Google Scholar, repositori)
- Tambah **Catatan dari Lapangan**: pengalaman menelusuri referensi untuk keperluan editorial
- Tambah **Latihan**: simulasi menelusuri sumber untuk topik tertentu

#### [MODIFY] [bab2-bibliografi.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab2-bibliografi.md)
- Tambah **Pemantik Bab**: "Sebuah artikel ditolak indeksasi bukan karena isinya buruk, tapi karena format referensinya kacau..."
- Perluas pembahasan gaya sitasi: APA, Chicago, Vancouver — kapan dan mengapa digunakan
- Tambah **Catatan dari Lapangan**: kasus referensi bermasalah yang pernah dijumpai
- Tambah **Latihan**: latihan konversi format referensi

---

### Bagian II — Pengenalan OJS 3.3

#### [MODIFY] [bab3-gambaran-umum.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab3-gambaran-umum.md)
- Tambah **Pemantik Bab**: "Tahun 2001, sebuah perangkat lunak gratis diluncurkan dan perlahan mengubah lanskap penerbitan ilmiah dunia..."
- Perkuat sub-bab sejarah OJS/PKP dengan narasi yang lebih hidup
- Tambah subbab: **"OJS di Indonesia: Konteks Nasional"** — data adopsi, Garuda, Sinta, kebijakan Kemendikbudristek
- Tambah **Catatan dari Lapangan**: kesan pertama berinteraksi dengan OJS
- Tambah **Sorotan Standar Global**: Open Access dan BOAI (sudah ada, perkuat narasi)

---

### Bagian III — Alur Kerja Penulis

#### [MODIFY] [bab4-submission.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab4-submission.md)
- Tambah **Pemantik Bab**: "Sebagai penulis, kesan pertama Anda terhadap sebuah jurnal dimulai dari halaman submission-nya..."
- Tambah perspektif ganda: panduan dari sisi penulis DAN dari sisi editor yang menerima
- Tambah **Catatan dari Lapangan**: kesalahan submission yang paling sering ditemui
- Tambah **Latihan**: skenario simulasi submission dengan naskah contoh

---

### Bagian IV — Alur Kerja Editorial (inti buku)

#### [MODIFY] [bab5-merespons-naskah.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab5-merespons-naskah.md)
- Tambah **Pemantik Bab**: skenario editor yang mendapat 15 submission baru dalam sehari
- Perluas desk review: kriteria substantif (kelayakan metodologi, novelty, scope) bukan hanya administratif
- Tambah **Sorotan Standar Global**: DOAJ tentang proses editorial terdokumentasi
- Tambah **Catatan dari Lapangan**: pengalaman atau observasi melakukan desk review
- Tambah **Latihan**: latihan menilai kelayakan abstrak untuk desk review

#### [MODIFY] [bab6-similarity-check.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab6-similarity-check.md)
- Tambah **Pemantik Bab**: "Similarity report menunjukkan 35% — apakah naskah ini plagiat?"
- Tambah subbab: **"Membaca Laporan Similarity dengan Bijak"** — perbedaan self-plagiarism, plagiarism, dan false positive
- Tambah **Sorotan Standar Global**: COPE flowchart plagiarism, standar Turnitin/iThenticate
- Tambah **Studi Kasus**: kasus similarity tinggi tapi ternyata bukan plagiarism (misalnya: methods section yang baku)
- Tambah **Latihan**: latihan menginterpretasi similarity report fiktif

#### [MODIFY] [bab7-assigning-reviewer.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab7-assigning-reviewer.md)
- Tambah **Pemantik Bab**: "Database reviewer Anda hanya berisi 8 orang — bagaimana Anda mengelola peer review yang adil?"
- Tambah subbab: **"Membangun dan Merawat Database Reviewer"** — strategi rekrutmen, diversifikasi
- Perluas pembahasan konflik kepentingan dengan lebih banyak skenario
- Tambah **Catatan dari Lapangan**: pengalaman mencari reviewer untuk topik yang sangat niche
- Tambah **Latihan**: skenario simulasi pemilihan reviewer

#### [MODIFY] [bab8-panduan-reviewer.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab8-panduan-reviewer.md)
- Tambah **Pemantik Bab**: kutipan tentang apa yang diharapkan dari seorang reviewer yang baik
- Tambah subbab: **"Anatomi Review yang Baik"** — bagaimana menulis komentar yang konstruktif
- Tambah **Sorotan Standar Global**: COPE Ethical Guidelines for Peer Reviewers
- Tambah **Studi Kasus**: contoh review yang buruk vs review yang konstruktif (anonim)
- Tambah **Latihan**: latihan menulis komentar review untuk abstrak fiktif

#### [MODIFY] [bab9-editorial-decision.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab9-editorial-decision.md)
- Tambah **Pemantik Bab**: "Dua reviewer memberikan rekomendasi yang bertolak belakang — apa yang Anda lakukan?"
- Perluas pembahasan: kapan perlu reviewer ketiga, penanganan reviewer yang tidak profesional
- Tambah **Sorotan Standar Global**: COPE flowchart keputusan editorial
- Tambah **Catatan dari Lapangan**: pengalaman menghadapi situasi review yang rumit
- Tambah **Latihan**: simulasi pengambilan keputusan editorial dari berbagai skenario

---

### Bagian V — Pasca-Review, Produksi, dan Penerbitan

#### [MODIFY] [bab10-copyediting.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab10-copyediting.md)
- Tambah **Pemantik Bab**: "Apa yang terjadi jika sebuah artikel terbit dengan kesalahan ketik pada judul?"
- Tambah subbab: **"Gaya Selingkung (House Style)"** — pentingnya konsistensi dan cara membuat style guide
- Tambah **Sorotan Standar Global**: DOAJ tentang transparansi proses penyuntingan
- Tambah **Catatan dari Lapangan**: observasi copyediting di berbagai jurnal
- Tambah **Latihan**: latihan copyediting pada paragraf dengan berbagai jenis kesalahan

#### [MODIFY] [bab11-produksi.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab11-produksi.md)
- Tambah **Pemantik Bab**: "Artikel sudah terbit, tapi tidak bisa dibaca di ponsel — siapa yang bertanggung jawab?"
- Perluas pembahasan Pandoc dan XML JATS dengan penjelasan lebih aksesibel
- Tambah **Sorotan Standar Global**: persyaratan galley untuk PubMed Central, Scopus
- Tambah **Studi Kasus**: (sudah ada, perkuat dengan data konkret)
- Tambah **Latihan**: simulasi memilih format galley berdasarkan target indeksasi

#### [MODIFY] [bab12-manajemen-edisi.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab12-manajemen-edisi.md)
- Tambah **Pemantik Bab**: "Jurnal Anda hampir terindeks DOAJ, tapi tim reviewer menemukan back issue tanpa DOI..."
- Tambah subbab: **"DOI dan Crossref: Mengapa Setiap Artikel Perlu Identitas Permanen"**
- Tambah **Sorotan Standar Global**: standar Crossref, DOAJ terkait kepemilikan DOI
- Tambah **Catatan dari Lapangan**: pengalaman mengurus DOI untuk back issue
- Tambah **Latihan**: latihan perencanaan edisi dan deposit DOI

---

### Bagian VI — Visibilitas dan Indeksasi

#### [MODIFY] [bab13-metadata.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab13-metadata.md)
- Tambah **Pemantik Bab**: "Artikel Anda sudah terbit 6 bulan — tapi tidak muncul di Google Scholar sama sekali..."
- Perkuat penjelasan Dublin Core, schema.org, JATS agar lebih mudah dipahami non-teknis
- Tambah **Sorotan Standar Global**: perkuat DOAJ metadata requirements
- Tambah **Studi Kasus**: (sudah ada kasus Google Scholar, perkuat dan tambah satu kasus lagi)
- Tambah **Latihan**: latihan mengaudit metadata artikel yang memiliki masalah

---

### Bagian VII — Diseminasi

#### [NEW] [bab14-diseminasi.md](file:///d:/opot/antigravity/modul-ojs-3/src/bab14-diseminasi.md)
Bab baru yang belum ada. Topik yang diusulkan:
- **14.1** Mengapa Diseminasi Pasca-Terbit Itu Penting
- **14.2** Strategi Diseminasi di Media Sosial Akademik (ResearchGate, Academia.edu, Twitter/X untuk akademisi)
- **14.3** Repository Institusional dan Sinta
- **14.4** Mendaftarkan Jurnal ke DOAJ dan Indeksator Lainnya
- **14.5** Mengoptimalkan Profil Google Scholar Jurnal
- **14.6** Komunikasi dengan Komunitas Ilmiah

---

### Aparatus Belakang

#### [MODIFY] [glosarium.md](file:///d:/opot/antigravity/modul-ojs-3/src/glosarium.md)
- Perkaya dengan semua istilah baru yang masuk seiring penambahan konten
- Tambahkan: `schema.org`, `JATS`, `Dublin Core`, `ORCID`, `CrossRef`, `DOAJ`, `COPE`, `Desk Review`, `House Style`, dll.

#### [MODIFY] [daftar-pustaka.md](file:///d:/opot/antigravity/modul-ojs-3/src/daftar-pustaka.md)
- Konsolidasi semua referensi dari semua bab
- Verifikasi setiap URL masih aktif
- Format konsisten: APA 7th Edition

#### [NEW] `src/indeks-subjek.md` — Indeks Subjek
- Daftar alfabet istilah utama dengan referensi ke nomor bab
- Contoh: "Conflict of Interest → Bab 7, Bab 8", "DOI → Bab 12, Bab 13"

#### [NEW] `src/tentang-penulis.md` — Tentang Penulis
- Biografi singkat penulis
- Rekam jejak yang relevan dengan topik buku

#### [NEW] `src/lampiran.md` — Lampiran
- Lampiran A: Templat Surel Undangan Reviewer
- Lampiran B: Contoh Formulir Review Terstruktur
- Lampiran C: Checklist Pra-Submission DOAJ
- Lampiran D: Daftar Plugin OJS yang Direkomendasikan

---

## Elemen Baru Per Bab (Konvensi)

Berikut adalah elemen baru yang akan ditambahkan ke setiap bab secara konsisten:

### 1. Pemantik Bab (*Chapter Vignette*)
Diletakkan tepat setelah judul bab dan sebelum paragraf pembuka. Format:

```markdown
> *[Situasi atau pertanyaan pemantik yang menggambarkan tantangan nyata yang akan dijawab di bab ini.]*
```

### 2. Catatan dari Lapangan (*Field Notes*)
Diletakkan di posisi yang relevan dalam bab, umumnya setelah pembahasan konsep yang didukung pengalaman. Format:

```markdown
**Catatan dari Lapangan**

[Narasi singkat berdasarkan pengalaman atau observasi penulis. Tidak harus dramatis — cukup autentik dan relevan. Jika pengalaman tidak tersedia, gunakan observasi umum yang dapat diverifikasi.]
```

### 3. Sorotan Standar Global (*Global Standards Spotlight*)
Untuk setiap standar internasional yang relevan (COPE, DOAJ, Crossref, dll.). Format:

```markdown
**Sorotan Standar Global: [Nama Standar]**

[Penjelasan singkat: apa standar ini, siapa yang menetapkan, mengapa relevan bagi pengelola jurnal Indonesia.]

*Sumber: [URL]*
```

### 4. Latihan dan Skenario (*Exercises*)
Diletakkan sebelum Checklist, setelah pembahasan utama. Format:

```markdown
## Latihan Bab [X]

**Latihan [X.1]: [Judul Latihan]**
[Deskripsi skenario atau tugas reflektif]

**Panduan Fasilitator**: [Catatan untuk fasilitator pelatihan/workshop, jika relevan]
```

---

## Urutan Prioritas Pengerjaan

Mengingat buku ini ditujukan untuk audiens luas dan sebagian besar bab sudah ada (tinggal diperkaya), berikut urutan pengerjaan yang disarankan:

| Prioritas | Item | Alasan |
|---|---|---|
| 1 | Kata Pengantar (README.md) | Fondasi identitas buku |
| 2 | Cara Menggunakan Buku Ini | Panduan membaca untuk fasilitator |
| 3 | Bab 3 (Gambaran Umum) | Gerbang pembaca — paling sering dibaca pertama |
| 4 | Bab 7 (Assigning Reviewer) | Sudah punya studi kasus, tinggal diperkaya |
| 5 | Bab 9 (Keputusan Editorial) | Topik yang paling sering jadi pertanyaan di workshop |
| 6 | Bab 6 (Similarity Check) | Topik yang paling "viral" di komunitas jurnal |
| 7 | Bab 14 (Diseminasi) | Bab baru yang perlu dibuat dari nol |
| 8 | Bab 13 (Metadata) | Sudah paling lengkap, tinggal perkuat |
| 9 | Bab 5, 8, 10, 11, 12 | Kelompok bab inti |
| 10 | Bab 1, 2, 4 | Bab pendukung |
| 11 | Glosarium, Daftar Pustaka, Indeks | Aparatus akhir |
| 12 | Tentang Penulis, Lampiran | Aparatus pelengkap |

---

## Rencana Verifikasi

1. Setiap bab: pastikan semua 4 elemen baru hadir (Pemantik, Catatan Lapangan, Sorotan Standar, Latihan)
2. Lakukan pencarian global untuk memastikan tidak ada em-dash atau emotikon
3. Jalankan `mdbook build` setelah setiap batch pengerjaan
4. Push ke GitHub dan verifikasi tampilan di GitHub Pages

---

## Catatan Teknis

- **Format file**: tetap Markdown, tidak ada perubahan platform (tetap mdBook)
- **Gambar**: tetap menggunakan placeholder `../img/elementor-placeholder-image.png`
- **Bahasa**: tetap formal, baku — penambahan "Catatan dari Lapangan" boleh sedikit lebih personal tapi tetap tidak menggunakan bahasa santai/informal
- **Referensi**: setiap klaim baru harus disertai sumber atau diubah menjadi pernyataan prosedural

