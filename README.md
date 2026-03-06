# SIA-AI-POS-Fadhil
# Sistem POS Syariah

## Deskripsi Sistem
Sistem POS (Point of Sale) Syariah merupakan sistem kasir digital yang digunakan untuk mencatat transaksi penjualan secara otomatis dan transparan. Sistem ini membantu kasir dalam menghitung total harga, mengecek stok barang, serta menyimpan data transaksi secara real-time.

## Tujuan Sistem
Sistem ini dibuat untuk:
- Mengurangi kesalahan perhitungan manual oleh kasir
- Meningkatkan transparansi transaksi
- Memastikan pencatatan transaksi yang akurat
- Mendukung prinsip kejujuran dalam transaksi sesuai nilai syariah

## Flowchart Proses Transaksi POS
graph TD
A[Kasir memilih produk] --> B{Cek stok barang}
B -- Stok tersedia --> C[Hitung total harga]
B -- Stok habis --> D[Tampilkan notifikasi stok habis]
C --> E[Proses pembayaran]
E --> F[Simpan transaksi ke database]
F --> G[Cetak struk]
## Problem Statement

Pada sistem kasir manual sering terjadi beberapa permasalahan yang dapat merugikan penjual maupun pembeli. Beberapa risiko yang dapat terjadi antara lain:

1. Human Error
Kasir dapat melakukan kesalahan dalam menghitung total harga barang secara manual sehingga jumlah pembayaran tidak akurat.

2. Ketidaksesuaian Stok Barang
Barang yang terjual tidak selalu tercatat dengan baik sehingga stok di gudang tidak sesuai dengan kondisi sebenarnya.

3. Potensi Kecurangan Transaksi
Pada sistem manual terdapat kemungkinan manipulasi transaksi karena tidak adanya sistem pencatatan yang transparan.

## Solusi Sistem POS

Untuk mengatasi permasalahan tersebut, sistem POS berbasis digital digunakan untuk:

- Menghitung total harga secara otomatis
- Mengupdate stok barang secara real-time
- Menyimpan seluruh transaksi ke dalam database
- Menyediakan audit transaksi untuk meningkatkan transparansi
