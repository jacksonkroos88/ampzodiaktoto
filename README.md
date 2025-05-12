# Halaman AMP di Cloudflare Pages

Ini adalah contoh halaman AMP sederhana yang bisa kamu deploy langsung ke [Cloudflare Pages](https://pages.cloudflare.com).

## 🚀 Cara Deploy

1. Fork atau clone repo ini ke GitHub kamu.
2. Buka Cloudflare Pages dan klik **Create a Project**.
3. Hubungkan repo ini ke Cloudflare.
4. Build Settings:
   - Framework preset: `None`
   - Build command: *(kosongkan)*
   - Output directory: `.`

5. Klik **Deploy Site**

Setelah selesai, halaman AMP kamu akan tersedia di:
```
https://nama-proyek.pages.dev
```

Untuk validasi AMP, tambahkan `#development=1` di akhir URL dan cek Developer Console.

## 📝 Catatan

- Semua CSS wajib inline dan maksimal 75KB.
- Gunakan tag-tag AMP seperti `<amp-img>`, `<amp-video>`, dll.
