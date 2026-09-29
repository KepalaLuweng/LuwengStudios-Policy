# Kebijakan Privasi (Privacy Policy) — CATET

**Terakhir Diperbarui: September 2026**

Luweng Studios ("Kami") berkomitmen penuh untuk melindungi dan menghormati hak privasi Anda. Dokumen Kebijakan Privasi ini menerangkan standar tata kelola dan perlindungan informasi pada aplikasi **CATET: Financial & Mobility Intelligence System**.

---

### 1. Prinsip Dasar: Offline-First & Zero-Knowledge Architecture
Aplikasi CATET dibangun dengan prinsip kemandirian data mutlak (*Offline-First*). Seluruh data finansial, pembukuan kas UMKM, riwayat order, catatan servis kendaraan, dan target tabungan Anda disimpan secara lokal pada perangkat Anda dalam basis data internal terenkripsi. 

Kami **tidak pernah mengunggah, menyalin, menganalisis, ataupun menjual** catatan finansial maupun riwayat perjalanan Anda ke server pusat kami atau pihak ketiga mana pun.

---

### 2. Informasi yang Diproses & Izin Perangkat
Kami hanya meminta izin sistem yang secara mutlak dibutuhkan untuk fungsi aplikasi yang diaktifkan secara sadar oleh pengguna:

* **Autentikasi Pengguna (Google Sign-In via Firebase Auth):** Hanya menerima identitas profil publik dasar (Nama Lengkap, Email, dan Foto Profil) guna mengamankan kepemilikan akun. Kami tidak memiliki akses terhadap kata sandi Anda.
* **Izin Lokasi Presisi (GPS Fine & Coarse Location):** Digunakan untuk fitur **Radar BBM** dalam menghitung jarak ke SPBU terdekat, serta **Mode Mengemudi** untuk kalkulasi speedometer dan akumulasi jarak tempuh harian. Koordinat GPS diproses di memori perangkat dan tidak disimpan sebagai riwayat pelacakan di server.
* **Layanan Latar Belakang (Foreground Service):** Berjalan saat Anda menyalakan *Mode Mengemudi* atau *Widget Speedometer Mengambang* agar pencatatan jarak tempuh dan konsumsi BBM tetap akurat meskipun layar dimatikan atau saat membuka aplikasi navigasi lain.
* **Notifikasi Berkala (POST_NOTIFICATIONS):** Digunakan untuk menampilkan status mengemudi aktif serta *Pengingat Servis Berkala* (ganti oli mesin, oli gardan, CVT, rantai) yang dihitung murni secara lokal berdasarkan Odometer kendaraan Anda.

---

### 3. Keamanan File Cadangan (.CTT)
CATET menyediakan fitur pencadangan mandiri berformat `.ctt` dengan enkripsi tingkat lanjut (*client-side encryption*). File cadangan ini sepenuhnya menjadi hak milik Anda dan dapat disimpan secara aman di memori lokal, dikirim melalui media pribadi, atau dicadangkan ke Google Drive milik akun Anda sendiri.

---

### 4. Kepatuhan Standar Global & UU PDP
Sesuai dengan standar GDPR dan Undang-Undang Perlindungan Data Pribadi (UU PDP Indonesia), Anda memiliki hak mutlak untuk:
* Mencabut izin lokasi, notifikasi, dan overlay kapan saja melalui Pengaturan Sistem Android.
* Menghapus seluruh data lokal dan profil secara permanen melalui tombol *Hapus Semua Data* di aplikasi.

---

### 5. Hubungi Kami
Untuk pertanyaan hukum, klarifikasi privasi, atau dukungan teknis resmi:
* **Pengembang Utama:** Darmawan Aditya (KepalaLuweng)
* **Organisasi:** Luweng Studios Engineering
* **Telegram Dukungan Resmi:** [t.me/luwengtechofficial](https://t.me/luwengtechofficial)
* **Channel Pembaruan:** [t.me/luwengtechsupport](https://t.me/luwengtechsupport)
