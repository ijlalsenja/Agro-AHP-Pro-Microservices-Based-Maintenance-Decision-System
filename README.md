# 📱 Aplikasi Mobile Client–Server Berbasis Flutter & Python API

---

## 👤 Identitas Mahasiswa
Nama Mahasiswa : Muhammad Ijlal Senja Pratama 
NIM            : 206230010  
Program Studi  :Teknik Industri Pertanian  
Perguruan Tinggi : Universitas Linggabuana PGRI Sukabumi

---

## 📌 Deskripsi Kasus
Aplikasi ini merupakan aplikasi mobile berbasis Flutter (Android) yang menerapkan konsep Client–Server Architecture.  
Frontend aplikasi berfungsi sebagai antarmuka pengguna (client), sedangkan proses perhitungan dan pengolahan data sepenuhnya dilakukan di backend server menggunakan Python API yang dijalankan melalui Google Colab.

Aplikasi ini dibuat untuk membuktikan bahwa proses perhitungan tidak dilakukan secara hardcode di aplikasi, melainkan diproses di sisi server melalui REST API.

---

## 🎯 Tujuan Pembuatan Aplikasi
1. Mengimplementasikan komunikasi Client–Server.
2. Menerapkan REST API pada aplikasi mobile.
3. Menghubungkan Flutter dengan backend Python.
4. Membuktikan proses perhitungan berjalan di server.
5. Memenuhi syarat tugas pengembangan aplikasi berbasis API.

---

## 🧠 Arsitektur Sistem
Sistem aplikasi ini menggunakan arsitektur client–server, di mana aplikasi Flutter berperan sebagai client yang mengirimkan data ke server melalui HTTP request.  
Backend Python yang berjalan di Google Colab menerima data tersebut, melakukan proses perhitungan, kemudian mengembalikan hasil ke aplikasi dalam format JSON.

---

## 🛠️ Teknologi yang Digunakan

### Frontend (Client)
- Flutter
- Bahasa Dart
- HTTP Package
- Android SDK

### Backend (Server)
- Python
- FastAPI / Flask
- Uvicorn
- Google Colab

### Format Pertukaran Data
- JSON

---

## 📂 Struktur Repository
Repository proyek ini terdiri dari beberapa folder utama dengan fungsi sebagai berikut:

Folder **backend** berisi file notebook Google Colab (`.ipynb`) yang digunakan sebagai backend API.  
Di dalam file ini terdapat kode Python untuk membuat endpoint API, melakukan proses perhitungan, serta menampilkan Swagger UI sebagai bukti API berjalan.

Folder **frontend** berisi seluruh kode sumber aplikasi Flutter, termasuk file konfigurasi, folder `lib`, serta konfigurasi Android yang digunakan untuk membangun aplikasi mobile.

Folder **screenshots** berisi gambar tangkapan layar yang digunakan sebagai bukti bahwa backend API dan aplikasi Flutter berjalan dengan baik.  
Gambar ini ditampilkan pada bagian dokumentasi README.

File **README.md** berfungsi sebagai dokumentasi utama proyek yang menjelaskan tujuan, arsitektur, teknologi, dan bukti hasil pengerjaan.

---

## ⚙️ Penjelasan Backend (Python API)
Backend aplikasi dibuat menggunakan Python API yang dijalankan pada Google Colab.  
API ini bertugas untuk menerima data input dari aplikasi Flutter, memproses perhitungan sesuai logika program, dan mengembalikan hasil perhitungan kepada client.

Backend menyediakan endpoint yang dapat diakses melalui metode HTTP POST.

---

## 🧪 Bukti API Berjalan (Swagger UI)
Swagger UI digunakan untuk memastikan bahwa endpoint API dapat diakses dan berfungsi dengan baik.

![Swagger UI](screenshots/swagger.png)

---

## 📱 Penjelasan Frontend (Flutter)
Aplikasi Flutter berfungsi sebagai client yang menyediakan antarmuka input data bagi pengguna.  
Data yang dimasukkan akan dikirim ke backend server menggunakan HTTP POST, kemudian hasil perhitungan dari server akan ditampilkan di aplikasi.

Seluruh proses perhitungan dilakukan di server, sehingga aplikasi Flutter tidak mengandung logika perhitungan secara langsung.

---

## 📸 Bukti Aplikasi Flutter Berjalan
Berikut merupakan tampilan aplikasi Flutter saat dijalankan pada perangkat Android.

![Flutter App](screenshots/flutter_app.png)

---

## 🔗 Link Pendukung

### Google Colab (Backend API)
Pastikan permission dalam mode Viewer.

https://colab.research.google.com/(ISI LINK)

---

### GitHub Gist
https://gist.github.com/(ISI LINK)

---

### Demo Aplikasi
https://(ISI LINK VERCEL / DRIVE / APK)

---

## 📦 File APK Release
Aplikasi telah di-build menggunakan mode release dan diunggah pada menu Releases di GitHub Repository dengan nama file `app-release.apk`.

---

## 🎥 Video Demo Aplikasi
Video demo berdurasi 3–5 menit yang menampilkan:
1. Proses input data pada perangkat Android
2. Proses pengiriman data ke server
3. Hasil perhitungan dari server
4. Bukti bahwa perhitungan tidak dilakukan secara hardcode

Link video demo:
https://drive.google.com/(ISI LINK VIDEO)

---

## ✅ Kesimpulan
Berdasarkan hasil pengujian, aplikasi Flutter berhasil terhubung dengan backend Python melalui REST API.  
Proses perhitungan berjalan dengan baik di server dan hasilnya dapat ditampilkan di aplikasi, sehingga konsep client–server telah diterapkan secara optimal.

---

## 📄 Lisensi
Proyek ini dibuat untuk keperluan akademik dan pembelajaran.
