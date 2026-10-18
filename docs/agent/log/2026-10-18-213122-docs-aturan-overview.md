# Batas isi overview Greybeard

- Waktu: 2026-10-18 21:31:22 +08:00
- Jenis: dokumentasi
- Ringkasan: memperjelas aturan agar overview hanya menjelaskan gambaran umum proyek saat ini.

## Hasil
- Bagian 8 pada `greybeard-id.md`, `greybeard-id-compressed.md`, `greybeard-en.md`, dan `greybeard-en-compressed.md` membatasi overview pada tujuan, komponen utama, hubungan antarbagian, dan struktur penting.
- Rangkuman tugas, riwayat perubahan/keputusan, status pekerjaan, dan rencana tertunda dilarang masuk overview. Detail teknis masuk knowledge khusus; hasil/riwayat pekerjaan masuk log; pekerjaan aktif/tertunda masuk task.
- Pembaruan knowledge harus merevisi informasi terkait yang berubah, bukan menambahkan rangkuman tugas atau menyalin log/checklist. Peta diperbarui hanya bila tautan atau petunjuk pembacaan berubah.
- Isi `docs/agent/knowledge/overview.md`, peta dokumentasi, dan perubahan pengguna sebelumnya tidak diubah oleh tugas ini.

## Verifikasi
- Aturan baru pada empat versi dibaca dan dibandingkan; maknanya selaras. Perbedaan pola nama task/log Indonesia dan Inggris tetap dipertahankan.
- `git diff --check` tidak melaporkan kesalahan spasi; Git memberi peringatan konversi LF/CRLF pada overview yang sudah berubah sebelum tugas ini.
- Berkas Greybeard masih belum dilacak Git akibat penggantian nama sebelumnya, sehingga pemeriksaan aturan dilakukan langsung pada isi berkas. Tidak ada pengujian kode karena perubahan hanya instruksi Markdown.
