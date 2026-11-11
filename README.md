# Che Magz Blog — file siap upload (versi terbaru, 10 Nov 2026)

Isi folder ini = blog Che Magz versi publik terbaru:
- Arsip 250 postingan (thumbnail placeholder #FFC100, tanpa foto orang)
- Tab **Kalkulator** lengkap (6 kalkulator, R sudah nilai tepat 8,31446261815324, tes STP = 273,15 K)
- Caption sudah disensor (nama trainer/guest speaker/narasumber + blok payment post-015 dihapus; aslinya tersimpan di `~/workspace/backups/che-magz-blog/`)

Ukuran total ±18 MB (index.html 282 KB + 250 thumbnail di `assets/`). Semua thumbnail terverifikasi: 250 file yang dirujuk di index.html ada semua, tidak ada yang hilang.

## Opsi A — GitHub Pages (paling rapi jangka panjang, gratis)

1. Buat akun GitHub (kalau belum ada), lalu buat repo baru bernama `chemagz` — pilih **Public**.
2. Di repo, klik **Add file → Upload files**, lalu upload **isi folder ini** (`index.html` + folder `assets/`), bukan foldernya. Commit.
3. Masuk **Settings → Pages → Build and deployment → Source: Deploy from a branch**, pilih branch `main`, folder `/ (root)`, Save.
4. Tunggu ±1 menit, alamatnya jadi `https://<username>.github.io/chemagz/` — ganti `<username>` dengan username GitHub kamu. Mau alamat `chemagz.github.io` persis, nama reponya harus `<username>.github.io`.
5. Tiap ada update: upload ulang `index.html` (dan thumbnail baru kalau ada) ke repo yang sama.

## Opsi B — Vercel Drop (paling gampang, tanpa akun GitHub)

1. Buka `vercel.com/drop`, drag **folder ini** ke halaman itu.
2. Selesai — dapat alamat `*.vercel.app` gratis. Nama subdomain bisa diganti di dashboard Vercel (mis. `chemagz.vercel.app` kalau masih tersedia).
3. Tiap ada update: drag ulang folder versi terbaru.

## Catatan

- Link Muse yang sekarang tetap jalan sebagai cadangan; pindah hosting tidak mematikan link itu.
- Jangan upload file export lama di `~/workspace/your_files/che-magz-blog/` (7 Okt 2026) — file itu belum ada tab Kalkulatornya.
- Kalau nanti mau domain sendiri (mis. `chemagz.com`, ±Rp150–250 ribu/tahun), domain itu bisa dipasang gratis di GitHub Pages maupun Vercel; yang bayar cuma domainnya.
