# Aisyiyah Smartlife (Private Repository)

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![Platform](https://img.shields.io/badge/platform-flutter-blue.svg)
![Access](https://img.shields.io/badge/access-private-red.svg)

> **⚠️ PERINGATAN KERAHASIAAN**
>
> Repositori ini hanya berisi aplikasi **Aisyiyah Smartlife** yang digunakan untuk memberikan update app kepada pengguna sehingga dapat melakukan pembaruan via inApp(pengunduhan&perbaruan langsung didalam aplikasi).Hal ini bertujuan agar para pengguna tidak ketinggalan dengan fitur terbaru, sembari aplikasi sedang proses pengajuan untuk dipublish ke playstore. Source code project app ini bersifat private sehingga tidak diperuntukkan untuk publik.

---

## 📱 Tentang Aisyiyah Smartlife

**Aisyiyah Smartlife** adalah aplikasi *mobile* berbasis Flutter yang dirancang untuk mendukung ekosistem digital para anggota Aisyiyah. Aplikasi ini **hadir untuk semua tipe pengguna**, menyediakan fitur akses Tamu (Guest) untuk publik dan Login khusus untuk anggota yang telah terdaftar emailnya dikantor PD Aisyiyah Pamekasan.

Tujuan utama aplikasi ini adalah mempermudah manajemen kegiatan,donasi,umkm, dan transparansi organisasi dari tingkat Ranting hingga Wilayah, serta menyediakan fitur ibadah harian yang lengkap.

---

## 👥 Hak Akses & Tipe Pengguna

Aplikasi ini memiliki 6 tipe pengguna dengan hierarki dan hak akses yang berbeda:

| Role | Deskripsi & Hak Akses |
| :--- | :--- |
| **1. Wilayah** | • Kelola kegiatan tingkat Wilayah<br>• Monitoring aktivitas seluruh bawahan (Daerah/Cabang/Ranting)<br>• Melihat daftar & total Daerah, Cabang, Ranting<br>• Kirim notifikasi ke seluruh bawahan<br>• Export rekap kegiatan ke Excel<br>• Kelola Donasi tingkat Wilayah |
| **2. Daerah** | • Kelola kegiatan tingkat Daerah<br>• Monitoring aktivitas & total Cabang/Ranting<br>• Kirim notifikasi ke bawahan<br>• Export rekap kegiatan ke Excel<br>• Kelola Donasi tingkat Daerah |
| **3. Cabang** | • Kelola kegiatan tingkat Cabang<br>• Monitoring aktivitas & total Ranting<br>• Kirim notifikasi ke bawahan<br>• Export rekap kegiatan ke Excel<br>• Kelola Donasi tingkat Cabang<br>• **Kelola UMKM tingkat Cabang** |
| **4. Ranting** | • Kelola kegiatan tingkat Ranting<br>• Monitoring aktivitas bawahan<br>• Kirim notifikasi ke bawahan<br>• Export rekap kegiatan ke Excel<br>• Kelola Donasi tingkat Ranting<br>• **Kelola UMKM tingkat Ranting** |
| **5. Anggota** | • Melihat kegiatan, myquran, UMKM, dan melakukan Donasi<br>• Mengakses seluruh layanan tersedia sesuai lokasi terdaftar |
| **6. Tamu** | • Akses fitur My Quran |

---

## 🌟 Fitur Unggulan

### 📅 1. Manajemen Jadwal Kegiatan
Fitur transparansi agenda dari tingkat Ranting hingga Wilayah.
* **Hierarki Monitoring:** Memantau kegiatan bawahan atau atasan untuk transparansi yang lebih baik.
* **Filter Cerdas:** Filter kegiatan sesuai tingkatan dan cakupan wilayah.
* **Custom Alarm:** Pengingat kegiatan yang waktunya dapat disesuaikan pengguna.
* **Integrasi Peta:** Lokasi kegiatan terhubung langsung dengan Google Maps.
* **Export Data:** Fitur unduh rekap kegiatan ke Excel (khusus Role tertentu).

### 📖 2. My Quran & Fitur Islami
Pendamping ibadah harian yang lengkap.

#### **a. Baca Quran**
* Teks dan audio kata per kata (word-by-word).
* Audio playback per ayat.
* Kustomisasi ukuran font Arab dan Latin.
* Footnote (catatan kaki) pada setiap ayat.

#### **b. Quran Audio (Online & Offline)**
Mendukung *background playback* dengan pilihan Qari ternama:
* *Abdul Baset Abdul Samad (Murattal, Mujawwad)*
* *Mohamed Siddiq al-Minshawi (Murattal, Mujawwad)*
* *Abu Bakr al-Shatri, Hani ar-Rifai, Mahmoud Khalil Al-Husary*
* *Mishari Rashid al-Afasy, Abdur-Rahman as-Sudais, Sa’ud ash-Shuraym*

#### **c. Ensiklopedi Hadist**
* Status kesahihan (Shahih, Hasan, dll).
* Teks Arab, Terjemahan, dan Syarah (Penjelasan).
* Pelajaran dan faedah di setiap hadist.
* Kategori tematik (Klasifikasi Utama & Sub-kategori).

#### **d. Kalender & Jadwal Sholat**
* **Dual Date System:** Penanggalan Masehi & Hijriyah.
* **Penanda:** Puasa Sunnah & Hari Besar Islam.
* **Jadwal Sholat:** Realtime GPS (Offline support).
* **4 Tipe Jadwal:** Pagi, Siang & Sore, Malam, Qiyamul Lail.
* **Asmaul Husna:** Teks, terjemahan, dan pencarian.

### 🛍️ 3. UMKM & Donasi
* **Direktori UMKM:** Daftar unit usaha lengkap (Deskripsi, Kontak, Lokasi). Pengguna bisa langsung menghubungi penjual.
* **Donasi Terpercaya:** Informasi program sosial transparan dengan detail rekening bank pengurus yang jelas.

---

## 🛠️ Tech Stack & API

Aplikasi ini dibangun menggunakan teknologi modern:

### **Core**
* **Frontend:** [Flutter](https://flutter.dev/)
* **Backend:** [Supabase](https://supabase.com/) & [Firebase](https://firebase.google.com/)

### **3rd Party APIs**
Aplikasi ini mengambil data islami dari sumber berikut:
* `quran.com` (Data Al-Quran)
* `hadeeth.com` & `https://hadeethenc.com/` (Ensiklopedia Hadist)
* `aladhan.com` (Jadwal Sholat & Kalender)

---

## 📸 Preview

[![Aisyiyah Smartlife Video]](https://youtu.be/GSf9P0pX-aI)
*(Klik gambar untuk memutar video)*

---
