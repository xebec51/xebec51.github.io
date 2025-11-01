---
layout: post
title: "Pengantar API Testing (STQA #6)"
date: 2025-09-30 10:00:00 +0800
categories: [STQA]
tags: [stqa, api, postman, soapui, rest]
image: /assets/img/hero2.jpg
---

[cite_start]Rangkuman materi "API Testing" dari Kelompok 6[cite: 1020].

### Apa Itu API Testing?

[cite_start]*API Testing* adalah proses pengujian yang dilakukan langsung pada **Application Programming Interface** (API) untuk memastikan API tersebut berfungsi sesuai spesifikasi, menangani skenario dengan benar, dan mengembalikan *output* yang valid[cite: 1059].

[cite_start]Pengujian ini penting untuk [cite: 1068-1078]:
* **Meningkatkan Keandalan:** Mendeteksi bug di logika bisnis sebelum UI dibuat.
* **Menjamin Keamanan:** Memastikan API aman dari akses tidak sah.
* **Mengukur Performa:** Menguji seberapa baik API menangani beban tinggi.

### Anatomi Request dan Response

[cite_start]Pengujian API adalah tentang mengirim *request* dan memvalidasi *response*[cite: 1115].

[cite_start]**Anatomi Request (Permintaan Klien):** [cite: 1116, 1117]
1.  [cite_start]**Method (HTTP Verb):** Aksi yang ingin dilakukan (misal: `GET` untuk mengambil data, `POST` untuk membuat data baru, `PUT` untuk mengubah data, `DELETE` untuk menghapus data)[cite: 1119].
2.  [cite_start]**URL (Endpoint):** Alamat dari sumber daya yang ingin diakses (misal: `https://api.example.com/users`)[cite: 1120].
3.  **Headers:** Informasi tambahan (misal: Tipe Konten, Kunci Autentikasi).
4.  **Body:** Data yang dikirim (biasanya dalam format JSON), digunakan pada `POST` atau `PUT`.

[cite_start]**Anatomi Response (Balasan Server):** [cite: 1121, 1122]
1.  [cite_start]**Status Code:** Kode numerik yang menandakan hasil[cite: 1124]. Contoh umum:
    * `200 OK`: Permintaan berhasil.
    * `404 Not Found`: Sumber daya tidak ditemukan.
    * `401 Unauthorized`: Klien tidak memiliki izin.
    * `500 Internal Server Error`: Server mengalami masalah.
2.  **Body:** Data yang dikembalikan oleh server (biasanya dalam format JSON).

### Tools API Testing

* [cite_start]**Postman:** Alat paling populer, dikenal *user-friendly* untuk mengirim *request* dan melihat *response*[cite: 1081, 1089, 1090].
* [cite_start]**SoapUI:** Alat yang lebih *enterprise*, sangat kuat untuk menguji SOAP API (berbasis XML) dan REST API[cite: 1097, 1100, 1108].
