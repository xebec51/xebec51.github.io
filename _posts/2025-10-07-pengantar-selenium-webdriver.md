---
layout: post
title: "Pengantar Selenium WebDriver (STQA #7)"
date: 2025-10-07 10:00:00 +0800
categories: [STQA]
tags: [stqa, automation, selenium, webdriver]
image: /assets/img/hero3.jpg
---

[cite_start]Rangkuman materi "Pengantar Selenium WebDriver" dari Kelompok 7[cite: 813, 814].

### Apa itu Selenium?

[cite_start]Selenium adalah sebuah *framework open-source* yang sangat populer untuk **otomasi browser**[cite: 827, 828]. Tujuan utamanya adalah untuk mengotomatiskan pengujian aplikasi web.

### Apa itu Selenium WebDriver?

[cite_start]*WebDriver* adalah komponen inti (dan API) dari Selenium modern[cite: 833, 834]. [cite_start]Ia berfungsi sebagai "jembatan" atau penghubung yang memungkinkan kode pengujian Anda berkomunikasi dan memberi perintah langsung ke browser[cite: 835].

Sederhananya:
1.  Anda menulis **Test Script** (misal: dalam Python atau Java).
2.  *Script* Anda memanggil perintah **WebDriver** (misal: `klik tombol login`).
3.  [cite_start]**WebDriver** menerjemahkan perintah itu dan mengirimkannya ke **Browser** (Chrome, Firefox, dll) [cite: 837-844].
4.  Browser menjalankan perintah itu seolah-olah dilakukan oleh pengguna sungguhan.

### Kenapa Menggunakan Selenium?

[cite_start]Selenium menjadi standar industri karena beberapa alasan [cite: 849-854]:
* **Open-Source dan Gratis:** Tidak memerlukan biaya lisensi.
* [cite_start]**Multi-Bahasa:** Dapat ditulis dalam banyak bahasa (Python, Java, C#, JavaScript, Ruby)[cite: 850].
* [cite_start]**Multi-Browser:** Mendukung hampir semua browser modern (Chrome, Firefox, Edge, Safari)[cite: 830].
* [cite_start]**Multi-Platform:** Berjalan di Windows, macOS, dan Linux[cite: 851].
* [cite_start]**Komunitas Besar:** Memiliki komunitas yang sangat besar dan dokumentasi yang lengkap[cite: 854].
