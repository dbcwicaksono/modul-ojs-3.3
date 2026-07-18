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
| I | Persiapan dan Kemampuan Dasar | 1, 2 |
| II | Pengenalan OJS 3.3 | 3 |
| III | Alur Kerja Penulis | 4 |
| IV | Alur Kerja Editorial | 5, 6, 7, 8, 9 |
| V | Pasca-Review, Produksi, dan Penerbitan | 10, 11, 12 |
| VI | Visibilitas dan Indeksasi | 13 |
| VII | Diseminasi dan Peningkatan Visibilitas Jurnal | 14 (BELUM DIBUAT) |
| -- | Glosarium | (BELUM DIBUAT) |
| -- | Daftar Pustaka Terpadu | (BELUM DIBUAT) |

---

## 4. Status Pengerjaan

> **CATATAN UNTUK AI**: Bagian ini adalah "memori" proyek. Selalu perbarui tabel di bawah setelah selesai mengerjakan sesuatu di sesi manapun. Tanpa pembaruan ini, sesi berikutnya tidak tahu sudah sampai mana.

### Ringkasan Cepat (Perbarui Setiap Sesi)

- **Sesi terakhir**: 2026-07-18
- **Dikerjakan**: Penulisan dan penyempurnaan Bab 3 (Gambaran Umum OJS) dengan menambahkan Pemantik Bab, Catatan Lapangan, Latihan, dan subbab konteks OJS di Indonesia.
- **Berikutnya**: Beranjak ke Bab 7 atau bagian Front Matter (README.md, Cara Menggunakan Buku Ini).

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
| **Bab 1** | E-Resources & Penelusuran | `[ ]` | `[ ]` | — |
| **Bab 2** | Bibliografi & Referensi | `[ ]` | `[ ]` | — |
| **Bab 3** | Gambaran Umum OJS | `[R]` KB-001~010 | `[x]` | 2026-07-18 |
| **Bab 4** | Submission (Penulis) | `[ ]` | `[ ]` | — |
| **Bab 5** | Merespons Naskah (Desk Review) | `[ ]` | `[ ]` | — |
| **Bab 6** | Similarity Check | `[ ]` | `[ ]` | — |
| **Bab 7** | Assigning Reviewer | `[ ]` | `[ ]` | — |
| **Bab 8** | Panduan Reviewer | `[ ]` | `[ ]` | — |
| **Bab 9** | Keputusan Editorial | `[ ]` | `[ ]` | — |
| **Bab 10** | Copyediting | `[ ]` | `[ ]` | — |
| **Bab 11** | Produksi & Galley | `[ ]` | `[ ]` | — |
| **Bab 12** | Manajemen Edisi | `[ ]` | `[ ]` | — |
| **Bab 13** | Optimalisasi Metadata | `[ ]` | `[ ]` | — |
| **Bab 14** | Diseminasi (BARU) | `[ ]` | `[ ]` | — |
| Back | Glosarium | `[ ]` | `[ ]` | — |
| Back | Daftar Pustaka Terpadu | `[ ]` | `[ ]` | — |
| Back | Indeks Subjek (BARU) | `[ ]` | `[ ]` | — |
| Back | Tentang Penulis (BARU) | `[ ]` | `[ ]` | — |
| Back | Lampiran (BARU) | `[ ]` | `[ ]` | — |

### Tahap 3: Aparatus Buku Baru [BELUM DIMULAI]

- [ ] Bab 14 (Baru): Diseminasi dan Peningkatan Visibilitas Jurnal
- [ ] Glosarium (perkaya draft yang sudah ada)
- [ ] Daftar Pustaka Terpadu (konsolidasi dari semua bab)
- [ ] Indeks Subjek (`src/indeks-subjek.md`) — baru
- [ ] Tentang Penulis (`src/tentang-penulis.md`) — baru
- [ ] Lampiran (`src/lampiran.md`) — baru

### Knowledge Base: Riwayat Riset per Topik

> **UNTUK AGEN PENELITI**: Sebelum mulai riset, baca tabel ini. Jika sub-topik yang akan diteliti sudah ada di kolom "Sub-topik Tercakup", **jangan teliti ulang** — kecuali pengguna secara eksplisit meminta pendalaman. Cukup rujuk ke nomor KB yang sudah ada.

| Bab | Sub-topik Tercakup | Entri KB | Sub-topik yang Belum Diteliti | Tanggal Terakhir |
|-----|--------------------|----------|-------------------------------|------------------|
| Bab 3 | Definisi & sejarah OJS; sejarah & misi PKP (John Willinsky, 1998); krisis publikasi (serials crisis); statistik global OJS (58.000 jurnal, 156 negara, 2025); definisi Open Access dari BOAI; adopsi OJS di Indonesia (11.000-17.000 instalasi); ekosistem ARJUNA, SINTA, Garuda; PKP School & PKP Docs; evolusi arsitektur OJS 1.x/2.x vs 3.x; OJS 3.4 & 3.5 LTS (GDPR, self-invitation); interoperabilitas (OAI-PMH, Crossref, ORCID, ROR, Turnitin, PKP PN, LOCKSS); profil RJI | KB-001 s.d. KB-014 | Definisi *audit trail* formal; kebijakan Permendikbudristek spesifik tentang OA; fitur *Activity Log* OJS secara detail | 2026-07-18 |
| Bab lainnya | *(belum ada riset)* | — | *(semua sub-topik belum diteliti)* | — |


---

## 5. Prinsip Penulisan yang Harus Dipatuhi di Semua Bab

1. **Tidak ada em-dash (—)**. Ganti dengan titik dua, koma, atau susun ulang kalimat.
2. **Tidak ada emotikon** atau simbol dekoratif di luar kutipan antarmuka sistem.
3. **Tidak ada tanda seru** kecuali dalam kutipan antarmuka sistem OJS.
4. **Setiap klaim normatif atau definitif disertai sumber**, atau diubah menjadi pernyataan prosedural yang dapat diverifikasi.
5. **Gaya bahasa formal dan lugas**. Tidak ada frasa retoris tanpa dasar.
6. **Label informal dilarang**. Gunakan "Catatan Teknis", "Catatan Penting", "Arahan Editorial", atau "Catatan Kritis".
7. **Istilah asing ditulis miring (*italic*) pada kemunculan pertama** dan disertai padanan atau penjelasan singkat.
8. **Setiap bab dapat dibaca secara mandiri**. Rujukan silang ("lihat Bab X") bersifat petunjuk, bukan prasyarat.
9. **Setiap bab harus memiliki checklist** di bagian akhir sebelum Ringkasan.
10. **Referensi dari sumber daring** wajib disertai tautan langsung yang dapat diklik.

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
