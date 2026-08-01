# Undangan Pernikahan — Dhifa & Hafidz

## Isi folder
- `index.html` — halaman undangan
- `foto/` — semua foto yang dipakai di undangan (jangan dipisah dari index.html)

## Cara upload ke GitHub

1. Buka https://github.com dan login.
2. Klik tombol **New** (buat repository baru).
3. Beri nama repo, misalnya `undangan-dhifa-hafidz`. Pilih **Public**. Klik **Create repository**.
4. Di halaman repo yang masih kosong, klik **uploading an existing file**.
5. Seret (drag & drop) **semua isi folder ini** — `index.html`, folder `foto` (dengan seluruh isinya), dan `README.md` — ke kotak upload.
6. Scroll ke bawah, klik **Commit changes**.

## Cara deploy ke Vercel

1. Buka https://vercel.com dan login (bisa langsung pakai akun GitHub).
2. Klik **Add New... → Project**.
3. Pilih repo `undangan-dhifa-hafidz` yang baru dibuat tadi, klik **Import**.
4. Di bagian **Framework Preset**, pilih **Other** (karena ini bukan React/Next, cuma HTML biasa).
5. Biarkan pengaturan lain default, klik **Deploy**.
6. Tunggu sekitar 30 detik–1 menit, Vercel akan memberi link seperti:
   `https://undangan-dhifa-hafidz.vercel.app`

Link itu sudah bisa langsung dibagikan ke tamu.

## Menambahkan nama tamu di link

Tambahkan `?to=NamaTamu` di akhir link, contoh:

```
https://undangan-dhifa-hafidz.vercel.app/?to=Budi%20Santoso
```

Nama tamu akan otomatis muncul di halaman pembuka undangan.

## Custom domain (opsional)

Kalau punya domain sendiri (misal `dhifahafidz.com`), bisa dihubungkan lewat
menu **Settings → Domains** di project Vercel-nya.
