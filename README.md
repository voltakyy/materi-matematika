# Materi Matematika Interaktif

Situs statis berisi satu landing page dan dua halaman materi terpisah.

| File | Isi |
| --- | --- |
| `index.html` | Landing: pengantar, pilihan materi, alur belajar, dan fitur |
| `limit.html` | Materi limit fungsi aljabar |
| `turunan.html` | Materi turunan fungsi aljabar |

## Menjalankan

Buka `index.html` di browser. Tidak ada build step, dependensi, atau server khusus.
Ketiga halaman mandiri (CSS dan JavaScript ditulis inline), jadi folder ini bisa
langsung dipindah atau diunggah apa adanya.

## Navigasi

- Landing → kartu materi atau menu **Limit** / **Turunan** di header.
- Halaman materi → logo **Materi Matematika** atau ikon rumah di subnav untuk
  kembali ke landing.
- Footer setiap materi → tautan ke materi lain dan beranda.

## Catatan

- Sumber materi turunan: artikel Ruangguru (tercantum di footer `turunan.html`).
- Preferensi efek suara disimpan di `localStorage`: `lfa_sound_enabled` untuk
  halaman limit dan `tfa_sound_enabled` untuk halaman turunan.
- Ketiga halaman memakai variabel CSS yang sama di bagian `:root` (warna
  harbour blue, reef teal, outback gold, sandstone) agar tampilannya konsisten.
