---
layout: post
title: "Test Scenario, Case, & Bug Report (STQA #4)"
date: 2025-09-16 10:00:00 +0800
categories: [STQA]
tags: [stqa, test case, test scenario, bug report]
image: /assets/img/hero4.jpg
---

Rangkuman materi "Test Scenario, Test Case, and Bug Report" dari Kelompok 4.

### Test Scenario vs Test Case

Dua konsep ini adalah inti dari perencanaan pengujian dan sering tertukar:

* **Test Scenario (Apa yang diuji?)**
    Ini adalah gambaran umum *high-level* dari fungsionalitas yang akan diuji. Ini menjawab pertanyaan "Apa yang harus saya uji?".
    * **Contoh:** "Periksa fungsi perhitungan BMI".

* **Test Case (Bagaimana cara mengujinya?)**
    Ini adalah serangkaian langkah detail, input, dan hasil yang diharapkan untuk mengeksekusi sebuah skenario.
    * **Contoh:** "Masukkan Tinggi=170, Berat=65. *Expected Result*: Hasil BMI = 22.49".

### Bug Report

Saat *Actual Result* tidak sama dengan *Expected Result*, maka ditemukan *bug*. *Bug Report* adalah laporan formal untuk mendokumentasikan *bug* tersebut.

Komponen penting dalam laporan *bug* meliputi:
* **Title:** Judul yang jelas dan spesifik (misal: "Perhitungan BMI salah saat...").
* **Steps to Reproduce:** Langkah-langkah untuk memunculkan *bug* kembali.
* **Actual Result:** Apa yang sebenarnya terjadi (misal: "Hasil BMI = 12.5").
* **Expected Result:** Apa yang seharusnya terjadi (misal: "Hasil BMI seharusnya = 20.8").
* **Severity (Tingkat Keparahan):** Seberapa besar dampak *bug* pada sistem.
    * **Critical:** Kegagalan total, data rusak, aplikasi *crash*.
    * **Major (High):** Fungsionalitas utama tidak berfungsi.
    * **Minor (Medium):** Fungsionalitas non-utama bermasalah atau *workaround* ada.
    * **Low:** Cacat kosmetik (typo, UI sedikit salah).
* **Priority (Prioritas):** Seberapa cepat *bug* ini harus diperbaiki (P1-P4).
