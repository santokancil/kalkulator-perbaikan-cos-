# Kalkulator Perbaikan Faktor Daya (Cos φ)

Aplikasi berbasis web untuk analisis dan simulasi perbaikan faktor daya (cos φ) menggunakan kapasitor.

Aplikasi ini dikembangkan sebagai bagian dari penelitian skripsi pada Program Studi Pendidikan Teknik Elektro, Universitas Negeri Yogyakarta.

## Informasi Peneliti

Nama        : Khusnullissanto  
NIM         : 22501244001  
Program Studi : Pendidikan Teknik Elektro  
Universitas : Universitas Negeri Yogyakarta  

## Latar Belakang

Faktor daya merupakan salah satu parameter penting dalam sistem tenaga listrik. Faktor daya yang rendah dapat menyebabkan peningkatan arus listrik, kerugian daya, serta penurunan efisiensi sistem.

Untuk mengatasi permasalahan tersebut, diperlukan metode perbaikan faktor daya menggunakan kapasitor. Oleh karena itu, penelitian ini mengembangkan sebuah **trainer perbaikan faktor daya** yang dilengkapi dengan sistem kontrol dan aplikasi analisis berbasis web.

## Tujuan Penelitian

Penelitian ini bertujuan untuk:

1. Mengembangkan **trainer perbaikan faktor daya** sebagai media pembelajaran pada bidang sistem tenaga listrik.
2. Mengembangkan **sistem kontrol berbasis ESP32** untuk pengoperasian trainer dalam mode manual dan otomatis.
3. Mengembangkan **aplikasi berbasis web** untuk melakukan analisis dan simulasi perbaikan faktor daya.
4. Mengintegrasikan trainer dengan aplikasi analisis sehingga dapat digunakan sebagai media praktik dan pembelajaran bagi mahasiswa.

## Komponen Sistem

Sistem yang dikembangkan dalam penelitian ini terdiri dari beberapa bagian utama:

### 1. Trainer Perbaikan Faktor Daya

Trainer digunakan sebagai media praktik untuk melakukan percobaan perbaikan faktor daya menggunakan kapasitor.

### 2. Sistem Kontrol ESP32

ESP32 digunakan sebagai pengendali sistem dengan dua mode operasi:

- **Mode Manual** → Pengguna dapat mengaktifkan kapasitor secara manual
- **Mode Otomatis** → Sistem akan mengatur kapasitor secara otomatis berdasarkan kondisi faktor daya

### 3. Aplikasi Analisis Berbasis Web

Aplikasi web digunakan untuk:

- Menghitung daya semu (VA)
- Menghitung nilai cos φ awal
- Menentukan kebutuhan kapasitor
- Melakukan simulasi penggunaan kapasitor
- Menampilkan hasil perbaikan faktor daya

## Input Data

Pengguna memasukkan data pengukuran berupa:

- Tegangan (Volt)
- Arus (Ampere)
- Daya Aktif (Watt)

## Output Sistem

Aplikasi akan menghasilkan:

- Daya Semu (VA)
- Nilai Cos φ awal
- Nilai kapasitor teoritis
- Nilai Cos φ setelah perbaikan

## Teknologi yang Digunakan

Penelitian ini menggunakan beberapa teknologi berikut:

- HTML
- CSS
- JavaScript
- ESP32
- Sistem kontrol kapasitor

## Manfaat Penelitian

Hasil penelitian ini diharapkan dapat:

- Menjadi media pembelajaran pada mata kuliah sistem tenaga listrik
- Membantu mahasiswa memahami konsep faktor daya
- Memberikan pengalaman praktik langsung melalui trainer
- Mengintegrasikan pembelajaran teori dan praktik

## Akses Aplikasi

Aplikasi dapat diakses melalui GitHub Pages setelah sistem di-deploy.
