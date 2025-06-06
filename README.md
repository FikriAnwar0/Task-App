<h1 align="center">🚀 TaskEasy – Aplikasi Manajemen Tugas Modern</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Selesai-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/Built%20With-React-blue?style=flat-square&logo=react"/>
  <img src="https://img.shields.io/badge/Deployed%20On-Vercel-black?style=flat-square&logo=vercel"/>
</p>

<p align="center">
  <em>Dibuat oleh: <strong>Fikri Anwar</strong> (NIM 231112145) — Extreme Programming</em><br/>
  🌐 <strong>Live Demo:</strong> <a href="https://task-app-snowy-seven.vercel.app/" target="_blank">task-app-snowy-seven.vercel.app</a>
</p>

---

## 🎯 Deskripsi Proyek

**TaskEasy** adalah aplikasi manajemen tugas modern berbasis web dengan antarmuka bersih, intuitif, dan ramah pengguna. Proyek ini dikembangkan dalam waktu **1 minggu** sebagai tugas mata kuliah **Extreme Programming**, dengan menerapkan praktik XP secara nyata: TDD, CI/CD, refactoring, dan simulasi pair programming.

> 💡 Dikerjakan **sendiri** oleh **Fikri Anwar**, yang memerankan seluruh peran tim pengembang secara individual.

---

## 📸 Cuplikan Aplikasi

<p align="center">
  <img src="https://github.com/user-attachments/assets/4bbae90b-d87b-4834-9014-e544f1b496dc" alt="Tampilan TaskEasy" width="100%" style="border-radius: 8px; box-shadow: 0px 4px 12px rgba(0,0,0,0.1);"/>
</p>

---

## 🧩 Fitur Utama

- ✅ Tambah tugas lengkap: judul, deskripsi, prioritas, status
- 📝 Edit & hapus tugas dengan mudah
- 🔍 Sortir tugas berdasarkan **prioritas**
- 💾 Penyimpanan lokal (localStorage)
- 📱 UI modern dan **responsif** (React + Tailwind CSS)
- 🧪 Unit testing berbasis **TDD** (Jest)
- 🚀 Deployment otomatis ke **Vercel**
- 🔄 Integrasi berkelanjutan via **GitHub Actions**

---

## 🧪 Praktik Extreme Programming (XP)

| 🔧 Praktik XP            | ✅ Implementasi                                                                 |
|--------------------------|--------------------------------------------------------------------------------|
| **Test-Driven Development** | Menulis test sebelum implementasi fitur utama (menggunakan Jest)            |
| **Refactoring**          | Perbaikan struktur kode tanpa mengubah hasil akhir                            |
| **Pair Programming**     | Disimulasikan via timeboxing: mode driver & navigator secara bergantian       |
| **Planning Game**        | Penulisan & estimasi user story harian                                         |
| **Continuous Integration** | Workflow otomatis testing & build via GitHub Actions                         |
| **Small Releases**       | Commit fitur kecil setiap hari                                                 |
| **Customer Feedback**    | Simulasi uji coba dan perbaikan dari perspektif pengguna harian                |

---

## 📋 User Stories & Estimasi

| 🆔 | User Story                                                                                   | ⏱️ Estimasi |
|-----|----------------------------------------------------------------------------------------------|------------|
| 1️⃣ | Sebagai pengguna, saya bisa membuat tugas dengan detail lengkap                             | 3 poin     |
| 2️⃣ | Sebagai pengguna, saya bisa melihat tugas berdasarkan prioritas                             | 2 poin     |
| 3️⃣ | Sebagai pengguna, saya bisa mengedit tugas yang sudah dibuat                                | 2 poin     |
| 4️⃣ | Sebagai pengguna, saya bisa menghapus tugas yang tidak diperlukan                           | 1 poin     |
| 5️⃣ | Sebagai pengguna, saya ingin data tetap tersimpan saat halaman direfresh                    | 2 poin     |

---

## 🛠️ Teknologi yang Digunakan

| Kategori       | Teknologi             |
|----------------|-----------------------|
| Frontend       | React + TypeScript    |
| Styling        | Tailwind CSS          |
| Testing        | Jest                  |
| Build Tool     | Next.js               |
| CI/CD          | GitHub Actions        |
| Deployment     | Vercel                |
| Storage        | Browser LocalStorage  |

---

## 📁 Struktur Direktori

```bash
TaskEasy/
├── app/                    # Halaman utama & routing
│   ├── layout.tsx
│   └── page.tsx
├── components/             # Komponen UI (Form, List, Item)
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
```

## 🚀 Menjalankan Aplikasi Lokal

### 1. Clone repositori
```bash
git clone https://github.com/fikrianwar0/Task-App.git
cd Task-App
```

### 2. Install dependencies
```bash
npm install --legacy-peer-deps
```

### 3. Jalankan server lokal
```bash
npm run dev
Akses di browser: http://localhost:3000
```

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

## 📄 Lisensi

> 🛡️ **Hak Cipta © 2025 – Fikri Anwar (NIM 231112145)**  
> Proyek ini dikembangkan sebagai bagian dari pemenuhan tugas mata kuliah **Extreme Programming** di **Universitas Muhammadiyah Sidoarjo**.

🔓 **Izin Penggunaan:**
Kode sumber dan aset dalam proyek ini **boleh digunakan ulang, dimodifikasi, dan dibagikan** secara bebas untuk **keperluan non-komersial dan edukasi**, dengan syarat:

- 📝 Mencantumkan atribusi yang jelas kepada pembuat asli (Fikri Anwar).
- 🔗 Menyertakan tautan kembali ke repositori atau aplikasi asli.
- 🚫 Tidak digunakan untuk tujuan komersial tanpa izin tertulis.

📘 Lisensi ini bersifat terbuka dan fleksibel, mendukung kolaborasi dan pembelajaran terbuka dalam semangat pengembangan perangkat lunak bebas dan pendidikan.

---

> _“Bagikan ilmu, tebarkan manfaat. Satu baris kode hari ini bisa menjadi solusi bagi banyak orang esok hari.”_ ✨
