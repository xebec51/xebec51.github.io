---
layout: post
title: "EatoSphere - Global Restaurants Catalog"
date: 2025-01-16
categories: [Project]
tags: [frontend, pwa, web development, javascript]
---

![EatoSphere](https://pbs.twimg.com/media/Gh3TDjVbEAAnBKV?format=jpg&name=4096x4096)

🌐 **Final Submission dari Kelas**: [Menjadi Front-End Web Developer Expert (MFWDE) - Dicoding](https://www.dicoding.com/academies/219)  
🌐 **Link Production**: [https://eatosphere.netlify.app](https://eatosphere.netlify.app)

---

![Sertifikat](https://pbs.twimg.com/media/Gh3TFXZbUAAZYwe?format=jpg&name=4096x4096)

## Deskripsi Proyek
EatoSphere adalah aplikasi katalog restoran global yang memungkinkan pengguna untuk:
- Menjelajahi restoran dengan berbagai informasi lengkap.
- Menyimpan restoran favorit untuk akses mudah.
- Menambahkan ulasan pelanggan langsung di aplikasi.
- Mengakses aplikasi secara offline berkat fitur Progressive Web App (PWA).

### Fitur Utama
1. **Halaman Utama**  
   Menampilkan daftar restoran lengkap dengan nama, kota, rating, dan deskripsi.

2. **Halaman Detail**  
   Menyediakan informasi lengkap restoran termasuk menu, lokasi, dan ulasan pelanggan.

3. **Halaman Favorit**  
   Menyimpan dan menampilkan restoran favorit.  
   Memungkinkan pengguna menghapus restoran dari favorit.

4. **Offline Support**  
   Mendukung akses offline dengan cache Service Worker.

## Langkah Menjalankan Proyek

### Prasyarat
- **Node.js** versi >= 18  
- **npm** versi >= 8  
- **Git** untuk mengelola repository

### Langkah-Langkah
1. Clone repository ini:  
   ```bash
   git clone https://github.com/xebec51/EatoSphere-GlobalRestaurantsCatalog.git
   ```  
2. Masuk ke folder proyek:  
   ```bash
   cd EatoSphere-GlobalRestaurantsCatalog
   ```  
3. Instal semua dependensi:  
   ```bash
   npm install
   ```  
4. Jalankan server pengembangan:  
   ```bash
   npm run start-dev
   ```  
5. Akses aplikasi di browser:  
   [http://localhost:8080](http://localhost:8080)

## Build untuk Production
1. Jalankan perintah berikut:  
   ```bash
   npm run build
   ```  
2. File hasil build akan tersimpan di folder `dist`.

### Bundle Analyzer
Untuk memeriksa optimasi bundle, jalankan:
```bash
ANALYZE=true npm run build
```
Akses Webpack Bundle Analyzer di [http://localhost:8888](http://localhost:8888).

## Pengujian
### Unit Testing
Jalankan pengujian unit menggunakan Jest:  
```bash
npm test
```

### End-to-End Testing
Jalankan pengujian E2E menggunakan Playwright:  
```bash
npm run e2e
```

## Teknologi Pendukung
- **HTML, CSS, JavaScript**: Teknologi dasar antarmuka.
- **Webpack**: Untuk optimasi dan bundling kode.
- **Workbox**: Untuk mendukung PWA.
- **IndexedDB**: Untuk penyimpanan lokal data favorit.
- **Jest**: Untuk pengujian unit.
- **Playwright**: Untuk pengujian E2E.
- **Imagemin dan WebP**: Untuk optimasi gambar.

## Kontributor
- **Muh. Rinaldi Ruslan**
  - **Email**: [rinaldi.ruslan51@gmail.com](mailto:rinaldi.ruslan51@gmail.com)
  - **GitHub**: [xebec51](https://github.com/xebec51)
  - **Instagram**: [@rinaldiruslan](https://www.instagram.com/rinaldiruslan/)

## Lisensi
Proyek ini dilisensikan di bawah **MIT License**. Lihat file [LICENSE](https://raw.githubusercontent.com/xebec51/EatoSphere-GlobalRestaurantsCatalog/refs/heads/main/LICENSE) untuk informasi lebih lanjut.
```
