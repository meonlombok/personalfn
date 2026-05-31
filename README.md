# Financely Pro - Sistem Manajemen Keuangan Personal

**Financely Pro** adalah sistem manajemen keuangan personal berbasis web yang modern, ringan, dan mandiri. Dirancang dengan mengutamakan kesederhanaan dan fleksibilitas, aplikasi ini memungkinkan pengguna untuk mengelola aset, melacak pengeluaran, memantau hutang, dan sinkronisasi data secara mulus dengan Google Sheets.

![Bahasa](https://img.shields.io/badge/Bahasa-Indonesia-blue)
![Tech Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20Tailwind%20CSS%20%7C%20JS-orange)

## 🚀 Fitur Utama

### 📊 Dashboard & Analitik
- **Ringkasan Kekayaan Bersih**: Perhitungan real-time untuk Total Aset, Total Hutang, dan Kekayaan Bersih (Net Worth).
- **Widget Dinamis**:
  - **Ringkasan Bulan Ini**: Perbandingan visual antara Pemasukan vs Pengeluaran.
  - **Rata-Rata Harian**: Melacak rata-rata pengeluaran Anda per hari.
  - **Next Payment Planner**: Memantau cicilan kredit yang akan datang dan tanggal jatuh temponya.
- **Estimasi Dana 7 Hari**: Perhitungan otomatis dana yang dibutuhkan untuk tagihan dalam satu minggu ke depan.

### 💳 Pengelolaan Akun
- Mendukung berbagai jenis akun: **Rekening Bank**, **E-Wallet**, dan **Limit Kredit/Pinjaman**.
- **Kredit & Cicilan**: Kelola struktur hutang yang kompleks dengan pelacakan tenor otomatis.

### 📝 Pencatatan Transaksi
- **Log Pemasukan & Pengeluaran**: Catat transaksi harian dengan kategori yang jelas.
- **Pembayaran Hutang**: Alur khusus untuk membayar cicilan dengan dukungan biaya admin dan biaya tambahan.
- **Transfer Saldo**: Pindahkan dana antar akun dengan mudah.
- **Filter Lanjutan**: Cari dan saring riwayat transaksi berdasarkan tipe, akun, dan rentang tanggal.

### ☁️ Sinkronisasi Cloud (Google Sheets)
- **Teknologi Delta Sync**: Sinkronisasi cerdas yang hanya memperbarui data yang berubah.
- **Integrasi Google Apps Script**: Gunakan Google Sheets sebagai database cloud pribadi yang aman.
- **Penyimpanan Lokal**: Tetap dapat digunakan secara offline menggunakan Browser Local Storage.

### 📱 Antarmuka Responsif
- Desain modern menggunakan **Tailwind CSS** dan font **Plus Jakarta Sans**.
- Navigasi mobile khusus dan menu aksi melayang (*floating action menu*) untuk pengalaman seperti aplikasi native.

## 🛠 Teknologi yang Digunakan
- **Frontend**: HTML5, Vanilla JavaScript.
- **Styling**: Tailwind CSS (melalui CDN).
- **Ikon**: Heroicons (SVG).
- **Backend/Cloud**: Google Apps Script (Web App).

## 📖 Cara Penggunaan

1. **Akses Lokal**: Cukup buka file `index.html` di browser modern apa pun.
2. **Setup Akun**: Tambahkan rekening bank, e-wallet, atau kartu kredit Anda di tab Dashboard.
3. **Catat Transaksi**: Gunakan tombol "Catat Transaksi" untuk mulai mengelola keuangan Anda.
4. **Backup Cloud (Opsional)**:
   - Buka menu **Google Sheets Sync**.
   - Ikuti instruksi untuk menerapkan Google Apps Script yang telah disediakan di dalam modal.
   - Tempelkan URL Web App Anda untuk mengaktifkan sinkronisasi awan.

## 🔒 Privasi
Financely Pro dirancang dengan privasi sebagai prioritas. Data Anda tetap berada di penyimpanan lokal browser Anda dan di Google Spreadsheet pribadi Anda. Tidak ada server pihak ketiga yang terlibat dalam penanganan data keuangan Anda.

---

*Dibuat untuk pengelolaan keuangan yang lebih mandiri dan fleksibel.*
