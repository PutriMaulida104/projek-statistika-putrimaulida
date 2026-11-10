# Milestone 1 - Exploratory Data Analysis (EDA)

## 1. Deskripsi Proyek
Proyek ini merupakan tugas Milestone 1 mata kuliah Statistika yang bertujuan untuk melakukan Exploratory Data Analysis (EDA) terhadap dataset Medical Cost Personal. Analisis dilakukan untuk memahami karakteristik data dan mengetahui hubungan antara beberapa variabel dengan biaya asuransi kesehatan.

## 2. Dataset
- **Nama Dataset:** Medical Cost Personal Dataset
- **Sumber:** [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Nama File:** insurance.csv
- **Jumlah Data Awal:** 1.338 baris
- **Jumlah Kolom:** 7 kolom
- **Jumlah Data Setelah Pembersihan:** 1.337 baris

## 3. Variabel Dataset
| Variabel | Keterangan |
|---|---|
| age | Usia peserta asuransi |
| sex | Jenis kelamin |
| bmi | Indeks massa tubuh |
| children | Jumlah anak |
| smoker | Status merokok |
| region | Wilayah tempat tinggal |
| charges | Biaya asuransi |

## 4. Metode Analisis
Analisis dilakukan melalui beberapa tahapan:
1. Memuat dataset.
2. Memeriksa missing value dan data duplikat.
3. Menghitung ukuran pemusatan data (mean, median, dan modus).
4. Menghitung ukuran penyebaran data (standar deviasi, varians, IQR, dan CV).
5. Membuat visualisasi univariat.
6. Membuat visualisasi bivariat.
7. Menyusun insight dan hipotesis.

## 5. Visualisasi
Visualisasi yang digunakan meliputi:
- Histogram distribusi usia (age).
- Histogram distribusi BMI.
- Histogram distribusi biaya asuransi (charges).
- Scatter plot hubungan age dan charges.
- Scatter plot hubungan BMI dan charges.
- Box plot perbandingan charges berdasarkan status merokok.
- Interactive Plotly Dashboard dengan dua grafik interaktif.

## 6. Hasil Insight
1. Dataset awal memiliki 1.338 baris dan ditemukan satu data duplikat yang dihapus sehingga tersisa 1.337 baris.
2. Variabel charges memiliki distribusi menceng ke kanan (right-skewed).
3. Age memiliki korelasi positif lemah dengan charges sebesar 0,298.
4. BMI memiliki korelasi positif sangat lemah dengan charges sebesar 0,198.
5. Kelompok perokok memiliki rata-rata biaya asuransi lebih tinggi dibandingkan kelompok bukan perokok.

## 7. Hipotesis untuk Milestone 2
1. Terdapat perbedaan biaya asuransi yang signifikan antara peserta perokok dan bukan perokok.
2. Terdapat hubungan antara usia dan biaya asuransi.
3. Terdapat hubungan antara BMI dan biaya asuransi.

## 8. Tools yang Digunakan
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Plotly
- GitHub

## 9. File Repository
- `Milestone_1_Medical_Cost_EDA.ipynb` — Notebook analisis EDA.
- `insurance.csv` — Dataset yang digunakan.
- `README.md` — Dokumentasi proyek.
