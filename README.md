<h1 align="center">🚀 TaskEasy – Aplikasi Manajemen Tugas Modern</h1>

<p align="center">
  <em>Dibuat oleh: Fikri Anwar (NIM 231112145) – Extreme Programming</em><br/>
  🌐 <strong>Live Demo:</strong> <a href="https://task-app-snowy-seven.vercel.app/" target="_blank">task-app-snowy-seven.vercel.app</a>
</p>

<div align="center">
  <img src="./public/images/homepage-preview.png" alt="Preview TaskEasy" width="800"/>
  <p><em>💻 Tampilan halaman utama TaskEasy</em></p>
</div>

---

## 🎯 Deskripsi Singkat

**TaskEasy** adalah aplikasi web untuk mengelola daftar tugas dengan antarmuka yang bersih, intuitif, dan responsif. Dibuat dalam waktu **1 minggu** sebagai bagian dari tugas mata kuliah **Extreme Programming**, aplikasi ini mencerminkan penerapan praktik XP secara nyata—mulai dari TDD, CI/CD, sampai simulasi pair programming.

> 📌 Proyek ini dikembangkan **individu** oleh **Fikri Anwar**, yang memerankan seluruh bagian tim pengembang sesuai dengan semangat Extreme Programming.

---

## 🧩 Fitur Unggulan

✅ Tambah tugas lengkap (judul, deskripsi, prioritas, status)  
📋 Kelola tugas: ubah, hapus, filter by prioritas  
💾 Data otomatis tersimpan di browser (local storage)  
🎨 UI modern dan responsif (Tailwind + React)  
🚀 Deployment instan via **Vercel**  
🧪 Unit test berbasis **TDD** menggunakan **Jest**

---

## 🧪 Penerapan Praktik Extreme Programming

| Praktik XP            | Implementasi                                                                  |
|------------------------|-------------------------------------------------------------------------------|
| **TDD**               | Test ditulis terlebih dahulu menggunakan **Jest**, baru implementasi kode.     |
| **Refactoring**       | Perbaikan kode rutin tanpa mengubah fungsionalitas.                           |
| **Pair Programming**  | Disimulasikan melalui dua mode kerja: driver & navigator dalam timeboxing.    |
| **Planning Game**     | Estimasi tiap user story dan implementasi berdasarkan prioritas.              |
| **Continuous Integration** | Otomatisasi pengujian dan build melalui GitHub Actions.                    |
| **Small Releases**    | Rilis dan commit setiap harinya dengan fitur kecil yang stabil.               |
| **Customer Feedback** | Simulasi pengguna melalui uji coba harian oleh developer.                     |

---

## 📋 Daftar User Story & Estimasi

| 🆔 | User Story                                                                                   | ⏱️ Estimasi |
|-----|----------------------------------------------------------------------------------------------|------------|
| 1️⃣ | Sebagai pengguna, saya bisa membuat tugas dengan lengkap                                     | 3 poin     |
| 2️⃣ | Sebagai pengguna, saya bisa melihat daftar tugas berdasarkan prioritas                      | 2 poin     |
| 3️⃣ | Sebagai pengguna, saya bisa mengedit tugas                                                   | 2 poin     |
| 4️⃣ | Sebagai pengguna, saya bisa menghapus tugas yang tidak diperlukan                            | 1 poin     |
| 5️⃣ | Sebagai pengguna, saya ingin tugas tetap tersimpan meski refresh halaman                     | 2 poin     |

---

## 🛠️ Teknologi yang Digunakan

| Kategori       | Teknologi             |
|----------------|-----------------------|
| Frontend       | React + TypeScript    |
| Styling        | Tailwind CSS          |
| Testing        | Jest                  |
| Build Tool     | Next.js               |
| Deployment     | Vercel                |
| CI/CD          | GitHub Actions        |
| Data Storage   | Local Storage (Browser) |

---

## 📁 Struktur Direktori

## 📁 Struktur Direktori

```plaintext
TaskEasy/
├── app/
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── TaskForm.tsx
│   ├── TaskList.tsx
│   └── TaskItem.tsx
├── hooks/
│   └── useTasks.ts
├── lib/
│   └── taskStorage.ts
├── public/
│   └── images/
│       └── screenshot-homepage.png
├── styles/
│   └── globals.css
├── types/
│   └── task.ts
├── utils/
│   └── helpers.ts
├── tests/
│   ├── TaskForm.test.tsx
│   └── TaskList.test.tsx
├── .github/
│   └── workflows/
│       └── ci.yml
├── package.json
└── tailwind.config.ts
---

## 🚀 Menjalankan Aplikasi Lokal

### 1. Clone repositori
git clone https://github.com/fikrianwar0/Task-App.git
cd Task-App

### 2. Install dependencies
npm install --legacy-peer-deps

### 3. Jalankan server lokal
npm run dev
Akses di browser: http://localhost:3000

📸 Preview Aplikasi

![image](https://github.com/user-attachments/assets/eddc12f8-f7ae-49f9-84f8-f5ef974df72e)

---

👤 Tentang Saya

| Informasi      | Detail                            |
| -------------- | --------------------------------- |
| Nama           | Fikri Anwar                       |
| NIM            | 231112145                         |
| Universitas    | Universitas Muhammadiyah Sidoarjo |
| Mata Kuliah    | Extreme Programming               |
| Dosen Pengampu | *(Isi jika diperlukan)*           |

---

📄 Lisensi

Proyek ini dibuat untuk keperluan akademik. Bebas digunakan dengan tetap mencantumkan atribusi kepada pembuat.
