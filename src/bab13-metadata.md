# Bab 13: Optimalisasi Metadata Artikel

Metadata adalah fondasi dari visibilitas dan kemampuan artikel untuk ditemukan (*discoverability*) di era digital. Metadata yang lengkap, akurat, dan konsisten menentukan seberapa mudah artikel Anda dapat ditemukan, dikutip, dan diindeks oleh mesin pencari dan basis data ilmiah.

> **Metadata adalah tanggung jawab bersama** antara editor dan penulis. Kesalahan metadata dapat berdampak serius — mulai dari distribusi DOI yang gagal hingga sitasi yang salah di Google Scholar.

---

## 13.1 Pengertian Metadata Artikel

**Metadata** adalah data yang mendeskripsikan data lain — dalam konteks artikel ilmiah, metadata adalah informasi *tentang* artikel: pengarang, judul, abstrak, kata kunci, tanggal publikasi, DOI, dan sebagainya.

Fungsi utama metadata dalam publikasi ilmiah:

1. **Penemuan Sumber (*Resource Discovery*)** — Memungkinkan mesin pencari dan database menemukan artikel.
2. **Kemudahan Sitasi** — Memudahkan software manajemen referensi (Mendeley, Zotero) mengambil data bibliografi secara otomatis.
3. **Indeksasi** — Memudahkan lembaga pengindeks (Scopus, WoS, DOAJ) memproses artikel.
4. **Distribusi DOI** — Metadata yang benar memastikan DOI artikel terdistribusi dengan tepat ke Crossref.

> **Ingat:** Mengubah metadata artikel *setelah* terbit (terutama tanggal) dapat merubah data di Google Scholar dan mesin pengindeks lain. Pastikan semua data sudah benar **sebelum** artikel diterbitkan.

---

## 13.2 Pengaturan Metadata di OJS 3 (Konfigurasi Awal)

Sebelum metadata artikel dapat diisi dengan lengkap, pengelola jurnal perlu melakukan beberapa pengaturan di tingkat sistem:

### A. Basic Journal Identity (Masthead)

**OJS 3.0–3.1 & 3.2–3.3:**
```
Login Journal Manager → Settings → Journal → Masthead
```
Isi nama jurnal, ISSN, dan informasi dasar lainnya. Data ini akan digunakan sebagai dasar metadata di semua artikel.

### B. Submission Metadata

**OJS 3.0–3.1:**
```
Login Journal Manager → Settings → Workflow → Submission → Submission Metadata
```

**OJS 3.2–3.3:**
```
Login Journal Manager → Settings → Workflow → Submission → Metadata
```

Di sini, Journal Manager mengaktifkan (*centang*) field metadata apa saja yang dapat diisi penulis saat submission — misalnya: kata kunci, abstrak, agensi pendukung, dll.

### C. Copyright dan Lisensi

**OJS 3.0–3.1:**
```
Login Journal Manager → Settings → Distribution → Permissions
```

**OJS 3.2–3.3:**
```
Login Journal Manager → Settings → Distribution → License
```

Atur pemegang hak cipta (jurnal atau penulis) dan jenis lisensi (mis. Creative Commons).

### D. Section Artikel

```
Login Journal Manager → Settings → Journal → Sections
```
Buat dan kelola bagian-bagian jurnal (Articles, Reviews, Notes, dll.).

### E. Plugin Tambahan

**Plugin Funding** (mendukung pencatatan hibah/pendanaan penelitian):
```
Login Journal Manager → Settings → Website → Plugins → Funding Plugin → Enable
```

**Plugin Crossref Reference Linking** (menghubungkan referensi dengan DOI secara otomatis):
```
Login Journal Manager → Settings → Website → Plugins → Crossref Reference Linking Plugin → Enable
```

---

## 13.3 Struktur Metadata Artikel OJS 3

Metadata artikel di OJS 3 terdiri dari beberapa bagian. Berikut panduan lengkap untuk setiap bagian:

### A. Title and Abstract (Judul dan Abstrak)

Isian wajib: **Prefix**, **Title**, **Subtitle**, **Abstract**.

**Panduan Judul:**
- Ditulis dalam format **Sentence case** atau **Title Case** — BUKAN huruf kapital semua.
- Singkat dan merupakan *highlight* dari temuan penelitian.
- Judul artikel ≠ judul penelitian. Judul artikel adalah "iklan" dari keseluruhan isi.
- Cek konsistensi: judul di metadata harus **sama persis** dengan judul di file PDF.

**Checklist Judul:**
- [ ] Judul ditulis dalam Sentence case / Title Case.
- [ ] Judul di metadata identik dengan judul di file PDF.
- [ ] Tidak mengandung singkatan yang tidak umum.

**Panduan Abstrak:**
- Ditulis dalam **bahasa Inggris** saja (untuk jurnal internasional).
- **1 paragraf**, tidak lebih dari **250 kata**.
- Harus memuat: tujuan penelitian, metode, populasi/sampel, hasil, dan kesimpulan.
- **Jangan** memasukkan kata kunci di dalam kolom abstrak.
- **Jangan** menuliskan "Abstract" sebagai awalan di dalam kolom abstrak.

**Checklist Abstrak:**
- [ ] Dalam bahasa Inggris.
- [ ] 1 paragraf, maksimal 250 kata.
- [ ] Memuat tujuan, metode, hasil, dan kesimpulan.
- [ ] Tidak ada kata kunci di dalam kolom abstrak.

---

### B. Contributors (Data Penulis)

Isian penting: **Given Name**, **Family Name**, **Email**, **Country**, **Affiliation**, **ORCID**, **Role**.

**Panduan Penulisan Nama Penulis:**

| Nama | Given Name (Depan) | Family Name (Belakang) |
|------|---------------------|------------------------|
| Soekarno *(1 suku kata)* | S | Soekarno |
| Soekarno *(alternatif)* | Soekarno | Soekarno |
| Asep Erlan Maulana | Asep Erlan | Maulana |
| Andista Candra Yusro | Andista Candra | Yusro |
| Faradila Hasan | Faradila | Hasan |

> **Catatan:** Untuk nama dengan 3 kata atau lebih, pastikan *Family Name* hanya terdiri dari **1 kata**. Jangan mengisi *Middle Name* jika tidak diperlukan. Jangan isi kolom kosong dengan tanda (-).

**Checklist Penulis:**
- [ ] Jumlah penulis di metadata sama dengan di fulltext.
- [ ] Nama ditulis dengan benar (huruf kapital di awal setiap kata — *Title Case*).
- [ ] Email penulis aktif (sebaiknya email institusi).
- [ ] Afiliasi lengkap dan konsisten (nama departemen, institusi, kota, negara).
- [ ] Country sudah dipilih.
- [ ] ORCID ID sudah dimasukkan jika tersedia (**sangat dianjurkan**).

**Tentang ORCID:**

ORCID (Open Researcher and Contributor ID) adalah pengenal digital persisten yang membedakan seorang peneliti dari peneliti lain. Manfaatnya:
- Menghubungkan peneliti dengan seluruh publikasi, hibah, dan afiliasi mereka.
- Mengurangi risiko kesalahan identifikasi penulis.
- Meningkatkan visibilitas dan rekam jejak akademik.

Daftarkan ORCID gratis di [orcid.org](https://orcid.org).

---

### C. Metadata (Kata Kunci & Pendanaan)

**Kata Kunci (*Keywords*):**
- Masukkan kata kunci satu per satu, akhiri setiap kata kunci dengan menekan **Enter** (bukan koma atau titik koma).
- Ini memastikan setiap kata kunci tersimpan sebagai tag terpisah untuk fungsi pencarian *faceted search* di website jurnal.

**Supporting Agencies (Pendanaan):**
- Isi dengan nama organisasi yang memberikan pendanaan riset.
- Jika ada dana hibah, masukkan juga di **Funding Plugin** jika tersedia.
- Informasi pendanaan juga harus masuk dalam XML yang disetor ke Crossref.

---

### D. References (Daftar Pustaka)

Masukkan seluruh daftar pustaka artikel ke dalam kolom References di metadata.

**Panduan pengisian:**
- Copy-paste dari file **Docx** (bukan PDF) untuk menghindari kesalahan karakter.
- Pisahkan setiap entri referensi dengan **baris kosong**.
- Lebih baik jika setiap referensi dilengkapi dengan **tautan DOI atau URL**.

**Perlu dilakukan 2 kali checking:**
1. Saat artikel pertama kali diterima (*pre-copyediting*).
2. Saat artikel akan diterbitkan (*pre-production*).

---

### E. Identifiers (DOI)

**Cara meng-assign DOI:**
1. Pastikan pengaturan DOI sudah diset melalui:
   ```
   Login Journal Manager → Settings → Website → Plugins → Public Identifier Plugins → DOI → Settings
   ```
2. Masuk ke halaman naskah → tab Publication → submenu Identifiers.
3. Klik **"Assign"** di sebelah kolom DOI untuk meng-generate nomor DOI sesuai pola yang ditetapkan.
4. Verifikasi nomor DOI sudah sesuai pola jurnal.

**Deposit DOI ke Crossref:**
```
Login Journal Manager → Tools → Import/Export → Crossref XML Export Plugin → Settings
```
Masukkan akun Crossref (username dan password) yang diberikan oleh Crossref.

---

### F. Galleys

Pengelola jurnal mengunggah file PDF (dan format lain) hasil akhir dari proses produksi pada bagian ini. Galley adalah representasi final artikel yang akan diunduh pembaca.

---

### G. Permission and Disclosure

| Field | Yang Harus Diverifikasi |
|-------|------------------------|
| **Copyright Holder** | Nama jurnal (atau nama penulis jika hak cipta ada di penulis). Harus sesuai dengan nama pada ISSN. |
| **License** | Pilihan lisensi (biasanya terisi otomatis berdasarkan pengaturan jurnal). |
| **License URL** | URL lisensi (biasanya otomatis). |
| **Copyright Year** | Tahun terbit (biasanya otomatis — perlu diperhatikan untuk artikel *back issue*). |

---

### H. Issue (Penempatan Artikel)

Di bagian ini, editor dapat:
- Memilih atau mengganti **Issue** (edisi) tempat artikel akan ditempatkan.
- Memilih **Section** (bagian jurnal).
- Mengunggah **Cover Image** khusus untuk artikel.
- Mengatur **Pages** (nomor halaman).
- Mengatur **URL Path** kustom.
- Mengatur **Date Published** (penting untuk artikel *back issue*).

> Setelah semua perubahan dilakukan, jangan lupa klik **Save**.

---

## 13.4 Cara Edit Metadata di OJS 3.2 dan 3.3 (Sebelum Terbit)

**Prosedur standar edit metadata sebelum publikasi:**

1. Login sebagai Editor.
2. Masuk ke **Submissions → My Queue**.
3. Pilih artikel yang akan diedit, klik **View**.
4. Klik tab **Publication**.
5. Edit metadata yang diperlukan di sub-tab yang sesuai.
6. Klik **Save** setelah setiap perubahan.

---

## 13.5 Cara Edit Metadata Artikel yang Sudah Terbit (OJS 3.2 & 3.3)

> **Perhatian:** Pada OJS 3.2 dan 3.3, mengedit metadata artikel yang sudah terbit **memerlukan proses unpublish terlebih dahulu**. Berbeda dengan OJS 3.0 dan 3.1 yang dapat mengedit tanpa unpublish (namun ini juga tidak disarankan).

**Prosedur:**
1. Login sebagai Editor.
2. Masuk ke **Issues → Back Issues**.
3. Klik nama edisi yang berisi artikel.
4. Klik judul artikel yang akan diedit.
5. Anda akan diarahkan ke halaman alur kerja artikel tersebut.
6. Klik tab **Publication** untuk mengedit metadata.

---

## Checklist Lengkap Metadata Artikel

Gunakan checklist komprehensif ini sebelum menerbitkan setiap artikel:

**Judul & Abstrak:**
- [ ] Judul Sentence case / Title Case, konsisten dengan PDF.
- [ ] Abstrak bahasa Inggris, 1 paragraf, maks 250 kata.
- [ ] Tidak ada kata kunci di dalam kolom abstrak.

**Penulis:**
- [ ] Jumlah penulis sama dengan di fulltext.
- [ ] Nama penulis benar dan konsisten.
- [ ] Afiliasi lengkap (departemen, institusi, kota, negara).
- [ ] Email aktif tersedia.
- [ ] ORCID dimasukkan (jika ada).

**Metadata:**
- [ ] Kata kunci dimasukkan per tag (satu per satu, tekan Enter).
- [ ] Pendanaan/hibah dicantumkan (jika ada).

**References:**
- [ ] Semua referensi sudah dimasukkan.
- [ ] Setiap referensi dipisahkan dengan baris kosong.
- [ ] DOI/URL referensi sudah dicantumkan.

**Identifiers:**
- [ ] DOI sudah ter-assign sesuai pola.

**Permissions:**
- [ ] Copyright holder benar.
- [ ] Lisensi sudah dipilih.
- [ ] Tahun copyright sesuai tahun terbit.

**Issue:**
- [ ] Edisi dan bagian (*section*) sudah dipilih.
- [ ] Nomor halaman sudah diisi.
- [ ] Tanggal terbit sudah benar.

---

## Ringkasan Bab

Metadata yang optimal adalah investasi jangka panjang untuk visibilitas jurnal. Setiap editor harus menganggap pengisian metadata bukan sebagai formalitas belaka, melainkan sebagai **penjaga gerbang kredibilitas jurnal** — karena metadata yang buruk berarti artikel yang susah payah dihasilkan penulis tidak akan dapat ditemukan oleh siapapun.

> **Prinsip Utama:** Periksa, verifikasi, dan konfirmasi semua metadata **sebelum** artikel diterbitkan. Lebih mudah memperbaiki sebelum terbit daripada sesudahnya.
