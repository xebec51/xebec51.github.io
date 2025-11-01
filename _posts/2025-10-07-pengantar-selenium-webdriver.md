---
layout: post
title: "Pengantar Selenium WebDriver (STQA #7)"
date: 2025-10-07 10:00:00 +0800
categories: [STQA]
tags: [stqa, automation, selenium, webdriver]
image: /assets/img/hero3.jpg
---

Rangkuman materi "Pengantar Selenium WebDriver" dari Kelompok 7.

### Apa itu Selenium?

Selenium adalah sebuah *framework open-source* yang sangat populer untuk **otomasi browser**. Tujuan utamanya adalah untuk mengotomatiskan pengujian aplikasi web.

### Apa itu Selenium WebDriver?

*WebDriver* adalah komponen inti (dan API) dari Selenium modern. Ia berfungsi sebagai "jembatan" atau penghubung yang memungkinkan kode pengujian Anda berkomunikasi dan memberi perintah langsung ke browser.

Sederhananya:
1.  Anda menulis **Test Script** (misal: dalam Python atau Java).
2.  *Script* Anda memanggil perintah **WebDriver** (misal: `klik tombol login`).
3.  **WebDriver** menerjemahkan perintah itu dan mengirimkannya ke **Browser** (Chrome, Firefox, dll).
4.  Browser menjalankan perintah itu seolah-olah dilakukan oleh pengguna sungguhan.

### Kenapa Menggunakan Selenium?

Selenium menjadi standar industri karena beberapa alasan:
* **Open-Source dan Gratis:** Tidak memerlukan biaya lisensi.
* **Multi-Bahasa:** Dapat ditulis dalam banyak bahasa (Python, Java, C#, JavaScript, Ruby).
* **Multi-Browser:** Mendukung hampir semua browser modern (Chrome, Firefox, Edge, Safari).
* **Multi-Platform:** Berjalan di Windows, macOS, dan Linux.
* **Komunitas Besar:** Memiliki komunitas yang sangat besar dan dokumentasi yang lengkap.
