# e-Retribusi Karimun — Frontend Prototype

Prototype frontend-only untuk presentasi/review klien.

## Isi
- Website publik: Beranda, Alur Kerja, Fitur, Login Demo
- Role Petugas Lapangan
- Role Operator Aplikasi
- Role Admin / Pimpinan
- Objek Retribusi, pembayaran, tunggakan, verifikasi
- Dashboard analitik, laporan, master data, manajemen pengguna
- Profil, modal, toast, filter/search, tabel, badge, grafik dummy

## Teknologi
HTML + CSS + JavaScript vanilla. Tidak ada backend, database, autentikasi, atau API.
Routing menggunakan hash (`#/route`) sehingga dapat dijalankan langsung melalui GitHub Pages.

## Cara menjalankan lokal
Buka `index.html` langsung di browser, atau gunakan static server sederhana.

## Deploy ke GitHub Pages
1. Buat repository baru, misalnya `eretribusi-karimun-frontend`.
2. Upload seluruh isi folder ini ke root repository.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`.
6. Save. Tunggu proses deploy selesai.
7. Bagikan URL GitHub Pages yang diberikan GitHub.

## Catatan prototype
Semua data adalah dummy/statis. Tombol Simpan, Verifikasi, Export, Upload, Edit, dan filter hanya mensimulasikan interaksi UI. Tidak ada data yang tersimpan permanen di server.

## Role Demo
- Operator: `#/login` → Operator Aplikasi
- Petugas: `#/login` → Petugas Lapangan
- Admin: `#/login` → Admin / Pimpinan

Tidak ada password/API sungguhan.
