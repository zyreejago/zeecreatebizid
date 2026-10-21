# zeecreate.biz.id

Situs pendukung resmi untuk domain utama [zeecreate.site](https://zeecreate.site).
Berisi landing page dan artikel orisinal seputar pembuatan website untuk UMKM Indonesia,
dikelola oleh studio Zeecreate (Bali).

## Struktur

- `index.html` — landing page utama
- `styles.css` — gaya bersama semua halaman
- `perbedaan-landing-page-company-profile-toko-online/` — artikel panduan memilih jenis website
- `tanda-bisnis-perlu-website/` — artikel tanda bisnis perlu website
- `checklist-sebelum-bikin-website/` — artikel checklist persiapan proyek
- `robots.txt`, `sitemap.xml`

## Deploy di Vercel

1. Import repo ini sebagai project baru (framework preset: Other, tanpa build command).
2. Tambahkan domain `zeecreate.biz.id` dan `www.zeecreate.biz.id` di Settings → Domains.
3. Di registrar, pasang DNS: A record `@` → `76.76.21.21` dan CNAME `www` → `cname.vercel-dns.com`.
