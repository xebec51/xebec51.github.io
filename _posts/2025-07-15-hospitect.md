---
layout: post
title: "Hospitect: Sistem Informasi Manajemen Rumah Sakit"
date: 2025-07-15 10:00:00 +0800
categories: [Project]
tags: [web development, php, laravel, mysql, tailwindcss, full-stack]
image: /assets/img/hero2.jpg
---

**Hospitect** adalah Sistem Informasi Rumah Sakit (SIRS) berbasis web yang dirancang untuk membantu rumah sakit mengelola data pasien, dokter, obat-obatan, janji temu, dan rekam medis secara efisien.

Ini adalah proyek *full-stack* yang dibangun menggunakan **Laravel** untuk backend dan **Tailwind CSS** untuk *styling* antarmuka.

🌐 **Link Repositori:** [**https://github.com/xebec51/hospitect-finalproject-pemrograman-web**](https://github.com/xebec51/hospitect-finalproject-pemrograman-web)

---

### Fitur Utama

Aplikasi ini menerapkan sistem autentikasi multi-peran (*multi-role*) yang membagi fungsionalitas berdasarkan tiga jenis pengguna: Admin, Dokter, dan Pasien.

#### 1. Dashboard Admin
* **Manajemen Pengguna:** Kemampuan penuh (CRUD) untuk mengelola akun Dokter, Pasien, dan Admin lainnya.
* **Manajemen Obat:** Mengelola (CRUD) data master untuk semua obat yang tersedia di rumah sakit.
* **Manajemen Janji Temu:** Dapat melihat dan mengelola semua janji temu yang dibuat oleh pasien.

#### 2. Dashboard Dokter
* **Manajemen Jadwal:** Dokter dapat mengatur jadwal ketersediaan mereka untuk konsultasi.
* **Manajemen Janji Temu:** Melihat daftar janji temu yang masuk dan memberikan persetujuan atau penolakan.
* **Rekam Medis (EHR):** Membuat, melihat, dan memperbarui rekam medis digital untuk pasien setelah konsultasi.

#### 3. Dashboard Pasien
* **Pendaftaran Janji Temu:** Pasien dapat memilih dokter, melihat jadwal yang tersedia, dan membuat janji temu baru.
* **Melihat Riwayat Rekam Medis:** Mengakses riwayat rekam medis pribadi mereka.
* **Umpan Balik (Feedback):** Memberikan ulasan atau umpan balik terhadap layanan yang diterima.
