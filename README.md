# Jejak Qada

Web app untuk mencatat solat yang tertinggal dan menjejak qada.

- Input tempoh tinggal ikut tahun, bulan dan hari (anggaran: 1 tahun = 365 hari, 1 bulan = 30 hari)
- Pilih waktu yang tertinggal (Subuh, Zohor, Asar, Maghrib, Isyak)
- Catat qada yang dah dibuat, dengan sejarah penuh
- Sandaran dan pulihkan data melalui fail JSON (simpan ke Google Drive sendiri)
- BM / English

## Deploy

Setiap push ke cabang `main` akan deploy automatik ke GitHub Pages melalui
`.github/workflows/pages.yml`. Kali pertama: Settings > Pages > Source > **GitHub Actions**.

## Nota

Di GitHub Pages, data disimpan dalam pelayar (localStorage) sahaja. Gunakan butang
sandaran untuk simpan salinan. Penyegerakan Google Drive dirancang untuk versi app.
