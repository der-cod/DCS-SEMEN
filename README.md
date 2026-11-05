# DCS di Industri Semen (PWA)

Isi: index.html, manifest.webmanifest, sw.js, folder icons/.

## Deploy ke GitHub Pages
1. Buat repository baru di GitHub, unggah semua isi folder ini ke root repository.
2. Settings > Pages > Source: Deploy from a branch > pilih branch main, folder /(root).
3. Buka https://NAMAUSER.github.io/NAMAREPO/ lewat HTTPS, lalu pilih "Pasang aplikasi" atau Add to Home Screen.

Service worker dan instalasi PWA hanya jalan lewat HTTPS (atau localhost), bukan dengan membuka file langsung.
Untuk uji lokal: python3 -m http.server 8000, lalu buka http://localhost:8000.
Setelah mengubah isi, naikkan nama CACHE di sw.js (misalnya dcs-semen-v2) agar pengguna mendapat versi baru.
