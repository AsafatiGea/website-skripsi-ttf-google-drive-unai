# Portal Penelitian TTF Google Drive UNAI — Versi 3

Website ini dibuat dari file HTML terbaru yang diberikan oleh peneliti, dengan sitasi naskah diperbarui/ditegaskan sesuai format berikut:

> Gea, A., & Limbong, A. (2026). Analisis penggunaan fitur Google Drive oleh mahasiswa UNAI menggunakan model TTF (Task-Technology Fit) [Naskah belum dipublikasikan]. Program Studi Sistem Informasi, Fakultas Teknologi Informasi, Universitas Advent Indonesia.

## Struktur proyek

```text
web-skripsi-ttf-unai-v3/
├── index.html
└── README.md
```

File HTML sumber sudah memuat CSS dan JavaScript di dalam `index.html`, serta menggunakan Tailwind CSS, Chart.js, dan Lucide melalui CDN. Karena itu, struktur satu-file ini dipertahankan agar tampilan dan interaksi dari file yang diberikan tidak rusak akibat pemisahan kode.

## Menjalankan di Windows 11

1. Ekstrak ZIP.
2. Buka Visual Studio Code.
3. Pilih **File → Open Folder**, lalu pilih folder `web-skripsi-ttf-unai-v3`.
4. Buka `index.html`.
5. Jalankan dengan ekstensi **Live Server** (klik kanan → Open with Live Server), atau buka file `index.html` langsung di Chrome.

Tidak memerlukan `npm install`, `npm run dev`, Node.js, backend, atau database. Koneksi internet diperlukan untuk memuat Tailwind CSS, Chart.js, Lucide, dan Google Fonts dari CDN.

## Sitasi

Bagian **Sitasi & Naskah** di halaman menyediakan format APA dan BibTeX. Sitasi APA ditetapkan sesuai informasi bibliografis yang diberikan peneliti. Naskah tetap berstatus **belum dipublikasikan**.

## Catatan integritas data

Dashboard di halaman ini memiliki status simulasi. Angka contoh yang sudah ada di dalam file hanya untuk demonstrasi tampilan, bukan hasil penelitian. Jangan mengubah status simulasi menjadi hasil empiris sebelum angka diganti dengan output SPSS yang benar dan diverifikasi.

## Deploy

Unggah `index.html` ke root repository GitHub. Hubungkan repository tersebut ke Vercel sebagai proyek statis (framework **Other**, tanpa build command). Pastikan `index.html` berada di root proyek.
