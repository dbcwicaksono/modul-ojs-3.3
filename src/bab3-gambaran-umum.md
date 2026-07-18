# Bab 3: Gambaran Umum Alur Kerja Editorial OJS

> *Bagaimana perangkat lunak bersumber terbuka dapat berkembang menjadi infrastruktur utama bagi puluhan ribu jurnal di seluruh dunia, termasuk di Indonesia?*

Open Journal Systems (OJS) versi 3.3 adalah perangkat lunak sumber terbuka (*open-source*) yang dirancang secara modular untuk membantu pengelola jurnal mengelola proses editorial secara sistematis. Memahami alur kerja editorial OJS 3.3 berperan penting dalam memastikan setiap naskah dikelola dengan transparansi dan integritas akademik yang memadai.

## 3.1 Fondasi, Evolusi, dan Lanskap Kontemporer OJS

### Akar Filosofis: Krisis Publikasi dan Lahirnya Gerakan Akses Terbuka

Pengembangan Open Journal Systems (OJS) berakar dari kondisi krisis jurnal ilmiah (*serials crisis*) pada akhir abad ke-20. Pada periode tersebut, biaya berlangganan jurnal komersial meningkat secara signifikan dan membebani anggaran perpustakaan institusi pendidikan. Kondisi ini membatasi aksesibilitas publik terhadap hasil penelitian yang sebagian besar didanai oleh anggaran publik, karena literatur tersebut terkunci di balik sistem berbayar (*paywall*) (PKP, 2026, https://pkp.sfu.ca/about/). 

Situasi tersebut memicu lahirnya gerakan akses terbuka (*open access*), yang bertujuan menyediakan akses literatur ilmiah secara gratis di internet. Merespons kebutuhan ini, John Willinsky mendirikan Public Knowledge Project (PKP) pada tahun 1998 di University of British Columbia. Tujuan utama PKP adalah mendemokrasikan pengetahuan dengan mempermudah penerbitan ilmiah secara mandiri. OJS, yang diluncurkan pada tahun 2001, dikembangkan sebagai sarana teknis untuk mewujudkan tujuan tersebut. Platform ini menekan biaya operasional penerbitan dan memfasilitasi institusi pendidikan, termasuk di negara-negara berkembang, untuk mengelola jurnal dengan standar kualitas yang tinggi.

**Sorotan Standar Global: Budapest Open Access Initiative (BOAI)**

Landasan filosofis akses terbuka secara formal dikukuhkan melalui Budapest Open Access Initiative (BOAI) pada Februari 2002. BOAI mendefinisikan akses terbuka sebagai ketersediaan literatur ilmiah secara gratis di internet publik. Definisi ini mengizinkan pengguna membaca, mengunduh, menyalin, mendistribusikan, mencari, atau menautkan ke teks lengkap artikel tanpa hambatan finansial, hukum, atau teknis, selain batas konektivitas internet.

*Sumber: https://www.budapestopenaccessinitiative.org/read/*

### Arsitektur Teknologi dan Jejak Evolusi Generasi OJS

Sejak peluncurannya, arsitektur teknologi OJS terus berevolusi merespons tuntutan standar keamanan, kemudahan penggunaan, dan komputasi modern:

1. **Era OJS 1.x dan 2.x (Awal 2000-an hingga 2016)**: Versi awal ini menggunakan arsitektur monolitik berbasis PHP prosedural. OJS 2.x menawarkan stabilitas operasional yang tinggi dan menjadi sistem utama bagi banyak jurnal, namun memiliki keterbatasan dalam penyesuaian tata letak antarmuka. Perubahan tata letak mengharuskan modifikasi pada kode inti sistem, yang berisiko menimbulkan galat saat pembaruan versi dilakukan.
2. **Perubahan Arsitektur OJS 3.x (2016)**: PKP melakukan penulisan ulang sistem secara menyeluruh untuk memisahkan pengolahan data (*back-end*) dan antarmuka pengguna (*front-end*). OJS 3.x mengadopsi kerangka Bootstrap untuk menghasilkan tampilan situs yang responsif pada berbagai ukuran layar. Versi ini juga mengintegrasikan sistem peran dalam satu dasbor terpadu, menghilangkan keharusan bagi pengguna untuk berpindah antarmuka saat menjalankan peran yang berbeda (PKP Docs, 2021).
3. **Versi OJS 3.4 dan 3.5 LTS**: Versi terbaru dan versi dukungan jangka panjang (*Long-Term Support*) berfokus pada peningkatan antarmuka pengguna dan kepatuhan terhadap regulasi pelindungan data global. Dasbor editorial dirancang ulang untuk memfasilitasi pemantauan seluruh naskah dalam satu tampilan layar. Sistem ini juga mengimplementasikan fitur persetujuan mandiri (*self-invitation*) untuk memenuhi standar privasi data seperti *General Data Protection Regulation* (GDPR) dari Uni Eropa.

## 3.2 OJS di Indonesia: Konteks Nasional

Berdasarkan data tahun 2025, OJS digunakan oleh lebih dari 58.000 jurnal di 156 negara. Indonesia menempati posisi sentral sebagai negara pengguna OJS terbesar di dunia, dengan proporsi instalasi mencapai 40% dari total instalasi global (PKP, 2026). Sebagian besar instalasi ini beroperasi menggunakan domain institusi akademik (`.ac.id`) dan mengadopsi model *Diamond Open Access*, yaitu publikasi yang tidak membebankan biaya kepada penulis maupun pembaca.

Tingginya tingkat adopsi OJS di Indonesia terkait dengan kebijakan standardisasi dari Kementerian Pendidikan, Kebudayaan, Riset, dan Teknologi (Kemendikbudristek). Untuk memenuhi kriteria pada portal ARJUNA (Akreditasi Jurnal Nasional) dan meraih peringkat SINTA (S1 hingga S6), pengelola jurnal diwajibkan menyelenggarakan proses editorial secara elektronik. OJS memenuhi spesifikasi yang dibutuhkan oleh asesor akreditasi, termasuk transparansi riwayat penelaahan sejawat dan integrasi pengindeksan dengan portal Garuda (Garba Rujukan Digital). Komunitas independen seperti Relawan Jurnal Indonesia (RJI) berperan memberikan bimbingan teknis bagi pengelola jurnal lokal dalam implementasi dan standardisasi OJS di lingkungan akademik.

**Catatan dari Lapangan**

Berdasarkan temuan di berbagai lokakarya pengelolaan jurnal, pengguna baru kerap mengalami kebingungan saat pertama kali mengoperasikan dasbor OJS yang sarat fitur. Keterbatasan pemahaman teknis ini sering kali memicu pengelola jurnal untuk memindahkan komunikasi dengan penulis atau mitra bestari ke aplikasi pesan singkat atau surel pribadi. Praktik di luar sistem ini berakibat fatal pada hilangnya riwayat jejak audit (*audit trail*). Akibatnya, jurnal tidak dapat menyediakan bukti terdokumentasi mengenai proses penilaian naskahnya saat menjalani evaluasi akreditasi.

## 3.3 Para Aktor dalam Ekosistem Jurnal OJS

Proses penerbitan jurnal dikelola melalui pembagian tanggung jawab. OJS 3.3 menyediakan sistem peran yang fleksibel; pengguna dapat memegang beberapa peran secara merangkap atau membaginya secara spesifik dalam tim editorial.

| Peran | Tanggung Jawab Utama |
|-------|---------------------|
| **Journal Editor** *(Editor Jurnal)* | Memiliki kendali penuh atas sistem dan kebijakan jurnal. Bertanggung jawab mengelola akun pengguna dan mengambil keputusan akhir terhadap kelayakan naskah. |
| **Section Editor** *(Editor Bagian)* | Mengelola naskah pada ruang lingkup atau rubrik tertentu. Mengawasi alur naskah dari tahap penelaahan sejawat hingga penetapan keputusan editorial. |
| **Author** *(Penulis)* | Mendaftarkan naskah, mengelola kelengkapan metadata, dan melakukan perbaikan berdasarkan instruksi editorial. |
| **Reviewer** *(Mitra Bestari)* | Ahli di bidang terkait yang melakukan penelaahan sejawat secara objektif dan memberikan rekomendasi kelayakan naskah kepada editor. |
| **Copyeditor** *(Penyunting Naskah)* | Memeriksa ketepatan bahasa, konsistensi terminologi, dan kesesuaian format teks dengan gaya selingkung jurnal. |
| **Layout Editor** *(Editor Tata Letak)* | Memproses naskah final menjadi format siap terbit atau *Galleys* (PDF, HTML, XML). |
| **Proofreader** *(Pemeriksa Pracetak)* | Melakukan verifikasi akhir pada dokumen *Galley* sebelum dipublikasikan. |

![Ilustrasi: Ekosistem peran dalam OJS](../img/elementor-placeholder-image.png)

## 3.4 Mekanisme Alur Kerja Editorial yang Terintegrasi

OJS memiliki kemampuan mengotomatisasi siklus penerbitan naskah ilmiah. Alur kerja dalam OJS 3.3 dibagi menjadi empat fase utama yang saling terhubung secara terstruktur:

`[Submission] → [Review] → [Copyediting] → [Production]`

### Tahap 1: Submission (Pengajuan Naskah)

Penulis menyerahkan naskah beserta kelengkapan metadata, seperti abstrak, daftar penulis, dan rujukan, melalui antarmuka pendaftaran. Editor jurnal akan melakukan penilaian kelayakan awal (*desk review*) dan merespons pengajuan dengan tiga pilihan tindakan:
1. **Send to Review**: Meneruskan naskah ke tahap penelaahan sejawat jika naskah memenuhi kriteria dasar jurnal.
2. **Accept and Skip Review**: Memindahkan naskah langsung ke tahap penyuntingan tanpa ulasan sejawat (berlaku untuk teks non-riset seperti editorial atau ulasan buku).
3. **Decline Submission**: Menolak naskah apabila di luar ruang lingkup keilmuan atau tidak memenuhi kelayakan akademis dasar.

### Tahap 2: Review (Penelaahan Sejawat)

Tahap penelaahan memfasilitasi evaluasi substansi naskah. OJS memfasilitasi metode penelaahan nirnama ganda (*double-blind review*) maupun penelaahan terbuka. Sistem secara otomatis mencatat tenggat waktu, mengelola notifikasi, dan merekam hasil tinjauan. Berdasarkan penilaian mitra bestari, editor menetapkan keputusan akhir berupa penerimaan (*Accept*), permintaan revisi minor atau mayor (*Revisions Required / Resubmit for Review*), maupun penolakan (*Decline*).

### Tahap 3: Copyediting (Penyuntingan Naskah)

Naskah yang diterima secara substansi akan dievaluasi ketepatan kebahasaan dan disesuaikan dengan format penerbitan. Proses ini melibatkan pertukaran draf antara editor, penyunting, dan penulis melalui fasilitas diskusi di dalam sistem, hingga seluruh revisi tata bahasa dan tata letak disetujui.

### Tahap 4: Production (Produksi dan Publikasi)

Teks yang telah disetujui akan diubah menjadi format cetak digital akhir (*Galleys*) seperti PDF, HTML, atau JATS XML. Sesudah proses verifikasi pracetak (*proofreading*), editor menempatkan artikel pada nomor edisi tertentu, mengatur urutan publikasi, dan mempublikasikan terbitan ke portal publik.

## 3.5 Integritas Akademik, Interoperabilitas, dan Preservasi

Sistem penerbitan jurnal modern membutuhkan integrasi data dengan infrastruktur pengindeksan global. OJS memfasilitasi kebutuhan ini melalui berbagai fitur bawaan dan protokol standar:

1. **Protokol OAI-PMH**: OJS menggunakan *Open Archives Initiative Protocol for Metadata Harvesting* (OAI-PMH). Protokol ini memungkinkan basis data eksternal, seperti Google Scholar dan Directory of Open Access Journals (DOAJ), untuk membaca dan menyalin metadata artikel secara otomatis (PKP Docs).
2. **Integrasi Ekosistem Riset**: OJS mendukung konektivitas dengan infrastruktur publikasi internasional, seperti registrasi **DOI (Crossref)** untuk menjamin identitas permanen artikel, **ORCID** untuk memverifikasi profil unik penulis, dan **ROR (Research Organization Registry)** untuk standardisasi data institusi afiliasi penulis.
3. **Jejak Audit (Audit Trail)**: Seluruh tindakan operasional dalam sistem direkam ke dalam *Activity Log* kronologis. Pendokumentasian otomatis ini berfungsi sebagai alat pembuktian yang valid untuk mendemonstrasikan transparansi manajerial kepada asesor maupun untuk kebutuhan penelusuran jika terjadi pelanggaran etik publikasi.
4. **Keamanan Preservasi Digital**: OJS memfasilitasi pengarsipan jangka panjang (*dark archive*) menggunakan teknologi **LOCKSS** (*Lots of Copies Keep Stuff Safe*) dan **PKP Preservation Network (PKP PN)**. Layanan ini dirancang untuk memastikan arsip jurnal tetap utuh dan tersedia di pangkalan data cadangan meskipun layanan situs jurnal utama mengalami kegagalan teknis secara permanen.

## 3.6 Struktur Pembelajaran Kursus

Buku panduan ini disusun agar merefleksikan tahapan kerja pada OJS 3.3 secara kronologis dan mempertimbangkan berbagai peran pengguna:

| Bab | Topik | Tahap OJS / Peran |
|-----|-------|-----------|
| Bab 1–2 | Persiapan dan Kemampuan Dasar | Pra-OJS (Keterampilan Esensial) |
| Bab 3 | Gambaran Umum OJS | Pengenalan |
| Bab 4 | Panduan Mengirimkan Artikel | Tahap Submission (Sudut pandang Penulis) |
| Bab 5 | Merespons Naskah Baru | Tahap Submission (Sudut pandang Editor) |
| Bab 6 | Pemeriksaan Plagiasi | Pra-Review (Integritas Akademik) |
| Bab 7 | Menugaskan Reviewer | Tahap Review (Sudut pandang Editor) |
| Bab 8 | Panduan Reviewer | Tahap Review (Sudut pandang Mitra Bestari) |
| Bab 9 | Merespons Hasil Ulasan | Tahap Review (Keputusan Akhir Editor) |
| Bab 10 | Penyuntingan Naskah (Copyediting) | Tahap Copyediting |
| Bab 11 | Produksi dan Galley | Tahap Production |
| Bab 12 | Manajemen Edisi | Publikasi Pasca-Produksi |
| Bab 13 | Optimalisasi Metadata | Visibilitas dan Indeksasi |
| Bab 14 | Diseminasi dan Peningkatan Visibilitas | Diseminasi Pasca-Terbit |

## 3.7 Persiapan Sebelum Memulai

Sebelum menerapkan pengelolaan jurnal menggunakan instalasi utama, pengelola sangat disarankan menyiapkan jurnal simulasi atau lingkungan percobaan. Fasilitas ini penting untuk menguji fungsi lintas peran dan melatih simulasi keputusan tanpa risiko merusak integritas basis data jurnal yang beroperasi.

PKP menyediakan dokumentasi resmi melalui portal **PKP Docs** (https://docs.pkp.sfu.ca) dan modul pelatihan daring melalui platform **PKP School** (https://pkpschool.sfu.ca) sebagai referensi panduan lanjutan.

## Latihan Bab 3

**Latihan 3.1: Identifikasi Fungsi Alur Kerja**
Tinjau tiga jenis naskah berikut ini. Identifikasi tahapan alur kerja di OJS (mulai dari *Submission* hingga *Production*) yang wajib dilewati dan tahapan yang dapat dilewati.

1. **Artikel Penelitian Orisinal** (Naskah utama yang menyajikan hasil observasi lapangan).
2. **Komentar Editorial** (Pernyataan Editor Kepala terkait isu terkini yang tidak mensyaratkan penelaahan pakar eksternal).
3. **Resensi Buku Akademik** (Tinjauan kritis literatur oleh penulis undangan yang proses penelaahannya dikelola secara langsung oleh Editor Bagian).

**Panduan Fasilitator**: Latihan ini bertujuan menunjukkan fleksibilitas alur kerja di OJS 3.3. Diskusikan fungsi opsi *Accept and Skip Review* untuk jenis naskah non-riset dan tegaskan keharusan pemanfaatan fitur *Review* untuk naskah riset murni guna menjaga kualitas objektivitas evaluasi.

## Checklist Bab 3

- [ ] Latar belakang krisis publikasi dan tujuan utama inisiatif akses terbuka telah diidentifikasi.
- [ ] Signifikansi fungsional OJS dalam struktur akreditasi jurnal nasional di Indonesia (ARJUNA, SINTA) telah dimengerti.
- [ ] Susunan dan fungsi keempat tahapan editorial utama (*Submission*, *Review*, *Copyediting*, *Production*) telah dikenali.
- [ ] Manfaat integrasi infrastruktur digital (OAI-PMH, Crossref, ORCID) dan prosedur keamanan preservasi (PKP PN) telah dipahami secara konseptual.
- [ ] Ruang simulasi mandiri untuk uji coba fitur manajerial jurnal telah dipersiapkan jika diperlukan.

## Ringkasan Bab

OJS didesain sebagai ekosistem digital untuk mengelola proses penerbitan ilmiah secara profesional dan terdokumentasi. Platform ini berperan penting sebagai infrastruktur penggerak akses terbuka secara global, khususnya dalam memfasilitasi jurnal perguruan tinggi di Indonesia. Memahami arsitektur empat tahap operasionalnya, serta menjaga konsistensi komunikasi dalam sistem untuk merekam jejak audit, akan memastikan jurnal dapat mematuhi standar prosedur akreditasi nasional serta menjaga akuntabilitas penilaian kualitas keilmuan.
