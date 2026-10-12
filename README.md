# UTS Pengkodean

## Voucher Entri Transaksi Kas Keluar

**Nama:** Budi Austiano Darmadji  
**NIM:** 12030124140215  
**Kelas:** E   
**Mata Kuliah:** Pengkodean

## Deskripsi Proyek
Purwarupa aplikasi web Voucher Entri Transaksi Kas Keluar untuk membantu pencatatan transaksi akuntansi secara terstruktur dan menerapkan prinsip pencatatan jurnal berpasangan (*double-entry accounting*).

## Fitur
- Input nomor voucher, tanggal, penerima pembayaran, metode pembayaran, dan keterangan.
- Penambahan dan penghapusan baris jurnal.
- Pemilihan akun dari daftar akun contoh.
- Perhitungan total debit dan kredit secara otomatis.
- Indikator keseimbangan jurnal.
- Validasi nominal dan keseimbangan sebelum posting.
- Simulasi penyimpanan draft/posting pada browser.

## Teknologi
- HTML5
- CSS
- Vanilla JavaScript

## Daftar File
- `README.md`: dokumentasi proyek.
- `prompt_log.md`: dokumentasi prompt untuk Gemini Canvas.
- `voucher_entri_kas_keluar.html`: purwarupa web.

## Cara Menjalankan
1. Buka `voucher_entri_kas_keluar.html` di browser seperti Google Chrome.
2. Isi informasi voucher dan rincian jurnal.
3. Uji jurnal seimbang dan tidak seimbang.
4. Gunakan tombol Simpan Draft atau Submit/Post untuk menguji interaksi.

## Catatan Implementasi
File HTML ini merupakan purwarupa mandiri dengan data akun contoh dan simulasi pada sisi browser. Koneksi Supabase/PostgreSQL belum diimplementasikan dalam file ini, sehingga transaksi belum tersimpan permanen ke database. Fitur ini tidak boleh dianggap sebagai sistem produksi.
