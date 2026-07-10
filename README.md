# UAS-Ransomware-BSI-EtikaProfesi
Project Based Learning Mata Kuliah Etika Profesi Kasus Ransomware Bank Syariah Indonesia (BSI)  — Mei 2023 

# 1. Kronologi & Konteks

## 1.1 Konteks Kasus

Transformasi digital telah merubah sektor perbankan menjadi bidang yang sangat tergantung pada teknologi informasi. Berbagai layanan seperti perbankan mobile, perbankan internet, ATM, pengiriman uang, pembayaran tagihan, serta pembukaan rekening kini dilakukan secara daring. Digitalisasi menawarkan kemudahan, efisiensi, dan kecepatan dalam melayani nasabah, namun juga meningkatkan ancaman serangan siber karena sistem perbankan menjadi target yang sangat menarik bagi pelaku kejahatan siber.

Bank Syariah Indonesia (BSI) merupakan bank syariah terbesar di tanah air yang terbentuk melalui penggabungan PT Bank BRI Syariah Tbk, PT Bank Syariah Mandiri, dan PT Bank BNI Syariah pada tahun 2021. Sebagai lembaga keuangan yang melayani jutaan nasabah di seluruh pelosok Indonesia, BSI memiliki tanggung jawab besar dalam menjaga keberlangsungan layanan, keamanan informasi, serta perlindungan data pribadi nasabah.

Di awal Mei 2023, BSI mengalami gangguan layanan yang bersifat nasional, menyebabkan sebagian besar layanan digital tidak dapat diakses selama beberapa hari. Gangguan ini kemudian dihubungkan dengan serangan ransomware yang diaku oleh kelompok ransomware LockBit 3. 0, salah satu kelompok ransomware paling aktif di dunia. Kejadian ini menarik perhatian publik karena tidak hanya mengganggu operasional perbankan, tetapi juga menimbulkan kecurigaan mengenai kebocoran data nasabah dan karyawan, sehingga mengangkat pertanyaan tentang kesiapan Rencana Keberlangsungan Bisnis (BCP), Rencana Pemulihan Bencana (DRP), transparansi publik, serta tanggung jawab etika dan hukum perusahaan.


## 1.2 Konteks Teknis

Ransomware adalah tipe malware yang dirancang untuk mengunci atau mengenkripsi sistem komputer, sehingga korban kehilangan akses ke data dan layanan yang ada. Setelah berhasil menginfeksi sistem, pelaku umumnya meminta sejumlah uang tebusan agar akses dapat dikembalikan. Dalam beberapa tahun terakhir, kelompok ransomware modern tidak hanya mengenkripsi data, tetapi juga mencuri informasi korban sebelum melakukan enkripsi. Strategi ini dikenal sebagai double extortion, di mana korban diancam dengan penyebaran data yang dicuri jika tebusan tidak dibayar.

Kelompok LockBit 3. 0 terkenal karena penggunaan teknik ini. Mereka memanfaatkan celah dalam sistem keamanan untuk masuk ke jaringan internal korban, meningkatkan hak akses, mencuri informasi penting, lalu mengenkripsi server dan sistem operasional. Jenis serangan seperti ini sangat berisiko bagi lembaga keuangan karena dapat menghentikan layanan publik dan juga mengancam kerahasiaan informasi nasabah.

Pada kasus BSI, diduga serangan ransomware menyebabkan gangguan pada berbagai layanan penting seperti aplikasi BSI Mobile, mesin ATM, internet banking, dan transaksi antarbank. Gangguan ini memperlihatkan bahwa insiden keamanan siber tidak hanya berdampak pada teknologi, tetapi juga berpengaruh pada operasional bisnis, reputasi perusahaan, kepercayaan publik, dan stabilitas sektor keuangan.


## 1.3 Kronologi Kejadian

| **Tanggal** | **Peristiwa** | **Dampak** |
|-------------|---------------|------------|
| **8 Mei 2023** | Nasabah mulai mengeluhkan gangguan pada layanan BSI Mobile, ATM, dan transaksi digital. BSI menyampaikan bahwa gangguan terjadi karena proses *maintenance* sistem. | Nasabah mengalami kesulitan melakukan transaksi dan mulai mempertanyakan penyebab gangguan. |
| **9 Mei 2023** | Gangguan masih berlanjut pada layanan mobile banking, internet banking, ATM, serta beberapa layanan di kantor cabang. Keluhan masyarakat meningkat di media sosial dan menjadi perhatian media nasional. | Aktivitas transaksi masyarakat terganggu dan muncul kekhawatiran mengenai keamanan sistem BSI. |
| **10 Mei 2023** | BSI membuka layanan secara terbatas melalui kantor cabang sambil melakukan proses pemulihan sistem bersama tim internal dan pihak terkait. | Operasional mulai berjalan secara manual, namun layanan digital masih belum normal sehingga menimbulkan spekulasi adanya serangan siber. |
| **11 Mei 2023** | Kelompok **LockBit 3.0** mengklaim bertanggung jawab atas serangan terhadap sistem BSI dan mengaku telah memperoleh sekitar **1,5 TB** data internal. Kelompok tersebut juga mengancam akan mempublikasikan data apabila tidak terjadi negosiasi. | Kekhawatiran masyarakat meningkat karena adanya dugaan kebocoran data nasabah dan pegawai. |
| **12–15 Mei 2023** | BSI melakukan pemulihan layanan secara bertahap. Aplikasi BSI Mobile, ATM, internet banking, dan layanan transaksi lainnya mulai kembali beroperasi. BSI juga menyampaikan permohonan maaf kepada nasabah. | Sebagian besar layanan berhasil dipulihkan, namun kepercayaan masyarakat terhadap keamanan sistem masih menjadi perhatian. |

## 1.4 Analisis Kronologi

Berdasarkan kronologi tersebut, insiden yang dialami BSI tidak hanya berdampak pada gangguan operasional, tetapi juga memengaruhi kepercayaan masyarakat terhadap keamanan layanan perbankan digital. Kasus ini menunjukkan bahwa ancaman keamanan siber dapat mengganggu keberlangsungan bisnis, menimbulkan kerugian bagi nasabah, serta menguji kesiapan organisasi dalam menangani insiden melalui penerapan Business Continuity Plan (BCP) dan Disaster Recovery Plan (DRP). Oleh karena itu, peristiwa ini menjadi salah satu contoh penting mengenai perlunya tata kelola keamanan informasi yang baik, transparansi kepada publik, serta tanggung jawab profesional dalam menghadapi insiden keamanan siber.

# 2. Fakta Kunci & Catatan Transparansi

## 2.1 Fakta Terverifikasi

Dalam menganalisis kasus ransomware yang menimpa Bank Syariah Indonesia (BSI), penting untuk membedakan antara fakta yang telah terverifikasi dengan informasi yang masih berupa dugaan atau klaim. Fakta yang disajikan pada bagian ini berasal dari sumber resmi seperti pernyataan Bank Syariah Indonesia, Otoritas Jasa Keuangan (OJK), Badan Siber dan Sandi Negara (BSSN), serta pemberitaan media yang mengutip sumber resmi.
Berikut merupakan fakta-fakta yang telah terverifikasi terkait insiden tersebut.

| No | Fakta Terverifikasi | Keterangan |
|----|---------------------|------------|
| 1 | Gangguan layanan BSI mulai terjadi pada **8 Mei 2023**. | Gangguan dialami pada layanan BSI Mobile, ATM, internet banking, dan transaksi digital lainnya. |
| 2 | BSI menyampaikan bahwa sedang dilakukan proses pemulihan sistem. | Informasi disampaikan melalui pengumuman resmi kepada nasabah selama masa gangguan. |
| 3 | Layanan digital BSI mengalami gangguan selama beberapa hari. | Banyak nasabah tidak dapat melakukan transaksi secara normal. |
| 4 | Kelompok ransomware **LockBit 3.0** mengklaim bertanggung jawab atas serangan terhadap sistem BSI. | Klaim tersebut dipublikasikan melalui situs kebocoran data milik LockBit. |
| 5 | BSI melakukan pemulihan layanan secara bertahap hingga sistem kembali beroperasi. | Proses normalisasi dilakukan setelah gangguan berlangsung selama beberapa hari. |
| 6 | **OJK** dan **BSSN** ikut memantau proses penanganan insiden. | Hal ini dilakukan untuk memastikan stabilitas layanan dan mendukung proses investigasi. |

## 2.2 Informasi yang Masih Memerlukan Verifikasi

Selain fakta yang telah dipastikan kebenarannya, terdapat beberapa informasi yang beredar di masyarakat namun belum dapat dipastikan secara resmi. Oleh karena itu, informasi berikut tidak dapat langsung dianggap sebagai fakta dan masih memerlukan verifikasi lebih lanjut.

| No | Informasi | Status |
|----|-----------|--------|
| 1 | Seluruh data nasabah berhasil dicuri oleh pelaku. | ⚠️ **Belum terverifikasi.** Tidak ada pernyataan resmi yang menyatakan seluruh data nasabah berhasil dicuri. |
| 2 | Data yang dicuri mencapai **1,5 TB**. | ⚠️ Berasal dari klaim **LockBit 3.0** dan belum dapat diverifikasi secara independen. |
| 3 | Semua data yang diklaim dicuri telah dipublikasikan. | ⚠️ Belum dapat dipastikan karena tidak ada konfirmasi resmi mengenai keseluruhan data tersebut. |
| 4 | Penyebab gangguan sepenuhnya disebabkan oleh ransomware. | ⚠️ Masih memerlukan hasil investigasi teknis secara lengkap karena detail penyebab tidak dipublikasikan secara menyeluruh kepada masyarakat. |

## 2.3 Catatan Transparansi

Dalam penyusunan laporan ini, penulis berupaya menerapkan prinsip transparansi dengan membedakan secara jelas antara fakta yang telah terverifikasi dan informasi yang masih berupa dugaan. Pendekatan ini dilakukan agar laporan tetap objektif, tidak menyesatkan pembaca, serta sesuai dengan etika akademik.

Kasus BSI juga menunjukkan pentingnya transparansi organisasi dalam menghadapi insiden keamanan siber. Pada awal terjadinya gangguan, BSI menyampaikan bahwa layanan mengalami kendala akibat proses maintenance sistem. Seiring berkembangnya informasi, muncul klaim dari kelompok LockBit mengenai dugaan serangan ransomware dan pencurian data. Perbedaan informasi tersebut menimbulkan berbagai spekulasi di masyarakat sehingga diperlukan komunikasi yang jelas, konsisten, dan didukung oleh hasil investigasi yang dapat dipertanggungjawabkan.

Bagi pembaca, informasi yang berasal dari pihak resmi seperti BSI, OJK, dan BSSN dapat dijadikan rujukan utama. Sementara itu, informasi yang berasal dari klaim kelompok LockBit perlu diperlakukan secara kritis karena belum seluruhnya dapat diverifikasi melalui sumber independen. Oleh sebab itu, setiap kesimpulan mengenai jumlah data yang diduga dicuri maupun dampak kebocoran data harus mempertimbangkan hasil investigasi resmi yang tersedia.

## 2.4 Analisis Fakta dan Transparansi

Berdasarkan fakta yang tersedia, dapat disimpulkan bahwa gangguan layanan BSI pada Mei 2023 merupakan insiden yang berdampak besar terhadap operasional perbankan dan kepercayaan masyarakat. Meskipun proses pemulihan layanan berhasil dilakukan, keterbatasan informasi pada tahap awal menyebabkan munculnya berbagai spekulasi di ruang publik.

Dari sudut pandang etika profesi, transparansi merupakan salah satu aspek penting dalam penanganan insiden keamanan siber. Organisasi perlu memberikan informasi yang akurat, tepat waktu, dan tidak menyesatkan tanpa mengungkapkan data yang dapat mengganggu proses investigasi atau memperbesar risiko keamanan. Dengan demikian, keseimbangan antara keterbukaan informasi dan perlindungan keamanan menjadi faktor penting dalam menjaga kepercayaan nasabah serta memenuhi tanggung jawab profesional perusahaan.


