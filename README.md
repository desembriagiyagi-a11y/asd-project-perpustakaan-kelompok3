# Sistem Perpustakaan Mini

Proyek Semester 3 Mata Kuliah Algoritma dan Struktur Data — Tahap 1: Array & Struct.

## Nama & NIM Anggota

Ganti placeholder di bawah ini dengan data anggota kelompok sebelum mengumpulkan:

| No. | Nama | NIM |
| --- | --- | --- |
| 1 | Nama Anggota 1 | NIM Anggota 1 |
| 2 | Nama Anggota 2 | NIM Anggota 2 |
| 3 | Nama Anggota 3 | NIM Anggota 3 |

## Deskripsi Sistem

Sistem Perpustakaan Mini adalah aplikasi berbasis terminal untuk mengelola koleksi buku. Data buku disimpan selama program berjalan dalam `koleksi_buku`, sebuah list of dictionary yang menerapkan konsep array of struct. Setiap buku memiliki kode, judul, pengarang, genre, tahun terbit, dan status.

Aplikasi menggunakan Python 3 dan hanya pustaka standar Python. Data tidak disimpan secara permanen; koleksi akan kosong kembali setelah program ditutup.

## Cara Menjalankan

1. Pastikan Python 3 terpasang.
2. Buka terminal pada folder proyek.
3. Jalankan:

   ```bash
   python main.py
   ```

   Pada sebagian sistem, gunakan `python3 main.py`.
4. Pilih menu dengan memasukkan angka 0 sampai 6.

## Daftar Fitur

1. **Tambah buku** — memvalidasi kode unik, kolom wajib, dan tahun terbit bulat positif sampai 2026. Buku baru berstatus `Tersedia`.
2. **Tampilkan semua buku** — menampilkan tabel dan jumlah buku tersedia/dipinjam, termasuk pesan ketika koleksi kosong.
3. **Cari buku** — pencarian kode (exact match, tidak membedakan kapital) atau judul (partial match, tidak membedakan kapital).
4. **Update status buku** — mengganti status `Tersedia` dan `Dipinjam` setelah konfirmasi petugas.
5. **Filter genre** — menyaring buku menggunakan sebagian teks genre tanpa membedakan kapital.
6. **Hapus buku** — buku berstatus `Dipinjam` ditolak; buku `Tersedia` memerlukan konfirmasi.
0. **Keluar** — menutup program.

## Pembagian Tugas

Sesuaikan pembagian berikut dengan anggota kelompok:

| Anggota | Tanggung jawab |
| --- | --- |
| Anggota 1 | Perancangan struktur data dan fitur tambah/tampilkan buku |
| Anggota 2 | Fitur pencarian dan filter genre |
| Anggota 3 | Fitur update status, penghapusan, dan pengujian |
| Seluruh anggota | Integrasi modul, dokumentasi, dan presentasi |

