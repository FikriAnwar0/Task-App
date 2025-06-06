<h1 align="center">🚀 TaskEasy – Aplikasi Manajemen Tugas Sederhana</h1>
<p align="center">
  <em>Dibuat oleh: Fikri Anwar (NIM 231112145) | Mata Kuliah: Extreme Programming</em><br/>
  <strong>Demo Langsung ➝</strong> <a href="https://task-app-snowy-seven.vercel.app/" target="_blank">task-app-snowy-seven.vercel.app</a>
</p>

---

## 🎯 Ringkasan Proyek

**TaskEasy** adalah aplikasi web manajemen tugas ringan yang dibangun dalam waktu **satu minggu** dengan menerapkan metodologi **Extreme Programming (XP)** secara menyeluruh. Aplikasi ini bertujuan untuk memudahkan pengguna dalam mengelola tugas harian mereka dengan fitur sederhana namun fungsional.

Proyek ini diselesaikan secara **individu** oleh **Fikri Anwar**, dengan mensimulasikan seluruh peran tim pengembang sesuai dengan praktik XP.

---

## 🧩 Fitur Utama

🔹 Tambah tugas dengan:  
  ✔️ Judul  
  ✔️ Deskripsi  
  ✔️ Prioritas (📉 Low | 📊 Medium | 📈 High)  
  ✔️ Status (🕒 To-do | 🔧 In-progress | ✅ Done)

🔹 Lihat daftar tugas tersortir berdasarkan **prioritas**  
🔹 Perbarui dan hapus tugas  
🔹 Data tersimpan otomatis di **local storage**  
🔹 UI responsif & modern menggunakan **React + Tailwind CSS**  
🔹 Dapat diakses online melalui **Vercel Hosting**

---

## 🔧 Teknologi yang Digunakan

| Kategori      | Teknologi         |
|---------------|------------------|
| Frontend      | React + TypeScript |
| Styling       | Tailwind CSS |
| Testing       | Jest (TDD) |
| Build Tool    | Next.js |
| CI/CD         | GitHub Actions |
| Hosting       | Vercel |
| Data Storage  | Local Storage |

---

## 🛠️ Praktik XP yang Diimplementasikan

| Praktik XP                | Implementasi                                                                 |
|---------------------------|------------------------------------------------------------------------------|
| **Pair Programming**      | Disimulasikan melalui pembagian waktu kerja antara "driver" dan "navigator". |
| **TDD**                   | Penulisan unit test menggunakan **Jest** sebelum implementasi fitur.        |
| **Continuous Integration**| Menggunakan **GitHub Actions** untuk menjalankan test otomatis saat push.   |
| **Small Releases**        | Fitur dirilis dan diuji setiap hari dengan commit harian yang teratur.      |
| **Refactoring**           | Refactoring berkala menjaga kualitas dan keterbacaan kode.                  |
| **Customer Collaboration**| Disimulasikan sebagai feedback pengguna harian oleh developer sendiri.      |
| **Planning Game**         | User story dibuat dan diberi estimasi story point untuk prioritisasi tugas. |

---

## 📋 User Stories & Estimasi

| 🆔 | User Story                                                                                  | 🧮 Estimasi |
|-----|---------------------------------------------------------------------------------------------|------------|
| 1️⃣ | Sebagai pengguna, saya dapat membuat tugas dengan detail lengkap agar bisa melacak pekerjaan | 3 poin     |
| 2️⃣ | Sebagai pengguna, saya ingin melihat daftar tugas tersortir berdasarkan prioritas           | 2 poin     |
| 3️⃣ | Sebagai pengguna, saya ingin mengedit tugas agar dapat menyesuaikan dengan perubahan        | 2 poin     |
| 4️⃣ | Sebagai pengguna, saya ingin menghapus tugas yang sudah tidak relevan                      | 1 poin     |
| 5️⃣ | Sebagai pengguna, saya ingin data tersimpan otomatis agar tidak hilang saat refresh         | 2 poin     |

---

## 📁 Struktur Proyek

TaskEasy/
├── app/ # Halaman utama dan routing
├── components/ # UI reusable (TaskForm, TaskList, dsb.)
├── hooks/ # Custom React hooks
├── lib/ # Konfigurasi penyimpanan lokal
├── public/ # Aset publik
├── styles/ # Styling global
├── types/ # Tipe data TypeScript
├── utils/ # Fungsi bantu (sort, helper)
├── tests/ # Unit test (TDD)
├── .github/workflows/ # CI pipeline
├── package.json # Dependency management
└── tailwind.config.ts # Tailwind configuration

---

## 🧪 Menjalankan Project

npm install --legacy-peer-deps
npm run dev

🚀 Jalankan Secara Lokal

Clone repo:
- git clone https://github.com/fikrianwar0/Task-App.git
- cd Task-App

Install dependency:
- npm install
- Start development server:
Akses di browser: http://localhost:3000

⚙️ Continuous Integration
CI/CD dijalankan otomatis setiap ada perubahan pada kode melalui GitHub Actions, dengan pipeline yang menjalankan npm test.

📂 Path: .github/workflows/ci.yml

🧾 Ringkasan Refleksi
✅ Keberhasilan:

Berhasil membangun aplikasi sepenuhnya dalam waktu seminggu.

Praktik XP membantu menjaga kualitas & fokus pengembangan.

⚠️ Tantangan:

Menyimulasikan semua peran XP dalam pengerjaan individu.

Konsistensi TDD saat pengembangan cepat.

💡 Solusi:

Menggunakan timeboxing antara coding & review sebagai simulasi peran.

Menulis test untuk logika utama, lalu refactor setelah validasi.

🎤 Presentasi & Demo
🎥 Demo Langsung: task-app-snowy-seven.vercel.app
🧭 Durasi: ±5 menit
📊 Penjelasan fitur utama dan penerapan XP
🎯 Fokus pada pengembangan berkelanjutan dan integrasi berkelanjutan (CI)

👤 Tentang Pengembang
Nama: Fikri Anwar

NIM: 231112145

Kampus: Universitas Muhammadiyah Sidoarjo

Mata Kuliah: Extreme Programming

Dosen Pengampu: (disesuaikan jika perlu)

📄 Lisensi
Proyek ini dikembangkan hanya untuk tujuan akademik. Silakan gunakan kembali dengan mencantumkan atribusi yang sesuai.

Terima kasih telah membaca dokumentasi ini! 🎉
Jangan lupa cek aplikasinya di task-app-snowy-seven.vercel.app
