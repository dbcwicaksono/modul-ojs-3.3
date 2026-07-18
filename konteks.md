# Konteks Proyek: Modul Pengelolaan Jurnal Elektronik dengan OJS 3.3

Gunakan dokumen ini untuk memahami konteks proyek ini di awal setiap sesi kerja baru.

---

## 1. Identitas Proyek

- **Nama Proyek**: Penulisan Modul Pengelolaan Jurnal Elektronik dengan Open Journal Systems (OJS) 3.3
- **Repositori GitHub**: https://github.com/dbcwicaksono/modul-ojs-3.3
- **Lokasi Lokal**: `d:\opot\antigravity\modul-ojs-3`
- **Platform Buku**: mdBook (dirender dari Markdown)
- **Bahasa**: Indonesia (formal, akademis, baku)

---

## 2. Struktur Proyek

```
modul-ojs-3/
├── src/                        ← semua file bab di sini
│   ├── SUMMARY.md              ← daftar isi/navigasi mdBook
│   ├── README.md               ← halaman kata pengantar
│   ├── bab1-eresources.md
│   ├── bab2-bibliografi.md
│   ├── bab3-gambaran-umum.md
│   ├── bab4-submission.md
│   ├── bab5-merespons-naskah.md
│   ├── bab6-similarity-check.md
│   ├── bab7-assigning-reviewer.md
│   ├── bab8-panduan-reviewer.md
│   ├── bab9-editorial-decision.md
│   ├── bab10-copyediting.md
│   ├── bab11-produksi.md
│   ├── bab12-manajemen-edisi.md
│   └── bab13-metadata.md
├── sumber-rji/                 ← materi sumber dari RJI (dokumen referensi, JANGAN diubah)
│   └── markdown/               ← versi markdown dari modul RJI asli
├── img/                        ← gambar placeholder (pakai elementor-placeholder-image.png)
├── book.toml                   ← konfigurasi mdBook
└── konteks.md                  ← file ini
```

---

## 3. Struktur Buku (Bagian dan Bab)

| Bagian | Judul | Bab |
|---|---|---|
| I | Pengenalan dan Persiapan Jurnal | 1, 2, 3, 4 |
| II | Alur Kerja Penulis (Author) | 5 |
| III | Alur Kerja Editorial | 6, 7, 8, 9, 10 |
| IV | Pasca-Review, Produksi, dan Penerbitan | 11, 12, 13 |
| V | Visibilitas dan Indeksasi | 14 |
| VI | Diseminasi dan Peningkatan Visibilitas Jurnal | 15 (BELUM DIBUAT) |
| -- | Glosarium | (BELUM DIBUAT) |
| -- | Daftar Pustaka Terpadu | (BELUM DIBUAT) |

---

## 4. Status Pengerjaan

> **CATATAN UNTUK AI**: Bagian ini adalah "memori" proyek. Selalu perbarui tabel di bawah setelah selesai mengerjakan sesuatu di sesi manapun. Tanpa pembaruan ini, sesi berikutnya tidak tahu sudah sampai mana.

### Ringkasan Cepat (Perbarui Setiap Sesi)

- **Sesi terakhir**: 2026-07-19
- **Dikerjakan**: Menyunting dan memperkaya **Bab 4 (Bibliografi & Referensi)**. Menambahkan Pemantik Bab tentang dampak daftar pustaka acak terhadap indeksasi, Sorotan Standar Global (Ekstraksi Referensi OJS 3.3, Crossref Reference Linking, Controlled Vocabularies vs Author Keywords), Catatan dari Lapangan (keluhan editor terkait gagalnya parser pada *hardcoded citations*), dan Latihan Bab 4 (Analisis Ekstraksi Referensi & Audit Kata Kunci).
- **Berikutnya**: Melanjutkan ke Bab 5 (Submission Penulis) atau bab lain sesuai urutan prioritas.

### Tahap 1: Pembersihan Gaya Bahasa [SELESAI — 2026-07-17]

Semua 13 bab yang ada (bab1 s.d. bab13) telah dibersihkan dari:
- Em-dash (—), emotikon, label informal, tanda seru berlebihan, frasa retoris

### Tahap 2: Transformasi Menjadi Buku Teks [SEDANG BERJALAN]

Setiap bab diperkaya dengan 4 elemen baru: **Pemantik Bab**, **Catatan dari Lapangan**, **Sorotan Standar Global**, **Latihan/Skenario**.

Legenda status: `[ ]` Belum | `[R]` Riset selesai | `[/]` Sedang dikerjakan | `[x]` Selesai

| Bab | Judul | Riset KB | Penulisan | Terakhir Diperbarui |
|-----|-------|----------|-----------|---------------------|
| README | Kata Pengantar | `[ ]` | `[ ]` | — |
| Baru | Cara Menggunakan Buku Ini | `[ ]` | `[ ]` | — |
| **Bab 1** | Gambaran Umum OJS | `[R]` KB-001~010 | `[x]` | 2026-07-18 |
| **Bab 2** | Identitas & Kebijakan Jurnal | `[R]` KB-017~023 | `[ ]` | 2026-07-18 |
| **Bab 3** | E-Resources & Penelusuran | `[x]` | `[x]` | 2026-07-18 |
| **Bab 4** | Bibliografi & Referensi | `[R]` KB-026~030 | `[x]` | 2026-07-19 |
| **Bab 5** | Submission (Penulis) | `[R]` KB-024~025 | `[ ]` | 2026-07-18 |
| **Bab 6** | Merespons Naskah (Desk Review) | `[ ]` | `[ ]` | — |
| **Bab 7** | Similarity Check | `[ ]` | `[ ]` | — |
| **Bab 8** | Assigning Reviewer | `[ ]` | `[ ]` | — |
| **Bab 9** | Panduan Reviewer | `[ ]` | `[ ]` | — |
| **Bab 10** | Keputusan Editorial | `[R]` KB-024 | `[ ]` | 2026-07-18 |
| **Bab 11** | Copyediting | `[R]` KB-024~025 | `[ ]` | 2026-07-18 |
| **Bab 12** | Produksi & Galley | `[R]` KB-024 | `[ ]` | 2026-07-18 |
| **Bab 13** | Manajemen Edisi | `[ ]` | `[ ]` | — |
| **Bab 14** | Optimalisasi Metadata | `[ ]` | `[ ]` | — |
| **Bab 15** | Diseminasi (BARU) | `[ ]` | `[ ]` | — |
| Back | Glosarium | `[ ]` | `[ ]` | — |
| Back | Daftar Pustaka Terpadu | `[ ]` | `[ ]` | — |
| Back | Indeks Subjek (BARU) | `[ ]` | `[ ]` | — |
| Back | Tentang Penulis (BARU) | `[ ]` | `[ ]` | — |
| Back | Lampiran (BARU) | `[ ]` | `[ ]` | — |

### Tahap 3: Aparatus Buku Baru [BELUM DIMULAI]

- [ ] Bab 15 (Baru): Diseminasi dan Peningkatan Visibilitas Jurnal
- [ ] Glosarium (perkaya draft yang sudah ada)
- [ ] Daftar Pustaka Terpadu (konsolidasi dari semua bab)
- [ ] Indeks Subjek (`src/indeks-subjek.md`) — baru
- [ ] Tentang Penulis (`src/tentang-penulis.md`) — baru
- [ ] Lampiran (`src/lampiran.md`) — baru

### Knowledge Base: Riwayat Riset per Topik

> **UNTUK AGEN PENELITI**: Sebelum mulai riset, baca tabel ini. Jika sub-topik yang akan diteliti sudah ada di kolom "Sub-topik Tercakup", **jangan teliti ulang** — kecuali pengguna secara eksplisit meminta pendalaman. Cukup rujuk ke nomor KB yang sudah ada.

| Bab | Sub-topik Tercakup | Entri KB | Sub-topik yang Belum Diteliti | Tanggal Terakhir |
|-----|--------------------|----------|-------------------------------|------------------|
| Bab 1 | Definisi & sejarah OJS; sejarah & misi PKP (John Willinsky, 1998); krisis publikasi (serials crisis); statistik global OJS (58.000 jurnal, 156 negara, 2025); definisi Open Access dari BOAI; adopsi OJS di Indonesia (11.000-17.000 instalasi); ekosistem ARJUNA, SINTA, Garuda; PKP School & PKP Docs; evolusi arsitektur OJS 1.x/2.x vs 3.x; OJS 3.4 & 3.5 LTS (GDPR, self-invitation); interoperabilitas (OAI-PMH, Crossref, ORCID, ROR, Turnitin, PKP PN, LOCKSS); profil RJI | KB-001 s.d. KB-014 | Definisi *audit trail* formal; kebijakan Permendikbudristek spesifik tentang OA; fitur *Activity Log* OJS secara detail | 2026-07-18 |
| Bab 3 | Definisi manipulasi sitasi (COPE); sejarah Mendeley (2007) & akuisisi Elsevier; praktik sitasi etis | KB-015, KB-016 | Cara mendeteksi *citation rings* secara teknis | 2026-07-18 |
| Bab 2 | DOAJ Principles of Transparency (Identitas Jurnal, Focus & Scope, Transparansi APC, Etika Publikasi); Standar Editorial Board, keragaman afiliasi, larangan dewan fiktif/in-house; Perbedaan Hak Cipta vs Hak Penerbitan; Lisensi CC; Kepemilikan artikel menurut BOAI | KB-017 s.d. KB-023 | Kebijakan privasi, frekuensi terbitan, sponsorship | 2026-07-18 |
| Bab 4 | Controlled Vocabularies vs Author Keywords; Ekstraksi Referensi OJS 3.3; Gaya Selingkung (APA, IEEE, Vancouver); Crossref Reference Linking; Standarisasi Parsing Pustaka | KB-026 s.d. KB-030 | *(semua sub-topik belum diteliti)* | 2026-07-18 |
| Bab 5 | Praktik terbaik Author Guidelines (Template sederhana vs Layout); Masalah umum naskah penulis (line breaks, resolusi gambar, tabel kompleks) | KB-024, KB-025 | *(semua sub-topik belum diteliti)* | 2026-07-18 |
| Bab 10 | Praktik terbaik Author Guidelines (Template sederhana vs Layout) | KB-024 | *(semua sub-topik belum diteliti)* | 2026-07-18 |
| Bab 11 | Praktik terbaik Author Guidelines (Template sederhana vs Layout); Masalah umum naskah penulis (line breaks, resolusi gambar, tabel kompleks) | KB-024, KB-025 | *(semua sub-topik belum diteliti)* | 2026-07-18 |
| Bab 12 | Praktik terbaik Author Guidelines (Template sederhana vs Layout) | KB-024 | *(semua sub-topik belum diteliti)* | 2026-07-18 |
| Bab lainnya | *(belum ada riset)* | — | *(semua sub-topik belum diteliti)* | — |


---

## 5. Prinsip Penulisan yang Harus Dipatuhi di Semua Bab (Gaya Buku Panduan Praktis Profesional)

1. **Gaya Bahasa Praktis Profesional**: Menulis dengan lugas, jelas, dan berorientasi pada tindakan (*action-oriented*). Bahasa harus profesional namun mudah dipahami, tidak kaku seperti jurnal akademis, dan tidak terlalu dramatis seperti buku fiksi.
2. **LARANGAN KERAS PENGGUNAAN NADA "SOK ASIK"**: Dilarang keras menggunakan gaya bahasa yang "sok-sokan", "sok asik", terlalu akrab, atau hiperbolis. Pertahankan nada (*tone*) yang datar, objektif, dan berwibawa.
3. **Gunakan Format Terstruktur**: Sangat dianjurkan menggunakan daftar poin (*bullet points*) dan daftar bernomor (*numbered lists*) untuk merinci langkah-langkah, fitur, atau konsep.
4. **Tidak ada em-dash (—)**: Ganti dengan titik dua atau koma.
5. **Tidak ada emotikon** atau simbol dekoratif di luar kutipan antarmuka sistem.
6. **Tidak ada tanda seru** kecuali dalam kutipan antarmuka sistem OJS.
7. **Label informal dilarang**: Gunakan "Catatan Teknis", "Catatan Penting", "Arahan Editorial", atau "Catatan Kritis".
8. **Fokus pada Kepraktisan**: Penjelasan teori (seperti sejarah atau standar global) harus langsung dikaitkan dengan implikasi praktisnya di lapangan.
9. **Keakuratan Fakta**: Setiap klaim normatif atau definitif wajib disertai sumber (nama, tahun, URL).
10. **Istilah asing ditulis miring (*italic*) pada kemunculan pertama** dan disertai padanan atau penjelasan singkat.
11. **Setiap bab dapat dibaca secara mandiri**.
12. **Setiap bab harus memiliki checklist** di bagian akhir sebelum Ringkasan.
13. **Referensi dari sumber daring** wajib disertai tautan langsung yang dapat diklik.

---

## 6. Konvensi Gambar

Semua gambar di dalam bab menggunakan sintaks:
```markdown
![Keterangan gambar](../img/elementor-placeholder-image.png)
```
Gambar asli belum tersedia. Jangan ubah konvensi ini.

---

## 7. Sumber Referensi Utama yang Sering Dirujuk

| Lembaga / Sumber | URL |
|---|---|
| Public Knowledge Project (PKP / OJS) | https://pkp.sfu.ca/software/ojs/ |
| Directory of Open Access Journals (DOAJ) | https://doaj.org/apply/guide/ |
| Committee on Publication Ethics (COPE) | https://publicationethics.org |
| COPE Peer Reviewer Guidelines | https://publicationethics.org/files/cope-ethical-guidelines-peer-reviewers-v2.pdf |
| Crossref (DOI) | https://www.crossref.org/ |
| Budapest Open Access Initiative (BOAI) | https://www.budapestopenaccessinitiative.org/ |
| JATS (Journal Article Tag Suite) | https://jats.nlm.nih.gov/ |
| Dublin Core Metadata Initiative | https://dublincore.org/ |
| ORCID | https://orcid.org/ |
| Pandoc | https://pandoc.org/ |
| Modul Sumber RJI | Tersedia di `sumber-rji/markdown/` — JANGAN diubah |

---

## 8. Rencana Verifikasi Akhir (setelah semua tahap selesai)

1. Pencarian global untuk memastikan tidak ada em-dash yang tersisa.
2. Pencarian global untuk memastikan tidak ada emotikon yang tersisa.
3. Periksa setiap bab: ada checklist, ada paragraf pengantar konseptual, ada rujukan silang jika relevan.
4. Jalankan `mdbook build` untuk memastikan tidak ada kesalahan format atau tautan rusak.
5. Push ke GitHub dan tunggu deployment otomatis.

---

## 9. Cara Memulai Sesi Kerja Baru

1. Berikan file `konteks.md` ini kepada asisten AI.
2. Sebutkan tahap mana yang ingin dikerjakan dan bab mana yang jadi prioritas.
3. Asisten dapat langsung membuka file bab terkait di `src/` dan mulai bekerja.

Rencana implementasi lengkap tersedia di:
`C:\Users\LENOVO\.gemini\antigravity\brain\52194a1c-5c65-4a49-b4e1-47c1b97a7630\implementation_plan.md`

Bank pertanyaan lapangan per bab tersedia di:
`C:\Users\LENOVO\.gemini\antigravity\brain\52194a1c-5c65-4a49-b4e1-47c1b97a7630\pertanyaan-lapangan.md`

---

## 10. Sistem Agen (Mulai Juli 2026)

Proyek ini menggunakan sistem multi-agen. Dua agen khusus telah didefinisikan:

### Agen 1: `ojs-web-researcher`
**Fungsi**: Melakukan penelusuran web, mengekstrak informasi, dan mengarsipkan ke repositori penelitian.

**Output**:
- `research/knowledge-base.md` — informasi yang diekstrak, dikategorikan, dengan keywords
- `research/bibliography.md` — semua sumber dalam format APA 7, dikelompokkan per tipe sumber

**Cara menggunakan**: Kirim pesan ke agen ini dengan format:
```
Topik: [topik yang ingin diteliti]
Relevansi Bab: [bab mana yang membutuhkan informasi ini]
Fokus: [apa yang ingin dicari — definisi, standar, kasus, regulasi, dll.]
```

### Agen 2: `ojs-book-writer`
**Fungsi**: Menulis dan menyempurnakan bab-bab buku. Membaca knowledge base sebelum menulis. Menambahkan 4 elemen baru ke setiap bab: Pemantik Bab, Catatan dari Lapangan, Sorotan Standar Global, Latihan.

**Cara menggunakan**: Kirim pesan ke agen ini dengan format:
```
Bab: [nomor dan nama bab]
Tugas: [tulis ulang / perkaya / tambahkan elemen X]
Konteks tambahan: [jawaban pertanyaan lapangan jika ada]
```

### Alur Kerja Ideal per Sesi
1. Jalankan `ojs-web-researcher` untuk mengumpulkan informasi bab yang akan dikerjakan.
2. Setelah knowledge base diperbarui, jalankan `ojs-book-writer` untuk mengerjakan bab tersebut.
3. Review hasil dan minta revisi jika perlu.

---

## 11. Struktur Repositori Penelitian

```
research/
├── knowledge-base.md   ← semua informasi yang diekstrak (definisi, standar, kasus, dll.)
└── bibliography.md     ← semua sumber, format APA 7, dikelompokkan per tipe
```

Kedua file ini **tidak boleh diedit secara manual** kecuali untuk koreksi minor. Pengisian dilakukan eksklusif oleh agen `ojs-web-researcher`.
