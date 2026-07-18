# AGENTS.md — Aturan Proyek: Buku OJS 3.3

Dokumen ini dibaca otomatis di setiap sesi baru. Ikuti semua instruksi di bawah tanpa perlu diminta.

---

## Protokol Wajib di Awal Setiap Sesi

**BACA FILE-FILE INI SECARA BERURUTAN sebelum melakukan pekerjaan apapun:**

1. `d:\opot\antigravity\modul-ojs-3\konteks.md`
   - Fokus pada bagian: **"Ringkasan Cepat"** (apa yang terakhir dikerjakan dan apa berikutnya)
   - Fokus pada bagian: **"Tahap 2: Tabel Status Per Bab"** (bab mana yang `[ ]`, `[R]`, `[/]`, `[x]`)
   - Fokus pada bagian: **"Knowledge Base: Riwayat Riset per Topik"** (sub-topik apa yang sudah dan belum diteliti per bab)
   
2. `d:\opot\antigravity\modul-ojs-3\research\knowledge-base.md`
   - Baca tabel **"Log Topik yang Sudah Diteliti"** di bagian akhir file
   - Baca entri KB yang relevan dengan bab yang akan dikerjakan

3. `d:\opot\antigravity\modul-ojs-3\src\SUMMARY.md`
   - Berisi: daftar semua bab dan strukturnya

Setelah membaca ketiga file di atas, kamu harus bisa menjawab:
- Bab mana yang sudah selesai, sedang dikerjakan, dan belum dimulai?
- Sub-topik spesifik apa yang sudah diteliti dan belum untuk bab yang akan dikerjakan?
- Apa satu hal paling penting yang perlu dikerjakan sesi ini?

---

## Protokol Wajib di Akhir Setiap Sesi

**Setelah selesai mengerjakan sesuatu, SELALU perbarui `konteks.md` bagian "Status Pengerjaan":**

1. **Ringkasan Cepat**: perbarui tanggal sesi, apa yang dikerjakan, dan apa yang berikutnya
2. **Tabel Status Per Bab**: ubah status bab yang dikerjakan (`[ ]` → `[R]` → `[/]` → `[x]`) dan isi tanggal
3. **Tabel Riwayat Riset per Topik**: 
   - Tambahkan sub-topik baru yang baru saja diteliti ke kolom "Sub-topik Tercakup"
   - Pindahkan dari kolom "Belum Diteliti" ke "Tercakup" untuk sub-topik yang sudah selesai
   - Tambahkan baris baru jika ada bab baru yang mulai diteliti
4. **Jangan lupa** memperbarui tabel "Log Topik" di `research/knowledge-base.md` juga

Tanpa pembaruan ini, sesi berikutnya tidak tahu:
- Sudah sampai mana pengerjaan bab
- Sub-topik mana yang sudah diteliti vs yang masih kosong
- Riset mana yang perlu dilakukan vs yang sudah tersedia di KB

---

## Aturan Perilaku Khusus Agen (Sangat Penting)

1. **JANGAN MENGHAPUS TANPA IZIN**: Agen dilarang keras menghapus instruksi, aturan, poin pedoman, atau informasi lama di dalam *file* konfigurasi, kecuali pengguna secara eksplisit menginstruksikan penghapusan tersebut. Aturan ini KHUSUS untuk file konfigurasi agar memori proyek tidak rusak. Agen tetap leluasa mengedit, memotong, atau merombak isi draf buku (`src/bab*.md`) demi kesesuaian gaya bahasa.
2. **KONFIRMASI TERLEBIH DAHULU**: Jika sebuah instruksi pembaruan dari pengguna berpotensi menimpa atau menghapus aturan krusial yang sudah ada di dalam file konfigurasi, agen **WAJIB** meminta konfirmasi persetujuan terlebih dahulu. Jangan mengambil inisiatif sepihak yang merusak data aturan.

---

## Agen yang Tersedia di Proyek Ini

Dua agen sudah dikonfigurasi. Untuk menggunakannya di sesi baru, baca file konfigurasi lalu panggil `define_subagent`:

### Agen 1: Peneliti Web (ojs-web-researcher)
- Konfigurasi: `d:\opot\antigravity\modul-ojs-3\.agents\skills\ojs-setup\references\researcher-config.md`
- Fungsi: cari informasi di web → tulis ke `research/knowledge-base.md` dan `research/bibliography.md`
- Panggil dengan TypeName: `self`

### Agen 2: Penulis Buku (ojs-book-writer)
- Konfigurasi: `d:\opot\antigravity\modul-ojs-3\.agents\skills\ojs-setup\references\writer-config.md`
- Fungsi: baca knowledge base → tulis/perkaya bab di `src/`
- Panggil dengan TypeName: `self`

**Cara mendefinisikan ulang agen di sesi baru:**
1. Baca file konfigurasi di atas
2. Panggil `define_subagent` dengan nama, deskripsi, dan system_prompt dari file konfigurasi
3. Konfirmasi ke pengguna bahwa agen siap

---

## Prinsip Gaya Bahasa (Berlaku untuk Semua Output)

1. **Gaya Buku Panduan Praktis Profesional**: Tulisan harus jelas, ringkas, profesional, dan berorientasi pada kepraktisan. Hindari bahasa berbunga-bunga, dramatis, atau retoris berlebihan.
2. **LARANGAN KERAS**: Dilarang menggunakan gaya bahasa "sok asik", "sok-sokan", hiperbolis, atau sok akrab. Pertahankan *tone* yang datar, objektif, dan profesional.
3. **Struktur yang Mudah Dipindai (*Skimmable*)**: Sangat dianjurkan menyajikan data, langkah, atau konsep dalam bentuk poin-poin (*bullet points* / *numbered lists*) atau tabel.
4. **Tidak ada em-dash (—)**: Ganti dengan titik dua atau koma.
5. **Tidak ada emotikon** atau simbol dekoratif.
6. **Tidak ada tanda seru** kecuali kutipan antarmuka OJS.
7. **Label informal dilarang**: Gunakan "Catatan Teknis", "Catatan Penting", "Catatan Kritis".
8. **Keakuratan Fakta**: Setiap klaim normatif/definitif wajib bersumber (Nama, Tahun, URL).
9. **Istilah Asing**: Ditulis miring (*italic*) pada kemunculan pertama.
10. **Tautan Langsung**: Semua referensi daring disertai tautan (*link*) yang dapat diklik.

---

## Lokasi File Penting

| File | Lokasi | Fungsi |
|------|--------|--------|
| Konteks proyek | `konteks.md` | Master dokumen, status, cara kerja |
| Knowledge base | `research/knowledge-base.md` | Informasi hasil penelitian web |
| Bibliografi | `research/bibliography.md` | Semua sumber dalam format APA 7 |
| Bab-bab buku | `src/bab*.md` | Konten buku yang dikerjakan |
| Config peneliti | `.agents/skills/ojs-setup/references/researcher-config.md` | System prompt agen peneliti |
| Config penulis | `.agents/skills/ojs-setup/references/writer-config.md` | System prompt agen penulis |
| Implementation plan | `C:\Users\LENOVO\.gemini\antigravity\brain\52194a1c-5c65-4a49-b4e1-47c1b97a7630\implementation_plan.md` | Rencana lengkap transformasi buku |
| Bank pertanyaan | `C:\Users\LENOVO\.gemini\antigravity\brain\52194a1c-5c65-4a49-b4e1-47c1b97a7630\pertanyaan-lapangan.md` | Pertanyaan per bab untuk catatan lapangan |
