---
layout: post
title: "Pengantar Framework Cypress (STQA #8)"
date: 2025-10-14 10:00:00 +0800
categories: [STQA]
tags: [stqa, automation, cypress, e2e]
image: /assets/img/hero4.jpg
---

Rangkuman materi "Pengantar Cypress" dari Kelompok 8.

### Apa itu Cypress?

Cypress adalah *framework end-to-end testing* generasi baru yang dibuat khusus untuk aplikasi web modern (seperti yang dibangun dengan React, Vue, Angular). Seperti Selenium, tujuannya adalah mengotomatiskan tindakan pengguna di browser.

### Keunggulan Cypress (Perbedaannya dengan Selenium)

Cypress dirancang untuk mengatasi beberapa kelemahan yang ada pada *framework* lama seperti Selenium. Keunggulan utamanya ada pada arsitekturnya:

* **Arsitektur Modern:** Tidak seperti Selenium yang berjalan *di luar* browser, Cypress berjalan **di dalam** browser, pada *run-loop* yang sama dengan aplikasi Anda. Ini memberinya kontrol yang lebih cepat dan lebih andal.
* **Test Runner Interaktif:** Cypress hadir dengan "Test Runner", sebuah aplikasi visual di mana Anda dapat melihat pengujian Anda berjalan *step-by-step* dan melihat tampilan aplikasi Anda pada setiap langkah.
* **Time Travel:** Di dalam Test Runner, Anda bisa "mundur" ke langkah sebelumnya dan melihat *snapshot* DOM (tampilan) aplikasi pada saat itu, membuat *debugging* menjadi sangat mudah.
* **Automatic Waits:** Cypress secara otomatis menunggu elemen muncul di layar (misal: data dari API) tanpa perlu menulis kode *wait* secara manual. Ini menghilangkan banyak *error* "flaky test" (tes yang kadang berhasil kadang gagal).

Secara keseluruhan, Cypress menawarkan pengalaman pengembang yang lebih modern dan cepat untuk *end-to-end testing*.
