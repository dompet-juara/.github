# Dompet Juara 🏆💸

**Solusi Cerdas Manajemen Keuangan Pribadi Anda dengan Rekomendasi AI.**

[![Status Proyek](https://img.shields.io/badge/Status-Pengembangan%20Aktif-brightgreen.svg)](https://github.com/dompet-juara)
[![Desain UI/UX](https://img.shields.io/badge/Desain-Figma-blueviolet.svg)](https://github.com/dompet-juara/uiux)
[![Frontend](https://img.shields.io/badge/Frontend-React%20%7C%20Next.js-cyan.svg)](https://github.com/dompet-juara/frontend)
[![Backend](https://img.shields.io/badge/Backend-Supabase-3979FF.svg)](https://github.com/dompet-juara/backend)
[![Machine Learning](https://img.shields.io/badge/AI%20Engine-Python-yellow.svg)](https://github.com/dompet-juara/machine-learning)
[![Lisensi](https://img.shields.io/badge/Lisensi-MIT-blue.svg)](LICENSE)

Dompet Juara adalah sebuah aplikasi manajemen keuangan pribadi inovatif yang dirancang untuk membantu pengguna mengelola pemasukan dan pengeluaran mereka dengan lebih efektif. Lebih dari sekadar pencatatan, Dompet Juara dilengkapi dengan **AI Financial Recommender** yang cerdas untuk memberikan klasifikasi perilaku keuangan dan tips yang dipersonalisasi, serta **AI Chatbot** untuk menjawab pertanyaan seputar keuangan Anda.

## 📖 Daftar Isi

*   [✨ Fitur Utama](#-fitur-utama)
*   [🏗️ Arsitektur Proyek](#️-arsitektur-proyek)
*   [🛠️ Tumpukan Teknologi (Tech Stack)](#️-tumpukan-teknologi)
*   [🎨 Tampilan Aplikasi (UI/UX)](#-tampilan-aplikasi-uiux)
*   [🚀 Memulai (Getting Started)](#-memulai-getting-started)
*   [🤝 Berkontribusi](#-berkontribusi)
*   [🗺️ Peta Jalan (Roadmap)](#️-peta-jalan-roadmap)
*   [📜 Lisensi](#-lisensi)
*   [🧑‍💻 Tim Proyek & Kontak](#-tim-proyek--kontak)

## ✨ Fitur Utama

*   **Pencatatan Pemasukan & Pengeluaran:** Catat transaksi keuangan Anda dengan mudah dan kategorikan secara otomatis.
*   **Dashboard Keuangan Interaktif:** Visualisasikan kondisi keuangan Anda melalui ringkasan, grafik, dan laporan yang mudah dipahami.
*   **AI Financial Recommender:** Dapatkan analisis perilaku keuangan Anda (misalnya, normal, hemat, boros) beserta tips yang relevan untuk meningkatkan kesehatan finansial.
*   **AI Chatbot Keuangan:** Ajukan pertanyaan seputar keuangan dan dapatkan jawaban instan dari asisten AI Dompet Juara.
*   **Manajemen Profil Pengguna:** Kelola informasi akun dan preferensi Anda.
*   **Filter & Pencarian Transaksi:** Temukan transaksi spesifik dengan cepat berdasarkan tanggal, kategori, atau jumlah.
*   **Impor Data (Opsional):** Kemampuan untuk mengimpor riwayat transaksi dari file (misalnya, XLSX).
*   **Responsif:** Desain yang adaptif untuk pengalaman optimal baik di perangkat mobile maupun desktop.

## 🏗️ Arsitektur Proyek

Dompet Juara dirancang dengan arsitektur modular yang terdiri dari beberapa komponen utama:

1.  **🎨 Antarmuka Pengguna (UI/UX):**
    *   **Deskripsi:** Bertanggung jawab atas seluruh aspek visual dan pengalaman pengguna aplikasi. Didesain menggunakan Figma.
    *   **Repositori:** [dompet-juara/uiux](https://github.com/dompet-juara/uiux)

2.  **📱 Aplikasi Frontend:**
    *   **Deskripsi:** Implementasi dari desain UI/UX yang berinteraksi dengan API Backend untuk menampilkan data dan fungsionalitas kepada pengguna.
    *   **Repositori:** [dompet-juara/frontend](https://github.com/dompet-juara/frontend)

3.  **⚙️ Backend & Database:**
    *   **Deskripsi:** Mengelola logika bisnis, otentikasi pengguna, penyimpanan data (pemasukan, pengeluaran, profil), dan menyediakan API untuk frontend. Menggunakan Supabase (PostgreSQL).
    *   **Repositori:** [dompet-juara/backend](https://github.com/dompet-juara/backend)

4.  **🧠 Machine Learning (AI Engine):**
    *   **Deskripsi:** Mengembangkan dan melatih model klasifikasi perilaku keuangan serta logika untuk AI Recommender dan Chatbot.
    *   **Repositori:** [dompet-juara/machine-learning](https://github.com/dompet-juara/machine-learning)

## 🛠️ Tumpukan Teknologi (Tech Stack)

*   **Desain UI/UX:** Figma
*   **Frontend:** React, Next.js (Potensi lainnya: Vue, Flutter)
*   **Backend & Database:** Supabase (PostgreSQL, Supabase Auth, Supabase Storage)
*   **API Backend (jika dikembangkan terpisah dari Supabase):** Node.js (Express/NestJS) / Python (FastAPI/Django) / Go (Gin)
*   **Machine Learning:** Python (Scikit-learn, Pandas, TensorFlow/PyTorch)
*   **Platform Deployment (Potensial):** Vercel, Netlify, Supabase Hosting, Heroku, AWS, Google Cloud.

## 🎨 Tampilan Aplikasi (UI/UX)

Untuk melihat visualisasi desain aplikasi Dompet Juara yang telah dibuat di Figma, silakan kunjungi repositori UI/UX kami yang menyajikan screenshot lengkap:

➡️ **[Lihat Desain UI/UX Dompet Juara](https://github.com/dompet-juara/uiux)**

Di sana Anda akan menemukan:
*   [Tampilan Mobile](https://github.com/dompet-juara/uiux#tampilan-mobile)
*   [Tampilan Desktop](https://github.com/dompet-juara/uiux#tampilan-desktop)

## 🚀 Memulai (Getting Started)

Karena Dompet Juara terdiri dari beberapa komponen yang dikembangkan secara terpisah, silakan merujuk ke README di masing-masing repositori untuk instruksi instalasi, konfigurasi, dan cara menjalankan setiap bagian:

*   **UI/UX:** Ikuti panduan di [README UI/UX](https://github.com/dompet-juara/uiux/blob/main/README.md) untuk mengakses file Figma dan aset desain.
*   **Frontend:** Ikuti panduan di [README Frontend](https://github.com/dompet-juara/frontend/blob/main/README.md) untuk menjalankan aplikasi antarmuka pengguna.
*   **Backend & Database:** Ikuti panduan di [README Backend](https://github.com/dompet-juara/backend/blob/main/README.md) untuk setup Supabase dan skema database.
*   **Machine Learning:** Ikuti panduan di [README Machine Learning](https://github.com/dompet-juara/machine-learning/blob/main/README.md) untuk melatih model dan menjalankan inferensi.

## 🤝 Berkontribusi

Kami sangat terbuka untuk kontribusi dari komunitas! Jika Anda tertarik untuk berkontribusi pada Dompet Juara, silakan:

1.  **Fork** repositori utama ini atau repositori komponen yang ingin Anda kontribusikan.
2.  **Buat Branch Baru:** (`git checkout -b fitur/nama-fitur-anda` atau `fix/perbaikan-bug`).
3.  **Lakukan Perubahan:** Implementasikan fitur atau perbaikan bug.
4.  **Commit Perubahan Anda:** (`git commit -m 'feat: Menambahkan fitur X'`).
5.  **Push ke Branch Anda:** (`git push origin fitur/nama-fitur-anda`).
6.  **Buka Pull Request** ke branch `main` dari repositori terkait.

Sebelum mengerjakan fitur besar, disarankan untuk membuka *issue* terlebih dahulu untuk diskusi. Pastikan untuk mengikuti pedoman kontribusi (jika ada) di masing-masing repositori.

## 🗺️ Peta Jalan (Roadmap)

Berikut adalah beberapa rencana pengembangan Dompet Juara ke depan:

*   **Q3 2025:**
    *   [ ] Finalisasi Desain UI/UX Mobile & Desktop.
    *   [ ] Implementasi Skema Database & API Backend v1.0.
    *   [ ] Pengembangan Model ML Klasifikasi Perilaku Keuangan v0.1.
*   **Q4 2025:**
    *   [ ] Pengembangan Aplikasi Frontend Mobile (MVP) menggunakan React/Next.js.
    *   [ ] Integrasi Frontend dengan Backend & Model ML.
    *   [ ] Pengujian Internal & Umpan Balik Awal.
*   **2026 & Seterusnya:**
    *   [ ] Rilis Publik Beta.
    *   [ ] Pengembangan Aplikasi Frontend Desktop.
    *   [ ] Peningkatan Akurasi Model ML.
    *   [ ] Penambahan Fitur Baru (misalnya, perencanaan anggaran, target tabungan).

## 📜 Lisensi

Proyek ini dilisensikan di bawah **Lisensi MIT**. Lihat file `LICENSE` untuk detail lebih lanjut.

## 🧑‍💻 Tim Proyek & Kontak

*   **Organisasi GitHub:** [Dompet Juara](https://github.com/dompet-juara)
*   **Email Kontak Utama:** `juaradompet@gmail.com`

Kami bersemangat untuk membangun Dompet Juara dan membantu lebih banyak orang mencapai kebebasan finansial!
