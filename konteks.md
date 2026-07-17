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

### Tahap 1: Pembersihan Gaya Bahasa [SELESAI]

Semua 13 bab yang ada (bab1 s.d. bab13) telah dibersihkan dari:
- Em-dash (—) → diganti dengan tanda baca yang tepat
- Emotikon (✅, ⚠️, dll)
- Label informal ("Pro-Tip", "Expert Tip") → diganti "Catatan Teknis" / "Catatan Penting"
- Tanda seru yang tidak perlu
- Frasa informal dan retoris tanpa dasar

### Tahap 2: Pendalaman Konten Per Bab [BELUM DILAKUKAN]

Setiap bab perlu diperkaya dengan penambahan materi spesifik berikut:

| Bab | Penambahan yang Diperlukan |
|-----|---------------------------|
| **Bab 3** | Sejarah singkat OJS dan PKP; konsep *Open Access* dan BOAI (2002); kebijakan OA di Indonesia (Permendikbudristek); definisi formal *audit trail*. |
| **Bab 5** | Paragraf pengantar tentang *desk review* sebagai tahap penyaringan pertama; standar DOAJ terkait proses editorial yang terdokumentasi. |
| **Bab 6** | Standar Turnitin/iThenticate yang diterima lembaga indeksasi; panduan COPE tentang penanganan plagiat. |
| **Bab 7** | Standar waktu ulasan DOAJ (4-8 minggu); pembahasan konflik kepentingan sesuai COPE; definisi *reviewer fatigue* dan *information overload*; studi kasus konflik kepentingan. |
| **Bab 8** | Sumber untuk definisi *reviewer*; referensi COPE Ethical Guidelines for Peer Reviewers; standar DOAJ terkait jenis *peer review*; studi kasus reviewer dengan konflik kepentingan. |
| **Bab 9** | Prosedur penanganan reviewer yang bertentangan; kapan perlu reviewer ketiga (*adjudicator*); referensi ke COPE flowchart keputusan editorial. |
| **Bab 10** | Definisi *copyediting* dari literatur penyuntingan; standar DOAJ tentang transparansi proses penyuntingan. |
| **Bab 11** | Penjelasan perangkat galley (Pandoc, plugin XML JATS); penjelasan XML JATS dan kepentingannya untuk PubMed Central dan Scopus; studi kasus peningkatan visibilitas setelah menyediakan galley HTML/XML. |
| **Bab 12** | Penjelasan Crossref sebagai otoritas registrasi DOI; standar DOAJ terkait kepemilikan DOI. |
| **Bab 13** | Subbab standar metadata internasional: Dublin Core, schema.org, JATS; standar DOAJ terkait aksesibilitas metadata; studi kasus artikel sulit ditemukan di Google Scholar akibat metadata buruk. |

### Tahap 3: Aparatus Buku Baru [BELUM DILAKUKAN]

- [ ] Bab 14 (Baru): Diseminasi dan Peningkatan Visibilitas Jurnal
- [ ] Glosarium (`src/glosarium.md`)
- [ ] Daftar Pustaka Terpadu (`src/daftar-pustaka.md`)
- [ ] Penulisan ulang `src/README.md` menjadi Kata Pengantar formal

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
`C:\Users\LENOVO\.gemini\antigravity\brain\04f2e7f7-eb57-4d38-8c02-694939b87052\implementation_plan.md`
