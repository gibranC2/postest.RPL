# Sistem Manajemen Penjualan Toko Barang Antik

## 1. Diagram Konteks
Diagram ini menunjukkan hubungan antara sistem dengan entitas luar seperti Pelanggan, Admin, dan Pemasok.

![Diagram Konteks](diagram_konteks.png)

## 2. DFD Level 0
DFD Level 0 merinci proses utama dalam sistem:
- **Pengelolaan Data Barang** (berhubungan dengan Admin dan Pemasok)
- **Pengelolaan Transaksi Penjualan** (berhubungan dengan Pelanggan)
- **Pengelolaan Pengguna** (berhubungan dengan Admin)

![DFD Level 0](dfd_level_0.png)

## 3. DFD Level 1
DFD Level 1 merinci setiap proses utama dari DFD Level 0 menjadi beberapa sub-proses:

### Pengelolaan Data Barang
- 1.1 Menambah Data Barang
- 1.2 Mengupdate Data Barang
- 1.3 Menghapus Data Barang
- 1.4 Melihat Data Barang

### Pengelolaan Transaksi Penjualan
- 2.1 Memproses Pembelian
- 2.2 Menghitung Total Transaksi
- 2.3 Mencetak Nota Pembelian

### Pengelolaan Pengguna
- 3.1 Registrasi Pengguna
- 3.2 Login Pengguna
- 3.3 Manajemen Hak Akses

![DFD Level 1](dfd_level_1.png)

## 4. Perbaikan Duplikasi Data Store
Pada DFD sebelumnya, terdapat duplikasi data store "Kamar". Perbaikan telah dilakukan dengan:
- Menghilangkan duplikasi yang tidak perlu.
- Menyederhanakan alur data agar lebih jelas.
- Memastikan hubungan antar proses tetap sesuai.

![Perbaikan DFD](dfd_perbaikan.png)

## 5. File yang Disertakan
Berikut adalah file yang disertakan dalam repository GitHub:
- `diagram_konteks.png` - Diagram Konteks
- `dfd_level_0.png` - DFD Level 0
- `dfd_level_1.png` - DFD Level 1
- `dfd_perbaikan.png` - Perbaikan DFD
- `README.md` - Dokumentasi proyek

---

