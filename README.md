# La Suvarna Property

Website statis untuk promosi proyek La Suvarna Property. Halaman utama publish ada di `index.html`, sehingga bisa langsung di-deploy ke Vercel tanpa proses build.

## Cara Publish di Vercel

1. Upload folder ini ke GitHub.
2. Buka Vercel, lalu pilih **Add New Project**.
3. Import repository GitHub yang berisi folder ini.
4. Biarkan pengaturan build kosong/default:
   - Framework Preset: **Other**
   - Build Command: kosong
   - Output Directory: kosong
5. Klik **Deploy**.

Setelah selesai, bagikan link Vercel ke dosen. Halaman utama otomatis terbuka dari `index.html`.

## Halaman Penting

- `index.html`: halaman utama untuk publish.
- `index_lihat.html`: daftar dan filter lokasi proyek.
- `index_detail.html`: halaman detail proyek.
- `navbar_simulasi.html`: simulasi KPR.
- `navbar_whatsapp.html`: halaman kontak WhatsApp.
- `admin/index.html`: halaman admin lokal untuk mengubah data lewat browser.
