# 

**Implikasi:**

---

## 1. Pendahuluan

Detour Post (selanjutnya disebut sebagai "Aplikasi") dioperasikan oleh Yong Wang (selanjutnya disebut sebagai "kami", "kita", atau "milik kami"). Kami bertindak sebagai pengontrol data untuk informasi pribadi Anda.

Kebijakan Privasi ini menjelaskan informasi apa yang kami kumpulkan, alasan kami memprosesnya, cara penanganan dan penyimpanannya, periode penyimpanannya, dan cara Anda menggunakan hak privasi Anda.

Prinsip dasar kami sangat jelas: **Surat Anda bersifat pribadi antara Anda dan penerima. Kami tidak dapat membacanya, dan kami tidak mempunyai niat untuk membacanya.**

## 2. Informasi yang Kami Proses

### 2.1 Informasi yang Anda Berikan Secara Aktif

| Informasi | Detail | Kebutuhan |

|---|---|---|

| Pengenal Akun | Pengidentifikasi unik diperoleh melalui Masuk dengan Apple atau Google | Diperlukan untuk pembuatan akun |

| Kredensial Masuk | Token autentikasi sesi | Diperlukan untuk akses aman |

| Tanggal Lahir & Wilayah | Digunakan pada saat pendaftaran semata-mata untuk menentukan kelayakan usia | Diperlukan untuk pendaftaran. **Tanggal lahir hanya digunakan pada saat evaluasi dan segera dibuang; kami tidak pernah menyimpannya.** Hanya versi aturan dan wilayah yang dipilih yang dipertahankan |

| Nama Tampilan | Nama khusus yang ditetapkan di profil Anda, dapat dilihat oleh penerima Anda | Opsional |

| Kota | Kota dipilih sebagai titik keberangkatan/kedatangan | Opsional, tetapi wajib mengirim surat |

| Info Koneksi | Status hubungan, kode undangan, dan kode rahasia pengambilan surat | Wajib bertukar surat |

| Isi Surat | Teks surat, pilihan kertas surat dan dekorasi, foto terlampir, kurir, waktu tiba | Dibuat hanya ketika Anda memilih untuk mengirim |

| Detail Laporan | Kategori pelanggaran yang dipilih (Pelecehan, Spam, Keamanan) dan ID target. **TIDAK berisi teks huruf, foto, teks bentuk bebas, atau koordinat**; otomatis memblokir pihak tersebut secara bersamaan | Dibuat hanya ketika Anda mengajukan laporan |

| Catatan Pribadi | Catatan pribadi yang Anda tetapkan ke kontak | Opsional. **Disimpan secara ketat di perangkat lokal Anda, tidak pernah diunggah** |

**Enkripsi Surat dan Foto ujung ke ujung.** Teks surat dan foto dienkripsi langsung di perangkat lokal Anda sebelum dikirim. Kami hanya menyimpan ciphertext dan tidak memiliki kunci dekripsi. Oleh karena itu, **kami tidak dapat membaca, memeriksa, atau memberikan teks atau foto surat Anda kepada siapa pun**—termasuk pertanyaan penegakan hukum, yang hanya dapat memberikan teks sandi. Lihat Bagian 4.

### 2.2 Informasi yang Dihasilkan Secara Otomatis Selama Penggunaan

| Informasi | Detail | Tujuan |

|---|---|---|

| Status Pengiriman | Keberangkatan, tonggak perjalanan, kedatangan, penarikan kembali, status penghentian | Mendukung jalur pengiriman pos |

| Status Akun & Keamanan | Reputasi akun, daftar blokir timbal balik, status penanganan laporan | Administrasi akun dan pencegahan penyalahgunaan |

| Buku Besar Perdagangan | Catatan pesanan, saldo koin, kepemilikan barang permanen, langganan aktif | Penanganan penagihan, pemenuhan, dan pengembalian dana |

| Token Dorong & Perangkat | Token push perangkat dan metadata yang diperlukan | Mengirimkan pemberitahuan status surat |

| Log Layanan | Log operasional API, jejak kesalahan, dan diagnostik kinerja | Keamanan, stabilitas, dan pemecahan masalah |

**Tidak Ada Rahasia di Log atau Pemberitahuan Push.** Log operasional tidak pernah berisi teks surat, foto, kode undangan, atau koordinat pasti. Pemberitahuan push hanya berisi frasa status umum (misalnya, "Surat telah tiba") tanpa pengenal pribadi, teks pesan, atau kota.

### 2.3 Apa yang TIDAK PERNAH Kami Lakukan

- Kami TIDAK mengakses perpustakaan foto lengkap, kontak, atau lokasi GPS tepat Anda;

- Kami TIDAK mengumpulkan pengidentifikasi pelacakan (IDFA/IDFV), menyematkan SDK iklan, atau terlibat dalam pelacakan lintas aplikasi;

- Kami TIDAK memasukkan data huruf ke dalam model pelatihan AI—kami tidak memiliki akses ke teks biasa;

- Kami TIDAK PERNAH menjual informasi pribadi Anda kepada pihak ketiga.

## 3. Mengapa Kami Memproses Informasi

| Tujuan | Informasi Terlibat | Dasar Hukum |

|---|---|---|

| Pengiriman dan penerimaan pos | ID Akun, nama tampilan, kota, info koneksi, surat terenkripsi, status pengiriman | Kinerja kontrak layanan |

| Pembelian Dalam Aplikasi dan pengembalian dana | Buku besar pembelian, validitas berlangganan | Kinerja kontrak layanan |

| Pemberitahuan push pengiriman | Token dorong, status pengiriman | Persetujuan Anda (dapat dibatalkan kapan saja) |

| Keamanan, pencegahan penyalahgunaan, dan laporan | Status keselamatan, rincian laporan, log operasional | Kepentingan yang sah & kewajiban hukum |

| Diagnostik dan stabilitas layanan | Log operasional | Kepentingan yang sah |

| Menangani hak dan pertanyaan pengguna | Informasi yang Anda berikan | Kewajiban hukum |

## 4. Enkripsi Ujung-ke-Ujung

Ini adalah perlindungan teknis paling penting dari Detour Post:

**Enkripsi Terjadi Secara Lokal di Perangkat Anda.** Saat Anda mengetuk "Segel surat ini", semua teks dan foto dienkripsi di perangkat Anda sebelum dikirim. Kunci dekripsi dipegang secara eksklusif oleh Anda dan penerima yang Anda tunjuk.

**Kami Hanya Menyimpan Ciphertext.** Server kami hanya menyimpan blob terenkripsi. Kami tidak menyimpan kunci dekripsi dalam bentuk apa pun, kami juga tidak menyediakan pemulihan kunci manual.

**Tanpa Pengecualian.** Kami tidak melakukan pintu belakang administratif, saluran inspeksi konten, atau penggantian layanan pelanggan. Karena kami tidak dapat melihat teks biasa, kami tidak dapat melakukan pemfilteran kata kunci otomatis atau rekomendasi konten.

- Hanya Anda yang dapat melihat konten sebelum pengiriman;

- Hanya Anda dan penerima Anda yang dapat melihat konten setelah pengiriman;

- Jika Anda kehilangan perangkat dan tidak memiliki cadangan iCloud pribadi, kami tidak dapat memulihkan surat Anda—kami tidak memiliki kuncinya;

- Laporan keselamatan memicu pemblokiran hubungan dan penalti akun, tanpa operator manusia membaca isi surat.

**Cadangan Pribadi.** Pencadangan data surat terjadi secara eksklusif melalui iCloud pribadi Anda jika diaktifkan. Cadangan sepenuhnya berada dalam ekosistem ID Apple Anda. Kami tidak memiliki akses ke cadangan iCloud atau kunci Rantai Kunci Anda.

## 5. Izin Sistem

Aplikasi hanya meminta satu izin sistem:

| Izin | Saat Diminta | Tujuan |

|---|---|---|

| Pemberitahuan | Saat Anda ikut serta dalam peringatan surat | Memberi tahu Anda ketika surat berangkat atau tiba. Payload hanya berisi frasa umum |

Menonaktifkan notifikasi tidak mempengaruhi pengiriman atau penerimaan surat.

**Izin yang TIDAK Kami Minta:**

- **Foto:** Pemilihan foto menggunakan pemilih foto sistem asli. Hanya satu gambar terpilih yang diteruskan ke Aplikasi; akses perpustakaan foto lengkap tidak diminta atau diwajibkan.

- **Lokasi:** Kota dipilih secara manual dari daftar. Kami tidak pernah melacak koordinat perangkat Anda.

- **Kontak, Kamera, Mikrofon, Pelacakan Aplikasi (ATT):** Tidak diminta dan tidak ada kode yang sesuai.

## 6. Pihak Ketiga

Kami tidak pernah menjual data pribadi. Informasi dibagikan secara ketat kepada penyedia infrastruktur yang diperlukan:

| Pihak Ketiga | Data Diolah | Tujuan | Catatan |

|---|---|---|---|

| apel | ID Akun, pembelian StoreKit, pengiriman push, geocoding MapKit | Otentikasi, penagihan dalam aplikasi, notifikasi, tampilan peta | Tunduk pada [Kebijakan Privasi Apple](https://www.apple.com/legal/privacy/) |

| Google | ID Akun | Otentikasi opsional | Tunduk pada [Kebijakan Privasi Google](https://policies.google.com/privacy) |

| Layanan Pemberitahuan Push Apple (APN) | Token dorong, muatan peringatan umum | Pengiriman pemberitahuan | Payload tidak mengandung teks surat atau identitas penerima |

| Penyedia Infrastruktur Cloud | Gumpalan surat terenkripsi, buku besar akun | Komputasi awan dan penyimpanan aman | Diproses secara ketat di bawah instruksi kami |

Aplikasi iOS tidak berisi SDK pelacakan, periklanan, atau analitik pihak ketiga.

## 7. Penyimpanan Data dan Transfer Internasional

- **Di Perangkat Anda:** Surat, draf, dan preferensi lokal.

- **Di iCloud Pribadi Anda:** Cadangan basis data terenkripsi dalam akun Apple pribadi Anda.

- **Di Server Kami:** ID Akun, nama tampilan, muatan surat terenkripsi, dan buku besar transaksi yang disimpan dalam infrastruktur cloud luar negeri yang aman. Data dapat ditransfer dan diproses secara internasional berdasarkan perlindungan kontrak yang ketat.

## 8. Periode Penyimpanan Data

| Informasi | Periode Retensi |

|---|---|

| Tanggal Lahir | Tidak disimpan. Dievaluasi sekali pada saat registrasi dan langsung dibuang |

| ID Akun, Nama Tampilan, Kota, Koneksi | Durasi siklus hidup akun; dihapus atau dianonimkan secara permanen setelah penghapusan akun |

| Teks Sandi Huruf | Dihapus segera setelah konfirmasi pengiriman oleh penerima; surat yang tidak diklaim dibersihkan setelah 90 hari |

| Buku Besar Pembelian | Dipertahankan sebagaimana diwajibkan oleh undang-undang keuangan, pajak, dan perlindungan konsumen |

| Token Dorong | Dihapus dari server segera setelah pemberitahuan opt-out atau penghapusan akun |

| Log Layanan | Disimpan selama jendela diagnostik singkat dan dihapus secara otomatis. Tidak mengandung rahasia pribadi |

## 9. Hak Privasi Anda

Anda dapat menggunakan hak-hak berikut mengenai informasi pribadi Anda:

| Benar | Cara Berolahraga |

|---|---|

| Akses & Portabilitas | Lihat profil, pembelian, dan aset di "Profil Saya"; minta ekspor melalui detourpost@aivolo.studio |

| Perbaikan | Edit nama tampilan dan kota di Pengaturan Profil; hubungi kami untuk catatan lainnya |

| Penghapusan | Gunakan fitur "Hapus Akun" dalam aplikasi, atau hubungi kami untuk permintaan data tertentu |

| Tarik Persetujuan | Matikan notifikasi di Pengaturan Aplikasi atau Pengaturan Sistem iOS |

| Penghapusan Akun | Navigasikan ke "Profil Saya" → "Penghapusan & Isolasi Akun" → "Hapus Akun" |

| Pertanyaan & Permintaan | Hubungi detourpost@aivolo.studio |

**Apa yang Terjadi pada Penghapusan Akun:** Surat yang tidak dikirim dihentikan; surat berangkat melanjutkan ke tujuannya; catatan profil, relasi blok, dan token perangkat segera dihapus secara permanen.

Kami menanggapi semua permintaan privasi dalam **48 jam**.

## 10. Anak di bawah umur

Aplikasi ini ditujukan untuk pengguna berusia 13 tahun ke atas (atau lebih tinggi tergantung pada persyaratan yurisdiksi setempat). Kami tidak dengan sengaja mengumpulkan data pribadi dari anak di bawah umur di bawah usia pendaftaran yang berlaku. Jika Anda yakin ada anak di bawah umur yang mendaftar tanpa izin, hubungi detourpost@aivolo.studio dan kami akan segera menghapus akun tersebut.

## 11. Tindakan Keamanan

- Enkripsi ujung ke ujung untuk teks surat dan foto;

- Saluran transportasi terenkripsi (TLS/HTTPS);

- Kredensial dan kunci disimpan dalam penyimpanan sistem yang aman (iOS Keychain);

- Prinsip hak istimewa paling rendah untuk infrastruktur server;

- Pemindaian kerentanan berkelanjutan dan audit konfigurasi.

## 12. Pembaruan Kebijakan

Kami dapat memperbarui Kebijakan Privasi ini secara berkala. Perubahan signifikan akan diberitahukan secara jelas di dalam Aplikasi. Jika Anda tidak setuju dengan ketentuan yang diubah, Anda dapat menghapus akun Anda.

## 13. Hubungi Kami & Pengaduan

- **Operator:** Yong Wang

- **Email:** detourpost@aivolo.studio

Kami menanggapi pertanyaan dalam **48 jam**. Anda juga berhak mengajukan keluhan kepada otoritas pengawas perlindungan data setempat.

© 2026 Yong Wang. Semua hak dilindungi undang-undang.

---

© 2026 Yong Wang. All rights reserved.
