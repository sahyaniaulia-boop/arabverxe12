# ARABVERSE
Website statis pembelajaran Bahasa Arab berbasis petualangan, tanpa dependensi atau API key.

## Menjalankan lokal
Buka index.html, atau jalankan `python -m http.server 8000` pada folder ini lalu buka http://localhost:8000.

## Deploy ke Vercel
1. Ekstrak ZIP. Unggah isi folder arabverse ke repositori GitHub baru (index.html harus berada di root).
2. Masuk https://vercel.com/new dan impor repositori tersebut.
3. Framework Preset: Other. Root Directory: folder yang berisi index.html. Build Command: kosong/nonaktif. Output Directory: `.` (sudah dikonfigurasi di vercel.json).
4. Klik Deploy. Gunakan alamat yang Vercel berikan.
Alternatif: jika Node.js terpasang, jalankan `npx vercel` di folder ini dan ikuti instruksi, lalu `npx vercel --prod` untuk produksi.

## Fitur
6 wilayah, 18 soal, kristal, XP dan koin, level, avatar, bonus harian, progres lokal, peta SVG responsif. Audio menggunakan suara Arab perangkat jika tersedia.

## Batasan MVP
Tidak ada login server, database, leaderboard multipengguna, dashboard dosen, AI, pengenalan suara, atau sinkronisasi lintas perangkat. Progres tersimpan pada localStorage per browser/origin; menghapus data browser menghapus progres. Soal merupakan contoh dasar dan perlu validasi pedagogis sebelum penggunaan formal. Misi Istana Bahasa masih berbentuk pilihan ganda, bukan penilaian berbicara/menulis autentik. Ilustrasi berupa SVG sederhana yang disertakan dalam proyek.
