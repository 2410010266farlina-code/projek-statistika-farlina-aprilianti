
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

## Milestone 2 - Hypothesis Testing

Pada Milestone 2 dilakukan pengujian statistik menggunakan
dataset Google Play Store untuk mengetahui hubungan dan
perbedaan antarvariabel.

### 1. Confidence Interval
Menghitung Confidence Interval 95% untuk rata-rata
Rating aplikasi yang valid.

### 2. Hypothesis Testing

**Hipotesis 1: Reviews dan Installs**
- Metode: Pearson Correlation
- Tujuan: Menguji hubungan jumlah ulasan dan instalasi aplikasi.

**Hipotesis 2: Rating aplikasi gratis dan berbayar**
- Metode: Welch's Independent Samples t-test
- Tujuan: Menguji perbedaan rata-rata rating kedua kelompok.

**Hipotesis 3: Rating dan Installs**
- Metode: Pearson Correlation
- Tujuan: Menguji hubungan rating dan jumlah instalasi.

### 3. Evaluasi Statistik
Analisis mencakup:
- Confidence Interval 95%
- Pengujian asumsi
- Statistik uji dan p-value
- Effect size
- Kesimpulan statistik dan interpretasi bisnis

### 4. Tools
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Google Colab

## Milestone 3 - Sampling Distribution, Bootstrap, and Power Analysis

Milestone 3 berfokus pada analisis distribusi sampling,
perbandingan Confidence Interval, dan Power Analysis
menggunakan dataset Google Play Store.

### 1. Sampling Distribution
Menganalisis distribusi rata-rata Rating dengan ukuran sampel:
- 30
- 300
- 3000

Membandingkan Standard Error empiris dan teoritis.

### 2. Confidence Interval: Rumus vs Bootstrap
Membandingkan CI 95% selisih rata-rata Rating aplikasi
Free dan Paid menggunakan metode Welch dan Bootstrap.

### 3. Power Analysis
Menentukan kebutuhan ukuran sampel berdasarkan:
- MDE: 0.1 poin Rating
- Alpha: 0.05
- Statistical Power: 0.80

### 4. Rekomendasi Ship or Not
Menentukan rekomendasi berdasarkan posisi CI terhadap
nilai 0 dan batas MDE.

### 5. Tools
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Statsmodels
- Google Colab

## Penutup

Melalui proyek ini, dilakukan eksplorasi data untuk memperoleh pemahaman mengenai karakteristik aplikasi Google Play Store. Hasil analisis diharapkan dapat menjadi dasar untuk pengujian hipotesis pada Milestone 2.


