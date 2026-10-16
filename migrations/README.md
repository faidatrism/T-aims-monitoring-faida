# Database Migrations

Folder ini berisi file migrasi SQL terstruktur.

## Konvensi Penamaan

`NOMOR_deskripsi.sql`

Contoh:
- `001_add_created_at_to_users.sql`
- `002_add_offline_since_index.sql`

## Cara Pakai

1. Jalankan file secara berurutan (001, 002, 003, ...)
2. Setiap file ada bagian **UP** (untuk migrasi) dan **DOWN** (untuk rollback)
3. Catat migrasi yang sudah dijalankan

## Daftar Migrasi

| No | File | Tanggal | Deskripsi |
|---|---|---|---|
| 001 | `001_add_created_at_to_users.sql` | 2026-10-16 | Fix BUG-009 |