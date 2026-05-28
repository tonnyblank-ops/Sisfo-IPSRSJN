# SISFO STOCK BARANG IPSRS (RSUD SINJAI)

Sistem Informasi (Sisfo) Manajemen Stok Barang untuk Instalasi Pemeliharaan Sarana Rumah Sakit (IPSRS) di RSUD Sinjai, Sulawesi Selatan. Aplikasi berbasis web ini dirancang untuk memantau, mencatat, dan mengelola inventaris serta sirkulasi barang secara real-time dan efisien.

## 🚀 Fitur Utama

Dasbor interaktif aplikasi ini menyediakan metrik visual dan kontrol data sebagai berikut:
* **Dashboard Ikhtisar:** Ringkasan cepat jumlah item tersedia, kuantitas barang masuk, kuantitas barang keluar, dan status item stok kritis.
* **Peringatan Stok Menipis:** Deteksi otomatis barang yang mendekati batas minimum stok dalam 30 hari terakhir.
* **Analisis Produk Terpopuler:** Statistik performa barang dengan tingkat perputaran atau keluar tertinggi.
* **Rekapitulasi Satuan:** Grafik visual lingkaran (donut chart) untuk memantau distribusi barang berdasarkan jenis satuan (Picies, Meter, dll).
* **Riwayat Sirkulasi Real-Time:** Log kronologis transparan untuk melacak log masuk gudang dan log keluar unit.
* **Asisten AI:** Fitur kecerdasan buatan terintegrasi untuk membantu analisis data stok atau rekomendasi kebutuhan logistik.
* **Menu Manajemen Lengkap:** Akses cepat ke modul Referensi, Barang Masuk, Barang Keluar, Stok Gudang, dan Laporan Penjualan/Mutasi.

## 🛠️ Teknologi yang Digunakan

* **Frontend:** HTML5, CSS3, JavaScript (Dashboard dengan visualisasi grafik interaktif)
* **Backend:** *[Isi dengan Node.js / PHP / Python / Go sesuai backend Anda]*
* **Database:** *[Isi dengan MySQL / PostgreSQL / MongoDB sesuai database Anda]*

## 💻 Cara Menjalankan Proyek (Lokal)

Ikuti langkah berikut untuk menjalankan aplikasi ini di lingkungan lokal Anda:

### 1. Kloning Repositori
```bash
git clone https://github.com
cd sisfo-stock-ipsrs
```

### 2. Instalasi Dependensi
*[Sesuaikan perintah di bawah ini dengan package manager yang Anda gunakan]*
```bash
npm install
# atau jika menggunakan PHP (Composer): composer install
```

### 3. Konfigurasi Database & Environment
1. Salin file konfigurasi contoh:
   ```bash
   cp .env.example .env
   ```
2. Buka file `.env` dan sesuaikan kredensial database Anda.

### 4. Jalankan Aplikasi
```bash
npm run dev
# atau jika menggunakan PHP: php -S localhost:8000
```
Buka `http://localhost:8000` atau port yang tertera pada terminal Anda melalui peramban web (browser).

## 📄 Lisensi

Hak Cipta © 2026 KUODSKOM. Dikembangkan khusus untuk RSUD Sinjai.
