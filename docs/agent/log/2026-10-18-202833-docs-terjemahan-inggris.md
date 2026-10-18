# Terjemahan Inggris skill Greybeard

- Waktu: 2026-10-18 20:28:33 +08:00
- Jenis: docs
- Ringkasan: menambahkan terjemahan Inggris 1:1 untuk versi lengkap dan ringkas tanpa mengubah sumber Indonesia.

## Hasil

- `SKILL.en.md` menerjemahkan `SKILL.md`; `SKILL.compressed.en.md` menerjemahkan `SKILL.compressed.md`.
- Urutan bagian, poin, dan ketentuan dipertahankan. Nama tool, path, pola nama berkas, serta format status dalam backtick tetap identik agar tidak mengubah aturan literal.
- `docs/agent/knowledge/overview.md` menjelaskan pasangan berkas dan kewajiban menyelaraskan terjemahan saat sumber berubah.
- Verifikasi otomatis: 67 baris pada pasangan lengkap, 55 baris pada pasangan ringkas; struktur per baris, literal backtick, dan angka cocok. Git memastikan sumber Indonesia tidak berubah.
- Makna diperiksa per poin oleh agen utama. Pemeriksaan otomatis hanya membuktikan kesetaraan struktur dan literal, bukan makna bahasa. Tidak ada pengujian kode karena perubahan hanya dokumentasi.
