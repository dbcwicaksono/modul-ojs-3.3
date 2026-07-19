# Bab 3: Pengelolaan e-Resources dan Manajemen Referensi

> **Pemantik Bab**
> Pernahkah Anda menemukan naskah dengan argumen yang sangat meyakinkan, namun setelah diperiksa, referensi yang digunakan tidak relevan, berupa tautan rusak (*broken links*), atau bersumber dari blog pribadi yang tidak melalui proses penelaahan sejawat (*peer-review*)? Bagi pengelola jurnal, situasi ini adalah alarm bahaya. Cacatnya sitasi bukan sekadar masalah estetika tata letak, melainkan indikasi rapuhnya validitas metodologis dan replikabilitas karya ilmiah. 

Bagaimana Anda dapat memastikan keandalan fondasi keilmuan naskah tersebut tanpa harus menghabiskan waktu berjam-jam untuk melakukan verifikasi manual satu per satu? Di sinilah pengelolaan sumber daya elektronik (*e-resources*) serta pemanfaatan perangkat lunak manajemen referensi yang terstandarisasi menjadi krusial.

Penulisan ilmiah yang kredibel selalu berdiri di atas bahu pemikiran terdahulu. Setiap klaim, data, dan teori yang dirujuk wajib diakui melalui mekanisme sitasi (*citation*) dan didokumentasikan secara presisi dalam daftar pustaka berdasarkan gaya selingkung (*house style*) yang berlaku. Untuk mengelola data bibliografi secara masif dan meminimalkan kesalahan manusia, penggunaan perangkat lunak manajemen referensi (*Reference Management Software* atau RMS) telah bergeser dari sekadar alat bantu menjadi kebutuhan mutlak.

Bab ini mengupas konsep dasar manajemen referensi, urgensi integritas akademik dalam sitasi, serta panduan pemanfaatan Mendeley sebagai RMS yang paling banyak diintegrasikan dalam ekosistem publikasi global, termasuk Open Journal Systems (OJS).

## 3.1 Konsep Sitasi dan Signifikansinya

Sitasi atau kutipan bibliografi adalah pencatatan formal berbasis struktur tertentu yang merujuk pada dokumen ilmiah terkodifikasi, seperti buku, artikel jurnal, atau himpunan data (*dataset*). Sitasi memberikan rincian metadata yang memadai untuk mengidentifikasi dokumen tersebut secara unik (MIT Libraries, 2009).

Di era digital, sitasi bukan lagi teks statis, melainkan data interaktif yang terhubung melalui pengenal persisten (*Persistent Identifiers* atau PID). Bentuk PID paling standar adalah *Digital Object Identifier* (DOI), yakni alamat permanen suatu artikel di internet sehingga tetap dapat diakses meskipun situs web penyedianya berubah.

Penerapan sitasi yang akurat memiliki tiga fungsi fundamental:

1. **Pencegahan Plagiarisme dan Pelanggaran Etik**: Sitasi menjadi batas yang jelas antara gagasan orisinal penulis dengan pemikiran peneliti terdahulu. Kegagalan menyitasi dengan benar dapat menjatuhkan sanksi akademik dan merusak reputasi jurnal.
2. **Pengakuan Hak Intelektual**: Penulisan sitasi menghargai kontribusi intelektual peneliti sebelumnya. Atribusi ini dikonversi menjadi metrik performa ilmiah, seperti *h-index* dan total jumlah kutipan.
3. **Penyusunan Peta Jalan Informasi (*Citation Chaining*)**: Daftar pustaka yang kredibel berfungsi sebagai navigasi bagi pembaca, peninjau, dan editor untuk menelusuri validitas data ke belakang maupun melacak perkembangan teori ke depan.

> **Sorotan Standar Global: Committee on Publication Ethics (COPE)**
> 
> *Committee on Publication Ethics* (COPE) mengategorikan pelanggaran terhadap prinsip sitasi sebagai tindakan salah laku ilmiah (*scientific misconduct*). Praktik tidak etis ini dikenal sebagai manipulasi sitasi (*citation manipulation*), yaitu penyisipan referensi yang tidak memiliki relevansi ilmiah dengan isi artikel. Manifestasi manipulasi ini meliputi:
> 
> 1. **Sitasi Paksaan (*Coercive Citation*)**: Editor jurnal memaksa penulis menambahkan referensi dari jurnal yang dipimpinnya demi menggelembungkan faktor dampak (*Impact Factor*).
> 2. **Kartel Sitasi (*Citation Cartels*)**: Kerja sama tidak etis antar-peneliti untuk saling menyitasi karya satu sama lain guna mendongkrak metrik personal.
> 3. **Sitasi Mandiri Berlebihan (*Excessive Self-Citation*)**: Sitasi berlebihan terhadap karya sendiri yang tidak relevan dengan substansi artikel.
> 
> Pengelola jurnal wajib menyusun Kebijakan Etika Publikasi yang tegas terkait integritas sitasi ini guna memitigasi risiko pencabutan indeksasi oleh basis data reputasi global. (Sumber: [https://publicationethics.org/](https://publicationethics.org/))

## 3.2 Perangkat Lunak Manajemen Referensi

Memproses sitasi secara manual pada draf naskah yang memiliki banyak referensi sangat rentan terhadap ketidakberaturan format. RMS hadir sebagai solusi automasi untuk mengoleksi metadata, mengorganisasi berkas digital, serta melakukan injeksi sitasi secara langsung (*real-time*) ke dalam perangkat lunak pengolah kata. 

RMS bekerja dengan mengekstraksi dan mengekspor data bibliografi melalui format standar pertukaran data, antara lain format `.ris`, `.bib` (*BibTeX*), dan `.xml`. 

Berikut adalah perbandingan empat RMS yang dominan di ranah akademik global:

| Perangkat Lunak | Keunggulan Utama | Keterbatasan | Relevansi Pengguna |
| :--- | :--- | :--- | :--- |
| **Mendeley** | Terintegrasi dengan ekosistem Elsevier, memiliki ekstraksi metadata PDF otomatis yang sangat akurat. Penyimpanan awan dasar gratis 2 GB. | Fleksibilitas modifikasi gaya sitasi mandiri lebih terbatas pada versi terbaru dibandingkan versi klasiknya. | Sangat direkomendasikan untuk jurnal berbasis OJS dan peneliti umum. |
| **Zotero** | Sangat andal menangkap metadata dari halaman web, didukung banyak fitur tambahan komunitas. Sumber terbuka dan gratis. | Kapasitas penyimpanan awan bawaan gratis relatif kecil (300 MB). | Ideal untuk riset multidisiplin dan tim dengan anggaran terbatas. |
| **EndNote** | Penyimpanan awan tidak terbatas (pada versi premium), fitur penyaringan duplikasi tingkat lanjut, integrasi optimal dengan Web of Science. | Kurva pembelajaran cukup curam, biaya lisensi berbayar relatif mahal. | Standar emas untuk institusi besar dan peneliti tinjauan sistematis. |
| **RefWorks** | Sepenuhnya berbasis web (*cloud-based*), memudahkan kolaborasi institusional tanpa instalasi aplikasi lokal. | Ketergantungan penuh pada koneksi internet. | Umumnya digunakan jika universitas melanggan paket layanannya. |

Bab ini berfokus pada **Mendeley** karena aksesibilitasnya yang gratis, ketersediaan lintas platform, serta adopsi yang sangat masif di kalangan peneliti dan pengelola jurnal di Indonesia.

![Ilustrasi Perangkat Lunak Manajemen Referensi](../img/elementor-placeholder-image.png)

## 3.3 Pengenalan Mendeley

Mendeley telah bertransisi sepenuhnya dari arsitektur lokal lama menuju ekosistem terintegrasi baru yang berpusat pada **Mendeley Reference Manager (MRM)**. Ekosistem digital Mendeley saat ini terdiri atas tiga komponen interaktif utama:

1. **Mendeley Reference Manager (MRM)**: Aplikasi utama yang mensinkronkan basis data bibliografi lokal secara otomatis dengan peladen awan Mendeley.
2. **Mendeley Web Importer (MWI)**: Pengaya peramban (*browser extension*) yang berfungsi mengekstraksi metadata artikel ilmiah secara langsung dari situs web jurnal tanpa perlu mengunduh berkas PDF.
3. **Mendeley Cite**: Aplikasi pihak ketiga (*add-in*) yang dipasang pada Microsoft Word untuk mengelola sitasi secara langsung.

Keunggulan arsitektur modern Mendeley meliputi ekstraksi metadata otomatis berbasis kecerdasan buatan, pencarian teks penuh di dalam dokumen PDF, dan sinkronisasi awan lintas platform (Windows, macOS, Linux, web).

## 3.4 Instalasi Mendeley

Untuk membangun sistem manajemen referensi yang stabil, pengguna harus memasang ekosistem Mendeley secara berurutan.

**Jalur Eksekusi Cepat: Instalasi Ekosistem Mendeley**

1. **Pembuatan Akun Elsevier**: Kunjungi situs resmi Mendeley ([www.mendeley.com](https://www.mendeley.com)). Klik tombol **Create a free account** di sudut kanan atas. Masukkan alamat surel aktif (disarankan menggunakan surel institusi `.ac.id`). Lengkapi nama depan, nama belakang, kata sandi, dan data profil akademik, lalu klik **Create Account**.
2. **Mengunduh dan Memasang Mendeley Reference Manager**: Akses menu **Download** pada situs Mendeley. Klik tombol unduh sesuai sistem operasi yang digunakan. Jalankan berkas instalasi dan ikuti instruksi *Setup Wizard* hingga selesai.
3. **Pemasangan Mendeley Web Importer**: Buka aplikasi MRM, akses menu **Tools**, lalu pilih **Install Mendeley Web Importer**. Anda akan diarahkan ke toko ekstensi peramban. Klik konfirmasi pemasangan. Ikon Mendeley akan muncul di sudut kanan atas peramban.
4. **Pemasangan Mendeley Cite pada Microsoft Word**: Buka aplikasi MRM, akses menu **Tools**, lalu pilih **Install Mendeley Cite for Microsoft Word**. Laman Microsoft AppSource akan terbuka. Klik **Get it now** dan selesaikan validasi akun Microsoft. Buka aplikasi Microsoft Word. Panel Mendeley Cite akan tersedia pada tab menu **References**.

> **Troubleshooting: Mendeley Cite Tidak Muncul di Word**
> 
> **Masalah**: Anda sudah menginstal Mendeley Cite dari aplikasi MRM, tetapi saat membuka Microsoft Word, tab **References** tetap kosong dari ikon Mendeley.
> 
> **Solusi Cepat**: Ini sering terjadi karena sinkronisasi akun Microsoft. Pastikan Anda *login* ke aplikasi Word menggunakan akun Microsoft yang sama dengan saat mengunduhnya. Jika masih tidak muncul, klik menu **Insert** > **Get Add-ins** > klik tab **My Add-ins**, lalu klik **Refresh** di sudut kanan atas. Mendeley Cite akan muncul di sana.

![Proses Instalasi Mendeley](../img/elementor-placeholder-image.png)

## 3.5 Memasukkan dan Memvalidasi Referensi

Langkah awal terbaik adalah mengumpulkan berkas-berkas PDF artikel hasil unduhan dari basis data ilmiah terpercaya ke dalam satu folder khusus di penyimpanan lokal komputer.

**Metode Memasukkan Dokumen ke Mendeley:**
1. **Seret dan Lepas (*Drag and Drop*)**: Seret berkas PDF dari File Explorer dan lepaskan di area panel konten utama aplikasi MRM.
2. **Menambahkan Berkas Manual**: Klik tombol **Add new** di sudut kiri atas MRM, pilih **Files from computer**, dan pilih dokumen yang diinginkan.
3. **Entri Data Manual**: Untuk dokumen non-digital, klik **Add new**, pilih **Add manual entry**, lalu masukkan parameter bibliografi secara mandiri.
4. **Impor Berkas (*.ris/.bib*)**: Untuk data dari basis data seperti Scopus, klik **Add new** lalu **Import library**, dan pilih format berkas pertukaran data yang sesuai.

**Catatan Teknis: Melengkapi dan Memvalidasi Metadata**
Meskipun Mendeley mengekstraksi metadata secara otomatis, kesalahan dapat terjadi (misalnya judul tertulis kapital semua atau nama jurnal kosong). Untuk memperbaikinya:
1. Klik pada artikel yang metadatanya tidak lengkap di panel tengah MRM.
2. Pada panel informasi di sisi kanan, gulir ke bawah hingga menemukan kolom **Catalog IDs**.
3. Cari nomor DOI dari artikel tersebut di internet, tempelkan ke kolom DOI di Mendeley.
4. Klik ikon pencarian (kaca pembesar). Mendeley akan menarik data bibliografi yang valid dari lembaga registrasi seperti Crossref untuk menggantikan data yang rusak.

![Menambah Referensi ke Mendeley](../img/elementor-placeholder-image.png)

## 3.6 Pengelolaan Berkas Referensi

Mendeley menyediakan instrumen untuk menjaga kerapian pangkalan data pustaka Anda.

1. **Fitur Koleksi (*Collections*)**: Buat koleksi baru pada panel kiri untuk mengelompokkan referensi berdasarkan edisi jurnal atau proyek naskah.
2. **Tanda Khusus (*Tags*)**: Sisipkan kata kunci spesifik pada kolom *Tags* untuk mempermudah penyaringan pencarian.
3. **Penyaringan Duplikasi**: Rutin periksa daftar penulis melalui fitur saringan (*Filter*) untuk memastikan tidak ada entri ganda untuk artikel yang sama. Hapus entri dengan metadata yang kurang lengkap.
4. **Alat Penanda (*Highlighting* dan *Sticky Notes*)**: Klik dua kali entri artikel untuk membuka pembaca PDF internal Mendeley. Gunakan alat penanda warna dan sisipkan catatan pada teks penting. Catatan ini tersimpan secara permanen.

## 3.7 Memasukkan Sitasi ke Microsoft Word

Setelah pustaka referensi tersimpan rapi, proses penulisan sitasi dan pembuatan daftar pustaka dapat diotomatisasi melalui Microsoft Word.

**Jalur Eksekusi Cepat: Prosedur Injeksi Sitasi**
1. Buka naskah di Microsoft Word.
2. Akses tab menu **References**, lalu klik ikon **Mendeley Cite**. Masuk menggunakan akun Elsevier Anda.
3. Letakkan kursor tik pada teks yang membutuhkan rujukan.
4. Cari kata kunci (nama penulis atau judul) di kolom pencarian panel Mendeley Cite.
5. Centang kotak referensi yang sesuai, lalu klik **Insert Citation**. Kode sitasi dinamis akan tersemat.

**Jalur Eksekusi Cepat: Pengaturan Gaya Sitasi dan Pembuatan Daftar Pustaka**
1. Pada panel Mendeley Cite, buka tab **Citation Settings** dan klik **Change citation style**.
2. Pilih gaya selingkung yang digunakan jurnal tujuan, misalnya *American Psychological Association* (APA) edisi ke-7 atau *IEEE*. Jika tidak tersedia, klik **Search for another style** untuk mencari dan mengunduhnya.
3. Arahkan kursor ke bagian akhir dokumen tempat daftar pustaka akan diletakkan.
4. Klik ikon tiga titik horizontal (**More**) pada panel Mendeley Cite, lalu pilih **Insert Bibliography**.
5. Klik **Continue**. Daftar pustaka akan dibangkitkan secara otomatis dan akan diperbarui setiap kali terdapat penambahan sitasi di dalam teks.

![Memasukkan Sitasi dengan Mendeley Cite](../img/elementor-placeholder-image.png)

> **Catatan dari Lapangan: Mitigasi Masalah oleh Editor Jurnal**
> 
> Editor sering mendapati draf naskah awal dengan sumber referensi yang tidak dapat dilacak. Hal ini dapat dimitigasi melalui **Audit Sitasi Elektronik**:
> 
> 1. **Periksa Kode Bidang Otomatis**: Klik salah satu tanda sitasi dalam naskah. Jika teks tersebut berubah menjadi berlatar belakang abu-abu, berarti dokumen menggunakan kode bidang otomatis yang valid. Jika tidak, naskah diketik manual dan harus dikembalikan ke penulis.
> 2. **Uji Keaktifan Pranala (Tautan)**: Daftar pustaka yang baik menyertakan tautan DOI. Jika tautan diuji dan menghasilkan galat tidak ditemukan (*Error 404*), metadata referensi penulis bermasalah.
> 3. **Identifikasi Percampuran Gaya Sitasi**: Jika dalam satu daftar pustaka terdapat gaya penulisan yang bercampur (misalnya gaya APA berdampingan dengan gaya Vancouver), penulis kemungkinan melakukan penyalinan teks manual secara langsung dari internet ke dalam naskah mereka.

## 3.8 Sinkronisasi dan Fitur Kolaborasi

Mendeley mendukung interaksi antarpelaku akademik melalui fitur kolaborasi.

**Mekanisme Sinkronisasi Awan:**
Perubahan lokal pada MRM disinkronkan secara otomatis saat terhubung internet. Pengguna juga dapat menekan ikon lingkaran panah berputar (**Synchronize**) untuk menyelaraskan data secara manual guna memastikan salinan cadangan tersimpan di peladen awan.

**Manajemen Grup Kolaboratif (*Mendeley Groups*):**
Fitur ini krusial bagi tim redaksi (kolaborasi antara Editor Utama dan Editor Bagian) atau penulis bersama.
1. Pada panel kiri MRM, pilih menu **Groups**, lalu klik **New Group**.
2. Grup pada Mendeley terbaru berjenis Grup Privat (*Private Groups*), yang membatasi anggota hingga 25 orang. Keunggulannya, anggota dapat saling berbagi berkas PDF teks penuh.
3. Klik kanan pada nama grup, pilih **Manage Group**, dan undang anggota menggunakan alamat surel.
4. Seluruh anggota dapat menambahkan referensi. Coretan penanda atau catatan pada PDF yang dibuat oleh seorang editor akan muncul di layar editor lain dengan warna ikon yang berbeda, memangkas waktu koordinasi editorial.

## Latihan Bab 3

**Skenario Simulasi: Membangun Daftar Pustaka Otomatis dan Memperbaiki Metadata**

Anda adalah Editor Bagian yang menerima naskah dengan lima kutipan langsung tanpa format sitasi standar, dan daftar pustakanya masih diketik manual sehingga susunannya berantakan.

**Tugas:**
1. Buat folder koleksi bernama "Latihan OJS" di Mendeley Reference Manager.
2. Cari lima artikel ilmiah di pangkalan data terbuka (misalnya Google Scholar atau DOAJ) terkait tata kelola jurnal. Unduh berkas PDF-nya.
3. Masukkan kelima artikel ke folder Mendeley Anda.
4. Lakukan validasi metadata. Jika ada data yang tidak lengkap, temukan nomor DOI artikel tersebut dan gunakan fitur pencarian pada bagian *Catalog IDs* untuk melengkapinya secara otomatis.
5. Buka Microsoft Word dan siapkan paragraf kosong. Gunakan *Mendeley Cite* untuk menyisipkan kelima sitasi tersebut, dan atur gaya sitasi menjadi *American Psychological Association* (APA) edisi ke-7.
6. Bangkitkan daftar pustaka di bagian bawah halaman menggunakan fitur *Insert Bibliography*.

**Arahan Editorial (Untuk Fasilitator):** 
Pastikan seluruh peserta telah mengaktifkan akun Elsevier, memasang *Mendeley Reference Manager*, dan memasang pengaya *Mendeley Cite* pada Microsoft Word sebelum latihan dimulai. Sediakan dokumen simulasi agar peserta dapat fokus pada penggunaan Mendeley alih-alih mengetik teks naskah.

## Checklist Bab 3

- [ ] Konsep sitasi dan integritas data (mencegah manipulasi sitasi menurut panduan COPE) telah dipahami.
- [ ] Akun Elsevier telah dibuat dan diaktivasi menggunakan surel resmi.
- [ ] Mendeley Reference Manager (MRM), Mendeley Web Importer (MWI), dan Mendeley Cite telah dipasang dengan sukses.
- [ ] Dokumen referensi telah dimasukkan ke pangkalan data Mendeley dan kelengkapan metadatanya telah diverifikasi (melalui DOI/Crossref).
- [ ] Fitur penyisipan sitasi dan pembuatan daftar pustaka (*Insert Bibliography*) di Microsoft Word telah digunakan tanpa kendala teknis.
- [ ] Grup privat Mendeley telah dibuat atau dipahami fungsinya untuk kebutuhan kolaborasi tim editorial.
- [ ] Gaya sitasi telah disesuaikan secara konsisten dengan standar yang ditentukan oleh jurnal tujuan.

## Ringkasan Bab

Penggunaan perangkat lunak manajemen referensi seperti Mendeley telah berevolusi menjadi standar kompetensi wajib bagi penulis dan dewan redaksi jurnal. Melalui ekosistem digitalnya yang mutakhir, Mendeley menawarkan solusi automasi yang memotong jalur birokrasi penulisan manual yang rentan terhadap kesalahan. Ketelitian dalam melengkapi keandalan metadata bibliografi sejak awal dokumen diunggah merupakan kunci utama keberhasilan sistem ini. Standardisasi proses sitasi ini tidak hanya menaikkan citra profesionalisme jurnal ilmiah, tetapi juga berkontribusi langsung dalam melindungi integritas dan keandalan rekam jejak publikasi akademik secara global.
