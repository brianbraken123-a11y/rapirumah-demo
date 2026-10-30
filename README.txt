CLOUDFLARE WORKERS - DEMO THINKABLE.PRO

Ekstrak ZIP dan upload ISI folder ini ke root repo GitHub.
Susunan: public/index.html, wrangler.jsonc, package.json, package-lock.json.
Jangan upload ZIP saja atau membungkusnya dalam folder tambahan.

Nama Worker Cloudflare: demo-jasa-pembersih-ac.
Jika nama Worker yang sudah ada berbeda, ubah name di wrangler.jsonc
agar SAMA PERSIS dengan nama Worker di Cloudflare (bukan nama repo).

Root directory: root repo (kosong/default).
Build command: kosong.
Deploy command: npx wrangler deploy
Commit lalu ulangi deploy.

Gambar, CSS, JS menyatu di public/index.html.
Semua layanan, nama usaha, harga, area, jam adalah demo fiktif.
WhatsApp: 6287895582152.

Cek lokal: npm ci lalu npm run check.
Dry-run menguji konfigurasi tanpa publikasi.
Deploy live tetap membutuhkan akses akun dan setting Cloudflare yang benar.
