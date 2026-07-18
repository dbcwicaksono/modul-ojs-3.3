# Bab 1: Gambaran Umum Alur Kerja Editorial OJS

> *Penerbitan jurnal ilmiah elektronik memerlukan sistem tata kelola yang terstandardisasi. Bab ini menguraikan struktur operasional, evolusi sistem, dan empat fase alur kerja utama pada platform Open Journal Systems (OJS).*

Open Journal Systems (OJS) versi 3.3 adalah perangkat lunak sumber terbuka (*open-source*) yang dirancang secara modular untuk memfasilitasi pengelola jurnal dalam mengatur proses editorial secara sistematis. Memahami alur kerja OJS 3.3 berperan penting dalam memastikan proses penerbitan berjalan dengan transparan, terdokumentasi, dan memenuhi standar integritas akademik.

## 1.1 Fondasi, Evolusi, dan Lanskap Kontemporer OJS

### Latar Belakang: Krisis Publikasi dan Akses Terbuka

Pengembangan OJS berakar dari fenomena krisis jurnal ilmiah (*serials crisis*) pada akhir abad ke-20. Pada periode tersebut, biaya langganan jurnal yang dikuasai penerbit komersial melonjak tajam, sehingga membebani anggaran perpustakaan institusi pendidikan. Kondisi ini membatasi akses publik terhadap hasil penelitian yang mayoritas didanai oleh anggaran publik, karena literatur tersebut terkunci di balik sistem berbayar (*paywall*) komersial (PKP, 2026, https://pkp.sfu.ca/about/).

Situasi ini memicu munculnya gerakan Akses Terbuka (*Open Access*). Merespons kebutuhan infrastruktur untuk penerbitan mandiri, John Willinsky mendirikan Public Knowledge Project (PKP) pada tahun 1998. OJS dirancang sebagai solusi teknis untuk menekan biaya operasional penerbitan jurnal, sehingga memungkinkan institusi pendidikan di seluruh dunia untuk mengelola jurnal secara profesional dan independen.

**Sorotan Standar Global: Budapest Open Access Initiative (BOAI)**

Standar akses terbuka secara formal dikukuhkan melalui Budapest Open Access Initiative (BOAI) pada Februari 2002. BOAI menetapkan bahwa literatur ilmiah harus tersedia secara gratis di internet. Pengguna diizinkan untuk membaca, mengunduh, menyalin, mendistribusikan, atau menautkan teks lengkap artikel tanpa hambatan finansial, hukum, atau teknis di luar batas konektivitas internet.

*Sumber: https://www.budapestopenaccessinitiative.org/read/*

### Arsitektur Teknologi dan Evolusi OJS

Sejak peluncurannya pada tahun 2001, OJS mengalami pembaruan arsitektur untuk menyesuaikan dengan standar keamanan dan kebutuhan pengguna modern:

1. **Era OJS 1.x dan 2.x (2000-an hingga 2016)**
   Versi ini menggunakan arsitektur monolitik berbasis PHP prosedural. OJS 2.x memiliki stabilitas tinggi, namun kaku dalam hal kustomisasi tata letak. Perubahan antarmuka mengharuskan pengelola mengubah kode inti (*core code*), yang berisiko menimbulkan galat sistem.
2. **Perubahan Arsitektur OJS 3.x (2016)**
   Tim PKP melakukan penulisan ulang sistem secara menyeluruh (*total rewrite*). OJS 3.x memisahkan arsitektur *back-end* dan *front-end*, serta mengadopsi kerangka kerja Bootstrap untuk memastikan antarmuka situs responsif di berbagai perangkat. Selain itu, manajemen peran pengguna disatukan dalam satu dasbor, sehingga pengguna tidak perlu berpindah antarmuka (PKP Docs, 2021).
3. **Versi OJS 3.4 dan 3.5 LTS (Kontemporer)**
   Versi dukungan jangka panjang (*Long-Term Support*) berfokus pada optimalisasi Pengalaman Pengguna (*User Experience*) dan kepatuhan regulasi. Dasbor editorial dirancang agar editor dapat memantau seluruh antrean naskah secara komprehensif. OJS 3.5 LTS juga menerapkan fitur undangan pengulas mandiri (*self-invitation*) untuk mematuhi regulasi privasi data global, seperti *General Data Protection Regulation* (GDPR) dari Uni Eropa.

## 1.2 OJS di Indonesia: Konteks Nasional

Hingga tahun 2025, OJS digunakan oleh lebih dari 58.000 jurnal di 156 negara (PKP, 2026). Indonesia tercatat sebagai negara pengguna OJS terbesar di dunia, mencakup sekitar 40% dari total instalasi global. Sebagian besar jurnal di Indonesia beroperasi menggunakan domain institusi (`.ac.id`) dan mengimplementasikan model *Diamond Open Access*, di mana proses publikasi dan akses artikel digratiskan.

Adopsi massal OJS di Indonesia didorong oleh kebijakan Kementerian Pendidikan, Kebudayaan, Riset, dan Teknologi (Kemendikbudristek). Untuk memenuhi syarat akreditasi di portal ARJUNA (Akreditasi Jurnal Nasional) dan sistem pemeringkatan SINTA, pengelola jurnal diwajibkan menggunakan sistem manajemen jurnal elektronik. OJS memenuhi kriteria verifikasi asesor karena kemampuannya merekam riwayat penelaahan (*peer review*) secara transparan.

**Catatan dari Lapangan**

Pada implementasi awal, pengelola baru kerap mengalami kesulitan dalam mengoperasikan antarmuka OJS yang memiliki banyak fitur. Hal ini sering memicu pengelola untuk beralih menggunakan aplikasi pesan instan pihak ketiga (seperti WhatsApp) atau surel pribadi guna berkoordinasi dengan penulis dan pengulas. Praktik komunikasi di luar sistem ini menimbulkan risiko manajerial yang tinggi, yaitu hilangnya riwayat jejak audit (*audit trail*). Saat menjalani evaluasi akreditasi, pengelola jurnal tidak akan dapat melampirkan bukti validitas proses penelaahan naskah apabila riwayat komunikasi tersebut tidak terekam di dalam sistem OJS.

## 1.3 Sistem Manajemen Peran pada Ekosistem OJS

OJS 3.3 memiliki sistem manajemen peran yang fleksibel, memungkinkan pengguna memegang peran ganda (untuk tim kecil) atau membaginya secara spesifik (untuk tim redaksi profesional).

| Peran | Tanggung Jawab Utama |
|-------|---------------------|
| **Journal Editor** | Memiliki akses penuh terhadap pengaturan sistem, mengelola pengguna, dan mengambil keputusan akhir (penerimaan/penolakan) naskah. |
| **Section Editor** | Mengelola lalu lintas naskah pada bagian/rubrik tertentu, mulai dari tahap penugasan pengulas hingga rekomendasi keputusan. |
| **Author** | Mengunggah naskah awal, melengkapi metadata (abstrak, afiliasi), dan melakukan perbaikan sesuai instruksi editor. |
| **Reviewer** | Pakar independen yang bertugas mengevaluasi substansi naskah secara objektif dan memberikan rekomendasi kelayakan. |
| **Copyeditor** | Memeriksa ketepatan tata bahasa, ejaan, dan kesesuaian format referensi dengan gaya selingkung jurnal. |
| **Layout Editor** | Memformat naskah final menjadi dokumen publikasi (*Galleys*) seperti PDF, HTML, atau XML. |
| **Proofreader** | Melakukan verifikasi akhir pada tata letak *Galleys* sebelum artikel diterbitkan secara publik. |

![Ilustrasi: Ekosistem peran dalam OJS](../img/elementor-placeholder-image.png)

## 1.4 Mekanisme Alur Kerja Editorial yang Terintegrasi

OJS mengotomatisasi siklus penerbitan naskah ilmiah melalui empat tahapan utama yang berurutan:

`[Submission] → [Review] → [Copyediting] → [Production]`

1. **Submission (Pengajuan Naskah)**
   Penulis mengirimkan naskah dan memasukkan metadata secara terstruktur. Editor kemudian melakukan tinjauan kelayakan awal (*desk review*). Keputusan di tahap ini meliputi: *Send to Review* (untuk artikel riset), *Accept and Skip Review* (untuk naskah non-riset seperti opini redaksi), atau *Decline Submission*.
2. **Review (Penelaahan Sejawat)**
   Tahap ini mengelola proses evaluasi substansi naskah. OJS memfasilitasi berbagai metode, termasuk *blind review* maupun *open review*. Sistem akan melacak tenggat waktu evaluasi, mengirim peringatan otomatis, dan mendokumentasikan masukan dari pengulas.
3. **Copyediting (Penyuntingan Naskah)**
   Naskah yang telah lolos ulasan diserahkan untuk proses penyuntingan kebahasaan. Komunikasi terkait perbaikan tata bahasa dan format berlangsung di dalam platform hingga naskah mencapai versi final (*clean copy*).
4. **Production (Produksi dan Publikasi)**
   Teks akhir diformat menjadi *Galleys* (PDF/HTML/XML). Setelah pemeriksaan pracetak selesai, editor mendaftarkan artikel tersebut ke dalam daftar isi terbitan (volume dan isu tertentu) untuk dipublikasikan.

## 1.5 Integritas Akademik, Interoperabilitas, dan Preservasi

OJS dirancang agar jurnal dapat terintegrasi dengan ekosistem penelitian global dan menjaga standar etika publikasi melalui fitur-fitur berikut:

* **Interoperabilitas Metadata (OAI-PMH):** OJS menggunakan protokol *Open Archives Initiative Protocol for Metadata Harvesting* (OAI-PMH). Protokol ini memungkinkan basis data eksternal (seperti Google Scholar, DOAJ, dan Garuda) untuk secara otomatis menarik metadata artikel segera setelah dipublikasikan (PKP Docs).
* **Integrasi Infrastruktur Digital:** OJS mendukung aktivasi **DOI (Crossref)** untuk menjamin tautan permanen artikel, **ORCID** untuk memverifikasi profil peneliti, dan **ROR (Research Organization Registry)** untuk standardisasi data afiliasi institusi.
* **Jejak Audit (*Audit Trail*):** Sistem secara otomatis merekam seluruh aktivitas (pengunggahan berkas, korespondensi, dan perubahan status naskah) di dalam *Activity Log*. Catatan ini menjadi bukti validitas operasional saat pengajuan akreditasi atau investigasi etika publikasi.
* **Preservasi Jangka Panjang:** OJS mendukung pengarsipan terdistribusi melalui **LOCKSS** dan **PKP Preservation Network (PKP PN)**. Jaringan *dark archive* ini menjamin artikel tetap tersimpan dan dapat diakses di masa depan meskipun server utama jurnal mengalami gangguan permanen.

## 1.6 Struktur Pembelajaran Kursus

Buku panduan ini menguraikan tahapan manajemen jurnal secara sekuensial berdasarkan alur kerja OJS 3.3:

| Bab | Topik | Tahap OJS |
|-----|-------|-----------|
| Bab 1–2 | Persiapan Dasar | Tahap Pra-OJS |
| Bab 3 | Gambaran Umum | Pengenalan Sistem |
| Bab 4 | Pengajuan Naskah | Tahap Submission |
| Bab 5 | Merespons Naskah | Tahap Submission |
| Bab 6 | Pemeriksaan Plagiasi | Pra-Review |
| Bab 7 | Menugaskan Reviewer | Tahap Review |
| Bab 8 | Panduan Reviewer | Tahap Review |
| Bab 9 | Keputusan Editorial | Tahap Review |
| Bab 10 | Penyuntingan | Tahap Copyediting |
| Bab 11 | Produksi | Tahap Production |
| Bab 12 | Manajemen Edisi | Tahap Publikasi |
| Bab 13 | Manajemen Metadata | Visibilitas |
| Bab 14 | Diseminasi Eksternal | Pasca-Publikasi |

## 1.7 Persiapan Praktik

Untuk memaksimalkan pembelajaran, pengelola disarankan untuk melakukan uji coba pada jurnal simulasi (jurnal percobaan). Latihan pada jurnal simulasi memungkinkan Anda untuk menguji alur kerja lintas peran tanpa berisiko mengubah data atau pengaturan pada sistem jurnal yang berstatus produksi (aktif).

Referensi panduan teknis resmi dapat diakses melalui **PKP Docs** (https://docs.pkp.sfu.ca) dan modul pelatihan daring di **PKP School** (https://pkpschool.sfu.ca).

## Latihan Bab 1

**Latihan 1.1: Identifikasi Jalur Alur Kerja Naskah**

Tinjau tiga jenis naskah di bawah ini. Tentukan tahapan alur kerja mana saja (dari *Submission* hingga *Production*) yang harus dilewati oleh setiap dokumen di dalam sistem OJS.

1. **Artikel Penelitian Empiris** (Naskah utama berisi metode dan hasil riset lapangan).
2. **Catatan Editorial** (Pengantar edisi yang ditulis oleh Editor Kepala, berisi ringkasan topik terbitan berjalan).
3. **Resensi Buku** (Tinjauan singkat atas sebuah buku akademik yang ditulis oleh pakar undangan).

**Panduan Fasilitator**: Diskusikan secara kelompok mengenai penerapan fitur "Accept and Skip Review" pada OJS. Tekankan urgensi penerapan alur *Review* penuh bagi artikel penelitian empiris untuk menjamin standar objektivitas (*peer-review*), serta kapan pengecualian dapat diterapkan secara etis pada naskah non-riset.

## Checklist Bab 1

- [ ] Memahami definisi *serials crisis* dan peran OJS dalam memfasilitasi gerakan Akses Terbuka.
- [ ] Mengetahui urgensi OJS sebagai syarat teknis akreditasi jurnal nasional di Indonesia (ARJUNA/SINTA).
- [ ] Mampu mengidentifikasi urutan keempat tahapan editorial utama (*Submission*, *Review*, *Copyediting*, *Production*).
- [ ] Memahami dampak negatif komunikasi editorial di luar sistem (aplikasi pihak ketiga) terhadap jejak audit (*audit trail*).
- [ ] Mengenali fungsi dasar integrasi standar global seperti OAI-PMH, Crossref, dan PKP PN.

## Ringkasan Bab

Open Journal Systems (OJS) berfungsi sebagai infrastruktur digital komprehensif yang dirancang untuk mendukung penerbitan ilmiah profesional dan dapat diaudit. Dengan memahami arsitektur sistem—yang terbagi dalam fase Pengajuan, Penelaahan, Penyuntingan, dan Produksi—pengelola jurnal dapat memetakan pembagian tugas secara spesifik antarperan. Kepastian alur kerja di dalam OJS menjamin tersedianya jejak audit secara otomatis, memastikan bahwa jurnal mematuhi etika publikasi internasional, serta memenuhi syarat standar akreditasi dan indeksasi global.
