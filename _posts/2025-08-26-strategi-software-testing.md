---
layout: post
title: "Pengantar Strategi Software Testing (STQA #1)"
date: 2025-08-26 10:00:00 +0800
categories: [STQA]
tags: [stqa, strategi, stlc, sdc, black-box, white-box]
image: /assets/img/hero1.jpg
---

Rangkuman materi "Strategi Testing" dari Kelompok 1.

### Apa Itu Testing?

*Testing* adalah proses mengevaluasi produk perangkat lunak untuk menemukan cacat (bug) dan memastikan produk bekerja sesuai kebutuhan, baik fungsional maupun non-fungsional.

Tujuan utamanya adalah menemukan kesalahan, mengurangi risiko, meningkatkan kepercayaan *stakeholder*, menjamin keamanan, dan efisiensi biaya.

### Software Testing Life Cycle (STLC)

Testing memiliki siklus hidupnya sendiri (STLC) yang merupakan bagian dari *Software Development Life Cycle* (SDLC). Tahapannya meliputi:
1.  **Test Planning:** Membuat strategi dan rencana.
2.  **Test Design:** Mengidentifikasi dan menulis *test case*.
3.  **Test Eksekusi:** Menjalankan pengujian (Komponen, Integrasi, Sistem, Rilis).
4.  **Pelaporan & Analisis:** Melaporkan hasil, bug, dan rekomendasi.

### Klasifikasi Testing

Berdasarkan **Struktur**:
* **Black-Box Testing:** Menguji fungsionalitas tanpa mengetahui struktur kode internal. Fokus pada input dan output.
* **White-Box Testing:** Menguji dengan pengetahuan tentang struktur kode internal. Fokus pada alur logika dan algoritma.

Berdasarkan **Fungsi**:
* **Functional Testing:** Menguji apakah software berfungsi sesuai persyaratan (Contoh: fungsi login).
* **Non-Functional Testing:** Menguji *bagaimana* sistem bekerja (performa, keamanan, reliabilitas).

Berdasarkan **Abstraksi**:
* **Unit Testing:** Menguji komponen terkecil.
* **Integration Testing:** Menguji interaksi antar unit.
* **System Testing:** Menguji sistem secara keseluruhan.
* **Acceptance Testing:** Menguji dari perspektif pengguna akhir (klien).
