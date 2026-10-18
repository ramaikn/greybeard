# Checklist berdasarkan kompleksitas dan siklus dokumen

- Waktu: 2026-10-18 21:59:20 +08:00
- Jenis: dokumentasi
- Ringkasan: menyelaraskan aturan task, log, dan dokumen hidup pada empat versi Greybeard.

## Hasil
- Bagian 8–9 di `greybeard-id.md`, `greybeard-id-compressed.md`, `greybeard-en.md`, dan `greybeard-en-compressed.md` diperbarui.
- Perubahan sederhana dengan pemeriksaan singkat tidak membutuhkan task. Pekerjaan sedang–berat dengan beberapa tahap, penelusuran, atau verifikasi lebih luas wajib checklist; tugas ringan yang berkembang mengikuti aturan ini sebelum dilanjutkan.
- Setiap pekerjaan/perubahan selesai tetap mendapat log baru, termasuk tugas ringan. Folder log bertambah, sedangkan berkas log yang sudah dibuat tetap tidak dapat diedit/dihapus agen.
- Dokumen dapat diperbarui, kecuali log dan task selesai/ditutup. Task aktif dapat diedit; penutupan pekerjaan belum selesai memerlukan arahan pengguna dan tidak boleh mencentang bagian yang belum selesai.
- Setiap pekerjaan selesai harus memeriksa relevansi knowledge; perubahan hanya dilakukan bila pengetahuan proyek berubah. Knowledge dan petanya tidak memerlukan pembaruan untuk tugas ini.

## Verifikasi
- Empat versi diperiksa: aturan task per chat sudah tidak ada; aturan kompleksitas, tugas ringan, dan penutupan tersedia serta selaras.
- `git diff --check` tidak melaporkan kesalahan spasi; peringatan LF/CRLF berasal dari overview yang sudah berubah sebelumnya. Berkas skill belum dilacak Git akibat penggantian nama sebelumnya, sehingga aturan juga diperiksa langsung.
- Tidak ada task baru karena pekerjaan ini ringan. Tidak ada pengujian kode atau commit.
