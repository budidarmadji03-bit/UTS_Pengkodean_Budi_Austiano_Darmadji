# Prompt Log – Soal 3.1.a Gemini Canvas

## Tujuan
Mendokumentasikan instruksi untuk membuat purwarupa Voucher Entri Transaksi Kas Keluar.

## Prompt yang Digunakan
Buat purwarupa aplikasi web Voucher Entri Transaksi Kas Keluar yang profesional, responsif, dan mudah digunakan staf akuntansi. Gunakan HTML5, CSS, dan Vanilla JavaScript agar dapat dijalankan langsung melalui browser. Formulir harus memiliki nomor voucher, tanggal transaksi, nama penerima pembayaran, metode pembayaran, dan deskripsi. Sediakan tabel rincian jurnal dinamis dengan pemilihan akun dari chart of accounts, input debit dan kredit, serta tombol tambah dan hapus baris. Hitung total debit, total kredit, dan selisih secara otomatis setiap kali input berubah. Tampilkan indikator status SEIMBANG, BELUM SEIMBANG, atau BELUM LENGKAP. Tolak nominal negatif, akun yang belum dipilih, baris yang debit dan kreditnya sama-sama positif, serta posting ketika total debit tidak sama dengan total kredit. Sediakan tombol Simpan Draft, Submit/Post, dan Reset. Sertakan contoh jurnal seimbang dan tidak seimbang untuk pengujian. Gunakan akun contoh Kas Kecil, Bank BCA, Piutang Usaha, Persediaan, Utang Usaha, Utang Biaya Operasional, Beban Pembelian/HPP, dan Beban Operasional Lainnya. Jangan mengklaim koneksi Supabase atau penyimpanan permanen jika belum benar-benar diimplementasikan. Berikan kode lengkap dan petunjuk menjalankan aplikasi.

## Catatan Hasil
File `voucher_entri_kas_keluar.html` dalam folder ini adalah purwarupa mandiri yang dibuat untuk memudahkan pengujian awal. Jika prompt ini digunakan kembali di Gemini Canvas, simpan juga prompt dan hasil yang benar-benar digunakan saat pengerjaan.

## Skenario Pengujian
| Skenario | Hasil yang Diharapkan | Hasil Aktual |
|---|---|---|
| Debit Rp500.000 dan kredit Rp500.000 | Status SEIMBANG | Belum diuji oleh pengguna |
| Debit Rp500.000 dan kredit Rp400.000 | Status BELUM SEIMBANG | Belum diuji oleh pengguna |
| Nominal negatif | Ditolak oleh validasi | Belum diuji oleh pengguna |
| Tambah/hapus baris | Total dihitung ulang | Belum diuji oleh pengguna |
