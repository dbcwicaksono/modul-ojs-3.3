# Rencana Penyusunan Buku Panduan OJS 3 (Revisi)

Dokumen ini adalah revisi rencana penyusunan berdasarkan perubahan sumber referensi. Kita sekarang akan menggabungkan materi dari folder `sumber-pkp` (sebagai tulang punggung manajemen OJS) dengan materi spesifik dari folder `markdown` (File 1, 2, 3, dan 9), serta menyisipkan hal-hal penting dari file 4-7 `markdown` jika tidak ada di PKP. File 8 `markdown` diabaikan.

## Analisis Sumber Baru

**Sumber Utama Manajemen OJS (`sumber-pkp`):**
- Berisi 10 Modul yang menjelaskan sangat runut alur kerja OJS 3.3 (dari perspektif Author, Editor, dan Reviewer).

**Sumber Spesifik Tambahan (`markdown`):**
- `1. Modul_Artikel_Metadata.md` (Penting untuk Indeksasi)
- `2. Bibliography_Basic.md` (Dasar Analisis Subjek)
- `3. Reference_Tools_Manager.md` (Pengelolaan e-Resources/Mendeley/Zotero)
- `9. similarity-check.md` (Pengecekan Plagiasi)
- File 4, 5, 6, 7 akan dicek sebagai pelengkap Modul PKP.

## Proposed Changes (Rencana Struktur Bab Baru)

Berikut adalah usulan struktur buku yang menggabungkan seluruh sumber di atas secara logis:

### Bagian I: Persiapan dan Kemampuan Dasar
- **Pengantar**
- **Bab 1: Pengelolaan e-Resources & Manajemen Referensi** (Dari `markdown` file 3)
- **Bab 2: Analisis Subjek & Bibliografi** (Dari `markdown` file 2)

### Bagian II: Pengenalan OJS 3.3
- **Bab 3: Gambaran Umum Alur Kerja Editorial OJS** (Dari `sumber-pkp` Modul 1 & 2)

### Bagian III: Alur Kerja Penulis (Author)
- **Bab 4: Panduan Lengkap Mengirimkan Artikel (Submission)** (Dari `sumber-pkp` Modul 3)

### Bagian IV: Alur Kerja Editorial (Pre-Review & Review)
- **Bab 5: Merespons Kiriman Naskah Baru** (Dari `sumber-pkp` Modul 4 + Pelengkap `markdown` file 4 & 5)
- **Bab 6: Pengecekan Plagiasi (Similarity Check)** (Dari `markdown` file 9)
- **Bab 7: Menugaskan Peninjau (Assigning Reviewer)** (Dari `sumber-pkp` Modul 5)
- **Bab 8: Panduan Peninjau (Langkah Reviewer)** (Dari `sumber-pkp` Modul 6)
- **Bab 9: Merespons Hasil Ulasan (Editorial Decision)** (Dari `sumber-pkp` Modul 7)

### Bagian V: Pasca-Review, Produksi, dan Penerbitan
- **Bab 10: Tahap Penyuntingan Naskah (Copyediting)** (Dari `sumber-pkp` Modul 8 + Pelengkap `markdown` file 6)
- **Bab 11: Tahap Produksi (Layout & Galley)** (Dari `sumber-pkp` Modul 9 + Pelengkap `markdown` file 6)
- **Bab 12: Manajemen Edisi (Issue) & Pasca Penerbitan** (Dari `sumber-pkp` Modul 10 + Pelengkap `markdown` file 7)

### Bagian VI: Visibilitas & Indeksasi
- **Bab 13: Optimalisasi Metadata Artikel** (Dari `markdown` file 1)

## User Review Required

> [!IMPORTANT]
> Mohon tinjau restrukturisasi di atas. Struktur ini merajut alur kerja bawaan PKP yang sangat rapi (10 modul) dengan kompetensi tambahan dari file markdown (seperti e-Resources, Similarity Check, dan Metadata) sehingga menjadi satu buku yang utuh dan komprehensif.

## Verification Plan
Jika disetujui:
1. Saya akan memperbarui file `src/SUMMARY.md` dan `task.md`.
2. Mulai menulis Bab 1 (dari file 3 markdown).
3. Untuk bab yang membutuhkan penggabungan (seperti Bab 5, 10, 11, 12), saya akan membaca kedua sumber (PKP dan Markdown) lalu menggabungkan informasinya agar tidak ada yang terlewat.
