---
layout: post
title: "NutriJourney: Aplikasi Pelacak Nutrisi Desktop"
date: 2025-08-01 10:00:00 +0800
categories: [Project]
tags: [desktop, java, javafx, sqlite, mvc]
image: /assets/img/nutrijourney-dashboard.png
---

**NutriJourney** adalah aplikasi desktop yang dibangun menggunakan **JavaFX** untuk membantu pengguna melacak asupan nutrisi harian mereka. Aplikasi ini memungkinkan pengguna untuk memantau kalori, protein, lemak, dan karbohidrat yang dikonsumsi.

🌐 **Link Repositori:** [**https://github.com/xebec51/nutrijourney-javafxapp**](https://github.com/xebec51/nutrijourney-javafxapp)

---

### Fitur Utama

* **Autentikasi Pengguna:** Sistem login dan registrasi yang aman untuk mengelola data pengguna secara individual.
* **Dashboard Utama:** Menampilkan ringkasan total nutrisi harian (kalori, protein, dll.) dan daftar makanan yang telah dikonsumsi.
* **Katalog Makanan:** Daftar makanan yang dapat dicari dan difilter berdasarkan kategori (Buah, Sayuran, Daging), di mana setiap item makanan memiliki detail nutrisi yang lengkap.
* **Struktur Data Polimorfik:** Menggunakan pewarisan (inheritance) untuk mengelola berbagai jenis makanan (Food, Fruit, Vegetable, Meat).
* **Penyimpanan Lokal:** Menggunakan **SQLite** untuk menyimpan semua data pengguna, data makanan, dan riwayat konsumsi secara persisten di komputer pengguna.
