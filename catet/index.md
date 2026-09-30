# Kebijakan Privasi (Privacy Policy) — CATET

**Terakhir Diperbarui: September 2026** • **Organisasi: LuwengGroup**

**LuwengGroup** ("Kami") berkomitmen penuh untuk melindungi dan menghormati hak privasi Anda. Dokumen Kebijakan Privasi ini menerangkan standar tata kelola dan perlindungan informasi pada aplikasi **CATET: Financial & Mobility Intelligence System** (`com.luwengstudios.catet`).

---

### 1. Prinsip Dasar: Privacy-by-Design & Zero-Knowledge Architecture
Aplikasi CATET dibangun dengan prinsip kemandirian data mutlak (*Offline-First*). Seluruh data finansial, pembukuan kas UMKM, riwayat order, catatan servis kendaraan, dan target tabungan Anda disimpan secara lokal pada perangkat Anda dalam basis data internal terenkripsi. 

Kami **tidak pernah mengunggah, menyalin, menganalisis, ataupun menjual** catatan finansial maupun riwayat perjalanan Anda ke server pusat kami atau pihak ketiga mana pun.

---

### 2. Autentikasi Wajib Akun Google (Google Identity)
Untuk menjamin keamanan akun dan integritas sinkronisasi data cloud:
* **Data Profil Publik Dasar:** Kami menerima identitas profil publik terverifikasi (Nama, Alamat Email terdaftar, UID Firebase, dan Foto Profil) guna mengamankan kepemilikan akun.
* Kami **tidak pernah memiliki akses atau menyimpan kata sandi akun Google Anda**.

---

### 3. Informasi yang Diproses & Izin Lokasi Presisi
Kami hanya meminta izin sistem yang secara mutlak dibutuhkan untuk fungsi aplikasi yang diaktifkan secara sadar oleh pengguna:

* **Izin Lokasi Presisi (GPS Fine & Coarse Location):** Digunakan untuk fitur **Radar BBM** dalam menghitung jarak ke 4 stasiun SPBU Pertamina terdekat di sekitar posisi real-time pengguna, serta **Mode Mengemudi** untuk kalkulasi speedometer dan akumulasi jarak tempuh harian (KM). Koordinat GPS diproses secara real-time di memori kerja perangkat dan tidak disimpan sebagai riwayat pelacakan di server mana pun.
* **Layanan Latar Belakang (Foreground Service):** Berjalan saat Anda menyalakan *Mode Mengemudi* atau *Widget Speedometer Mengambang* dengan notifikasi tetap di bilah status agar pencatatan jarak tempuh dan konsumsi BBM tetap akurat saat menggunakan navigasi lain.
* **Pencadangan Mandiri dengan Jetpack WorkManager:** Menggunakan sistem penjadwalan hemat daya Android yang mematuhi pedoman Google Play tanpa memerlukan izin alarm khusus (*SCHEDULE_EXACT_ALARM*).
* **Storage Access Framework (SAF):** Tidak meminta izin akses penyimpanan luas (*MANAGE_EXTERNAL_STORAGE*). Pengguna bebas memilih folder penyimpanan file cadangan `.ctt` terenkripsi melalui pemilih dokumen resmi Android.

---

### 4. Hak Pengguna & Penghapusan Data (Right to Erasure)
Sesuai dengan Google Play User Data Policy, standar GDPR, dan UU Pelindungan Data Pribadi (UU PDP No. 27 Tahun 2022):
* Anda dapat menghapus seluruh data lokal dan histori catatan seketika melalui tombol *Hapus Semua Data* di aplikasi.
* Anda berhak mengajukan permohonan penghapusan permanen seluruh data profil akun cloud kami dengan menghubungi tim privasi kami melalui email **luwengstudio@gmail.com** atau saluran Telegram resmi.

---

### 5. Hubungi Kami
Untuk pertanyaan hukum, permohonan penghapusan data, atau dukungan teknis resmi:
* **Organisasi:** LuwengGroup
* **Lead Developer:** Darmawan Aditya (KepalaLuweng)
* **Email Resmi:** luwengstudio@gmail.com
* **Telegram Dukungan Resmi:** [t.me/luwengtechofficial](https://t.me/luwengtechofficial)
* **Channel Pembaruan:** [t.me/luwengtechsupport](https://t.me/luwengtechsupport)
