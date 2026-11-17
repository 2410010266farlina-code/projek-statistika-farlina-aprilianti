
# Analisis Statistik Deskriptif dan Exploratory Data Analysis (EDA) Google Play Store Apps

## Deskripsi Proyek

Proyek ini merupakan tugas praktikum Statistika yang bertujuan untuk melakukan analisis statistik deskriptif dan Exploratory Data Analysis (EDA) pada dataset Google Play Store Apps.

Analisis dilakukan menggunakan Python untuk memahami karakteristik data aplikasi, melihat distribusi data, mengetahui hubungan antarvariabel, serta menemukan informasi dan pola yang terdapat dalam dataset.

## Identitas

- **Nama:** Farlina Aprilianti
- **NIM:** 2410010266
- **Mata Kuliah:** Statistik dan Probabilitas

## Dataset

Dataset yang digunakan adalah Google Play Store Apps yang diperoleh dari Kaggle.

- **Sumber:** Kaggle
- **Nama Dataset:** Google Play Store Apps
- **Link Dataset:** https://www.kaggle.com/datasets/lava18/google-play-store-apps
- **Jumlah Data:** 10.841 baris
- **Jumlah Kolom:** 13 kolom

Dataset berisi informasi aplikasi Google Play Store, seperti nama aplikasi, kategori, rating, jumlah ulasan, ukuran aplikasi, jumlah instalasi, tipe aplikasi, harga, dan informasi lainnya.

## Tools dan Library

Proyek ini menggunakan beberapa tools dan library berikut:

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Tahapan Analisis

Analisis dilakukan melalui beberapa tahapan:

1. Load Dataset
2. Missing Values dan Duplicate Check
3. Central Tendency (Mean, Median, dan Modus)
4. Dispersion (Variance, Standard Deviation, IQR, dan CV)
5. Univariate Visualization
6. Bivariate Visualization
7. Plotly Interactive Dashboard
8. EDA Insights
9. Penyusunan Hipotesis untuk Milestone 2

## Ringkasan Hasil EDA

Berdasarkan analisis awal yang dilakukan, diperoleh beberapa temuan:

1. Dataset memiliki 10.841 baris dan 13 kolom, dengan 1.487 nilai kosong dan 483 data duplikat.
2. Rata-rata rating aplikasi adalah sekitar 4,19 dengan median 4,3.
3. Jumlah ulasan memiliki distribusi yang tidak merata, dengan rata-rata sekitar 444.152 dan median 2.094.
4. Jumlah instalasi memiliki variasi yang tinggi, dengan rata-rata sekitar 15,46 juta dan median 100 ribu.
5. Aplikasi gratis mendominasi dataset berdasarkan nilai median dan modus harga sebesar 0.

## Cara Menjalankan

1. Unduh atau clone repository ini.
2. Buka Google Colab melalui https://colab.research.google.com/
3. Upload notebook proyek ke Google Colab.
4. Upload file dataset `googleplaystore.csv`.
5. Jalankan setiap cell notebook secara berurutan dari awal hingga akhir.

## Hipotesis untuk Milestone 2

Beberapa hipotesis yang akan diuji pada tahap berikutnya:

1. Hubungan antara jumlah Reviews dan Installs.
2. Perbedaan rata-rata Rating antara aplikasi gratis dan berbayar.
3. Hubungan antara Rating dan Installs.

## Penutup

Melalui proyek ini, dilakukan eksplorasi data untuk memperoleh pemahaman mengenai karakteristik aplikasi Google Play Store. Hasil analisis diharapkan dapat menjadi dasar untuk pengujian hipotesis pada Milestone 2.
