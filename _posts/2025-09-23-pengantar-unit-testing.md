---
layout: post
title: "Pengantar Unit Testing (STQA #5)"
date: 2025-09-23 10:00:00 +0800
categories: [STQA]
tags: [stqa, unit testing, aaa, jest, junit, pytest]
image: /assets/img/hero1.jpg
---

Rangkuman materi "Pengantar Unit Testing" dari Kelompok 5.

### Apa Itu Unit Testing?

*Unit testing* adalah pengujian perangkat lunak yang berfokus pada **unit-unit terkecil** (komponen) dalam sebuah sistem, seperti *function*, *method*, atau *class*. Ini adalah level pengujian paling dasar dan paling cepat dalam piramida testing.

Analoginya adalah seperti mengecek setiap komponen mobil (mesin, ban, rem) secara terpisah sebelum dirakit menjadi mobil utuh.

### Kenapa Unit Testing Penting?

Penerapan *unit testing* sangat penting karena:
* **Mendeteksi Bug Lebih Awal:** Menemukan masalah di level kode sebelum diintegrasikan.
* **Mempermudah Refactoring:** Memberi kepercayaan diri saat mengubah atau membersihkan kode tanpa merusak fungsionalitas yang ada.
* **Dokumentasi Hidup:** *Test case* berfungsi sebagai dokumentasi teknis tentang bagaimana seharusnya sebuah fungsi bekerja.
* **Menghemat Waktu dan Biaya:** Bug lebih murah diperbaiki jika ditemukan di tahap awal.

### Pola Arrange, Act, Assert (AAA)

Ini adalah pola standar dalam penulisan *unit test*:
1.  **Arrange:** Menyiapkan kondisi awal, variabel, atau *mock data* yang diperlukan.
2.  **Act:** Menjalankan fungsi atau metode yang akan diuji.
3.  **Assert:** Memverifikasi bahwa hasil dari *Act* sesuai dengan ekspektasi.

### Framework Populer

Beberapa *framework* yang umum digunakan untuk *unit testing*:
* **JUnit 5 (Java):** Standar *de facto* untuk ekosistem Java/JVM.
* **Jest (JavaScript):** Dibuat oleh Meta, sangat populer untuk React, Node.js, dll..
* **Pytest (Python):** Dikenal sederhana dan kuat, sering dipakai di *data science* dan API.
