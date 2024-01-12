# Proyeksi Analisis Data Penjualan Ratu Frozen

## Informasi Umum

**Nama Toko**: Ratu Frozen

**Alamat Toko** : Jl. Semen Kujang perumahan Pesona Kahuripan 3 Tahap 4 Jl. Anggrek 10 Blok i7-02 Desa. Cikahuripan, Kec. Klapanunggal, Kab. Bogor

**Email**: ratufrozenofficial@gmail.com

## Deskripsi Proyek
Projek ini berfokus pada analisis data penjualan frozen food di desa Cikahuripan untuk mendapatkan wawasan mengenai pola dan tren penjualan frozen food berdasarkan minat beli frozen, harga, tiap bulan serta minat beli berdasarkan jenis frozennya. tiga dataset utama yang digunakan adalah `product_dataset_ratufrozen.csv`,`stock_dataset_ratufrozen.csv` dan `sales_dataset_ratufrozen.csv`, yang berisi data penjualan.

## Pertanyaan Bisnis

1. Apakah trend penjualan frozen food dalam sebulan? dibulan manakah tren yang lebih tinggi?
2. Berapakah revenue yang didapat tiap bulannya? dibulan manakah tren yang lebih tinggi
3. Jenis frozen apakah yang banyak dicari dan diminati oleh pelanggan tiap bulannya?

## Analisis Data

Analisis data dilakukan dengan menggunakan Python dan berbagai library seperti pandas, matplotlib, dan seaborn. Proses analisis meliputi eksplorasi data, visualisasi, dan interpretasi hasil untuk menjawab pertanyaan bisnis.

## Dashboard

Dashboard interaktif dibuat dengan menggunakan Streamlit untuk memvisualisasikan hasil analisis data secara interaktif. Dashboard dapat diakses ....

## Setup Environment
Anda perlu membuat environment khusus menggunakan Conda dan menginstall dependensi yang diperlukan. Ikuti langkah-langkah berikut:
```sh
conda create --name main-ds python=3.11
conda activate main-ds
pip install streamlit pandas numpy matplotlib seaborn
```
## Run steamlit app
```
streamlit run dashboard_ratu_frozen.py
```
