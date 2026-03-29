# Tugas Metode Potensial: Analisis Gravitasi Tampomas

Proyek ini bertujuan untuk melakukan pemrosesan data gravitasi dari data mentah Jawa Barat hingga menghasilkan peta Anomali Free-Air dan Anomali Bouguer Sederhana (ABS) di wilayah Gunung Tampomas.

## Struktur Folder
- `data/data_mentah/`: Berisi file `jawabarat.dg`.
- `data/data_proses/`: Berisi hasil parsing (.csv) dan hasil gridding (.nc).
- `notebook/`: Berisi langkah-langkah pengerjaan:
  1. `1_parsing.ipynb`: Pemotongan data.
  2. `2_gridding.ipynb`: Interpolasi data ke grid UTM.
  3. `3_abs.ipynb`: Perhitungan Anomali Bouguer.
  4. `4_overlay.ipynb`: Visualisasi akhir dengan peta dasar.

## Cara Menjalankan
1. Pastikan environment `metodepotensial` sudah aktif.
2. Jalankan notebook secara berurutan dari nomor 1 sampai 4.
