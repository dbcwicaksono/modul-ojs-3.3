# Bab 7: Pemeriksaan Kemiripan (*Similarity Check*)

> **Pemantik Bab**
> Laporan Turnitin baru saja keluar. Angka kemiripan (similarity index) pada layar menunjukkan 35%, jauh di atas batas toleransi jurnal Anda yang sebesar 20%. Tanpa berpikir panjang, Anda langsung menekan tombol penolakan (Decline Submission) dengan alasan plagiarisme fatal. Namun keesokan harinya, penulis memprotes keras: "Semua teks yang disorot merah oleh Turnitin adalah rumus matematika standar, nama institusi, dan daftar pustaka!" Anda memeriksa ulang laporannya dan menyadari bahwa sang penulis benar. Anda baru saja menolak naskah orisinal karena membaca laporan mesin secara mentah tanpa intervensi akal budi editorial.

Salah satu tugas fundamental tim editorial adalah memastikan setiap naskah yang terbit merupakan karya orisinal. Pada alur kerja OJS, pemeriksaan kemiripan (*similarity check*) merupakan tahap krusial yang menjembatani fase *Desk Review* dengan *Peer Review*. Bab ini akan memandu Anda untuk tidak sekadar bergantung pada persentase angka, melainkan menafsirkan laporan kemiripan secara operasional.

## 7.1 Miskonsepsi Angka Kemiripan dan Plagiarisme

Dalam diskusi pengelolaan jurnal, sering kali istilah "pemeriksaan plagiasi" digunakan secara serampangan untuk merujuk pada perangkat lunak seperti Turnitin atau iThenticate. Secara konseptual, penamaan tersebut tidak akurat. Perangkat lunak mesin pencari **tidak dirancang untuk mendeteksi plagiarisme**, melainkan hanya mendeteksi **kemiripan teks (*text similarity*)**.

Plagiarisme, berdasarkan Permendiknas No. 17 Tahun 2010 maupun standar akademik global, adalah niat atau kelalaian untuk mengambil gagasan orang lain tanpa pengakuan yang sah. Mesin tidak dapat mengukur niat, mesin hanya mencocokkan deretan karakter. Oleh karena itu, persentase kemiripan yang tinggi (misalnya 40%) tidak selalu berarti plagiarisme jika yang terdeteksi adalah lampiran kuesioner baku, sedangkan persentase rendah (misalnya 5%) bisa jadi merupakan pencurian gagasan radikal apabila satu paragraf sentral disalin tanpa atribusi sitasi. Intervensi manusia (*human judgment*) adalah satu-satunya penentu apakah sebuah kemiripan teks dapat diklasifikasikan sebagai plagiasi akademik.

## 7.2 Membaca Laporan Kemiripan dengan Bijak

Ketika Editor Bagian menerima naskah, perangkat lunak kemiripan harus dikonfigurasi secara cermat sebelum laporannya dianalisis. Analisis yang bijak menuntut editor untuk mampu membedakan tiga fenomena pembentuk persentase laporan:

1.  **Positif Palsu (*False Positive*)**: Ini adalah pemicu utama inflasi angka kemiripan. Kutipan langsung yang sudah diapit tanda kutip ganda, frasa umum akademik ("Penelitian ini bertujuan untuk..."), nama kementerian atau institusi resmi, hingga keseluruhan daftar pustaka sering kali ditandai merah oleh mesin. Editor wajib menggunakan fitur penyaringan (*filter/exclude*) pada perangkat lunak untuk menyingkirkan kutipan langsung (*quotes*) dan bibliografi sebelum membaca angka akhir.
2.  **Plagiasi Diri (*Self-Plagiarism/Text Recycling*)**: Fenomena di mana penulis menggunakan kembali teks dari karya mereka sendiri yang telah terbit sebelumnya. Meski terkesan tidak merugikan pihak lain, praktik ini dilarang keras karena melanggar premis "orisionalitas kebaruan" (*novelty*) dari sebuah naskah riset. Jika mesin mendeteksi kemiripan dominan yang merujuk pada tesis mahasiswa atau prosiding konferensi penulis itu sendiri yang sudah diterbitkan, naskah tersebut bermasalah.
3.  **Plagiasi Aktual (*Direct/Mosaic Plagiarism*)**: Pencurian murni di mana blok kalimat dari karya peneliti lain digabungkan tanpa teknik parafrasa yang baik dan tanpa pencantuman sitasi yang memadai.

> **Catatan dari Lapangan: Jebakan Bagian Metodologi**
> 
> Beberapa editor jurnal keperawatan dan ilmu eksakta kerap berdebat sengit dengan penulis mengenai indikasi kemiripan pada bagian Metodologi. Dalam riset klinis atau uji laboratorium, prosedur eksperimental dan spesifikasi alat ukur adalah hal yang sangat baku. Menuntut penulis untuk memarafrase nama reagen kimia atau prosedur standar operasi alat medis demi mengejar angka kemiripan 0% adalah tindakan yang keliru dan berisiko merusak akurasi sains. Kebijaksanaan editorial harus diterapkan: kemiripan yang terkonsentrasi hanya di bab metodologi standar jauh lebih dapat ditoleransi dibandingkan kemiripan yang ditemukan di bab Kesimpulan atau Temuan Penelitian.

## 7.3 Spektrum Toleransi Indeks Kemiripan

Sering kali muncul pertanyaan di forum pengelola jurnal: *"Berapa batas maksimal persentase Turnitin yang diizinkan?"*

Secara global, tidak ada konvensi angka baku tunggal. Namun di Indonesia, Kementerian Pendidikan, Kebudayaan, Riset, dan Teknologi menjadikan angka **25%** sebagai batas wajar toleransi administratif maksimal. Jurnal internasional bereputasi umumnya mematok ambang batas yang lebih ketat, berkisar di angka **15% hingga 20%**. 

**Prinsip Sumber Dominan Tertunggal**
Ketentuan persentase total tidak boleh dibaca secara terisolasi. Jika sebuah naskah menghasilkan total skor 18% (berada di bawah ambang batas aman jurnal Anda), namun 15% di antaranya berasal dari penyalinan mentah dari **satu sumber tunggal**, naskah tersebut hakikatnya memuat pelanggaran etika yang berat. Sebaliknya, skor total 22% yang tersusun dari akumulasi 1% kemiripan yang tersebar di 22 sumber berbeda jauh lebih sehat karena umumnya merepresentasikan kelemahan memarafrasa, bukan pencurian substansial. 

## 7.4 Ekosistem Perangkat Lunak Pemeriksa

Pengelola jurnal harus membekali infrastruktur redaksinya dengan mesin pemindai yang memadai. Layanan berbayar profesional, seperti **Turnitin** dan saudara kandungnya **iThenticate**, merupakan standar emas (*gold standard*) di ranah penerbitan ilmiah karena memiliki hak akses eksklusif ke pangkalan data luring jurnal-jurnal berlangganan berbayar sedunia. iThenticate khususnya dirancang lebih spesifik untuk ekosistem editorial (sebagai penapis dokumen siap terbit), berbeda dengan Turnitin yang lebih berorientasi pada ekosistem penugasan kelas perkuliahan.

Bagi jurnal independen yang masih beroperasi tanpa dukungan finansial universitas, perangkat lunak gratis sering menjadi pelarian. Aplikasi semacam Duplichecker atau SmallSEOTools memang memberikan kemudahan akses, namun editor harus menyadari kelemahan absolutnya: batasan analisis yang hanya memindai hingga 1.000 kata per sesi dan algoritma yang hanya meraba arsip internet terbuka (*open web*). Tulisan yang menyalin naskah jurnal terkemuka berbayar tidak akan terdeteksi oleh perangkat gratis ini. Untuk jurnal yang merencanakan eskalasi akreditasi ke SINTA tingkat atas atau indeksasi Scopus, penganggaran lisensi premium bukan lagi pilihan, melainkan keharusan untuk mitigasi etika (*ethical mitigation*).

> **Sorotan Standar Global: Diagram Alir COPE untuk Kasus Plagiarisme**
> 
> *Committee on Publication Ethics* (COPE) menyediakan kerangka kerja definitif mengenai apa yang harus dilakukan editor jika menemukan indikasi plagiarisme yang tinggi sebelum publikasi. Prosedur utamanya melarang editor untuk menolak naskah secara diam-diam. Editor diwajibkan untuk mengumpulkan bukti laporan kemiripan, menghubungi seluruh penulis secara formal untuk meminta penjelasan, dan menahan alur naskah. Jika penjelasan penulis tidak memuaskan atau mereka mengakui kesalahan, barulah naskah ditolak dan editor mempertimbangkan untuk memberitahu institusi afiliasi penulis apabila pelanggarannya masif.
> 
> *Sumber: [https://publicationethics.org/guidance/Flowcharts](https://publicationethics.org/guidance/Flowcharts)*

## 7.5 Integrasi Pemeriksaan dalam OJS

Pemeriksaan kemiripan bukanlah modul bawaan pabrik dari instalasi dasar OJS 3.3. Secara konvensional, editor mengunduh naskah penulis dari panel *Submission Files*, mengunggahnya secara manual ke platform Turnitin/iThenticate, mengunduh hasil PDF-nya, lalu melampirkannya kembali ke dalam sistem OJS.

**Jalur Eksekusi Cepat: Melampirkan Laporan Kemiripan Secara Manual**
1. Unduh laporan kemiripan berformat PDF dari Turnitin atau iThenticate.
2. Buka naskah di OJS, masuk ke panel **Submission Files**.
3. Klik tautan **Upload File**.
4. Pilih komponen dokumen (misalnya **Other** atau buat komponen khusus **Similarity Report** jika admin Anda telah menambahkannya).
5. Unggah berkas PDF tersebut dan klik **Save**.
6. (Opsional) Buka panel **Pre-review Discussions**, buat pesan baru untuk penulis jika angka kemiripan perlu diturunkan, lalu lampirkan fail PDF tadi agar penulis bisa melihat bagian mana saja yang perlu diparafrasa.

> **Troubleshooting: Turnitin Menyorot Seluruh Daftar Pustaka**
> 
> **Masalah**: Anda melihat skor kemiripan mencapai 40%, tetapi setelah dibuka, 30%-nya adalah blok warna merah menyala pada bagian Daftar Pustaka (Referensi) di akhir naskah.
> 
> **Solusi Cepat**: Ini adalah *false positive* klasik. Jangan tolak naskah tersebut. Buka laporan Turnitin Anda, cari ikon **Filter** (berbentuk corong), lalu centang opsi **Exclude Bibliography** dan **Exclude Quotes**. Klik **Apply Changes**. Angka kemiripan akan langsung turun drastis menampilkan persentase riil dari isi naskah sesungguhnya.

Untuk memangkas birokrasi manual ini, PKP menyediakan dukungan *plugin* integrasi API (*Application Programming Interface*). Jika jurnal Anda memiliki administrator sistem yang andal dan lisensi layanan yang valid, *plugin* iThenticate dapat dihubungkan langsung ke OJS. Dengan aktivasi ini, persentase kemiripan naskah baru akan muncul secara otomatis di sebelah nama dokumen.

## Latihan Bab 7

**Skenario Simulasi: Membedah Laporan Palsu**

Sebuah naskah kajian teologi kontemporer diserahkan ke sistem Anda. Laporan Turnitin menunjukkan indeks kemiripan sebesar **31%** (di atas ambang batas wajar). Sebagai Editor Bagian, Anda menelusuri rincian laporan tersebut:
- 15% kemiripan berasal dari kutipan langsung ayat-ayat kitab suci yang terjemahannya baku.
- 5% kemiripan berasal dari blok panjang daftar pustaka.
- 11% kemiripan berasal dari tiga blog mahasiswa berbeda yang kalimat-kalimatnya tersebar sporadis pada bab pengantar.

**Tugas Praktik:**
1. Berdasarkan teori yang telah dijabarkan di atas, apakah Anda akan langsung menekan tombol *Decline Submission*? Mengapa?
2. Buka jurnal simulasi OJS Anda. Temukan naskah acak di menu *Submission*.
3. Gunakan fitur *Pre-review Discussions*. Simulasikan penulisan pesan profesional kepada penulis fiktif tersebut untuk meminta mereka melakukan perbaikan struktur bahasa (parafrasa) agar sisa kemiripan sebesar 11% dapat ditekan.
4. Lampirkan berkas (fiktif) PDF laporan kemiripan ke dalam ruang diskusi tersebut.

**Arahan Editorial (Untuk Fasilitator):** 
Pandu peserta untuk memahami konsep *Exclude Quotes* dan *Exclude Bibliography*. Tanamkan pola pikir bahwa editor bukan sekadar hakim angka kalkulator, melainkan analis substansi. Latih cara menegur penulis melalui OJS dengan bahasa yang konstruktif dan tidak menuduh.

## Checklist Bab 7

- [ ] Ambang batas toleransi indeks kemiripan (*similarity index*) telah ditetapkan dan dicantumkan secara transparan pada menu Kebijakan Jurnal (*Journal Policies*) di situs web.
- [ ] Editor telah menguasai pengaturan penyaringan laporan perangkat lunak (mengecualikan bibliografi dan blok kutipan langsung) untuk mengeliminasi positif palsu.
- [ ] Proses *Desk Review* tidak akan meloloskan naskah ke tahap penelaahan sebelum bukti empiris laporan kemiripan selesai dianalisis secara manual oleh editor.
- [ ] Bukti laporan (*similarity report*) PDF telah didokumentasikan ke dalam *Submission Files* naskah sebagai bagian dari kelengkapan jejak audit jurnal.
- [ ] Diagram alur penanganan sengketa dari COPE telah diintegrasikan sebagai rujukan mitigasi insiden jika ditemukan kecurangan berat.

## Ringkasan Bab

Laporan kemiripan naskah adalah instrumen mitigasi risiko, bukan palu hakim pemutus nasib. Perangkat lunak canggih seperti Turnitin mendeteksi kecocokan karakter numerik dan linguistik, namun kecerdasan editoriallah yang menentukan batas antara kelaziman saintifik dan pencurian akademik. Dengan memahami anatomi *false positive*, menyadari jebakan kelemahan perangkat lunak gratis, serta menjadikan diagram alir COPE sebagai kompas navigasi insiden, pengelola jurnal tidak hanya menghindarkan terbitannya dari skandal penarikan (*retraction*), tetapi juga membangun kultur keilmuan yang adil dan beradab.
