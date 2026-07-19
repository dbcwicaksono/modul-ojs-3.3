# Bab 14: Optimalisasi Metadata Artikel

> **Pemantik Bab**
> Pernahkah Anda mencari artikel di Google Scholar dan menemukan judulnya ditulis seluruhnya dengan huruf kapital, atau abstraknya terpotong oleh format aneh? Itulah malapetaka metadata. Metadata ibarat "KTP" bagi artikel jurnal Anda di jagat internet. Mesin pencari seperti Google atau pengindeks otomatis via OAI-PMH tidak peduli seberapa indah tata letak PDF Anda; mereka murni membaca metadata mentah yang Anda ketikkan. Kesalahan mengisi formulir metadata berarti menenggelamkan artikel Anda sendiri dari radar komunitas ilmiah global.

Metadata adalah fondasi dari visibilitas dan kemampuan penemuan artikel (*discoverability*) di ekosistem penerbitan digital. Metadata yang lengkap, akurat, dan konsisten menentukan seberapa mudah artikel ilmiah dapat ditemukan, disitasi, dan diindeks oleh mesin pencari maupun basis data kepustakaan global.

Pemeliharaan metadata merupakan tanggung jawab yang diemban bersama antara tim editor dan penulis. Kesalahan pencatatan metadata dapat menimbulkan dampak serius, mulai dari kegagalan distribusi DOI hingga penyematan sitasi yang keliru pada profil Google Scholar penulis.

## 14.1 Pengertian Metadata Artikel

Metadata secara harfiah merujuk pada data yang menyajikan informasi mengenai data lainnya (Pomerantz, 2015). Metadata tidak sekadar berfungsi mendeskripsikan data mentah; entitas ini turut menggambarkan bagaimana sebuah organisasi mengonseptualisasikan aktivitasnya, aspek kewilayahan, konteks waktu, serta tujuan pendiriannya (Hay, 2006). Menurut Riley (2017), metadata adalah struktur informasi yang dibuat, disimpan, dan dibagikan dengan tujuan memampukan interaksi sistematis untuk ekstraksi pengetahuan.

Dalam domain publikasi ilmiah, metadata bertindak sebagai representasi komprehensif dari sebuah artikel, yang mencakup nama kontributor, judul utama, abstrak penelitian, kata kunci spesifik, penanggalan penerbitan, hingga pengenal digital (DOI). Guna mendukung kelestarian arsip dan kemudahan pencarian retrospektif, setiap artikel ilmiah harus didukung oleh kerangka metadata yang kaya dan presisi (Rahutomo, Irawati, & Pramudita, 2019).

Berdasarkan studi Basuki (2000), terdapat tiga elemen fundamental dalam konstruksi metadata sebuah unit informasi:
1. Mekanisme penyandian (*encoding*);
2. Formulasialisasi deskripsi identitas informasi yang digabungkan dengan parameter manajemen pelestarian digital; dan
3. Penyediaan protokol akses menuju deskripsi yang bersangkutan.

### Fungsi Esensial Metadata Artikel

Fungsi primer metadata adalah memfasilitasi penemuan sumber informasi (*resource discovery*) (Basuki, 2000). Rao (1995) menegaskan bahwa instrumen ini menyokong proses seleksi, pemahaman analitis, dan daya ingat kolektif atas konten pustaka. Metadata menyediakan kerangka rasional bagi pemakai untuk menimbang tiga aspek (Basuki, 2000):
1. **Ketersediaan** parameter eksistensi, kuantitas, dan rute lokasi objek informasi.
2. **Kegunaan** yang merujuk pada otentisitas dan penjaminan kualitas.
3. **Relevansi** penentu kesesuaian nilai fungsional informasi tersebut bagi kebutuhan spesifik pencari.

Multazam (2021) merumuskan fungsi praktis metadata artikel dalam operasional jurnal harian:
1. Menjamin artikel dapat terindeks secara mulus oleh algoritma perayap (*crawler*) dari institusi pengindeks global.
2. Mengintegrasikan struktur informasi naskah agar dapat ditangkap tanpa cacat oleh perangkat lunak referensi pihak ketiga seperti Mendeley atau Zotero.
3. Memberikan umpan data matang bagi mesin analitik kepustakaan.

### Standar Metadata Internasional

Dalam ekosistem komunikasi ilmiah global, jurnal tidak lagi bekerja secara terisolasi. Metadata yang dihasilkan oleh OJS harus dapat dibaca oleh berbagai sistem internasional. Beberapa standar utama yang perlu dipahami:

- **Dublin Core (DC)**: Standar metadata paling umum di internet yang terdiri dari 15 elemen dasar (seperti Title, Creator, Subject, Description). OJS secara otomatis mengekspor metadata artikel dalam format Dublin Core untuk meningkatkan keterbacaan lintas sistem (https://dublincore.org/).
- **schema.org/ScholarlyArticle**: Skema markup terstruktur yang dikembangkan bersama oleh mesin pencari utama (Google, Microsoft, Yahoo, Yandex). Penerapan skema ini membantu mesin pencari seperti Google Scholar memahami bahwa sebuah halaman web adalah artikel ilmiah (https://schema.org/ScholarlyArticle).
- **JATS (Journal Article Tag Suite)**: Standar format XML yang dirancang khusus untuk memodelkan artikel jurnal ilmiah. Format ini merupakan persyaratan utama untuk pengindeksan di PubMed Central dan sangat dianjurkan untuk Scopus (https://jats.nlm.nih.gov/).

Selain itu, standar **Directory of Open Access Journals (DOAJ)** secara spesifik mengharuskan bahwa metadata artikel jurnal harus dapat diakses secara terbuka, terstruktur, dan disajikan di halaman awal (*landing page*) dari setiap artikel untuk memfasilitasi interoperabilitas dan perayapan mesin pencari (DOAJ, 2024, https://doaj.org/apply/guide/).

> **Catatan dari Lapangan: Bencana Format Metadata**
>
> **Studi Kasus:** Sebuah jurnal kesehatan mengeluhkan mengapa sebagian besar artikel terbarunya tidak muncul di Google Scholar. Setelah diselidiki, tim editor menemukan bahwa mereka salah menginput nama penulis pada kolom yang terbalik, menyisipkan teks penuh (*full-text*) ke dalam kolom abstrak, dan menuliskan daftar referensi tanpa jarak spasi enter. Metadata yang buruk dan format yang tidak terstruktur ini menyebabkan algoritma Google Scholar (*schema.org*) gagal mengurai data, sehingga menolak indeksasi secara massal. Kasus ini menegaskan bahwa validitas input metadata berdampak langsung pada kemampuan keterpaparan naskah.

> **Catatan Kritis**: Praktik mengubah metadata suatu artikel *setelah* rilis publikasi (seperti mengubah judul atau menambah penulis) sangat tidak direkomendasikan karena akan memicu konflik pembaruan data di Crossref (DOI) dan Google Scholar. Lakukan validasi ketat *sebelum* tombol publikasi ditekan.

## 14.2 Konfigurasi Awal Metadata di OJS 3

Sebelum setiap artikel dapat diisi metadatanya, pengelola jurnal diwajibkan menyelesaikan konfigurasi global pada pangkalan sistem:

### A. Identitas Dasar Jurnal (Masthead)

OJS 3.0 hingga 3.3: Akses melalui rute **Settings**, pilih **Journal**, kemudian **Masthead**.
Instruksi: Masukkan nama jurnal secara penuh, nomor ISSN, beserta data pengelola dasar. Data ini berfungsi sebagai metadata jangkar (*anchor*) yang menyertai seluruh artikel dalam jurnal tersebut.

### B. Konfigurasi Metadata Penyerahan Naskah

OJS 3.2 dan 3.3: Akses melalui rute **Settings**, pilih **Workflow**, masuk ke **Submission**, lalu **Metadata**.
Instruksi: Manajer Jurnal (*Journal Manager*) harus mengaktifkan kolom metadata yang wajib diisi oleh penulis saat pendaftaran naskah awal, seperti kolom kata kunci, lembaga pemberi hibah, hingga daftar rujukan.

### C. Lisensi dan Hak Cipta

OJS 3.2 dan 3.3: Akses melalui rute **Settings**, pilih **Distribution**, lalu **License**.
Instruksi: Tentukan dengan jelas kebijakan retensi hak cipta (apakah dipegang oleh pihak jurnal atau penulis) serta terapkan jenis lisensi diseminasi publik seperti Creative Commons.

### D. Penataan Bagian Jurnal (Sections)

Akses melalui rute **Settings**, pilih **Journal**, lalu **Sections**.
Instruksi: Kelola kompartemen penerbitan jurnal, misalnya kategori Artikel Penelitian Asli, Tinjauan Buku, atau Laporan Kasus.

### E. Integrasi Pengaya (Plugins) Tambahan

**Pengaya Pendanaan (Funding Plugin)**: Memfasilitasi pendaftaran dana hibah penelitian secara transparan. Diaktifkan melalui menu Plugins di Website Settings.
**Pengaya Crossref Reference Linking**: Mensinkronisasikan daftar referensi dengan pangkalan data DOI global secara otonom.

## 14.3 Standar Struktur Metadata Artikel OJS 3

Struktur metadata di dalam naskah terbagi atas beberapa kelompok inti. Berikut merupakan pedoman teknis pengelolaan masing-masing kelompok:

### A. Judul dan Abstrak (Title and Abstract)

Elemen data wajib meliputi Awalan (*Prefix*), Judul Utama (*Title*), dan Teks Abstrak (*Abstract*).

Panduan Formulasi Judul:
- Wajib diketik menggunakan format kapitalisasi standar atau kapital di awal kata utama (*Title Case*). Jangan mengetik judul dengan huruf kapital yang dominan sepenuhnya.
- Metadata judul di dalam sistem harus sama presisi dengan yang tertera di dokumen pracetak PDF.

Panduan Formulasi Abstrak:
- Ditulis utuh dalam satu paragraf.
- Tidak melebihi batas jumlah kata jurnal (lazimnya 250 kata).
- Memuat pilar tujuan, rancangan metode, penjabaran sampel, dan intisari temuan.
- Dilarang keras menyisipkan teks kata kunci ke dalam kolom isian khusus abstrak.
- Dilarang menambahkan kata "Abstrak" atau "Abstract" sebagai kata pembuka di dalam formulir.

### B. Informasi Kontributor (Contributors)

Elemen data wajib meliputi Nama Depan, Nama Belakang, Surel Afiliasi, Negara Asal, Nama Institusi, ID ORCID, serta Penugasan Peran (*Role*).

Pedoman Konversi Nama:
| Nama Penulis | Masukan Nama Depan | Masukan Nama Belakang |
|------|---------------------|------------------------|
| Soekarno (1 kata tunggal) | S | Soekarno |
| Soekarno (Format Alternatif) | Soekarno | Soekarno |
| Andista Candra Yusro | Andista Candra | Yusro |

Ketentuan Tambahan:
- Untuk nama yang terdiri dari tiga kata atau lebih, kompres seluruh unsur awal ke dalam Nama Depan, dan pertahankan hanya kata paling akhir sebagai Nama Belakang.
- Dilarang memberikan karakter setrip telegrafis pada kolom identitas nama.

ORCID (Open Researcher and Contributor ID) merupakan identifikasi unik yang bersifat persisten, bermanfaat untuk mengikat seorang akademisi dengan seluruh jejak rekam rekam hibah dan publikasinya di internet. Penulis dianjurkan keras untuk melampirkan identifikasi ini.

### C. Klasifikasi Kata Kunci dan Perekaman Pendanaan

**Kata Kunci (Keywords)**: Input setiap entitas kata kunci secara individu lalu tekan tombol Enter. Sistem OJS memproses setiap kata sebagai atribut tag independen untuk pengindeksan situs (*faceted search*), bukan sebagai deretan string biasa yang dipisahkan koma.

**Pendanaan (Supporting Agencies)**: Masukkan nama institusi pendonor riset dan koneksikan dengan plugin yang terkait agar informasi ini mengalir mulus ke dalam paket XML yang disetor kepada Crossref.

### D. Rujukan (References)

Semua entri daftar rujukan wajib ditranskripsikan ke dalam pangkalan metadata.

Panduan Teknis:
- Lakukan penyalinan dari dokumen berbasis pengolah kata (*Word processor*), bukan dokumen PDF, guna memitigasi kesalahan konversi karakter.
- Beri jarak pemisah satu baris kosong yang bersih di antara tiap referensi.
- Editor diharuskan melengkapi setiap referensi dengan tautan pengarah atau nomor DOI aktif, sesuai kaidah pengutipan modern.

### E. Pengidentifikasi (Identifiers / DOI)

Prosedur Penugasan Nomor Identifikasi:
1. Verifikasi pengaya *Public Identifier* telah dirancang pola identifikasinya melalui pengaturan pengelola web.
2. Pada halaman artikel yang akan disahkan (di tab *Publication*), beralih ke sub-menu *Identifiers*.
3. Klik tombol operasi *Assign* di sebelah kotak isian DOI untuk membangkitkan nomor sandi resmi.

Setoran DOI ke Crossref:
Otorisasi akun dan setoran (*deposit*) XML ke sistem Crossref dieksekusi melalui menu *Import/Export* di perkakas manajemen alat (*Tools*).

### F. Galley

Representasi dokumen terbitan final dalam bentuk portabel diunggah pada sesi ini dan dikunci modifikasinya dari pengguna awam.

### G. Perizinan dan Keterbukaan Publik (Permission and Disclosure)

Pemeriksaan akhir atas hak cipta berpusat pada:
- **Hak Cipta**: Memastikan pihak pemegang hukum lisensi dideklarasikan dengan benar.
- **Lisensi Rilis**: Memastikan kebijakan sirkulasi publik dicantumkan URL sahnya secara lengkap.
- **Tahun Hak Cipta**: Harus tersinkronisasi presisi dengan tahun rilis edisi, aspek vital yang kerap terabaikan saat menerbitkan jurnal edisi terdahulu (*back issue*).

### H. Penempatan Edisi Penerbitan (Issue)

Menu administratif penataan metadata tingkat lanjut di mana editor menyematkan artikel ke dalam kerangka edisi tertentu, menyematkan penomoran halaman yang utuh (*Pages*), menentukan gambar sampul artikel individual (apabila diimplementasikan), serta memvalidasi atribut penanggalan tanggal publikasi akhir artikel.

## 14.4 Teknik Penyuntingan Metadata Pra-Terbit

Siklus pengeditan baku sebelum status publikasi aktif dalam OJS 3.3:
1. Masuk ke pangkalan sistem dengan otorisasi Editor.
2. Akses antrean di **Submissions**.
3. Buka naskah spesifik yang membutuhkan perbaikan.
4. Sentuh penanda tab **Publication**.
5. Ganti nilai-nilai metadata pada porsi sub-tab yang dikehendaki.
6. Patenkan setiap perubahan melalui tombol **Save** sebelum berpindah tabulasi.

## 14.5 Teknik Penyuntingan Metadata Pasca-Terbit

**Jalur Eksekusi Cepat: Merevisi Metadata Artikel yang Telah Terbit**
1. Akses menu **Issues**, lanjutkan ke **Back Issues**.
2. Masuk ke halaman edisi kolektif dan klik tautan **Submission** di sebelah judul artikel yang hendak disunting.
3. Klik tombol **Unpublish** di pojok kanan atas untuk menariknya sementara.
4. Beralih ke tab **Publication**, lakukan revisi pada isian metadata (misal: abstrak atau nama penulis).
5. Klik **Save** lalu klik **Schedule for Publication** untuk memublikasikannya kembali.

> **Troubleshooting: Kegagalan Pengikatan DOI Pascarevisi**
>
> **Masalah**: Anda baru saja merevisi metadata judul artikel yang telah diterbitkan. Namun, tautan DOI yang lama kini menampilkan halaman *error* atau informasi yang tidak sesuai di Crossref.
>
> **Solusi Cepat**: Segera setelah Anda melakukan *Republish* artikel di OJS, Anda **WAJIB** masuk kembali ke menu **Tools > Import/Export > Crossref XML Export Plugin**, pilih artikel tersebut, dan lakukan klik tombol **Deposit** ulang. Hal ini akan memperbarui metadata baru ke basis data sentral Crossref, sehingga *link* DOI bekerja normal kembali.

## Latihan Bab 14

**Skenario Simulasi: Standarisasi Data Pengindeks**

Anda menyadari bahwa seorang penulis mengirimkan naskah dengan judul yang seluruhnya diketik dengan tombol *Caps Lock* dan abstraknya memuat gambar. Ini akan merusak indeksasi metadata OAI-PMH.

**Tugas Praktik:**
1. Buka naskah tersebut yang saat ini berada di antrean mana pun.
2. Klik tab **Publication** (pastikan naskah belum terbit, jika sudah terbit, ingatlah untuk menekan **Unpublish** terlebih dahulu).
3. Buka sub-tab **Title & Abstract**. Ubah penulisan judul menjadi format *Title Case* (Hanya Huruf Awal yang Kapital).
4. Bersihkan abstrak dari semua format aneh atau *bullet points* rumit, jadikan satu paragraf bersih yang padat (maksimal 250 kata).
5. Klik **Save**. Simulasi selesai. Metadata ini kini aman untuk dipanen (*harvested*) oleh Google Scholar dan DOAJ.

## Checklist Komprehensif Metadata Artikel

Patuhi daftar kontrol metadata di bawah ini sebagai prasyarat akhir sebelum naskah masuk antrean publikasi rilis:

**Judul dan Abstrak:**
- [ ] Judul ditulis menggunakan standar *Title Case* tanpa pemborosan huruf kapital.
- [ ] Abstrak dirangkum dalam satu blok paragraf bahasa Inggris yang padat (maksimal 250 kata).
- [ ] Tidak ditemukan penempatan kata kunci liar di dalam kolom abstrak.

**Atribut Kepengarangan:**
- [ ] Volume jumlah penulis sama persis dengan yang tertulis pada teks sumber.
- [ ] Identitas setiap penulis ditulis tanpa saltasi atau singkatan ejaan yang serampangan.
- [ ] Rincian hierarki afiliasi diklasifikasikan dengan sempurna.
- [ ] Ekstensi alamat surel penulis dipastikan status aktifnya.
- [ ] ID registri ORCID diikatkan pada profil kontributor terkait.

**Detail Metadata Lanjutan:**
- [ ] Setiap kata kunci telah tersimpan sebagai *tag* beridiri sendiri (terpisah melalui tombol *Enter*).
- [ ] Afiliasi lembaga penyedia dana riset telah dideklarasikan secara tertulis.

**Referensi dan Tautan:**
- [ ] Rujukan referensi komplit tanpa pemenggalan dari teks asli.
- [ ] Konvensi jarak baris pada antarmuka rujukan telah ditata sesuai instruksi pengindeks.

**Sandi Registri:**
- [ ] Atribut identifier publik (DOI) telah dirumuskan dan tertanam pada *database* OJS.

**Legalitas:**
- [ ] Penetapan klausul hak cipta tervalidasi dengan lisensi resmi publik yang transparan.
- [ ] Tahun legalitas lisensi selaras dengan tarikh rilis jurnal.

**Posisi Struktural:**
- [ ] Edisi penerbitan (*Issue*) serta kompartemen (*Section*) terkait telah dideklarasikan secara konkrit.
- [ ] Lembar penomoran angka (*Pages*) definitif tercantum dengan komplit.

## Ringkasan Bab

Implementasi arsitektur metadata yang komprehensif adalah wujud jaminan eksistensi dan integritas jurnal di alam perayapan digital tingkat global. Pengisian seluk beluk atribut meta data melampaui formalitas teknis; hal tersebut mendefinisikan batas antara artikel yang menghilang tertelan algoritma dan artikel yang meraih reputasi rujukan (*citation impact*) optimal. Doktrin utama pengelolaan: Verifikasi final selalu dilakukan sebelum tuas rilis ditekan. Evaluasi mitigasi awal selalu lebih bernilai ketimbang operasi koreksi sengketa kepustakaan pascapublikasi.
