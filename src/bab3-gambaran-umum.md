# Bab 3: Gambaran Umum Alur Kerja Editorial OJS

Open Journal Systems (OJS) versi 3.3 adalah perangkat lunak sumber terbuka (*open source*) yang dirancang secara modular untuk membantu pengelola jurnal mengelola proses editorial secara sistematis. Memahami alur kerja editorial OJS 3.3 berperan penting dalam memastikan setiap naskah dikelola dengan transparansi dan integritas akademik yang memadai.

## 3.1 Sejarah Singkat OJS dan Public Knowledge Project (PKP)

Open Journal Systems dikembangkan oleh Public Knowledge Project (PKP), sebuah inisiatif penelitian dan pengembangan yang didirikan pada tahun 1998 oleh John Willinsky di University of British Columbia. Tujuan utama PKP adalah meningkatkan mutu akademik dan mutu publik dari penelitian melalui pengembangan platform penerbitan yang inovatif (PKP, 2023, https://docs.pkp.sfu.ca/learning-ojs/3.3/en/).

OJS pertama kali dirilis pada tahun 2001 dan telah berkembang menjadi salah satu platform penerbitan jurnal paling banyak digunakan di dunia. Versi 3.x, termasuk OJS 3.3, membawa perombakan signifikan pada antarmuka pengguna dan alur kerja editorial, menjadikannya lebih intuitif dan responsif dibandingkan versi sebelumnya.

## 3.2 Konsep Akses Terbuka (Open Access)

Pengembangan OJS sejalan dengan gerakan akses terbuka (*open access*). Berdasarkan deklarasi Budapest Open Access Initiative (BOAI) tahun 2002, akses terbuka berarti ketersediaan literatur ilmiah secara gratis di internet publik, memungkinkan setiap pengguna untuk membaca, mengunduh, menyalin, mendistribusikan, mencetak, mencari, atau menautkan ke teks lengkap artikel tanpa hambatan finansial, hukum, atau teknis selain yang tidak terpisahkan dari akses internet itu sendiri (BOAI, 2002, https://www.budapestopenaccessinitiative.org/).

Bagi pengelola jurnal di Indonesia, pemahaman tentang konsep akses terbuka sangat relevan, sejalan dengan kebijakan Kementerian Pendidikan, Kebudayaan, Riset, dan Teknologi (Kemendikbudristek) yang mendorong publikasi hasil penelitian yang didanai negara secara terbuka.

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

## 3.4 Empat Pilar Utama Alur Kerja Editorial

Alur kerja dalam OJS 3.3 dibagi menjadi empat tahap utama yang saling terintegrasi:

`[Submission] → [Review] → [Copyediting] → [Production]`

Pengelola jurnal memiliki fleksibilitas penuh untuk menentukan aktor yang terlibat di setiap tahap.

### Tahap 1: Submission (Penyerahan Naskah)

Tahap ini adalah gerbang utama proses editorial. Editor melakukan penilaian awal atau tinjauan awal meja (*desk review*) untuk memastikan naskah memenuhi syarat sebelum diproses lebih lanjut.

Terdapat tiga opsi utama editor pada tahap ini:

1. **Send to Review**: Melanjutkan naskah ke tahap penelaahan sejawat jika memenuhi kriteria awal.
2. **Accept and Skip Review**: Memindahkan naskah langsung ke tahap Copyediting tanpa melalui penelaahan sejawat. Opsi ini digunakan untuk karya seperti komentar editorial atau resensi buku.
3. **Decline Submission**: Menolak naskah yang tidak sesuai dengan ruang lingkup atau standar awal jurnal.

Catatan Teknis: Editor dapat menggunakan fitur Diskusi (*Discussion*) untuk berkomunikasi dengan penulis guna melengkapi persyaratan administratif sebelum mengambil keputusan.

### Tahap 2: Review (Penelaahan Sejawat)

Tahap penelaahan sejawat merupakan tahap sentral dalam publikasi ilmiah. Naskah dievaluasi oleh satu atau lebih mitra bestari (*reviewer*). OJS 3.3 memfasilitasi format penelaahan nirnama ganda (*double-blind review*) untuk menjaga integritas dan objektivitas penilaian.

Berdasarkan rekomendasi mitra bestari, editor mengambil keputusan editorial:

| Keputusan Editor | Deskripsi |
|-----------------|-----------|
| **Accept as is** | Menerima naskah tanpa perubahan. Kondisi ini jarang terjadi. |
| **Revisions Required** | Penulis diwajibkan melakukan perbaikan minor. Editor memeriksa revisi tanpa perlu melibatkan mitra bestari lagi. |
| **Resubmit for Review** | Naskah memerlukan perubahan besar, sehingga memicu putaran kedua (*Round 2*) penelaahan sejawat. |
| **Resubmit Elsewhere** | Naskah berkualitas namun tidak sesuai dengan fokus dan ruang lingkup jurnal. |
| **Decline Submission** | Naskah ditolak karena tidak memenuhi standar kelayakan akademik. |

### Tahap 3: Copyediting (Penyuntingan Naskah)

Setelah naskah dinyatakan diterima secara substansi, naskah memasuki tahap penyuntingan naskah (*copyediting*). Fokus utama tahap ini adalah meningkatkan akurasi bahasa, kejelasan, dan kepatuhan tata letak terhadap gaya selingkung jurnal.

Di OJS 3.3, seluruh proses penyuntingan direkomendasikan untuk dilakukan di dalam sistem melalui fitur diskusi dan pengunggahan dokumen. Praktik ini mencegah pertukaran versi dokumen yang keliru dan menciptakan jejak audit (*audit trail*) yang terdokumentasi.

*Jejak audit* (*audit trail*) adalah rekaman historis yang mencatat setiap aktivitas komunikasi dan pertukaran berkas secara sistematis, sehingga proses editorial dapat dipertanggungjawabkan di kemudian hari.

Penulis berkewajiban meninjau setiap perubahan yang diusulkan oleh *copyeditor* sebelum naskah ditetapkan final.

### Tahap 4: Production (Produksi dan Publikasi)

Pada tahap akhir, tata letak naskah akhir diubah menjadi format publikasi profesional yang dikenal sebagai **Galleys**.

- **Pembuatan Galley**: Proses konversi naskah ke format PDF, HTML, XML, atau EPUB.
- **Proofreading**: Proses pengecekan akhir oleh penulis dan tim editorial sebelum penerbitan.
- **Penjadwalan**: Penempatan naskah ke dalam nomor terbitan (*issue*) tertentu untuk dipublikasikan.

## 3.5 Fitur Unggulan OJS 3.3

### Sistem Diskusi Terintegrasi

Fitur Diskusi terintegrasi pada setiap naskah di setiap tahap alur kerja. Seluruh korespondensi antara editor, penulis, dan aktor lainnya terdokumentasi di dalam sistem, mengurangi kebergantungan pada komunikasi surat elektronik eksternal.

Manfaat fitur diskusi meliputi:
- Membangun jejak audit yang transparan.
- Memastikan setiap aktor yang berwenang memiliki akses ke informasi yang sama.
- Mencegah kehilangan rekam jejak komunikasi penting.

### Activity Log

OJS 3.3 merekam setiap tindakan secara otomatis dan kronologis melalui **Activity Log**. Fitur ini mendukung transparansi dengan mencatat aktor pelaksana dan waktu tindakan secara akurat.

### Fleksibilitas Peran

Sistem peran dalam OJS 3.3 dapat disesuaikan dengan skala manajerial jurnal:
- **Tim besar**: Melibatkan Editor Kepala, sejumlah Editor Bagian, dan Editor Tata Letak yang terpisah.
- **Tim kecil**: Memungkinkan satu orang merangkap berbagai peran fungsional.
- Peran dapat diubah sewaktu-waktu sesuai dengan kebutuhan operasional jurnal.

![Ilustrasi: Alur kerja editorial OJS 3.3](../img/elementor-placeholder-image.png)

## 3.6 Struktur Pembelajaran Kursus

Buku panduan ini disusun mengikuti alur kerja OJS 3.3 secara berurutan:

| Bab | Topik | Tahap OJS |
|-----|-------|-----------|
| Bab 1–2 | Persiapan dan Kemampuan Dasar | Pra-OJS |
| Bab 3 | Gambaran Umum OJS | Pengenalan |
| Bab 4 | Panduan Mengirimkan Artikel | Submission (Penulis) |
| Bab 5 | Merespons Naskah Baru | Submission (Editor) |
| Bab 6 | Pemeriksaan Plagiasi | Pra-Review |
| Bab 7 | Menugaskan Reviewer | Tahap Review |
| Bab 8 | Panduan Reviewer | Tahap Review |
| Bab 9 | Merespons Hasil Ulasan | Keputusan Review |
| Bab 10 | Penyuntingan Naskah (Copyediting) | Tahap Copyediting |
| Bab 11 | Produksi dan Galley | Tahap Production |
| Bab 12 | Manajemen Edisi | Publikasi |
| Bab 13 | Optimalisasi Metadata | Visibilitas dan Indeksasi |

## 3.7 Persiapan Sebelum Memulai

Sebelum menerapkan praktik operasional pada jurnal utama, pengelola sangat disarankan untuk memiliki akses ke jurnal demonstrasi atau jurnal simulasi. Lingkungan simulasi ini memberikan ruang aman untuk:
- Bereksperimen dengan berbagai fitur manajerial.
- Menguji fungsi dari berbagai peran secara bergantian.
- Menyempurnakan konfigurasi alur kerja tanpa risiko mengubah data jurnal resmi.

Untuk panduan instalasi atau konfigurasi awal OJS, pengelola dapat merujuk ke materi PKP School di [pkpschool.ca](https://pkpschool.ca).

## Checklist Bab 3

- [ ] Konsep akses terbuka (open access) telah dipahami.
- [ ] Empat pilar utama alur kerja OJS (Submission, Review, Copyediting, Production) telah dikenali.
- [ ] Berbagai peran dalam ekosistem OJS dan batasan wewenangnya telah dipahami.
- [ ] Pentingnya fungsi jejak audit (*audit trail*) dalam proses editorial telah dipahami.
- [ ] Lingkungan jurnal simulasi untuk latihan telah disiapkan jika diperlukan.

## Ringkasan Bab

OJS 3.3 dikembangkan untuk mendukung publikasi ilmiah yang profesional, transparan, dan dapat dipertanggungjawabkan. Dengan menguasai empat pilar utama alur kerja editorial, pengelola jurnal dapat menyelenggarakan proses publikasi yang sesuai dengan standar pengelolaan jurnal ilmiah. Sistem komunikasi yang terpusat mencegah hilangnya jejak audit dan mendukung integritas proses editorial secara menyeluruh.
