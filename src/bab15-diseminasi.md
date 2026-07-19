# Bab 15: Diseminasi dan Peningkatan Visibilitas Jurnal

> **Pemantik Bab**
> Banyak editor merasa tugasnya selesai ketika tombol *Publish Issue* ditekan, lalu duduk manis menunggu datangnya sitasi. Kenyataannya, ribuan jurnal baru terbit setiap harinya. Tanpa dorongan diseminasi aktif dari editor, artikel brilian di dalam OJS Anda hanya akan menjadi kuburan digital yang tidak pernah dikunjungi. Bab ini membongkar mitos pasivitas penerbitan, memandu Anda menggunakan fitur bawaan seperti *Announcements*, hingga memanfaatkan jejaring sosial agar jurnal Anda memenangi perebutan atensi akademis.

Penerbitan suatu edisi jurnal bukanlah akhir dari tanggung jawab tim editorial, melainkan awal dari fase krusial berikutnya: diseminasi. Diseminasi adalah upaya proaktif untuk menyebarluaskan hasil penelitian agar dapat diakses, dibaca, dan disitasi oleh komunitas akademik yang lebih luas. Tanpa strategi diseminasi yang efektif, artikel berkualitas tinggi sekalipun berisiko tidak mendapatkan pengakuan dan dampak (*impact*) yang sepadan.

Bab ini membahas strategi komprehensif untuk meningkatkan visibilitas jurnal melalui pengindeksan, pemanfaatan media sosial, serta optimalisasi fitur bawaan OJS 3.3.

## 15.1 Konsep Diseminasi Hasil Penelitian

Dalam era digital, jangkauan sebuah jurnal sangat bergantung pada kemampuan artikel-artikelnya ditemukan (*discoverability*) di internet. Diseminasi bertujuan untuk menjembatani kesenjangan antara publikasi dan pembaca potensial. Pengelola jurnal harus mengadopsi pola pikir bahwa mereka bukan sekadar "penerbit", melainkan "promotor" pengetahuan.

Upaya peningkatan visibilitas terbagi menjadi dua pilar:
1. **Visibilitas Mesin**: Memastikan artikel dapat dibaca dan diindeks dengan benar oleh algoritma mesin pencari (*crawler*).
2. **Visibilitas Manusia**: Mempromosikan artikel langsung ke komunitas target melalui saluran komunikasi profesional.

## 15.2 Strategi Pengindeksan Jurnal

Pengindeksan adalah mekanisme utama untuk meningkatkan visibilitas mesin. Jurnal yang terindeks dalam pangkalan data terkemuka secara otomatis akan lebih mudah ditemukan oleh para peneliti di seluruh dunia.

Beberapa lembaga pengindeks prioritas yang harus ditargetkan oleh pengelola jurnal:

- **Directory of Open Access Journals (DOAJ)**: Direktori paling bergengsi untuk jurnal akses terbuka (*open access*). Terindeks di DOAJ merupakan bukti komitmen jurnal terhadap standar kualitas dan transparansi (https://doaj.org/).
- **Google Scholar**: Mesin pencari akademik terbesar. Pastikan metadata artikel disusun sesuai standar (lihat **Bab 13: Optimalisasi Metadata Artikel**) agar terindeks tanpa hambatan oleh Google Scholar.
- **SINTA (Science and Technology Index)**: Portal pengindeks utama di Indonesia yang dikelola oleh Kemendikbudristek. SINTA digunakan sebagai metrik utama penilaian kinerja jurnal nasional.
- **Garuda (Garba Rujukan Digital)**: Portal penelusuran artikel ilmiah Indonesia yang sangat esensial untuk meningkatkan rujukan lokal.
- **Dimensions**: Basis data sitasi global yang mengintegrasikan publikasi, hibah riset, dan paten. Pengindeksan di sini meningkatkan keterpaparan jurnal ke komunitas internasional.

## 15.3 Promosi Melalui Media Sosial Akademik

Selain mengandalkan pengindeks, tim editorial perlu membangun kehadiran (*presence*) di platform tempat para peneliti berkumpul.

### Jejaring Akademik

- **ResearchGate dan Academia.edu**: Mendorong tim editor dan penulis untuk membagikan pranala artikel ke profil mereka di platform ini.
- **ORCID**: Mewajibkan penulis untuk menautkan akun ORCID mereka saat mendaftar di OJS. Hal ini memastikan karya mereka secara otomatis terekam di rekam jejak publik publikasi internasional (https://orcid.org/).

### Media Sosial Umum

Penggunaan platform seperti X (sebelumnya Twitter), LinkedIn, atau Facebook dapat dimanfaatkan untuk mempromosikan terbitan baru.
- Buat ringkasan infografis (*graphical abstract*) dari artikel unggulan.
- Selalu sertakan tautan permanen (DOI) alih-alih URL biasa dalam setiap unggahan promosi.

## 15.4 Menggunakan Fitur Announcements di OJS

OJS 3.3 menyediakan fitur pengumuman (*Announcements*) yang sangat efektif untuk notifikasi internal pembaca setia jurnal langsung dari beranda.

**Jalur Eksekusi Cepat: Membuat Pengumuman Edisi Baru**
1. Pastikan fitur pengumuman telah diaktifkan via **Settings > Website > Setup > Announcements**.
2. Masuk ke dasbor, navigasikan ke **Announcements** di menu panel sebelah kiri.
3. Klik tombol **Add Announcement**.
4. Isi kolom *Title* (misal: "Volume 2 Nomor 1 Telah Terbit!") dan *Short Description*.
5. Centang opsi **Send an email to all registered users** agar sistem mengirim *blast* surel otomatis.
6. Klik **Save**.

> **Troubleshooting: Surel Pengumuman Tidak Terkirim**
>
> **Masalah**: Anda sudah mencentang opsi kirim surel massal, tetapi penulis atau pembaca melapor tidak pernah menerimanya.
>
> **Solusi Cepat**: Ini hampir selalu terjadi karena konfigurasi SMTP (pengaturan surel) di dalam file konfigurasi server (`config.inc.php`) jurnal Anda bermasalah atau mengalami limitasi *spam* dari penyedia *hosting*. Hubungi pengelola IT jurnal Anda untuk memeriksa kredensial SMTP dan pastikan pengiriman massal tidak diblokir oleh peladen (*server*).

![Fitur Pengumuman di beranda OJS](../img/elementor-placeholder-image.png)

## 15.5 Peningkatan Dampak (Impact)

Tujuan akhir dari visibilitas adalah peningkatan sitasi atau dampak riset. Praktik berikut sangat disarankan:

- **Edukasi Penulis**: Kirimkan surel kepada penulis sesaat setelah artikel mereka diterbitkan. Ucapkan selamat dan berikan instruksi singkat tentang cara mereka dapat mempromosikan artikelnya sendiri menggunakan tautan DOI.
- **Konsistensi DOI**: Pastikan bahwa pengutipan referensi di jurnal Anda selalu mencantumkan tautan DOI yang aktif. Hal ini membantu menumbuhkan ekosistem sitasi silang (*cross-referencing*) yang sehat (Crossref, 2024).

## 15.6 Meningkatkan Sitasi Setelah Memperbaiki Visibilitas

> **Catatan dari Lapangan: Dari Stagnan ke SINTA Atas**
>
> **Studi Kasus:** Sebuah jurnal ilmu sosial mengalami stagnasi jumlah sitasi selama tiga tahun berturut-turut. Tim editorial lalu mengimplementasikan intervensi: mereka mewajibkan penulis mendaftarkan ID ORCID, mereka memperbaiki metadata DOI, dan rutin membagikan tautan artikel via Twitter institusi. Hasilnya, dalam kurun 18 bulan, metrik kutipan di Google Scholar melonjak hingga 300% karena mesin pengindeks mudah merayapi data, dan penyebaran melalui jejaring sosial membangun ketertarikan nyata dari rekan akademisi.

## Latihan Bab 15

**Skenario Simulasi: Memanggil Naskah (Call for Papers)**

Anda membutuhkan naskah berkualitas untuk edisi khusus tahun depan. Anda memutuskan menggunakan fitur *Announcements*.

**Tugas Praktik:**
1. Masuk ke dasbor OJS, pergi ke **Settings > Website**, dan pastikan menu *Announcements* dalam keadaan aktif.
2. Pergi ke menu **Announcements** di panel utama.
3. Buat draf pengumuman baru dengan judul "Call for Papers: Edisi Khusus Kecerdasan Buatan".
4. Tulis instruksi singkat di deskripsi beserta tenggat waktunya.
5. Simpan pengumuman tersebut (jangan centang pengiriman surel massal untuk keperluan latihan ini).
6. Buka halaman publik beranda jurnal Anda dan verifikasi apakah pengumuman tersebut muncul di sana.

## Checklist Bab 15

- [ ] Jurnal telah didaftarkan ke pengindeks basis (minimal Google Scholar dan Garuda).
- [ ] Fitur *Announcements* diaktifkan dan digunakan secara rutin saat rilis edisi baru.
- [ ] Penulis didorong untuk menggunakan ORCID dan mempromosikan artikel mereka secara mandiri.
- [ ] Tautan DOI selalu digunakan pada seluruh kampanye media sosial atau korespondensi surat elektronik.
- [ ] Tim pengelola memiliki akun media sosial jurnal atau jejaring akademik untuk menyebarluaskan ringkasan artikel.

## Ringkasan Bab

Upaya diseminasi adalah katalis yang mengubah artikel ilmiah dari sekadar "tersedia" menjadi "terbaca dan disitasi". Kolaborasi antara metadata yang dirancang untuk keterbacaan algoritma pengindeks, ditambah dengan strategi kehumasan akademik (melalui media sosial, *Announcements*, dan advokasi penulis mandiri), membangun sebuah ekosistem yang melestarikan reputasi dan dampak jurnal secara berkelanjutan.
