# Bab 3: Gambaran Umum Alur Kerja Editorial OJS

> *Tahun 2001, sebuah perangkat lunak gratis diluncurkan dan perlahan mengubah lanskap penerbitan ilmiah dunia. Bagaimana sebuah inisiatif akademik dapat berkembang menjadi tulang punggung bagi puluhan ribu jurnal di seluruh dunia, termasuk di Indonesia?*

Open Journal Systems (OJS) versi 3.3 adalah perangkat lunak sumber terbuka (*open-source*) yang dirancang secara modular untuk membantu pengelola jurnal mengelola proses editorial secara sistematis. Memahami alur kerja editorial OJS 3.3 berperan penting dalam memastikan setiap naskah dikelola dengan transparansi dan integritas akademik yang memadai.

## 3.1 Fondasi, Evolusi, dan Lanskap Kontemporer OJS

### Akar Filosofis: Krisis Publikasi dan Lahirnya Gerakan Akses Terbuka

Untuk memahami esensi Open Journal Systems (OJS), kita harus melihat ke akhir abad ke-20 ketika dunia akademik dihadapkan pada apa yang dikenal sebagai krisis jurnal ilmiah (*serials crisis*). Pada masa itu, biaya langganan jurnal yang didominasi oleh segelintir penerbit komersial melonjak tajam melampaui daya beli sebagian besar perpustakaan universitas. Hal ini menciptakan paradoks ironis: penelitian yang sering kali didanai oleh institusi publik justru dikunci di balik tembok pembayaran (*paywall*) komersial, membuatnya tidak dapat diakses oleh peneliti lain (PKP, 2026, https://pkp.sfu.ca/about/). 

Dari kegelisahan struktural inilah gerakan Akses Terbuka (*Open Access*) lahir, menuntut agar hasil pemikiran manusia dapat diakses secara bebas, instan, dan universal. Sebagai respons konkret terhadap krisis ini, John Willinsky, seorang Profesor Pendidikan, mendirikan Public Knowledge Project (PKP) pada tahun 1998 di University of British Columbia. PKP tidak sekadar ingin menciptakan perangkat lunak, melainkan memelopori gerakan politik-akademik untuk mendemokrasikan pengetahuan. OJS, yang diluncurkan pertama kali pada 2001, dirancang sebagai instrumen utama misi ini—menekan biaya operasional penerbitan dan memberikan kesempatan setara bagi universitas di negara berkembang untuk menerbitkan jurnal berkualitas tinggi.

**Sorotan Standar Global: Budapest Open Access Initiative (BOAI)**

Landasan filosofis akses terbuka secara formal dikukuhkan melalui Budapest Open Access Initiative (BOAI) pada Februari 2002. BOAI mendefinisikan akses terbuka sebagai ketersediaan literatur ilmiah secara gratis di internet publik. Definisi ini mengizinkan pengguna membaca, mengunduh, menyalin, mendistribusikan, mencari, atau menautkan ke teks lengkap artikel tanpa hambatan finansial, hukum, atau teknis di luar batas konektivitas internet itu sendiri.

*Sumber: https://www.budapestopenaccessinitiative.org/read/*

### Arsitektur Teknologi dan Jejak Evolusi Generasi OJS

Sejak peluncurannya, arsitektur teknologi OJS terus berevolusi merespons tuntutan standar keamanan, kemudahan penggunaan, dan komputasi modern:

1. **Era OJS 1.x dan 2.x (Awal 2000-an hingga 2016)**: Memanfaatkan arsitektur monolitik berbasis PHP prosedural. Walaupun terbukti sangat stabil dan menjadi tulang punggung puluhan ribu jurnal, OJS 2.x memiliki keterbatasan fleksibilitas. Pengelola yang ingin mengubah antarmuka estetika harus merombak kode inti (*core code*), sebuah praktik yang rentan menimbulkan galat ketika sistem diperbarui.
2. **Titik Balik OJS 3.x (2016)**: PKP melakukan penulisan ulang kode secara menyeluruh (*total rewrite*). Versi ini memisahkan secara tegas antara pengolahan data (*back-end*) dan antarmuka pembaca (*front-end*). OJS 3.x mengadopsi mesin templat berbasis Bootstrap sehingga situs jurnal otomatis responsif di gawai portabel, serta memperkenalkan manajemen peran yang cair tanpa mengharuskan pengguna berpindah-pindah dasbor (PKP Docs, 2021).
3. **Lanskap Kontemporer (OJS 3.4 dan 3.5 LTS)**: Memasuki versi mutakhir dan versi dukungan jangka panjang (*Long-Term Support*), OJS memfokuskan diri pada optimalisasi Pengalaman Pengguna (*User Experience*). Dasbor editorial didesain ulang agar editor dapat melihat antrean naskah dalam layar tunggal. OJS modern ini juga dirancang untuk mematuhi regulasi privasi data global, seperti *General Data Protection Regulation* (GDPR) dari Uni Eropa, salah satunya dengan memperkenalkan sistem undangan mandiri yang mengutamakan persetujuan penggunaan data pribadi.

## 3.2 OJS di Indonesia: Konteks Nasional

Berdasarkan data 2025, OJS menopang lebih dari 58.000 jurnal di 156 negara. Di tengah lanskap ini, Indonesia menempati posisi sentral sebagai negara pengguna OJS terbesar, menampung sekitar 40% dari total instalasi global (PKP, 2026). Mayoritas instalasi ini beroperasi di bawah domain `.ac.id`, menyokong ekosistem jurnal berbasis *Diamond Open Access*—model publikasi yang tidak membebankan biaya kepada penulis maupun pembaca.

Adopsi masif ini didorong oleh kebijakan Kementerian Pendidikan, Kebudayaan, Riset, dan Teknologi (Kemendikbudristek). Untuk memenuhi standar akreditasi melalui portal ARJUNA (Akreditasi Jurnal Nasional) dan meraih peringkat SINTA (S1–S6), jurnal diwajibkan dikelola secara elektronik. Asesor akreditasi membutuhkan transparansi alur kerja yang disediakan OJS, lengkap dengan jejak rekam penelaahan sejawat dan publikasi berkala yang terindeks di portal Garuda (Garba Rujukan Digital). Dalam ekosistem ini, komunitas pendorong seperti Relawan Jurnal Indonesia (RJI) berperan krusial membimbing jurnal lokal untuk memenuhi standar nasional dan bermigrasi ke versi OJS modern.

**Catatan dari Lapangan**

Berdasarkan pengamatan di berbagai pelatihan pengelolaan jurnal, kesan pertama pengelola baru saat menghadapi dasbor OJS sering kali adalah kebingungan. Antarmuka dengan beragam menu dan peran terkadang terasa *overwhelming*. Ketidaktahuan ini kerap mendorong kembalinya kebiasaan buruk: berkomunikasi dengan penulis dan mitra bestari melalui WhatsApp atau surel pribadi di luar sistem. Praktik ini sangat fatal karena memutus jejak audit (*audit trail*), sehingga jika terjadi perselisihan atau proses evaluasi asesor, jurnal tidak dapat membuktikan kredibilitas proses penilaian naskahnya secara meyakinkan.

## 3.3 Para Aktor dalam Ekosistem Jurnal OJS

Kesuksesan penerbitan jurnal bergantung pada kolaborasi antar peran. OJS 3.3 dirancang dengan sistem peran yang fleksibel, di mana satu orang dapat memegang beberapa peran atau membagi peran ke tim yang lebih spesifik.

| Peran | Tanggung Jawab Utama |
|-------|---------------------|
| **Journal Editor** *(Editor Jurnal)* | Memiliki kendali penuh atas sistem dan kebijakan jurnal. Bertanggung jawab mengelola akun pengguna dan mengambil keputusan akhir terhadap naskah. |
| **Section Editor** *(Editor Bagian)* | Mengelola naskah di bagian atau rubrik tertentu. Bertindak sebagai motor penggerak operasional dari tahap penelaahan sejawat hingga keputusan editorial. |
| **Author** *(Penulis)* | Mendaftarkan naskah, menyediakan metadata, dan melakukan revisi berdasarkan masukan editorial. |
| **Reviewer** *(Mitra Bestari)* | Pakar di bidang terkait yang mengevaluasi kualitas konten secara objektif melalui proses penelaahan sejawat dan memberikan rekomendasi kepada editor. |
| **Copyeditor** | Memastikan akurasi bahasa, konsistensi istilah, dan kepatuhan terhadap gaya selingkung (*house style*) jurnal. |
| **Layout Editor** | Menyusun tata letak naskah menjadi format publikasi siap unduh (**Galleys**) seperti PDF, HTML, atau XML. |
| **Proofreader** | Melakukan pengecekan akhir pada pracetak sebelum naskah dipublikasikan. |

![Ilustrasi: Ekosistem peran dalam OJS](../img/elementor-placeholder-image.png)

## 3.4 Mekanisme Alur Kerja Editorial yang Terintegrasi

Sebagai *Journal Management System* (JMS), kekuatan OJS terletak pada kemampuannya mengotomatisasi siklus hidup naskah ilmiah melalui empat fase utama yang saling mengunci:

`[Submission] → [Review] → [Copyediting] → [Production]`

### Tahap 1: Submission (Pengajuan Naskah)

Penulis mengunggah naskah mereka melalui *wizard* interaktif. Pada tahap ini, penginputan metadata (abstrak, kata kunci, daftar pustaka) sangat krusial. Editor melakukan tinjauan awal (*desk review*) dan dapat merespons dengan:
1. **Send to Review**: Melanjutkan naskah untuk dievaluasi oleh pakar sejawat.
2. **Accept and Skip Review**: Memindahkan karya (seperti resensi buku) langsung ke penyuntingan.
3. **Decline Submission**: Menolak karya yang tidak sesuai ruang lingkup atau standar awal.

### Tahap 2: Review (Penelaahan Sejawat)

Menjadi jantung dari kendali mutu ilmiah, tahap ini memfasilitasi berbagai metode penilaian—termasuk *double-blind review* konvensional hingga *open peer review*. Sistem akan melacak tenggat waktu, mengirim pengingat otomatis, dan mendokumentasikan setiap poin revisi. Berdasarkan hasil tinjauan, editor membuat putusan (*Accept, Revisions Required, Resubmit for Review, Resubmit Elsewhere*, atau *Decline*).

### Tahap 3: Copyediting (Penyuntingan Naskah)

Naskah yang diterima secara substansi diperhalus tata bahasanya dan diselaraskan dengan gaya selingkung. Penulis, penyunting, dan editor bertukar umpan balik di dalam sistem untuk mengunci draf teks final yang disetujui bersama.

### Tahap 4: Production (Produksi dan Publikasi)

Artikel diformat menjadi lembar cetak digital (**Galleys**) dalam bentuk PDF, HTML, atau JATS XML. Setelah pengecekan pracetak (*proofreading*) selesai, editor menempatkan naskah dalam volume edisi tertentu dan menerbitkannya.

## 3.5 Integritas Akademik, Interoperabilitas, dan Preservasi

Dalam ekosistem akademik mutakhir, sebuah jurnal tidak boleh menjadi pulau yang terisolasi. OJS memfasilitasi integrasi pengetahuan global melalui beberapa teknologi kunci:

1. **Protokol OAI-PMH**: OJS memiliki dukungan bawaan untuk *Open Archives Initiative Protocol for Metadata Harvesting* (OAI-PMH). Protokol ini bertindak sebagai pemancar data otomatis yang memungkinkan pengindeks (Google Scholar, DOAJ) memanen metadata seketika setelah artikel diterbitkan (PKP Docs).
2. **Integrasi Ekosistem**: Melalui koneksi terstruktur, OJS mengotomatisasi deposit **DOI (Crossref)** agar tautan artikel tidak pernah rusak (*broken link*), mendata identitas peneliti secara unik melalui **ORCID**, dan menstandarkan identitas afiliasi institusional melalui **ROR (Research Organization Registry)**.
3. **Jejak Audit (Audit Trail)**: Seluruh tindakan (unggah dokumen, diskusi internal, putusan editor) direkam dalam *Activity Log* kronologis. Rekaman tak terbantahkan ini adalah bukti valid untuk mempertahankan integritas manajerial saat diaudit asesor atau terjadi perselisihan.
4. **Keamanan Preservasi Digital**: Untuk menjaga aset ilmiah dalam jangka panjang, OJS mengintegrasikan fitur preservasi melalui **LOCKSS** (*Lots of Copies Keep Stuff Safe*) dan **PKP Preservation Network (PKP PN)**. Layanan *dark archive* ini memastikan artikel akan tetap eksis dan dapat diakses publik biarpun jurnal terkait kelak berhenti beroperasi (PKP, 2026).

## 3.6 Struktur Pembelajaran Kursus

Buku panduan ini disusun sedemikian rupa agar merefleksikan alur kerja OJS 3.3 secara berurutan, dari perspektif berbagai peran:

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

Sebelum mempraktikkan proses manajerial pada instalasi jurnal utama yang mengelola data sungguhan, pengelola sangat disarankan untuk memiliki akses ke jurnal demonstrasi atau lingkungan simulasi. Ruang aman ini krusial untuk menguji fungsi lintas peran dan keputusan tanpa risiko mencoreng basis data (*database*) jurnal resmi.

Untuk panduan instalasi mendalam atau tutorial dasar berbasis video, PKP menyediakan sumber pembelajaran resmi melalui platform **PKP School** (https://pkpschool.sfu.ca) dan **PKP Docs** (https://docs.pkp.sfu.ca).

## Latihan Bab 3

**Latihan 3.1: Identifikasi "Jalur Cepat" dan "Jalur Normal"**
Tinjau tiga skenario pengajuan naskah di bawah ini. Tentukan alur kerja tahap apa saja yang harus dilewati oleh masing-masing jenis naskah dari Submission hingga Production.

1. **Artikel Penelitian Orisinal** (Naskah utama yang menyajikan hasil riset lapangan).
2. **Komentar Editorial** (Tanggapan singkat Editor Kepala terhadap isu terkini yang tidak memerlukan penelaahan sejawat).
3. **Resensi Buku** (Tinjauan terhadap buku baru oleh pakar undangan yang disetujui langsung oleh Editor Bagian).

**Panduan Fasilitator**: Diskusikan dengan peserta pelatihan bahwa OJS 3.3 memungkinkan fleksibilitas alur kerja (contoh: opsi *Accept and Skip Review*). Identifikasi implikasi fitur tersebut terhadap naskah non-riset, sembari menegaskan bahwa naskah riset wajib melewati tahapan Review secara utuh untuk memenuhi standar objektivitas.

## Checklist Bab 3

- [ ] Akar historis *Serials Crisis* dan misi demokratisasi pengetahuan OJS telah dipahami.
- [ ] Signifikansi OJS dalam ekosistem akreditasi jurnal nasional di Indonesia (ARJUNA, SINTA) telah dikenali.
- [ ] Empat pilar utama alur kerja OJS (*Submission*, *Review*, *Copyediting*, *Production*) beserta batasannya telah dipahami.
- [ ] Fungsi teknologi interoperabilitas (OAI-PMH, Crossref, ORCID) dan preservasi (PKP PN) telah diketahui konsepnya.
- [ ] Lingkungan jurnal simulasi untuk latihan telah disiapkan jika memungkinkan.

## Ringkasan Bab

OJS tidak sekadar berfungsi sebagai laci penyimpanan digital, melainkan direkayasa untuk mengawal publikasi ilmiah yang profesional, transparan, dan dapat dipertanggungjawabkan. Dari sejarah perintisannya merespons krisis publikasi hingga kemampuannya menjalin interoperabilitas data dengan raksasa pengindeks global, platform ini menjadi infrastruktur vital penggerak akses terbuka. Dengan memahami arsitektur empat fase—Pengajuan, Penelaahan, Penyuntingan, dan Produksi—serta menjaga keutuhan jejak audit (audit trail) pada sistem, pengelola dapat memastikan jurnalnya memenuhi standar mutakhir publikasi ilmiah dan akreditasi nasional.
