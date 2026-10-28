# Sistem Manajemen Media-Zefanya v2 (Buku)

Aplikasi web untuk manajemen data inventaris buku dan referensi perpustakaan yang terhubung langsung ke Supabase. 

## Fitur Utama

- **Manajemen Inventaris Buku** - Tambah, edit, hapus, dan lihat katalog buku lengkap dengan judul, pengarang, kategori, dan status ketersediaan.
- **Filter & Kategori** - Pengelompokan buku berdasarkan kategori literatur dengan pencarian cepat.
- **Mode Guru** - Fitur verifikasi khusus pengelola/guru menggunakan password (`zefanya123`) untuk kontrol data.
- **Sinkronisasi Supabase** - Seluruh data tersimpan terpusat di proyek Supabase `dytcoemthbngxoamoetr` tabel `buku`.

## Tech Stack

- Frontend: HTML, CSS, JavaScript / Frontend Framework
- Backend / Database: Supabase PostgreSQL (`dytcoemthbngxoamoetr`)
- Deployment Lokal: PM2 Process Manager (Port 8081)

## Perbandingan Versi Media-Zefanya (v1, v2, v3)

| Versi | Nama Proyek / Topik | Tabel Supabase | Port PM2 | Repository GitHub | Deskripsi Singkat |
|---|---|---|---|---|---|
| **v1** | Skripsi | `skripsi` | 8080 | `Carelyk/Media-Zefanya` | Manajemen data skripsi & nilai mahasiswa |
| **v2** | Buku | `buku` | 8081 | `Carelyk/Media-Zefanya-v2` | Manajemen inventaris perpustakaan dan buku |
| **v3** | Taman | `taman` | 8082 | `Carelyk/Media-Zefanya-v3` | Manajemen data fasilitas taman kota & tanaman |
