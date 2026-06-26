<div align="center">

# 🧮 Kalkulator Ekspresi Matematika

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/License-Free-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Selesai-brightgreen?style=for-the-badge)
![PyInstaller](https://img.shields.io/badge/Build-PyInstaller-orange?style=for-the-badge&logo=pyinstaller&logoColor=white)
![Semester](https://img.shields.io/badge/Semester-1-blueviolet?style=for-the-badge)

**Kalkulator berbasis CLI yang mampu menghitung ekspresi matematika kompleks.**

*Dibuat oleh Yogi Ario — Proyek Semester 1*

---

</div>

## 📖 Deskripsi

Program kalkulator sederhana berbasis **Command Line Interface (CLI)** yang dapat menghitung ekspresi matematika dengan mendukung operasi berantai. Program menerima input berupa ekspresi matematika lengkap (contoh: `2*9+6-7/2`) dan langsung mengembalikan hasilnya.

## ✨ Fitur

- ➕ Penjumlahan (`+`)
- ➖ Pengurangan (`-`)
- ✖️ Perkalian (`*`)
- ➗ Pembagian (`/`)
- 🔢 Mendukung angka desimal (`.`)
- 🔁 Perhitungan berulang tanpa restart program
- 🛡️ Validasi input — hanya menerima angka dan operator yang diizinkan
- 💻 Tersedia sebagai file `.exe` (tanpa perlu install Python)

## 📁 Struktur Proyek

```
01/
├── ekspresi.py          # Source code utama
├── ekspresi.spec        # Konfigurasi PyInstaller
├── img.ico              # Icon aplikasi
├── build/               # File build PyInstaller
│   └── ekspresi/
└── dist/
    └── ekspresi.exe     # Executable hasil build
```

## 🚀 Cara Menjalankan

### Opsi 1: Jalankan file Python

```bash
python ekspresi.py
```

### Opsi 2: Jalankan file Executable

Buka file `dist/ekspresi.exe` langsung (tanpa perlu install Python).

### Opsi 3: Build ulang executable

```bash
pip install pyinstaller
pyinstaller ekspresi.spec
```

## 📸 Contoh Penggunaan

```
Kalkulator Sederhana
Credit by Yogi Ario
Contoh soal:
2+9 atau 2*9+6-7/2

Masukkan soal matematikamu: 2*9+6-7/2
Hasil: 20.5
Tekan Sembarang tombol untuk mengulang perhitungan atau Tekan 1 untuk keluar:
```

## 🛠️ Teknologi

| Komponen      | Detail                    |
|---------------|---------------------------|
| Bahasa        | Python 3.x                |
| Build Tool    | PyInstaller               |
| Library       | `re` (regex, built-in)    |
| Platform      | Windows                   |

## 👤 Author & Kontak

**Yogi Ario Pratama**

Jika Anda memiliki pertanyaan seputar kode ini atau ingin berdiskusi, silakan hubungi saya melalui WhatsApp:
📱 **[Chat via WhatsApp (wa.me/6281358113087)](https://wa.me/6281358113087)**

---

### 💖 Donasi
Dukungan Anda sangat berarti agar saya dapat terus semangat belajar dan mengembangkan proyek-proyek open-source lainnya. Jika berkenan memberikan donasi/apresiasi, Anda dapat menyalurkannya melalui:

💳 **Bank Seabank**
- No Rekening: **901497113744**
- Atas Nama: **Yogi Ario Pratama**

<div align="center">
  <br>
  <em>Terima kasih atas kunjungannya. Proyek Mata Kuliah — Semester 1 — Teknik Informatika UNP</em>
</div>
