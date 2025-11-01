---
layout: post
title: "Pengantar API Testing (STQA #6)"
date: 2025-09-30 10:00:00 +0800
categories: [STQA]
tags: [stqa, api, postman, soapui, rest]
image: /assets/img/hero2.jpg
---

Rangkuman materi "API Testing" dari Kelompok 6.

### Apa Itu API Testing?

*API Testing* adalah proses pengujian yang dilakukan langsung pada **Application Programming Interface** (API) untuk memastikan API tersebut berfungsi sesuai spesifikasi, menangani skenario dengan benar, dan mengembalikan *output* yang valid.

Pengujian ini penting untuk:
* **Meningkatkan Keandalan:** Mendeteksi bug di logika bisnis sebelum UI dibuat.
* **Menjamin Keamanan:** Memastikan API aman dari akses tidak sah.
* **Mengukur Performa:** Menguji seberapa baik API menangani beban tinggi.

### Anatomi Request dan Response

Pengujian API adalah tentang mengirim *request* dan memvalidasi *response*.

**Anatomi Request (Permintaan Klien):**
1.  **Method (HTTP Verb):** Aksi yang ingin dilakukan (misal: `GET` untuk mengambil data, `POST` untuk membuat data baru, `PUT` untuk mengubah data, `DELETE` untuk menghapus data).
2.  **URL (Endpoint):** Alamat dari sumber daya yang ingin diakses (misal: `https://api.example.com/users`).
3.  **Headers:** Informasi tambahan (misal: Tipe Konten, Kunci Autentikasi).
4.  **Body:** Data yang dikirim (biasanya dalam format JSON), digunakan pada `POST` atau `PUT`.

**Anatomi Response (Balasan Server):**
1.  **Status Code:** Kode numerik yang menandakan hasil. Contoh umum:
    * `200 OK`: Permintaan berhasil.
    * `404 Not Found`: Sumber daya tidak ditemukan.
    * `401 Unauthorized`: Klien tidak memiliki izin.
    * `500 Internal Server Error`: Server mengalamialah.
2.  **Body:** Data yang dikembalikan oleh server (biasanya dalam format JSON).

### Tools API Testing

* **Postman:** Alat paling populer, dikenal *user-friendly* untuk mengirim *request* dan melihat *response*.
* **SoapUI:** Alat yang lebih *enterprise*, sangat kuat untuk menguji SOAP API (berbasis XML) dan REST API.
