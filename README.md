# SplitZen - Modern Bill Splitter Application

SplitZen adalah aplikasi desktop berbasis Java yang dirancang untuk mempermudah perhitungan pembagian tagihan (split bill) secara adil, cepat, dan akurat. Aplikasi ini secara otomatis menghitung komponen tambahan seperti **Pajak (Tax)** dan **Biaya Layanan (Service Charge)**, lalu membagi totalnya ke sejumlah orang yang ditentukan.

## ✨ Fitur Utama
- **Modern UI:** Menggunakan library **FlatLaf** untuk tampilan Dark Mode yang elegan dan minimalis.
- **Smart Calculation:** Perhitungan otomatis subtotal, pajak, biaya layanan, hingga total per orang.
- **Input Validation:** Penanganan error jika pengguna memasukkan data non-angka untuk mencegah aplikasi crash.
- **Format Rupiah:** Output rincian biaya ditampilkan dalam format mata uang Rupiah (IDR) yang rapi.
- **Portable Executable:** Tersedia dalam format `.exe` yang siap dijalankan di sistem operasi Windows.

## 🚀 Teknologi yang Digunakan
- **Bahasa Pemrograman:** Java (JDK 18)
- **IDE:** NetBeans
- **GUI Library:** Java Swing & FlatLaf (Look and Feel)
- **Distribution Tool:** Launch4j (untuk konversi JAR ke EXE)

## 🛠️ Prasyarat (Prerequisites)
Untuk menjalankan aplikasi ini, pastikan sistem Anda memiliki:
- **Java Runtime Environment (JRE) 18** atau versi yang lebih baru.

## 📂 Struktur Project
- `src/`: Berisi kode sumber Java.
- `lib/`: Berisi library eksternal (FlatLaf .jar).
- `dist/`: Berisi file executable `.jar` hasil build.
- `SplitZen.exe`: File executable utama untuk pengguna Windows.

## 📝 Cara Menjalankan Project (Development)
1. Clone repositori ini:
   ```bash
   git clone [https://github.com/username/SplitZen.git](https://github.com/username/SplitZen.git)
