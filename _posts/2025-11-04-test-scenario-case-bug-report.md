---
layout: post
title: "Test Scenario, Case, & Bug Report (STQA #4)"
date: 2025-11-04 10:00:00 +0800
categories: [STQA]
tags: [stqa, test case, test scenario, bug report]
image: /assets/img/hero4.jpg
---

[cite_start]Rangkuman materi "Test Scenario, Test Case, and Bug Report" dari Kelompok 4[cite: 374, 378].

### Test Scenario vs Test Case

Dua konsep ini adalah inti dari perencanaan pengujian dan sering tertukar:

* [cite_start]**Test Scenario (Apa yang diuji?)** [cite: 396]
    [cite_start]Ini adalah gambaran umum *high-level* dari fungsionalitas yang akan diuji[cite: 382]. Ini menjawab pertanyaan "Apa yang harus saya uji?".
    * [cite_start]**Contoh:** "Periksa fungsi perhitungan BMI"[cite: 403].

* [cite_start]**Test Case (Bagaimana cara mengujinya?)** [cite: 397]
    [cite_start]Ini adalah serangkaian langkah detail, input, dan hasil yang diharapkan untuk mengeksekusi sebuah skenario[cite: 384].
    * [cite_start]**Contoh:** "Masukkan Tinggi=170, Berat=65. *Expected Result*: Hasil BMI = 22.49"[cite: 408].

### Bug Report

Saat *Actual Result* tidak sama dengan *Expected Result*, maka ditemukan *bug*. [cite_start]*Bug Report* adalah laporan formal untuk mendokumentasikan *bug* tersebut[cite: 386, 387, 412].

[cite_start]Komponen penting dalam laporan *bug* meliputi [cite: 433-436]:
* **Title:** Judul yang jelas dan spesifik (misal: "Perhitungan BMI salah saat...").
* **Steps to Reproduce:** Langkah-langkah untuk memunculkan *bug* kembali.
* **Actual Result:** Apa yang sebenarnya terjadi (misal: "Hasil BMI = 12.5").
* **Expected Result:** Apa yang seharusnya terjadi (misal: "Hasil BMI seharusnya = 20.8").
* [cite_start]**Severity (Tingkat Keparahan):** Seberapa besar dampak *bug* pada sistem[cite: 415].
    * [cite_start]**Critical:** Kegagalan total, data rusak, aplikasi *crash*[cite: 422, 423].
    * [cite_start]**Major (High):** Fungsionalitas utama tidak berfungsi[cite: 420, 421].
    * [cite_start]**Minor (Medium):** Fungsionalitas non-utama bermasalah atau *workaround* ada[cite: 418, 419].
    * [cite_start]**Low:** Cacat kosmetik (typo, UI sedikit salah)[cite: 414, 417].
* [cite_start]**Priority (Prioritas):** Seberapa cepat *bug* ini harus diperbaiki (P1-P4) [cite: 424, 426-432].
