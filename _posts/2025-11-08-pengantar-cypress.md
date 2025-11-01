---
layout: post
title: "Pengantar Framework Cypress (STQA #8)"
date: 2025-11-08 10:00:00 +0800
categories: [STQA]
tags: [stqa, automation, cypress, e2e]
image: /assets/img/hero4.jpg
---

[cite_start]Rangkuman materi "Pengantar Cypress" dari Kelompok 8[cite: 1147, 1149].

### Apa itu Cypress?

[cite_start]Cypress adalah *framework end-to-end testing* generasi baru yang dibuat khusus untuk aplikasi web modern (seperti yang dibangun dengan React, Vue, Angular)[cite: 1186, 1187]. Seperti Selenium, tujuannya adalah mengotomatiskan tindakan pengguna di browser.

### Keunggulan Cypress (Perbedaannya dengan Selenium)

[cite_start]Cypress dirancang untuk mengatasi beberapa kelemahan yang ada pada *framework* lama seperti Selenium[cite: 1237]. Keunggulan utamanya ada pada arsitekturnya:

* [cite_start]**Arsitektur Modern:** Tidak seperti Selenium yang berjalan *di luar* browser, Cypress berjalan **di dalam** browser, pada *run-loop* yang sama dengan aplikasi Anda[cite: 1241]. Ini memberinya kontrol yang lebih cepat dan lebih andal.
* [cite_start]**Test Runner Interaktif:** Cypress hadir dengan "Test Runner", sebuah aplikasi visual di mana Anda dapat melihat pengujian Anda berjalan *step-by-step* dan melihat tampilan aplikasi Anda pada setiap langkah[cite: 1242].
* [cite_start]**Time Travel:** Di dalam Test Runner, Anda bisa "mundur" ke langkah sebelumnya dan melihat *snapshot* DOM (tampilan) aplikasi pada saat itu, membuat *debugging* menjadi sangat mudah[cite: 1243].
* **Automatic Waits:** Cypress secara otomatis menunggu elemen muncul di layar (misal: data dari API) tanpa perlu menulis kode *wait* secara manual. [cite_start]Ini menghilangkan banyak *error* "flaky test" (tes yang kadang berhasil kadang gagal)[cite: 1244].

Secara keseluruhan, Cypress menawarkan pengalaman pengembang yang lebih modern dan cepat untuk *end-to-end testing*.
