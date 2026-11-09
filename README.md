# Arsip & Realisasi Anggaran KRGT

Aplikasi web satu halaman untuk pencatatan arsip belanja dan monitoring realisasi anggaran Kebun Raya Gunung Tidar (KRGT).

## Fitur

- **Arsip Belanja** — tambah, cari, dan kelola data arsip belanja beserta status SPJ.
- **Laporan Realisasi Anggaran** — ringkasan pagu, realisasi, sisa pagu, dan persentase realisasi per kategori belanja (Januari–Desember).
- **Ekspor Excel** — unduh data arsip maupun laporan realisasi dalam format `.xlsx` (SheetJS).
- **Link Tampil Saja** — bagikan tautan mode hanya-baca.
- **Penyimpanan lokal** — data tersimpan di `localStorage` browser, tanpa backend.

## Menjalankan

Buka `index.html` langsung di browser, atau jalankan server statis sederhana:

```bash
python -m http.server 8000
```

Lalu akses `http://localhost:8000`.

## Teknologi

HTML, Tailwind CSS (CDN), Font Awesome, SheetJS, dan JavaScript vanilla.
