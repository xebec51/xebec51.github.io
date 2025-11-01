---
layout: post
title: "Pengantar Strategi Software Testing (STQA #1)"
date: 2025-11-01 10:00:00 +0800
categories: [STQA]
tags: [stqa, strategi, stlc, sdc, black-box, white-box]
image: /assets/img/hero1.jpg
---

[cite_start]Rangkuman materi "Strategi Testing" dari Kelompok 1[cite: 16].

### Apa Itu Testing?

[cite_start]*Testing* adalah proses mengevaluasi produk perangkat lunak untuk menemukan cacat (bug) dan memastikan produk bekerja sesuai kebutuhan, baik fungsional maupun non-fungsional[cite: 53].

[cite_start]Tujuan utamanya adalah menemukan kesalahan, mengurangi risiko, meningkatkan kepercayaan *stakeholder*, menjamin keamanan, dan efisiensi biaya [cite: 70-75].

### Software Testing Life Cycle (STLC)

[cite_start]Testing memiliki siklus hidupnya sendiri (STLC) yang merupakan bagian dari *Software Development Life Cycle* (SDLC)[cite: 37, 42]. [cite_start]Tahapannya meliputi[cite: 116, 132, 145, 162]:
1.  [cite_start]**Test Planning:** Membuat strategi dan rencana[cite: 119].
2.  [cite_start]**Test Design:** Mengidentifikasi dan menulis *test case*[cite: 133, 134].
3.  [cite_start]**Test Eksekusi:** Menjalankan pengujian (Komponen, Integrasi, Sistem, Rilis) [cite: 148-159].
4.  [cite_start]**Pelaporan & Analisis:** Melaporkan hasil, bug, dan rekomendasi [cite: 164-178].

### Klasifikasi Testing

[cite_start]Berdasarkan **Struktur**[cite: 298, 306]:
* **Black-Box Testing:** Menguji fungsionalitas tanpa mengetahui struktur kode internal. [cite_start]Fokus pada input dan output[cite: 307, 308].
* **White-Box Testing:** Menguji dengan pengetahuan tentang struktur kode internal. [cite_start]Fokus pada alur logika dan algoritma [cite: 333-335].

[cite_start]Berdasarkan **Fungsi**[cite: 233]:
* [cite_start]**Functional Testing:** Menguji apakah software berfungsi sesuai persyaratan (Contoh: fungsi login)[cite: 241].
* [cite_start]**Non-Functional Testing:** Menguji *bagaimana* sistem bekerja (performa, keamanan, reliabilitas)[cite: 250, 251].

[cite_start]Berdasarkan **Abstraksi**[cite: 185]:
* [cite_start]**Unit Testing:** Menguji komponen terkecil[cite: 187, 195].
* [cite_start]**Integration Testing:** Menguji interaksi antar unit[cite: 188, 204].
* [cite_start]**System Testing:** Menguji sistem secara keseluruhan[cite: 190, 215].
* [cite_start]**Acceptance Testing:** Menguji dari perspektif pengguna akhir (klien)[cite: 191, 225].
