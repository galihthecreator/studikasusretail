# Retail Java Analysis

Analisis tren retail di 5 provinsi Pulau Jawa menggunakan data penjualan retail tahun 2019.

## Dataset
- Sumber:
https://storage.googleapis.com/dqlab-dataset/10%25_original_randomstate%3D42/retail_data_from_1_until_3_reduce.csv
https://storage.googleapis.com/dqlab-dataset/10%25_original_randomstate%3D42/retail_data_from_4_until_6_reduce.csv
https://storage.googleapis.com/dqlab-dataset/10%25_original_randomstate%3D42/retail_data_from_7_until_9_reduce.csv
https://storage.googleapis.com/dqlab-dataset/10%25_original_randomstate%3D42/retail_data_from_10_until_12_reduce.csv

- Data mencakup transaksi retail dari bulan Januari hingga Desember.

## Analisis yang Dilakukan
- Data cleaning: menghapus harga minus dan order_id tidak valid.
- Data filtering: hanya provinsi di Pulau Jawa.
- Grouping dan aggregation: per tanggal dan provinsi.
- Visualisasi: tren order, customer, product, brand, dan GMV bulanan.

## Tools
- Python
- Pandas
- Matplotlib