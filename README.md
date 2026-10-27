# Portofolio Bintang Yudhistira

Website portofolio pribadi Bintang Yudhistira versi awal. Situs ini menampilkan profil, keahlian, pengalaman, pendidikan, proyek, dan kontak dalam satu aplikasi web berbasis React. Repositori ini adalah versi lama portofolio dan sudah digantikan oleh versi yang lebih baru, tetapi kodenya tetap disimpan sebagai arsip dan referensi.

## Fitur

- Halaman Hero sebagai pembuka dengan foto dan perkenalan singkat.
- Halaman Skills dengan ikon teknologi berbentuk icon cloud dan komponen interaktif lain.
- Halaman Experience berisi riwayat pengalaman kerja dan organisasi.
- Halaman Education berisi riwayat pendidikan.
- Halaman Projects berisi daftar proyek yang pernah dibuat.
- Halaman Contact berisi cara menghubungi pemilik situs.
- Dua mode tampilan: mode satu halaman yang menampilkan semua bagian sekaligus, dan mode router dengan halaman terpisah untuk setiap bagian.
- Animasi antarmuka memakai Framer Motion dan komponen UI bergaya shadcn.

## Teknologi

- React 18 dan Vite 7
- React Router DOM untuk navigasi antar halaman
- Tailwind CSS untuk styling
- Framer Motion untuk animasi
- Lucide React dan React Icons untuk ikon
- Radix UI untuk komponen dasar

## Cara Instalasi

Prasyarat: Node.js dan npm sudah terpasang.

Clone repositori ini, lalu pasang semua dependensi:

```bash
npm install
```

## Cara Menjalankan

Jalankan server pengembangan:

```bash
npm run dev
```

Buka alamat yang ditampilkan Vite di browser, biasanya `http://localhost:5173`.

Untuk build produksi dan melihat hasilnya:

```bash
npm run build
npm run preview
```

Struktur utama proyek:

- `src/pages` berisi halaman Hero, Skills, Experience, Education, Projects, dan Contact.
- `src/components` berisi komponen UI yang dipakai bersama.
- `src/App.jsx` mengatur mode tampilan dan routing.
- `vercel.json` mengatur rewrite agar semua rute diarahkan ke aplikasi utama saat di-deploy sebagai single page application.

## Lisensi

Proyek ini memakai lisensi MIT. Lihat berkas [LICENSE](LICENSE) untuk teks lengkapnya.
