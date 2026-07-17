# Bab 7: Menugaskan Peninjau (Assigning Reviewer)

Setelah naskah lolos dari tinjauan awal meja (*desk review*) dan pemeriksaan kemiripan (*similarity check*), tahap selanjutnya adalah mengirimkan naskah ke proses penelaahan sejawat (*peer review*). Bab ini memandu editor dalam memilih mitra bestari (*reviewer*) yang tepat, mengatur parameter penugasan, dan memantau jalannya proses penelaahan.

## 7.1 Memindahkan Naskah ke Tahap Review

Sebelum menugaskan mitra bestari, pastikan naskah telah siap secara teknis dan substantif untuk ditinjau.

Prosedur Teknis:
1. **Evaluasi pra-review**: Periksa kelengkapan dokumen kiriman dan fungsikan fitur *Pre-review Discussions* jika terdapat aspek yang perlu diklarifikasi dengan penulis.
2. Klik tombol **"Send to Review"** di panel kanan halaman naskah.
3. Sistem akan menampilkan daftar seluruh komponen naskah. Editor harus memilih dokumen yang akan dikirimkan kepada mitra bestari.

Perhatian Kritis untuk Penelaahan Nirnama Ganda (*Double-Blind Review*): Sebelum mengklik konfirmasi pengiriman, editor wajib memastikan bahwa dokumen yang dipilih telah melalui proses anonimisasi (*blinding*). Hapus seluruh identitas penulis dari properti dokumen dan badan naskah. Dilarang keras mengirimkan dokumen yang masih memuat nama atau afiliasi penulis kepada mitra bestari.

4. Setelah dikonfirmasi, status naskah secara otomatis berpindah dari tahap *Submission* ke tahap **Review (Round 1)**.

![Jendela pemilihan file untuk Send to Review](../img/elementor-placeholder-image.png)

## 7.2 Antarmuka Section Editor dan Editor Kepala

OJS 3.3 menerapkan pembagian tampilan berbasis peran yang spesifik untuk mencegah terjadinya beban informasi berlebih (*information overload*). Beban informasi berlebih adalah kondisi di mana editor dihadapkan pada volume data yang terlalu besar sehingga menghambat efisiensi pengambilan keputusan.

| Peran | Tampilan Dasbor | Tab Akses Utama |
|-------|----------------|-------------------|
| **Editor Kepala** | Kontrol menyeluruh atas semua naskah. | My Queue, **Unassigned**, **All Active**, Archives |
| **Section Editor** | Terfokus pada penugasan spesifik. | Hanya **My Queue** (naskah yang menjadi tanggung jawabnya) |

Sistem navigasi terfokus ini memungkinkan Section Editor bekerja lebih efisien tanpa terganggu oleh data naskah di luar tanggung jawabnya.

## 7.3 Memilih Mitra Bestari yang Tepat

Klik tombol **"Add Reviewer"** di panel *Reviewers* untuk mengakses basis data mitra bestari. OJS 3.3 menyediakan parameter pencarian mendalam untuk mendukung pengambilan keputusan berbasis rekam jejak:

| Parameter Pencarian | Keterangan |
|---------------------|-----------|
| **Jumlah Tinjauan** | Total penugasan penelaahan yang pernah diselesaikan oleh mitra bestari di jurnal ini. |
| **Rata-rata Waktu** | Kecepatan historis penyelesaian tugas (dalam hitungan hari atau minggu). |
| **Tinjauan Aktif** | Jumlah naskah yang sedang ditangani oleh mitra bestari saat ini. Angka tinggi berisiko memicu *reviewer fatigue*. |
| **Waktu Sejak Tinjauan Terakhir** | Kapan terakhir kali mitra bestari berpartisipasi, yang berguna untuk menilai tingkat keaktifan. |
| **Minat Meninjau** | Bidang keahlian mitra bestari yang didaftarkan. Sesuaikan kolom ini dengan topik naskah. |

Keletihan mitra bestari (*reviewer fatigue*) adalah fenomena menurunnya kualitas dan kecepatan penelaahan akibat beban tugas peninjauan yang berlebihan dan dilakukan secara terus-menerus. Editor harus menjaga keseimbangan beban kerja mitra bestari.

![Panel pemilihan reviewer dengan parameter pencarian](../img/elementor-placeholder-image.png)

### Etika Pemilihan Mitra Bestari (Standar COPE)

Pemilihan mitra bestari harus dilandasi objektivitas keahlian. Panduan Committee on Publication Ethics (COPE) menekankan bahwa editor tidak boleh menugaskan mitra bestari yang diketahui memiliki konflik kepentingan (*conflict of interest*) dengan penulis naskah (COPE, 2017). Konflik kepentingan meliputi hubungan keluarga, hubungan kerja (afiliasi institusi yang sama), atau kolaborasi publikasi dalam tiga tahun terakhir.

**Studi Kasus:** Sebuah jurnal naskah biologi kelautan membutuhkan mitra bestari khusus. Editor menemukan lima pakar di sistem, tetapi setelah ditelusuri, kelima pakar tersebut bekerja di institusi yang sama dengan penulis atau pernah menjadi rekan penulis makalah di tahun sebelumnya. Mengingat asas *double-blind review* dan potensi konflik kepentingan, editor dilarang keras menugaskan mereka. Sebagai gantinya, editor wajib mencari calon peninjau dari institusi atau negara lain, lalu mendaftarkan mereka ke dalam basis data OJS sebagai mitra bestari baru sebelum menugaskannya.

## 7.4 Mengatur Parameter Penugasan

Setelah memilih kandidat, sistem akan menampilkan formulir penugasan untuk mengatur detail evaluasi.

### Templat Surel Undangan

OJS menyediakan draf surel undangan otomatis yang menggunakan *Placeholders* untuk menarik metadata naskah secara dinamis:

| Placeholder | Data yang Diambil |
|-------------|-------------------|
| `{$reviewerName}` | Nama mitra bestari |
| `{$submissionTitle}` | Judul naskah |
| `{$abstract}` | Abstrak naskah |
| `{$reviewDueDate}` | Tanggal batas akhir ulasan |
| `{$journalName}` | Nama jurnal |

Editor dapat menyesuaikan atau menambahkan instruksi khusus pada badan surel sebelum dikirimkan.

### Standar Waktu Peninjauan

Standar Directory of Open Access Journals (DOAJ) mensyaratkan durasi waktu yang wajar dan transparan dalam penelaahan sejawat. DOAJ menetapkan standar kelayakan minimal proses evaluasi editorial adalah 4 minggu, dengan standar kelaziman jurnal internasional berkisar di 8 minggu. Pengelola jurnal harus mempertimbangkan durasi ini saat mengatur parameter penugasan:

| Tanggal Parameter | Keterangan |
|---------|-----------|
| **Response Due Date** | Batas waktu konfirmasi kesediaan (menerima atau menolak undangan). Idealnya diatur 3 hingga 7 hari. |
| **Review Due Date** | Batas akhir pengumpulan hasil ulasan lengkap. Idealnya diatur 4 minggu (28 hari) dari tanggal penugasan. |

### Formulir Penilaian

Apabila pengelola jurnal menggunakan instrumen penilaian terstruktur, editor harus memilih formulir penilaian dari menu tarik-turun (*drop-down*). Pengaturan formulir khusus ini merupakan wewenang Manajer Jurnal (*Journal Manager*) melalui menu pengaturan sistem.

![Formulir penugasan reviewer dengan parameter lengkap](../img/elementor-placeholder-image.png)

## 7.5 Konfirmasi dan Pemantauan Penugasan

Setelah parameter ditetapkan dan tombol **"Add Reviewer"** dieksekusi, sistem beroperasi secara otomatis untuk:
1. Mengirimkan surel undangan formal kepada mitra bestari.
2. Memasukkan nama mitra bestari ke dalam daftar pantauan di panel *Reviewers*.

Editor beralih ke fase pemantauan. Melalui dasbor OJS, editor memonitor:
- Status keterbacaan surel undangan oleh mitra bestari.
- Keputusan penerimaan atau penolakan penugasan.
- Perkembangan pengunggahan hasil ulasan.
- Kebutuhan intervensi pengingat (*reminder*).

![Panel pemantauan reviewer: status dan tanggal](../img/elementor-placeholder-image.png)

### Pengiriman Pengingat (Reminder)

Jika mitra bestari belum memberikan respons menjelang tanggal batas konfirmasi (*Response Due Date*), editor dapat menempuh dua cara:
- Menggunakan tombol **"Send Reminder"** yang tersedia di sebelah nama mitra bestari, atau
- Menggunakan fitur diskusi surel (*Notify*) untuk berkomunikasi secara lebih personal.

## 7.6 Mengelola Kelengkapan Peninjauan

Standar akademik kelayakan sebuah naskah umumnya mensyaratkan keterlibatan sekurang-kurangnya dua orang mitra bestari independen. Editor harus mengulangi langkah penugasan untuk melengkapi kuota peninjauan.

Praktik Terbaik:
- Tugaskan mitra bestari yang berasal dari latar belakang institusi atau geografis yang berbeda guna menghindari bias.
- Apabila mitra bestari utama menolak undangan, segera cari kandidat alternatif untuk mencegah penundaan durasi editorial.
- Jurnal bereputasi sering kali mengundang tiga kandidat di awal untuk mengantisipasi penolakan atau keterlambatan peninjauan.

## Checklist Bab 7

- [ ] Seluruh dokumen naskah yang dikirimkan telah dibersihkan dari properti metadata personal (*blinding*).
- [ ] Kandidat mitra bestari telah dipilih berdasarkan kesesuaian kepakaran (minat meninjau).
- [ ] Verifikasi ketidakadaan konflik kepentingan antara mitra bestari dan penulis telah dipastikan.
- [ ] Batas waktu konfirmasi (*Response Due Date*) dan penyelesaian ulasan (*Review Due Date*) telah diatur dengan rentang waktu wajar (standar DOAJ: minimal 4 minggu).
- [ ] Templat surel undangan penelaahan telah disesuaikan dengan kebutuhan naskah.
- [ ] Minimal dua mitra bestari independen telah berhasil ditugaskan untuk naskah.

## Ringkasan Bab

Manajemen penugasan penelaahan sejawat yang disiplin merupakan pilar penjaga mutu akademik jurnal. Dengan memanfaatkan basis data OJS, parameter pencarian berbasis metrik historis, serta pengaturan tanggal batas waktu sesuai standar DOAJ, editor dapat menjalankan alur *peer review* yang efisien. Pemahaman terhadap fenomena keletihan peninjau (*reviewer fatigue*) serta ketegasan dalam menegakkan aturan tanpa konflik kepentingan (*conflict of interest*) adalah ciri khas pengelolaan jurnal yang berintegritas.
