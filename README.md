# HBD Novelyne 🌻

Website kejutan ulang tahun Novelyne, 19 November 2026. Cukup HTML statis, tanpa build.

## Deploy ke Vercel
1. Buka vercel.com → **Add New → Project** → import repo `blackhespy/hbd`.
2. Framework Preset: **Other**. Build command & output dibiarkan kosong.
3. Klik **Deploy**.

## Edit konten
- Semua kenangan ada di array `MEMORIES` di bagian `<script>` pada `index.html`.
- `date` boleh `"2026-03-19"` (tampil `'26 3 19`) atau `"2026-04"` (tampil `Apr '26`).
- Foto ada di folder `photos/`. Tambah foto baru lalu daftarkan di `MEMORIES`.
- Teks pop-up ucapan ada di elemen `.slide` di dalam `#modal`.
