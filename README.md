# Media-Zefanya v2 (Buku)

Aplikasi manajemen inventaris perpustakaan/buku yang terhubung ke Supabase (`dytcoemthbngxoamoetr`).

## Fitur Utama
- CRUD data buku dan referensi literatur.
- Filter dan pencarian kategori buku.
- Mode verifikasi guru (password: `zefanya123`).

## Perbedaan v1, v2, v3
| Versi | Target Entitas | Tabel Supabase | Port PM2 |
|---|---|---|---|
| **v1** | Skripsi | `skripsi` | 8080 |
| **v2** | Buku | `buku` | 8081 |
| **v3** | Taman | `taman` | 8082 |
