<div align="center">
  <img src="./moneta-logo-launcher.png" alt="Logo Moneta" width="140" />
  <h1>Moneta</h1>
  <p><strong>Catat uangmu. Kenali pengeluaranmu. Ingat pembayaranmu.</strong></p>
  <p>Aplikasi keuangan pribadi untuk Android, dengan tampilan hijau yang sederhana dan nyaman digunakan.</p>
  <p>
    <img src="https://img.shields.io/badge/Android-APK-3B765C?style=for-the-badge&logo=android&logoColor=white" alt="Android APK" />
    <img src="https://img.shields.io/badge/Versi-1.3.0-163D30?style=for-the-badge" alt="Versi 1.3.0" />
    <img src="https://img.shields.io/badge/Bahasa-Indonesia-3B765C?style=for-the-badge" alt="Bahasa Indonesia" />
  </p>
  <p>
    <a href="https://github.com/daffaar01/moneta/releases/download/v1.3.0/Moneta-1.3.0.apk"><img src="https://img.shields.io/badge/Unduh_Moneta-APK_Android-087F5B?style=for-the-badge&logo=android&logoColor=white" alt="Unduh APK Moneta" /></a>
  </p>
  <p><a href="https://github.com/daffaar01/moneta/releases/latest">Lihat release terbaru</a> · <a href="#mulai-menggunakan-moneta">Panduan instalasi</a> · <a href="https://github.com/daffaar01/moneta/issues">Laporkan masalah</a></p>
</div>

---

## Keuangan harian, lebih mudah dipantau

Moneta membantu kamu mencatat pemasukan dan pengeluaran dalam rupiah, melihat ringkasan bulanan, serta mengingat tanggal pembayaran. Setiap pengeluaran bisa mengambil dana dari pemasukan tertentu sehingga sisa dana sumbernya tetap jelas.

## Yang bisa kamu lakukan

| Fitur | Manfaat untukmu |
| :--- | :--- |
| **Ringkasan bulanan** | Lihat total pemasukan, pengeluaran, selisih, dan rincian pengeluaran per kategori. |
| **Catatan transaksi** | Tambah, edit, dan hapus transaksi; cari riwayat berdasarkan bulan, jenis, dan kategori. |
| **Sumber dana pilihanmu** | Tentukan pemasukan yang digunakan untuk pengeluaran. Nominal yang melebihi sisa dana sumber tersebut ditolak. |
| **Kategori pribadi** | Kelola kategori sesuai kebutuhan dan arsipkan kategori yang sudah digunakan. |
| **Kalender pembayaran** | Tandai tanggal pembayaran, tulis catatan, dan pantau status belum dibayar atau lunas. |
| **Pengingat di HP** | Atur notifikasi H-1 dan hari pembayaran sekitar pukul 09.00. |
| **Kunci aplikasi** | Aktifkan sidik jari/biometrik dengan cadangan PIN atau pola kunci layar HP. |
| **Akun pribadi** | Login dengan akunmu untuk mengakses data keuangan yang tersimpan di Supabase. |

## Mulai menggunakan Moneta

1. **[Unduh Moneta 1.3.0.apk](https://github.com/daffaar01/moneta/releases/download/v1.3.0/Moneta-1.3.0.apk)** melalui HP Android.
2. Buka APK dan izinkan instalasi dari browser atau pengelola berkas jika Android memintanya.
3. Instal Moneta, lalu daftar dan verifikasi email, atau login jika sudah punya akun.
4. Catat pemasukan pertamamu, lalu pilih pemasukan tersebut sebagai sumber dana ketika menambahkan pengeluaran.
5. Tambahkan pengingat di **Kalender** dan izinkan notifikasi agar jadwal pembayaran muncul di HP.

> **Sudah memakai Moneta?** Instal APK sebagai pembaruan tanpa menghapus aplikasi sebelumnya. Versi 1.3.0 tidak memerlukan migrasi Supabase tambahan.

## Baru di versi 1.3.0

- **Kunci dengan sidik jari/biometrik** melalui **Pengaturan → Kunci aplikasi → Aktifkan kunci sidik jari**.
- Aplikasi terkunci saat dibuka kembali, dengan tombol **Kunci sekarang** untuk mengunci secara manual.
- Screenshot dan pratinjau recent apps Android dilindungi saat kunci aplikasi aktif.

Perangkat perlu memiliki kunci layar dan biometrik yang sudah terdaftar. Pengaturan kunci berlaku pada HP tempat kamu mengaktifkannya.

## Data dan akunmu

- **Akun baru memiliki catatan transaksi sendiri.** Transaksi milik pengguna lain tidak ikut muncul; kategori awal disediakan untuk setiap akun.
- Data mengikuti akun yang digunakan untuk login. Orang yang login dengan akunmu dapat mengakses data akunmu, jadi simpan kredensial login dengan baik.
- Data disimpan di Supabase, dengan aturan akses berdasarkan pemilik data (Row Level Security).
- Kunci sidik jari melindungi akses aplikasi pada perangkatmu. Isi notifikasi di luar aplikasi mengikuti pengaturan privasi notifikasi Android.

## Hal yang perlu diketahui

| | |
| :--- | :--- |
| **Platform** | Android |
| **Mata uang** | Rupiah (IDR), tanpa pecahan rupiah |
| **Koneksi** | Internet diperlukan untuk login dan mengakses data |
| **Selisih bulanan** | Pemasukan dikurangi pengeluaran pada bulan tersebut; bukan saldo rekening bank |
| **Pengingat** | Pengaturan baterai HP dapat menunda notifikasi |
| **Status lunas** | Menandai pengingat lunas tidak otomatis membuat transaksi pengeluaran |

<details>
<summary><strong>Teknologi di balik Moneta</strong></summary>

Moneta dibangun menggunakan **React Native, Expo, TypeScript, dan Expo Router**. **Supabase Auth** menangani akun pengguna, sedangkan database Supabase menyimpan kategori, transaksi, dan pengingat pembayaran. Notifikasi dan autentikasi biometrik menggunakan modul Expo.

Repositori ini menyediakan APK, catatan rilis, dan panduan penggunaan Moneta.

</details>

---

<div align="center">
  <p><strong>Mulai dari satu catatan hari ini.</strong></p>
  <p><a href="https://github.com/daffaar01/moneta/releases/latest">Download Moneta</a> · <a href="https://github.com/daffaar01/moneta/issues">Bantuan & laporan masalah</a></p>
</div>
