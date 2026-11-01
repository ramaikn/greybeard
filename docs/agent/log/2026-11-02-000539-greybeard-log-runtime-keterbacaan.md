# Log runtime, keterbacaan kode, dan pesan developer di skill Greybeard

- Waktu: 2026-11-02 00:05:39 +08:00 (MPST).
- Jenis: perubahan aturan skill.
- Ringkasan: ide log runtime, kode mudah diaudit untuk vibes coding, dan pesan developer lewat log dilebur ke aturan yang sudah ada, tanpa bagian baru.

## Perubahan
- Bagian 1: user bekerja hampir sepenuhnya lewat agen (vibes coding), jadi kode harus mudah dipahami agen berikutnya dan programmer profesional.
- Bagian 4: pesan teknis, peringatan, dan error untuk developer masuk ke log, bukan label di tampilan; user hanya melihat pesan ramah.
- Bagian 6: satu poin "Mudah Diaudit" berisi nama deskriptif, komentar alasan dan alur, serta log runtime di titik penting saja (alur kritis, error dengan konteks, batas ke sistem luar) dengan level, tanpa data sensitif, di `logs/` yang di-gitignore.
- Bagian 7: penelusuran bug membaca log relevan lebih dulu secara selektif sebelum memperbaiki akar masalah.

## Berkas
- `greybeard-id.md`, `greybeard-id-compressed.md`, `greybeard-en.md`, `greybeard-en-compressed.md`.

## Verifikasi
- Keempat berkas diedit pada bagian yang sama dan selaras. Tidak ada pengujian kode.
- Salinan terpasang di `~/.claude/skills/greybeard/SKILL.md` belum disinkronkan.
