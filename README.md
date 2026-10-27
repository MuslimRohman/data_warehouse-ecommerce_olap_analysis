# Perancangan Data Warehouse dan Data Mart untuk Analisis Penjualan E-Commerce

**Data Warehouse | ETL | Business Intelligence | OLAP**

## Deskripsi Proyek

Proyek ini bertujuan untuk membangun **Data Warehouse** menggunakan dataset **Olist E-Commerce** guna mengintegrasikan data transaksi, pelanggan, produk, pembayaran, dan pengiriman.

Pengolahan dilakukan melalui proses **Extract, Transform, Load (ETL)**, perancangan **Star Schema**, serta pengembangan **Data Mart dan OLAP Cube** menggunakan Atoti untuk mendukung analisis penjualan dan pengambilan keputusan bisnis.

## Tools & Libraries

- **Python** – Pengolahan dan integrasi data.
- **Pandas** – Data cleaning, transformasi, dan proses ETL.
- **SQLite** – Penyimpanan data hasil transformasi.
- **Atoti** – Pembuatan OLAP Cube dan analisis multidimensi.
- **SQL** – Query dan pengelolaan data.
- **Jupyter Notebook** – Pengembangan serta dokumentasi analisis.

## Tahapan Proyek

1. **Data Collection:** Menggunakan dataset Olist E-Commerce yang mencakup data pelanggan, pesanan, produk, pembayaran, dan penjual.
2. **ETL:** Melakukan ekstraksi, pembersihan, transformasi, dan penyimpanan data ke SQLite.
3. **Star Schema:** Merancang tabel fakta dan dimensi berdasarkan kebutuhan analisis.
4. **Data Mart:** Membangun Sales Mart, Product Mart, dan Logistic Mart.
5. **OLAP Cube:** Membuat custom measures dan hierarki untuk analisis multidimensi.
6. **Business Analysis:** Menganalisis pendapatan, transaksi, kategori produk, wilayah pelanggan, dan biaya pengiriman.

## Hasil Analisis

- Berhasil membangun Data Warehouse dengan tiga Data Mart.
- Mengintegrasikan data transaksi e-commerce melalui proses ETL.
- Mengimplementasikan OLAP Cube menggunakan Atoti.
- Memperoleh total revenue sebesar **13.591.643,70** dan total order sebanyak **98.666 transaksi**.
- Menghasilkan analisis multidimensi berdasarkan produk, lokasi, waktu transaksi, dan pengiriman.

## Struktur Repository

- `Datasets/` — Dataset Olist E-Commerce yang digunakan dalam proyek.
- `Code Final_Kelompok 11.ipynb` — Notebook Python berisi proses ETL, perancangan Data Warehouse, Data Mart, dan analisis OLAP.
- `Laporan Final_Kelompok 11.pdf` — Laporan akhir proyek.
- `README.md` — Dokumentasi repository.

## Anggota Tim

- **Nagatan Alief Putra Silahen**
- **Muslim Fazlur Rohman**
- **Muhammad Ramadhan Albaary Putra**
- **Kafka Praya Firmansyah**

**Program Studi Sains Data | Universitas Negeri Surabaya | 2026**
