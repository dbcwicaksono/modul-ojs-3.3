---
name: ojs-setup
description: Menyiapkan sistem agen untuk proyek buku OJS 3.3. Aktifkan skill ini ketika pengguna meminta setup agen, atau ketika memulai sesi kerja buku OJS. Trigger: "setup agen", "siapkan agen", "mulai sesi OJS", "inisialisasi proyek OJS".
---

# Skill: OJS Book Agent Setup

Skill ini menginisialisasi dua agen kerja untuk proyek buku "Pengelolaan Jurnal Elektronik dengan OJS 3.3". Jalankan skill ini di awal setiap sesi kerja baru.

## Langkah Eksekusi

1. Baca file konfigurasi lengkap dari `references/` sebelum mendefinisikan agen.
2. Definisikan kedua agen menggunakan `define_subagent` dengan konfigurasi dari file referensi.
3. Konfirmasi ke pengguna bahwa kedua agen siap digunakan.

### Agen 1: ojs-web-researcher
- Baca konfigurasi lengkap di: `.agents/skills/ojs-setup/references/researcher-config.md`
- Definisikan dengan `name: ojs-web-researcher`, `enable_write_tools: true`

### Agen 2: ojs-book-writer
- Baca konfigurasi lengkap di: `.agents/skills/ojs-setup/references/writer-config.md`
- Definisikan dengan `name: ojs-book-writer`, `enable_write_tools: true`

## Setelah Setup Selesai

Laporkan ke pengguna:
- Kedua agen telah siap
- Cara memanggil agen peneliti: "jalankan peneliti untuk Bab X, topik Y"
- Cara memanggil agen penulis: "kerjakan Bab X dengan agen penulis"
- Lokasi output penelitian: `research/knowledge-base.md` dan `research/bibliography.md`
