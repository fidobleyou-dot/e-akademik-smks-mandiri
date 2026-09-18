# e-Akademik SMKS Mandiri — Offline / GitHub Pages

Versi ini bekerja tanpa API AI. Data disimpan di browser/perangkat menggunakan localStorage.

## Offline
- Ekstrak ZIP dan buka `index.html`.
- Login: **admin** / **admin123**.
- Data siswa, guru, mapel, nilai, perilaku, kehadiran, prestasi, kenaikan/kelulusan, pengaturan dan raport tersimpan di perangkat.
- Gunakan **Backup** untuk membuat JSON dan **Restore** untuk memulihkan.

Service Worker/PWA tidak dapat didaftarkan dari `file://`, tetapi aplikasi tetap dapat dipakai offline. Untuk PWA/offline cache, gunakan localhost atau GitHub Pages.

## GitHub Pages
Upload `index.html`, `manifest.json`, dan `sw.js` ke root repository, lalu aktifkan GitHub Pages. Setelah pertama kali dibuka online, application shell akan dicache sehingga aplikasi dapat dibuka kembali saat offline.

**Catatan:** GitHub Pages bukan database. Data tetap lokal pada browser/perangkat. Backup JSON sangat dianjurkan.
