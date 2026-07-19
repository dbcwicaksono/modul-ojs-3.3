# Bab 8: Menugaskan Peninjau (*Assigning Reviewer*)

> **Pemantik Bab**
> Menemukan mitra bestari (*reviewer*) yang bersedia meluangkan waktunya secara sukarela, memiliki kepakaran yang tepat, dan mampu mengembalikan hasil evaluasi tepat waktu adalah salah satu tantangan paling berat dalam tata kelola jurnal. Fenomena "keletihan peninjau" (*reviewer fatigue*) kini diakui sebagai krisis sistemik global dalam penerbitan ilmiah, didorong oleh ledakan jumlah naskah yang tidak diimbangi ketersediaan pakar. Merespons krisis ini, beberapa editor yang panik mulai menggunakan alat kecerdasan buatan (AI) untuk mengirim ribuan undangan *review* acak kepada siapapun yang namanya muncul di internet (*spamming*). Praktik putus asa ini dikecam keras oleh DOAJ karena menghancurkan integritas (*quality control*) dari sistem *peer review*.

Setelah naskah berhasil melewati saringan ketat pada tahap *Desk Review* dan bebas dari indikasi plagiasi, proses beralih ke jantung dari sistem penerbitan keilmuan: Penelaahan Sejawat (*Peer Review*). Bab ini akan memandu Anda dalam menavigasi pangkalan data pakar OJS 3.3, memilih kandidat secara etis, memitigasi krisis kelelahan peninjau, mengatur batas waktu yang rasional, serta memantau jalannya proses penelaahan.

## 8.1 Editor Bagian Sebagai Garda Terdepan

Pada tahap ini, **Editor Bagian (*Section Editor*)** mengambil alih kendali penuh operasional. Sebagaimana dijelaskan pada **Bab 1: Gambaran Umum Alur Kerja Editorial OJS**, Editor Bagian adalah spesialis yang ditugaskan khusus oleh Editor Kepala untuk mengelola lalu lintas naskah pada rumpun ilmu tertentu. 

Untuk mencegah beban informasi berlebih (*information overload*), dasbor OJS 3.3 secara otomatis membatasi pandangan Editor Bagian. Mereka hanya akan melihat naskah-naskah yang didelegasikan ke dalam tab **My Queue** mereka. Dengan demikian, Editor Bagian dapat memusatkan seluruh atensinya pada pencarian mitra bestari yang paling mumpuni tanpa terganggu oleh tumpukan naskah dari disiplin ilmu lain.

## 8.2 Memastikan Keamanan Dokumen (*Blinding*)

Langkah absolut pertama sebelum menugaskan peninjau adalah memindahkan naskah ke tahap *Review*. Saat editor mengklik **Send to Review** pada tahap *Submission*, sebuah jendela konfirmasi pengiriman berkas akan muncul.

**Perhatian Kritis untuk Penelaahan Nirnama Ganda (*Double-Blind Review*):**
Editor Bagian wajib memverifikasi bahwa berkas yang dipilih bersih dari segala metadata personal penulis. Menyerahkan naskah yang masih memuat identitas penulis kepada mitra bestari adalah bentuk pelanggaran etika editorial yang fatal dan dapat menggugurkan prinsip objektivitas akademis. Jika berkas belum bersih, editor harus membatalkan tindakan ini, membersihkan dokumen secara luring, mengunggah ulang, lalu mengulangi proses pengiriman ke tahap penelaahan.

## 8.3 Strategi Pemilihan Mitra Bestari

Untuk mengundang peninjau, klik tombol **Add Reviewer** di panel *Reviewers*. OJS 3.3 tidak sekadar menampilkan daftar nama, melainkan menyediakan metrik kecerdasan historis untuk memandu keputusan Editor Bagian:

| Parameter Pencarian | Signifikansi Keputusan Editorial |
|---------------------|----------------------------------|
| **Minat Meninjau (*Reviewing Interests*)** | Parameter utama. Filter ini memastikan naskah ditugaskan kepada pakar dengan kepakaran spesifik (*subject matter expert*) yang selaras dengan teori naskah. |
| **Jumlah Tinjauan Selesai** | Mengindikasikan loyalitas dan keandalan peninjau terhadap jurnal Anda. |
| **Rata-rata Waktu (*Average Days*)** | Kunci prediksi ketepatan waktu. Mengetahui apakah seorang pakar biasanya mengembalikan ulasan dalam 2 minggu atau 2 bulan. |
| **Tinjauan Aktif (*Active Reviews*)** | Metrik vital untuk mencegah *reviewer fatigue*. Jangan menugaskan pakar yang sedang menelaah lebih dari dua naskah secara bersamaan. |

> **Sorotan Standar Global: Mencegah Konflik Kepentingan (COPE)**
> 
> *Committee on Publication Ethics* (COPE) menetapkan aturan ketat terkait kemandirian dan objektivitas (*independence and objectivity*) dalam penelaahan sejawat. Editor Bagian dilarang keras menugaskan mitra bestari yang memiliki konflik kepentingan (*conflict of interest*) dengan penulis. Bentuk konflik ini meliputi: memiliki afiliasi dengan institusi yang sama, memiliki hubungan keluarga, atau pernah menjadi rekan kerja dalam proyek publikasi/hibah selama tiga tahun terakhir. Jika jurnal tidak memiliki pakar eksternal yang independen di dalam pangkalan data, editor wajib melakukan rekrutmen peninjau baru sebelum mengeksekusi penugasan.
> 
> *Sumber: [https://publicationethics.org/](https://publicationethics.org/)*

> **Catatan Kritis: Bahaya Spam Undangan AI (Peringatan DOAJ)**
> 
> *Directory of Open Access Journals* (DOAJ) secara khusus menyoroti ancaman baru terhadap integritas jurnal terbuka, yaitu penggunaan perangkat kecerdasan buatan (AI) oleh editor untuk meraup (*scraping*) dan mengirimkan undangan peninjauan secara massal kepada ribuan orang yang tidak relevan. Tindakan kepanikan ini diambil oleh editor untuk memitigasi *reviewer fatigue*, namun hasilnya justru fatal. DOAJ secara tegas menyatakan bahwa praktik undangan *spam* ini merusak kualitas ulasan dan dapat menjadi alasan pencabutan jurnal dari pangkalan data indeks DOAJ. Editor harus memperluas jejaring secara organik dan selektif.

## 8.4 Pengaturan Parameter Undangan Penelaahan

**Jalur Eksekusi Cepat: Menugaskan Mitra Bestari**
1. Pada tahap *Review*, klik tombol **Add Reviewer**.
2. Gunakan saringan pencarian berdasarkan kepakaran (*Reviewing Interests*).
3. Klik tombol **Select Reviewer** pada nama pakar yang dipilih.
4. Pada panel konfigurasi surel, tambahkan sapaan personal atau instruksi khusus.
5. Atur tanggal *Response Due Date* (Batas Konfirmasi) dan *Review Due Date* (Batas Pengumpulan).
6. Centang formulir penilaian (*Review Form*) yang tepat jika tersedia.
7. Klik **Add Reviewer** di bagian bawah panel untuk mengeksekusi pengiriman undangan.

> **Troubleshooting: Peninjau Diundang Tetapi Tidak Merespons**
> 
> **Masalah**: Anda sudah mengirim undangan 10 hari yang lalu, tetapi status peninjau masih belum menerima atau menolak tugas tersebut.
> 
> **Solusi Cepat**: Buka panel ulasan peninjau tersebut. Jangan biarkan naskah menggantung terlalu lama. Klik **Send Reminder** jika Anda masih bersedia menunggunya. Jika Anda membutuhkan proses cepat, klik **Unassign Reviewer** untuk mencabut undangan tersebut dan langsung menugaskan peninjau alternatif.

Setelah mitra bestari dipilih, Editor Bagian dihadapkan pada panel konfigurasi penugasan yang lebih terperinci.

### 1. Templat Surel Otomatis dan Kustomisasi
OJS menyediakan templat surel undangan yang menggunakan variabel (*placeholders*) untuk menarik data secara dinamis, seperti nama peninjau (`{$reviewerName}`) dan abstrak naskah (`{$abstract}`). Editor Bagian disarankan untuk menambahkan sapaan personal atau instruksi spesifik di dalam badan surel untuk meningkatkan probabilitas kesediaan mitra bestari. Undangan yang terasa sangat mekanis (robotik) lebih sering diabaikan oleh para pakar.

### 2. Standar Kalibrasi Waktu Evaluasi
*Directory of Open Access Journals* (DOAJ) mensyaratkan durasi waktu yang masuk akal dan wajar untuk menjaga mutu ulasan. Terdapat dua tenggat waktu yang harus dikonfigurasi:

- **Batas Konfirmasi (*Response Due Date*)**: Waktu yang diberikan bagi pakar untuk membalas undangan (Menerima atau Menolak). Standar ideal: **3 hingga 7 hari**.
- **Batas Pengumpulan (*Review Due Date*)**: Waktu maksimal untuk mengumpulkan hasil ulasan mendalam. Standar ideal industri akademik: **4 minggu (28 hari)** sejak undangan diterima.

### 3. Pemilihan Formulir Penilaian (*Review Form*)
Apabila jurnal memiliki instrumen penilaian terstruktur (misalnya pembobotan khusus untuk metodologi), Editor Bagian harus mengaitkan penugasan ini dengan formulir penilaian dari menu tarik-turun (*drop-down*). Fitur ini memperjelas indikator evaluasi bagi mitra bestari dibandingkan hanya memberikan kotak teks kosong.

> **Catatan dari Lapangan: Kesenjangan Kuota Mitra Bestari**
> 
> Syarat validitas *peer review* yang diakui secara universal menuntut naskah ditinjau sekurang-kurangnya oleh **dua orang pakar independen**. Sering kali, editor hanya mengirimkan undangan kepada dua orang. Ketika salah satu menolak (atau mengabaikan) undangan, proses naskah tersebut akan lumpuh berhari-hari. Praktik manajerial terbaik bagi Editor Bagian adalah menugaskan tiga atau bahkan empat kandidat di awal. Begitu dua mitra bestari menyatakan kesediaannya, editor dapat segera membatalkan penugasan kandidat lainnya dengan mengirimkan surel apresiasi.

## 8.5 Pemantauan dan Intervensi Pengingat (*Reminders*)

Begitu tombol konfirmasi penugasan ditekan, sistem bergerak memindahkan nama peninjau ke panel pemantauan. Editor Bagian dapat melacak riwayat tindakan peninjau secara langsung, mulai dari waktu surel dibaca hingga keputusan menerima tugas.

Jika *Response Due Date* semakin dekat namun peninjau belum merespons, editor dapat melakukan intervensi dengan menekan tautan **Send Reminder** yang akan mengirimkan notifikasi peringatan. Jika langkah ini tidak berhasil, editor dapat menggunakan fitur **Notify** (lambang pesan) untuk menghubungi peninjau secara lebih kasual atau segera membatalkan penugasan (*Unassign*) untuk beralih ke kandidat berikutnya.

## Latihan Bab 8

**Skenario Simulasi: Mengeksekusi Penugasan Mitra Bestari**

Sebagai Editor Bagian, Anda telah meloloskan sebuah naskah bertopik *Artificial Intelligence* pada tahap prakajian. Naskah tersebut harus ditinjau, namun Anda sadar bahwa para pakar di bidang tersebut sangat sibuk.

**Tugas Praktik:**
1. Di tahap *Submission*, klik *Send to Review*. Pastikan dokumen naskah telah bersih dari identitas penulis.
2. Buka tahap *Review*. Klik **Add Reviewer**.
3. Gunakan saringan (*filter*) untuk mencari pakar dengan kata kunci "Artificial Intelligence". Temukan kandidat yang memiliki nilai beban kerja terendah (angka nol pada *Active Reviews*).
4. Konfigurasikan tanggal *Response Due Date* menjadi 5 hari dari hari ini, dan *Review Due Date* menjadi 21 hari.
5. Tambahkan satu kalimat sapaan personal ("Kami sangat menghargai kepakaran Anda di bidang AI...") pada templat surel undangan otomatis. 
6. Eksekusi pengiriman undangan.
7. Lakukan simulasi pengiriman pengingat (*reminder*) kepada kandidat tersebut.

**Arahan Editorial (Untuk Fasilitator):** 
Pastikan pangkalan data jurnal percobaan telah diisi oleh beberapa akun *dummy* yang berperan sebagai peninjau dengan berbagai minat menelaah (*reviewing interests*), agar fitur saringan pencarian dapat dioperasikan secara realistis oleh peserta.

## Checklist Bab 8

- [ ] Memahami pembagian peran strategis di mana Editor Bagian (*Section Editor*) menjadi komandan utama pada tahap *Review*.
- [ ] Memastikan pembersihan identitas personal penulis pada dokumen sebelum dipindahkan dari tahap *Submission* ke *Review*.
- [ ] Mampu menganalisis metrik riwayat mitra bestari (*Average Days*, *Active Reviews*) untuk mencegah *reviewer fatigue*.
- [ ] Mampu memitigasi potensi konflik kepentingan (sesuai standar COPE) dalam pemilihan pakar.
- [ ] Mengonfigurasi batas waktu konfirmasi dan evaluasi dengan standar kalibrasi yang rasional.
- [ ] Menguasai prosedur pelacakan status (*monitoring*) dan pengiriman peringatan (*reminder*) kepada mitra bestari yang pasif.

## Ringkasan Bab

Tahap penelaahan sejawat adalah mekanisme penjaga mutu (*quality control*) tertinggi dalam penerbitan ilmiah, dan pelaksanaannya sangat bergantung pada kecekatan Editor Bagian. Dengan memanfaatkan integrasi pangkalan data OJS, mulai dari analisis metrik historis peninjau, pemanfaatan templat surel dinamis terotomatisasi, hingga pemantauan berbasis batas waktu yang akurat, editor dapat mengurangi inefisiensi alur kerja secara substansial. Kemampuan editor untuk memitigasi kelelahan mitra bestari dan menegakkan batasan etis mengenai konflik kepentingan akan secara langsung menentukan integritas dan kredibilitas keilmuan jurnal di mata komunitas akademik global.
