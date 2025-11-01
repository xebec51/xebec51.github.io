---
layout: post
title: "Pengantar Unit Testing (STQA #5)"
date: 2025-09-23 10:00:00 +0800
categories: [STQA]
tags: [stqa, unit testing, aaa, jest, junit, pytest]
image: /assets/img/hero1.jpg
---

[cite_start]Rangkuman materi "Pengantar Unit Testing" dari Kelompok 5[cite: 559].

### Apa Itu Unit Testing?

[cite_start]*Unit testing* adalah pengujian perangkat lunak yang berfokus pada **unit-unit terkecil** (komponen) dalam sebuah sistem, seperti *function*, *method*, atau *class*[cite: 603, 604, 611]. [cite_start]Ini adalah level pengujian paling dasar dan paling cepat dalam piramida testing[cite: 609, 610].

[cite_start]Analoginya adalah seperti mengecek setiap komponen mobil (mesin, ban, rem) secara terpisah sebelum dirakit menjadi mobil utuh[cite: 615].

### Kenapa Unit Testing Penting?

[cite_start]Penerapan *unit testing* sangat penting karena [cite: 619-634]:
* **Mendeteksi Bug Lebih Awal:** Menemukan masalah di level kode sebelum diintegrasikan.
* **Mempermudah Refactoring:** Memberi kepercayaan diri saat mengubah atau membersihkan kode tanpa merusak fungsionalitas yang ada.
* **Dokumentasi Hidup:** *Test case* berfungsi sebagai dokumentasi teknis tentang bagaimana seharusnya sebuah fungsi bekerja.
* **Menghemat Waktu dan Biaya:** Bug lebih murah diperbaiki jika ditemukan di tahap awal.

### Pola Arrange, Act, Assert (AAA)

[cite_start]Ini adalah pola standar dalam penulisan *unit test*[cite: 666]:
1.  [cite_start]**Arrange:** Menyiapkan kondisi awal, variabel, atau *mock data* yang diperlukan[cite: 668, 669, 680].
2.  [cite_start]**Act:** Menjalankan fungsi atau metode yang akan diuji[cite: 671, 672, 681].
3.  [cite_start]**Assert:** Memverifikasi bahwa hasil dari *Act* sesuai dengan ekspektasi[cite: 674, 675, 682].

### Framework Populer

[cite_start]Beberapa *framework* yang umum digunakan untuk *unit testing*[cite: 638]:
* [cite_start]**JUnit 5 (Java):** Standar *de facto* untuk ekosistem Java/JVM[cite: 641].
* [cite_start]**Jest (JavaScript):** Dibuat oleh Meta, sangat populer untuk React, Node.js, dll.[cite: 649].
* [cite_start]**Pytest (Python):** Dikenal sederhana dan kuat, sering dipakai di *data science* dan API[cite: 657].
