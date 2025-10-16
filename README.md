🚀 MathTrick Demo: Trik Cepat Kuadrat (Berbagi Kecerdasan!)

Aplikasi web sederhana ini mendemonstrasikan trik matematika cepat untuk menghitung kuadrat bilangan yang berakhiran angka 5 (misalnya $25^2$, $35^2$, dll.) dan dilengkapi dengan fitur canggih seperti:

Analisis Langkah-langkah: Menampilkan proses trik secara detail.

Kecerdasan Buatan (Gemini): Memberikan penjelasan aljabar mendalam dan saran trik lain.

Kolaborasi Real-time (Firestore): Menyimpan dan menampilkan Papan Peringkat Kecepatan (Leaderboard).

✨ Fitur Utama

1. Trik Cepat Kuadrat

Trik ini didasarkan pada rumus aljabar $(10A + 5)^2$.

Contoh ($35^2$):

Ambil $A$ (Angka di depan 5): $A = 3$

Kalikan $A$ dengan $(A+1)$: $3 \times (3+1) = 3 \times 4 = 12$. (Ini adalah bagian depan hasil.)

Tambahkan 25 di belakang: $1225$.

2. Papan Peringkat Kecepatan (Multi-Pengguna)

Aplikasi ini menggunakan Firebase Firestore untuk fungsionalitas kolaborasi.

Setiap kali pengguna berhasil menghitung kuadrat, waktu komputasi (dalam milidetik) dicatat.

Hasil kecepatan tersebut secara otomatis disimpan ke database publik.

Semua pengguna dapat melihat 5 hasil tercepat di Papan Peringkat secara real-time, mendorong kompetisi yang seru!

3. Fitur Gemini (AI-Powered)

Tiga tombol di bagian bawah memanfaatkan model bahasa besar Gemini untuk:

Jelaskan Kenapa Trik Ini Bekerja: Memberikan pembuktian aljabar untuk trik $(10A+5)^2$, menjelaskan dasar teorinya.

Sarankan Trik Matematika Lain: Mencari dan menampilkan instruksi langkah demi langkah untuk trik matematika cepat yang berbeda (misalnya, trik perkalian 11).

Buat Soal Latihan Seru: Menghasilkan soal cerita yang jawabannya harus diselesaikan menggunakan trik kuadrat berakhiran 5, lengkap dengan jawaban dan penjelasannya.

🛠️ Teknologi yang Digunakan

Komponen

Teknologi

Tujuan

Frontend

HTML5, JavaScript (ES Modules)

Struktur dan logika aplikasi.

Styling

Tailwind CSS

Desain yang modern, responsif, dan menarik.

Kecerdasan

Gemini API (gemini-2.5-flash-preview-09-2025)

Menghasilkan penjelasan, saran, dan soal latihan.

Database

Firebase Firestore

Penyimpanan data Papan Peringkat real-time dan kolaboratif.

Autentikasi

Firebase Auth (Anonim/Kustom)

Mengidentifikasi pengguna untuk mencatat skor.

💡 Cara Penggunaan

Masukkan Angka: Ketik bilangan bulat positif yang berakhiran 5 (contoh: 85).

Hitung: Klik tombol "Hitung Kuadrat!".

Lihat Hasil: Trik akan dipecah menjadi langkah-langkah, dan hasil akhirnya akan ditampilkan. Waktu komputasi juga akan dicatat.

Cek Peringkat: Lihat apakah waktu Anda masuk 5 besar di Papan Peringkat Kecepatan.

Eksplorasi AI: Gunakan tombol Gemini untuk memperdalam pemahaman atau mencari trik baru.
