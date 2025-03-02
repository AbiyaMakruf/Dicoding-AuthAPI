# 📌 Dicoding-AuthAPI

Studi Kasus Clean Architecture + TDD: Membangun Auth API 🚀

## 📖 Daftar Isi
- [Tentang Proyek](#tentang-proyek)
- [Fitur](#fitur)
- [Persyaratan](#persyaratan)
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Struktur Proyek](#struktur-proyek)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)
- [Kontak](#kontak)

## 🔍 Tentang Proyek
Proyek ini bertujuan untuk membangun sebuah API otentikasi menggunakan pendekatan **Clean Architecture** dan **Test-Driven Development (TDD)**. Ini merupakan bagian dari latihan dalam kursus **"Menjadi Back-End Developer Expert dengan JavaScript"** yang diselenggarakan oleh Dicoding.

## ✨ Fitur
- 📝 **Registrasi Pengguna** - Membuat akun pengguna baru.
- 🔐 **Login Pengguna** - Mengautentikasi pengguna dan memberikan token akses.
- 🔄 **Manajemen Otentikasi** - Memvalidasi dan memperbarui token akses.

## ⚙️ Persyaratan
Pastikan Anda memiliki perangkat lunak berikut yang terinstal di sistem Anda:
- 🟢 [Node.js](https://nodejs.org/) (versi 14 atau lebih baru)
- 📦 [npm](https://www.npmjs.com/) (biasanya terinstal bersama Node.js)
- 🗄️ [PostgreSQL](https://www.postgresql.org/) (sebagai basis data)

## 🚀 Instalasi
1. **Kloning repositori ini:**
   ```bash
   git clone https://github.com/AbiyaMakruf/Dicoding-AuthAPI.git
   cd Dicoding-AuthAPI
   ```
2. **Instal dependensi:**
   ```bash
   npm install
   ```
3. **Konfigurasi basis data:**
   - Buat basis data PostgreSQL baru.
   - Salin file `.env.example` menjadi `.env` dan sesuaikan konfigurasi basis data sesuai dengan pengaturan Anda.
4. **Migrasi basis data:**
   ```bash
   npm run migrate
   ```

## 🛠️ Penggunaan
1. **Menjalankan server:**
   ```bash
   npm start
   ```
   Server akan berjalan di `http://localhost:3000`.
2. **Menjalankan pengujian:**
   ```bash
   npm test
   ```

## 📁 Struktur Proyek
```
├── src
│   ├── api
│   ├── config
│   ├── migrations
│   ├── models
│   ├── routes
│   └── utils
├── tests
│   ├── integration
│   └── unit
├── .env.example
├── .gitignore
├── package.json
└── README.md
```
- 📂 **`src/`**: Berisi kode sumber aplikasi.
- 📂 **`tests/`**: Berisi pengujian unit dan integrasi.
- 📄 **`.env.example`**: Contoh file konfigurasi lingkungan.
- 📜 **`package.json`**: Berisi informasi proyek dan dependensi.

## 🤝 Kontribusi
Kontribusi sangat diterima! Jika Anda memiliki saran atau perbaikan, silakan buat **issue** atau **pull request**. 🚀