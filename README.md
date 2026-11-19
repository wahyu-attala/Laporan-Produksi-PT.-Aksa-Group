# Papan Produksi PT Aksa Group

Aplikasi papan produksi publik. Pengunjung dapat melihat data; editor yang tercantum di tabel Supabase dapat menambah, mengubah, dan menghapus order.

## Menjalankan

1. Buat project gratis di [Supabase](https://supabase.com).
2. Jalankan seluruh isi `supabase.sql` pada SQL Editor Supabase.
3. Aktifkan Email Auth pada Authentication → Providers → Email.
4. Buka situs dan tekan **Pengaturan**.
5. Masukkan Project URL serta publishable/anon key.
6. Tambahkan email editor dengan SQL atau dashboard tabel `editors`.

## Publikasi

Aktifkan GitHub Pages melalui **Settings → Pages**, lalu pilih branch `main` dan folder `/ (root)`.

## Keamanan

Database menggunakan Row Level Security. Jangan memasukkan service-role key ke aplikasi browser.
