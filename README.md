# CoffeeShop POS Dashboard

Project ini adalah Admin Panel Point of Sale Coffee Shop berbasis HTML, CSS, dan JavaScript. Jalankan project menggunakan Live Server agar komponen navbar AJAX dapat dimuat dengan benar.

## Struktur Halaman

- POS / Kasir: `index.html`
- Template Layout Admin: `layout.html`
- Riwayat Pesanan: `pages/history.html`
- Dashboard: `pages/dashboard.html`
- Data Master Produk: `pages/data-master.html`
- Form Tambah/Edit Produk: `pages/form.html`
- Laporan Penjualan: `pages/report.html`

## Struktur Folder

```text
├── docs/
│   ├── PERANCANGAN.md
│   ├── perancangan.md
│   └── wireframes.html
├── assets/
│   ├── css/
│   ├── js/
│   └── img/
│       ├── wireframe-dashboard.svg
│       └── wireframe-data-master.svg
├── component/
│   └── navbar.html
├── css/
├── js/
├── pages/
│   ├── dashboard.html
│   ├── data-master.html
│   ├── form.html
│   ├── history.html
│   └── report.html
├── layout.html
└── index.html
```

## Pemetaan Milestone Tugas

### Milestone 1 - Perencanaan Menu dan UI Wireframing

Output tersedia pada:

- `docs/PERANCANGAN.md`
- `docs/wireframes.html`
- `assets/img/wireframe-dashboard.svg`
- `assets/img/wireframe-data-master.svg`

Catatan: link publik Figma/Stitch pada `docs/PERANCANGAN.md` masih harus diganti dengan link asli dari akun desain kelompok sebelum dikumpulkan.

### Milestone 2 - Slicing dan Layouting

Output tersedia pada:

- `layout.html`
- `css/admin.css`
- `js/layout.js`

Template memuat navbar/header, sidebar, content area, dan footer.

### Milestone 3 - Implementasi Komponen dan Interaktivitas UI

Output tersedia pada:

- Dashboard dengan Chart.js: `pages/dashboard.html`
- Data tabel master: `pages/data-master.html`
- Form input/edit dengan validasi JavaScript: `pages/form.html`
- Laporan/detail/cetak/export CSV: `pages/report.html`
- POS dan modal pembayaran: `index.html`

## Penyimpanan Data

Aplikasi menggunakan LocalStorage:

- `posProducts`: data produk master.
- `cart`: data keranjang sementara.
- `transactions`: data transaksi.

## Cara Menjalankan

1. Buka folder project di VS Code.
2. Jalankan menggunakan ekstensi Live Server.
3. Buka `index.html` untuk halaman POS.
4. Gunakan menu navbar untuk berpindah ke Dashboard, Data Master, Form, dan Laporan.
