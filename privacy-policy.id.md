# Kebijakan Privasi Detour Post

**Draf untuk peninjauan internal · diperbarui 6 Oktober 2026 · belum dipublikasikan dan belum berlaku · peninjauan hukum dan bahasa masih berlangsung.**

---

## 1. Pendahuluan

Detour Post dioperasikan oleh Yong Wang sebagai individu. Dalam Kebijakan Privasi ini, “kami” merujuk pada Yong Wang, yang menentukan cara data pribadi diproses untuk layanan ini.

Kebijakan Privasi ini menjelaskan informasi apa yang kami kumpulkan, alasan kami memprosesnya, cara penanganan dan penyimpanannya, periode penyimpanannya, dan cara Anda menggunakan hak privasi Anda.

Prinsip dasar kami sangat jelas: **Surat Anda bersifat pribadi antara Anda dan penerima. Kami tidak dapat membacanya, dan kami tidak mempunyai niat untuk membacanya.**

## 2. Informasi yang Kami Proses

### 2.1 Informasi yang Anda Berikan Secara Aktif

| Informasi | Detail | Kebutuhan |
|---|---|---|
| Akun dan identitas masuk | ID akun, ID dari penyedia masuk, dan email terverifikasi yang diberikan Apple atau Google | Diperlukan untuk membuat dan mengautentikasi akun |
| Kredensial masuk | Token sesi; layanan menyimpan hash dari setiap token | Diperlukan untuk akses yang aman |
| Bulan dan tahun lahir serta wilayah yang dipilih | Aplikasi memeriksa kelayakan usia pada perangkat berdasarkan bulan dan tahun yang Anda masukkan serta wilayah pilihan | Diperlukan untuk pendaftaran. Keduanya disimpan dalam data aplikasi terkait akun di perangkat Anda dan dapat dilihat serta diubah di profil; tidak dikirim ke atau disimpan di server kami. Layanan menyimpan versi aturan yang diterapkan dan wilayah saat masuk |
| Nama tampilan | Nama yang terlihat oleh orang yang bertukar surat dengan Anda | Diperlukan untuk menyelesaikan pendaftaran; dapat diubah kemudian di profil |
| Kota | Kota yang dipilih untuk mengirim surat, termasuk rincian tempat yang disimpan aplikasi | Diperlukan untuk pendaftaran dan pengiriman surat |
| Info Koneksi | Status hubungan, kode undangan, dan kode rahasia pengambilan surat | Diperlukan untuk bertukar surat |
| Isi surat | Teks, kertas surat dan dekorasi yang dipilih, foto terlampir, kurir, serta waktu penerimaan yang dipilih atau dijadwalkan | Dibuat hanya ketika Anda memilih untuk mengirim surat |
| Data laporan | ID akun pelapor dan pihak yang dilaporkan; jenis, sumber, dan ID sasaran laporan; alasan yang dipilih; ID penghubung untuk audit; status dan waktu pembuatan. **Tidak memuat teks surat, foto, teks bebas, atau koordinat.** Laporan juga memblokir pihak yang dilaporkan dan mengakhiri surat darinya yang belum tersedia bagi Anda | Dibuat hanya ketika Anda mengajukan laporan |
| Catatan pribadi | Catatan yang Anda tulis tentang kontak | Opsional. Disimpan di perangkat Anda dan dimasukkan ke cadangan iCloud pribadi hanya jika Anda mengaktifkannya; tidak diunggah ke layanan kami |

**Enkripsi surat dan foto dari ujung ke ujung.** Teks dan foto dienkripsi di perangkat sebelum dikirim ke layanan kami. Untuk isi surat tersebut, kami hanya menyimpan data terenkripsi tanpa kunci dekripsi. Data akun dan layanan lain yang dijelaskan di sini diproses secara terpisah. Lihat Bagian 4.

### 2.2 Informasi yang Dihasilkan Secara Otomatis Selama Penggunaan

| Informasi | Detail | Tujuan |
|---|---|---|
| Status Pengiriman | Keberangkatan, tonggak perjalanan, kedatangan, penarikan kembali, status penghentian | Mendukung jalur pengiriman pos |
| Status Akun & Keamanan | Status akun, daftar blokir timbal balik, dan status penanganan laporan | Administrasi akun dan pencegahan penyalahgunaan |
| Catatan pembelian dan aset | Pesanan, riwayat dan saldo koin, stok prangko dan unit layanan penjadwalan pengiriman, kepemilikan item permanen, keanggotaan, dan status pemulihan pembelian | Penagihan, pemenuhan, pemulihan, dan pengembalian dana |
| Token notifikasi push & Perangkat | Token push perangkat dan metadata yang diperlukan | Mengirimkan pemberitahuan status surat |
| Log Layanan | Log operasional API, jejak kesalahan, dan diagnostik kinerja | Keamanan, stabilitas, dan pemecahan masalah |

**Notifikasi push.** Pemberitahuan yang terlihat menggunakan teks umum. Data yang dikirim juga memuat kategori notifikasi dan ID peristiwa yang tidak mengungkapkan maknanya secara langsung, untuk membuka layar yang sesuai; tidak memuat teks surat, foto, atau lokasi. Log operasional dapat memuat rincian teknis permintaan atau kesalahan; lihat Bagian 8.

### 2.3 Apa yang TIDAK PERNAH Kami Lakukan

- Kami TIDAK mengakses perpustakaan foto lengkap, kontak, atau lokasi GPS tepat Anda;

- Aplikasi tidak menggunakan pengenal iklan (IDFA/IDFV) untuk penargetan iklan atau pelacakan lintas aplikasi, dan tidak menyertakan SDK iklan.

- Kami tidak menggunakan data surat untuk melatih model AI; kami tidak memiliki akses ke teks yang belum dienkripsi;

- Kami TIDAK PERNAH menjual informasi pribadi Anda kepada pihak ketiga.

## 3. Mengapa Kami Memproses Informasi

| Tujuan | Informasi yang diproses |
|---|---|
| Mengirim dan menerima surat | ID akun, nama tampilan, kota, informasi hubungan, surat terenkripsi, dan status pengiriman |
| Pembelian dalam aplikasi, pemenuhan, dan pengembalian dana | Catatan pembelian dan aset, serta status keanggotaan |
| Notifikasi pengiriman | Token push dan status pengiriman |
| Keamanan, laporan, dan pencegahan penyalahgunaan | Status akun dan keamanan, data laporan, serta log operasional |
| Diagnosis dan kestabilan layanan | Log operasional |
| Permintaan hak dan keluhan | Informasi yang Anda berikan kepada kami |

Dasar hukum untuk setiap pemrosesan bergantung pada hukum yang berlaku dan keadaan pemrosesan tersebut. Draf ini belum menetapkan dasar hukum untuk setiap tujuan. Peninjauan harus diselesaikan sebelum kebijakan diterbitkan; kami tidak akan menggunakan dasar yang tidak berlaku menurut hukum terkait.

## 4. Enkripsi Ujung-ke-Ujung

Ini adalah perlindungan teknis paling penting dari Detour Post:

**Enkripsi Terjadi Secara Lokal di Perangkat Anda.** Saat Anda mengetuk "Segel surat ini", semua teks dan foto dienkripsi di perangkat Anda sebelum dikirim. Kunci dekripsi dipegang secara eksklusif oleh Anda dan penerima yang Anda tunjuk.

**Teks dan foto surat hanya kami simpan dalam bentuk terenkripsi.** Kami tidak memegang kunci dekripsinya dan tidak menyediakan pemulihan kunci secara manual. Kami juga memproses data akun dan layanan yang dijelaskan dalam Kebijakan ini.

**Tanpa Pengecualian.** Kami tidak menyediakan akses khusus bagi administrator, saluran pemeriksaan isi, atau pengecualian yang memungkinkan layanan pelanggan mengakses isi surat. Karena kami tidak dapat melihat teks biasa, kami tidak dapat melakukan pemfilteran kata kunci otomatis atau rekomendasi konten.

- Sebelum surat tersedia bagi penerima, hanya Anda yang dapat melihat isinya;

- Setelah surat tersedia bagi penerima, hanya Anda dan penerima yang dapat melihat isinya;

- Jika Anda kehilangan perangkat dan tidak memiliki cadangan iCloud pribadi, kami tidak dapat memulihkan surat Anda—kami tidak memiliki kuncinya;

- Laporan keselamatan mencatat alasan yang dipilih dan ID akun atau surat terkait, memblokir kedua pihak, serta mengakhiri surat masuk dari pihak yang dilaporkan yang belum tersedia bagi Anda. Laporan tidak mengungkapkan isi surat. Jika Yong Wang mengetahui laporan tersebut, ia akan berupaya secara wajar untuk meninjaunya dan mengambil tindakan jika diperlukan. Tidak ada tenggat peninjauan atau balasan tertentu; tindakan akun lebih lanjut bergantung pada peninjauan.

**Cadangan pribadi.** Jika diaktifkan, data kantong pos yang dipilih — termasuk catatan pribadi kontak, draf, bahan undangan yang masih tertunda, dan surat tersimpan — dienkripsi di perangkat lalu dicadangkan ke iCloud pribadi melalui CloudKit. Kunci cadangan disimpan di Keychain perangkat. Setelah cadangan diverifikasi, kunci pemulihan disimpan di iCloud Keychain agar dapat tersedia di perangkat Apple Anda yang lain. Kami tidak menerima kedua kunci tersebut dan tidak dapat mendekripsi cadangan.

## 5. Izin Sistem

Aplikasi dapat meminta izin notifikasi setelah surat pertama dikirim atau diterima; Anda juga dapat memintanya melalui Pengaturan. Jika Anda memilih menyimpan kartu pelancong yang dibuat aplikasi ke pustaka foto, aplikasi meminta izin untuk menambahkan foto saja.

| Izin | Saat Diminta | Tujuan |
|---|---|---|
| Notifikasi | Setelah surat pertama dikirim atau diterima, atau saat diaktifkan di Pengaturan | Teks pemberitahuan umum; data yang dikirim juga memuat kategori dan ID peristiwa yang tidak bermakna langsung untuk membuka layar terkait, tanpa teks surat atau lokasi |
| Foto (hanya menambahkan) | Ketika Anda memilih menyimpan kartu pelancong yang dibuat aplikasi | Menyimpan gambar tersebut tanpa memberi izin menjelajahi pustaka foto |

Aplikasi menyinkronkan preferensi notifikasi Anda dengan layanan, yang menggunakannya untuk menentukan notifikasi yang dikirim. Izin iOS menentukan apakah notifikasi dapat tampil di perangkat. Kedua tindakan ini tidak dengan sendirinya menghapus atau menonaktifkan token perangkat pada layanan. Menolak izin opsional tidak dengan sendirinya menghalangi pengiriman atau penerimaan surat dasar.

**Penggunaan izin lainnya:**

- **Foto:** Saat Anda melampirkan foto, pemilih foto sistem hanya memberikan gambar yang dipilih kepada aplikasi; aplikasi tidak menjelajahi seluruh pustaka foto. Menyimpan kartu pelancong yang dibuat aplikasi menggunakan izin terpisah untuk menambahkan foto dan permintaan izin dari sistem.

- **Lokasi:** Anda memilih kota untuk setiap surat. Kami tidak mengumpulkan lokasi perangkat atau melacak pergerakan Anda. Aplikasi memiliki katalog terbatas berisi nama dan koordinat negara serta kota untuk saran pencarian lokal, hasil luring terbatas, dan label peta. Aplikasi memeriksa katalog ini terlebih dahulu; jika cocok, hasil digunakan secara lokal dan istilah pencarian tidak dikirim ke MapKit. Jika tidak cocok, aplikasi meminta hasil tempat dari Apple MapKit. Jika katalog tidak memiliki titik tengah untuk negara atau wilayah yang dipilih, aplikasi dapat mengirim nama negara atau wilayah tersebut kepada Apple melalui Core Location untuk mengatur tampilan peta. Aplikasi juga menggunakan Core Location untuk melakukan geocoding terbalik pada titik yang dipilih di peta. Jika Apple tidak memberi hasil, aplikasi dapat menggunakan kota katalog terdekat sebagai alternatif terbatas. Apple menerima teks pencarian, nama negara atau wilayah, atau koordinat titik peta yang terkait. Fitur ini tidak memerlukan izin lokasi.

- **Kontak, Kamera, Mikrofon, Pelacakan Aplikasi (ATT):** Tidak diminta dan tidak ada kode yang sesuai.

## 6. Pihak Ketiga

Kami tidak menjual informasi pribadi. Penyedia layanan yang diperlukan untuk fitur yang Anda gunakan memproses data terkait. Untuk penyimpanan dan pemrosesan teks serta foto surat pada server layanan, penyedia menerima data terenkripsi; kami tidak memberikan kunci dekripsi kepada mereka.

| Pihak Ketiga | Data Diolah | Tujuan | Catatan |
|---|---|---|---|
| Apple | ID masuk dan email terverifikasi, pembelian dan langganan dalam aplikasi, token push dan pengiriman notifikasi, cadangan iCloud pribadi terenkripsi serta kunci pemulihan jika diaktifkan, istilah pencarian tempat yang dikirim melalui MapKit, nama negara atau wilayah untuk mengatur peta saat katalog tidak memiliki titik tengah, dan koordinat titik peta untuk geocoding terbalik melalui Core Location | Masuk, pembayaran, notifikasi, pencadangan, dan fitur peta/pencarian | Tunduk pada [Kebijakan Privasi Apple](https://www.apple.com/legal/privacy/) |
| Google | ID dari penyedia masuk dan email terverifikasi, jika diberikan | Autentikasi ketika Anda memilih Google | Berlaku [Kebijakan Privasi Google](https://policies.google.com/privacy) |
| Apple Push Notification service (APNs) | Token push, teks pemberitahuan umum, kategori notifikasi, dan ID peristiwa yang tidak bermakna langsung | Pengiriman notifikasi | Data tidak memuat teks surat, foto, atau lokasi tepat |
| Cloudflare | Surat terenkripsi, catatan akun dan masuk, data kota yang dipilih, catatan pembelian dan pengiriman, token push, serta log layanan | Komputasi awan, basis data, dan penyimpanan objek | Berlaku [Kebijakan Privasi Cloudflare](https://www.cloudflare.com/privacypolicy/) |

Aplikasi iOS tidak berisi SDK pelacakan, periklanan, atau analitik pihak ketiga.

## 7. Penyimpanan Data dan Transfer Internasional

- **Di perangkat Anda:** Surat, draf, catatan pribadi kontak, dan preferensi.

- **Di iCloud pribadi:** Jika diaktifkan, cadangan terenkripsi dari data kantong pos yang dipilih, termasuk catatan pribadi kontak, draf, bahan undangan tertunda, dan surat tersimpan.

- **Di server kami:** ID akun dan masuk, email terverifikasi, nama tampilan, rincian tersimpan tentang kota pilihan, catatan hubungan dan pengiriman, isi surat terenkripsi, pembelian, token push, dan log layanan. Infrastruktur awan berada di luar negara atau wilayah sebagian pengguna, sehingga data ini dapat diproses secara internasional.

## 8. Periode Penyimpanan Data

| Informasi | Masa penyimpanan |
|---|---|
| Bulan dan tahun lahir | Disimpan dalam data aplikasi pada perangkat Anda dan terkait dengan akun; dapat dilihat serta diubah di profil. Data ini tidak dikirim ke atau disimpan di server kami. |
| Akun dan identitas masuk | Penghapusan akun menonaktifkan akun, mencabut sesi, serta menghapus data profil dan notifikasi. Rancangan layanan saat ini tetap menyimpan catatan akun yang dihapus dan ID penyedia masuk; batas waktu penghapusan tetap belum ditetapkan. |
| Isi surat terenkripsi | Pembersihan ciphertext di server dimulai setelah perangkat penerima mengonfirmasi bahwa seluruh surat telah disimpan. Jika tidak ada konfirmasi, surat menjadi tidak tersedia 90 hari sejak surat tersedia bagi penerima (untuk surat terjadwal, dihitung dari waktu penyampaian yang dijadwalkan), lalu masuk proses pembersihan. Berakhirnya jangka waktu tersebut tidak memulihkan akun pengirim yang telah dihapus. |
| Catatan pembelian dan pemenuhan | Disimpan untuk mengelola pembelian, pengembalian dana, dan pengiriman yang telah dimulai. Masa penyimpanan tetap belum ditentukan. |
| Token push | Preferensi notifikasi dalam aplikasi menentukan notifikasi yang dikirim; izin iOS mengatur tampilannya di perangkat. Penghapusan akun menghapus token perangkat akun tersebut; token yang dinyatakan tidak valid oleh APNs dinonaktifkan. |
| Laporan keselamatan | Alasan yang dipilih, ID akun atau surat terkait, status, dan waktu pembuatan. Masa penyimpanan dan pemicu penghapusan tetap belum ditetapkan. |
| Log layanan | Dapat dibuat untuk keamanan, keandalan, dan pemecahan masalah, serta dapat memuat rincian teknis permintaan atau kesalahan. Masa penyimpanan tetap belum ditetapkan. |

Masa penyimpanan atau kriteria penghapusan untuk catatan akun yang dihapus dan ID penyedia, catatan pembelian dan pemenuhan, laporan keselamatan, serta log layanan belum ditetapkan. Aturan tersebut dan dasar hukum setiap tujuan harus ditinjau sebelum kebijakan diterbitkan.

## 9. Hak Privasi Anda

Bergantung pada tempat tinggal Anda, hukum yang berlaku dapat memberikan hak untuk mengakses, memperbaiki, menghapus, atau memperoleh salinan informasi pribadi, menolak atau membatasi pemrosesan tertentu, atau menarik persetujuan. Kebijakan ini tidak membatasi hak yang diberikan hukum. Kirim permintaan ke detourpost@aivolo.studio; kami dapat meminta informasi yang diperlukan untuk memverifikasi identitas Anda.

| Hak | Cara menggunakan hak tersebut |
|---|---|
| Akses atau salinan | Buka “Saya” untuk melihat data akun, pembelian, dan aset; hubungi kami untuk permintaan yang tidak tersedia di aplikasi |
| Perbaikan | Buka “Saya” → “Profil” untuk mengubah nama tampilan dan kota; hubungi kami mengenai data lain |
| Penghapusan | Gunakan fitur "Hapus Akun" dalam aplikasi, atau hubungi kami untuk permintaan data tertentu |
| Penarikan persetujuan | Hubungi detourpost@aivolo.studio untuk menarik persetujuan atas pemrosesan yang bergantung pada persetujuan tersebut; dampak terhadap pemrosesan sebelumnya ditentukan oleh hukum yang berlaku |
| Penghapusan akun | “Saya” → “Hapus Akun” → “Hapus akun” |
| Pertanyaan & Permintaan | Hubungi detourpost@aivolo.studio |

**Saat akun dihapus:** Akun dinonaktifkan, sesinya dicabut, dan data profil serta notifikasi dihapus. Pengiriman yang belum berangkat dibatalkan; surat yang sudah berangkat tetap mengikuti rencana pengiriman. Menghapus akun aplikasi tidak membatalkan keanggotaan yang ditagihkan melalui Apple; kelola atau batalkan melalui pengaturan langganan akun Apple Anda. Layanan saat ini tetap menyimpan catatan akun yang dihapus dan ID penyedia masuk; lihat Bagian 8.

Kami akan menangani permintaan sesuai hukum yang berlaku. Waktu penanganan bergantung pada jenis permintaan; kami tidak menjanjikan batas waktu umum.

## 10. Anak di bawah umur

Aplikasi ditujukan bagi orang yang memenuhi usia minimum yang berlaku, sekurang-kurangnya 13 tahun dan dapat lebih tinggi di wilayah tertentu. Saat pendaftaran, aplikasi memeriksa pada perangkat Anda apakah bulan dan tahun lahir yang Anda masukkan serta wilayah yang dipilih memenuhi persyaratan usia. Bulan dan tahun lahir disimpan dalam data aplikasi di perangkat Anda dan tidak dikirim ke atau disimpan di server kami.

Jika Anda yakin seseorang mungkin belum mencapai usia minimum yang berlaku, hubungi detourpost@aivolo.studio. Jika Yong Wang mengetahui hal tersebut, ia akan berupaya secara wajar untuk meninjaunya dan mengambil langkah yang diwajibkan hukum. Tidak ada batas waktu peninjauan atau balasan tertentu yang dijanjikan. Wali juga dapat menghubungi alamat tersebut.

## 11. Tindakan Keamanan

- Enkripsi ujung ke ujung untuk teks surat dan foto;

- Data dikirim melalui saluran terenkripsi (TLS/HTTPS);

- Kredensial dan kunci disimpan dalam penyimpanan sistem yang aman (iOS Keychain);

- Perlindungan perangkat untuk kredensial dan kunci enkripsi yang disimpan secara lokal.

Tidak ada langkah keamanan yang menjamin keamanan mutlak. Jika terjadi insiden keamanan data, kami akan memberikan pemberitahuan dan mengambil langkah yang diwajibkan oleh hukum yang berlaku.

## 12. Pembaruan Kebijakan

Kebijakan ini dapat diperbarui. Teks terkini dan tanggal pembaruan akan ditampilkan di halaman ini. Kami tidak menggunakan informasi pribadi untuk tujuan yang tidak sesuai dengan tujuan yang dijelaskan di sini. Jika hukum yang berlaku mewajibkan pemberitahuan mengenai perubahan penting atau penggunaan data baru, kami akan memberikannya melalui cara yang sesuai.

## 13. Hubungi Kami & Pengaduan

- **Operator:** Yong Wang

- **Email:** detourpost@aivolo.studio

Untuk pertanyaan atau keluhan, hubungi detourpost@aivolo.studio. Jika Yong Wang mengetahui pesan Anda, ia akan berupaya secara wajar untuk meninjaunya dan membalas bila sesuai. Tidak ada tenggat balasan tertentu yang dijanjikan. Anda juga dapat mengajukan keluhan kepada otoritas pengawas yang berwenang atas persoalan Anda.
