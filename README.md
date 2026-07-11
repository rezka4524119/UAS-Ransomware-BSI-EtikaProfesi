# UAS-Ransomware-BSI-EtikaProfesi
Project Based Learning Mata Kuliah Etika Profesi Kasus Ransomware Bank Syariah Indonesia (BSI)  — Mei 2023 

# 10. ⁠Rancangan Dampak & Kontrol Preventif

## 10.1 Analisis Dampak Serangan Ransomware BSI (Mei 2023)
Berdasarkan analisis kronologi serangan ransomware LockBit 3.0 terhadap Bank Syariah Indonesia (BSI) pada Mei 2023, dampak yang ditimbulkan tidak hanya menyasar sektor teknis, melainkan meluas ke aspek operasional, finansial, dan reputasi institusi. Berikut adalah rincian dampak negatif yang diidentifikasi:

**1. Dampak Operasional (System Downtime & Service Interruption)**
- Deskripsi: Terjadinya kelumpuhan total pada seluruh layanan digital perbankan, termasuk ATM, Mobile Banking (BSI Mobile), dan layanan kantor cabang selama beberapa hari. Hal ini menghentikan jutaan transaksi nasabah secara instan.
- Tingkat Risiko: Tinggi (High).
  
**2. Dampak Kebocoran Data (Data Breach & Eksfiltrasi Data)**
- Deskripsi: Kelompok ransomware berhasil mengeksfiltrasi sekitar 1,5 Terabyte (TB) data internal. Data yang bocor mencakup data pribadi 15 juta nasabah, informasi kartu kredit, data karyawan, dokumen keuangan, hingga dokumen legalitas bank yang kemudian disebarkan di dark web.
- Tingkat Risiko: Tinggi (High).
  
**3. Dampak Reputasi dan Kepercayaan (Reputational Loss)**
- Deskripsi: Penurunan drastis tingkat kepercayaan nasabah (trust deficit) terhadap sistem keamanan perbankan syariah nasional, yang memicu sentimen negatif publik secara masif di media massa dan media sosial.
- Tingkat Risiko: Tinggi (High).
  
**4. Dampak Finansial dan Regulasi (Financial & Legal Impact)**
- Deskripsi: Potensi kerugian material akibat hilangnya perputaran biaya transaksi harian, biaya pemulihan sistem (disaster recovery), serta potensi denda dari regulasi penegakan hukum perlindungan data pribadi (UU PDP).
- Tingkat Risiko: Tinggi (High).

## 10.2 Rancangan Kontrol Preventif (Strategi Pencegahan)
Belajar dari kelemahan arsitektur keamanan pada kasus BSI, berikut adalah rancangan kontrol preventif yang wajib diterapkan guna mencegah terjadinya serangan serupa di masa depan:

### 10.2.1 Kontrol Teknis (Technical Controls)
- Penerapan Arsitektur Zero Trust Network Access (ZTNA): Menghilangkan asumsi kepercayaan implisit di dalam jaringan. Setiap perangkat dan pengguna, baik internal maupun eksternal, wajib melalui proses verifikasi dan otentikasi secara ketat sebelum diberikan hak akses minimal (Least Privilege Access).
- Implementasi Endpoint Detection and Response (EDR) & XDR: Memasang agen deteksi otomatis berbasis kecerdasan buatan (AI) di seluruh endpoint server dan komputer kerja untuk mendeteksi perilaku mencurigakan (seperti enkripsi massal secara tiba-tiba) dan mengisolasi perangkat yang terinfeksi secara seketika (real-time isolation).
- Segregasi Jaringan dan Mikro-segmentasi: Membagi jaringan bank menjadi segmen-segmen kecil yang terisolasi satu sama lain. Jika satu segmen komputer kerja terinfeksi ransomware, malware tidak akan bisa menyebar secara lateral (lateral movement) ke server inti perbankan (core banking).
- Strategi Backup Data Immutable (3-2-1-1-0 Rule): Menyimpan 3 salinan data, pada 2 media yang berbeda, dengan 1 salinan di lokasi luar (offsite/cloud), 1 salinan bersifat immutable (tidak dapat diubah atau dihapus oleh ransomware setelah ditulis), dan melakukan verifikasi pengujian pemulihan data dengan tingkat kesalahan 0.

### 10.2.2 Kontrol Administratif (Administrative Controls)
- Manajemen Kerentanan Berkala (Vulnerability Assessment & Penetration Testing - VAPT): Melakukan pemindaian celah keamanan secara rutin seminggu sekali dan melakukan simulasi peretasan (red teaming) minimal dua kali setahun untuk menutup celah keamanan sebelum dieksploitasi peretas.
- Kebijakan Hardening & Patch Management Otomatis: Mewajibkan pembaruan patch keamanan sistem operasi dan perangkat lunak secara otomatis dalam waktu maksimal 24 jam setelah patch resmi dirilis oleh vendor.
- Pelatihan Cyber Security Awareness & Phishing Simulation: Mengingat ransomware sering masuk melalui taktik social engineering (email phishing), karyawan wajib mengikuti pelatihan kesadaran siber dan simulasi jebakan email berkala setiap 3 bulan.

## 10.4 Rencana Kontingensi Singkat (Rencana Cadangan)
Jika kontrol preventif mengalami kegagalan teknis dan ransomware berhasil menembus pertahanan perimeter, langkah penanganan darurat yang disiapkan adalah:

**1. Aktivasi Incident Response Plan (IRP): Memutus seluruh koneksi internet luar secara instan dan mematikan jalur komunikasi antar-cabang untuk mengurung pergerakan ransomware.**
**2. Peralihan ke Disaster Recovery Center (DRC): Melakukan failover operasional ke pusat pemulihan bencana yang berada di lokasi geografis berbeda menggunakan data cadangan clean-state yang telah diverifikasi bebas dari malware.**





