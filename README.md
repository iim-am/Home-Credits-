# DATA SCIENCE PORTOFOLIO

Repository ini berisi portofolio proyek data science yang saya buat. Semua pengerjaan dibuat dalam bentuk iPython. 

### Database SQL
- [Database classicmodels – Exploratory Analysis](https://github.com/iim-am/Portofolio/blob/master/SQL/Tugas%20Classic%20Models.txt): Menganalisis dan mengexplore data dari Classic Models menggunakan Query SQL seperti menghitung komisi untuk setiap perwakilan penjualan dengan asumsi komisi 5% dari nilai pesanan, menghitung waktu rata-rata antarantanggal pesanan dan tanggal pengiriman untuk setiap pelanggan yang dipesan dengan selisih terbesar dan menghitung laba yang dihasilkan oleh setiap pelanggan berdasarkan pesanan mereka.

### 	Statistik
- [Iris dataset](https://github.com/iim-am/Portofolio/blob/master/Statistik/statistik_Data_Iris-checkpoint.ipynb): Mengexplore dan menganalisis berdasarkan output statistik seperti Count, Mean, Median, Standar Deviasi, Min, Max , Quartile serta visualisasi yang ditampilkan dengan boxplot sehingga dapat diketahui  ukuran tendensi sentral dan ukuran penyebaran (keragaman) data pengamatan. Selain itu dengan visualisai ini juga bisa melihat outlier dari sebaran data tersebut. Sedangkan untuk menentukan apakah hipotesis sesuai atau tidak, maka dapat menentukkannya dengan melihat keakurasian data yang sudah dimodelkan dengan Machine Learning sehingga dapat mengevaluasi keakurasian model tersebut. Dari hasil preposisi dan modeling, pada data train akurasi model berada pada angka 100% dan pada data test akurasi model menunjukkan angka 98%. Dengan perbedaan akurasi yang cenderung tidak signifikan, bisa dikatakan bahwa model tersebut tidak overfit. Dengan demikian, model ini bisa dikatakan model yang sudah cukup baik untuk mengklasifikasikan Dataset Iris.

### Data analysis and Visualization
- [Titanic Dataset - Analisis Eksplorasi](https://github.com/iim-am/Portofolio/blob/master/Data%20Analysis%20%26%20Visualisasi/Titanic/Titanic%20Dataset%20-%20Exploratory%20Analysis.ipynb): Analisis Eksplorasi penumpang di atas kapal RMS Titanic menggunakan Pandas dan visualisasi dengan matplotlib.<br>
- [Super Store Dataset](https://github.com/iim-am/Portofolio/blob/master/Data%20Analysis%20%26%20Visualisasi/Superstore/code%20superstore.ipynb) – menganalisis data dari super Store menggunakan pandas kemudian memvisualisasikannya dengan matplotlib sehingga didapat plot linier,scatter, barchart dan box untuk membandingkan penjualan dan keuntungan dari data superstore. <br>
- [Telco Customer Churn](https://github.com/iim-am/Portofolio/blob/master/Data%20Analysis%20%26%20Visualisasi/Telco_Customer/code%20telco%20customer.ipynb): Memprediksi perilaku untuk mempertahankan pelanggan. Menganalisis semua data pelanggan yang relevan dan mengembangkan program retensi pelanggan yang terfokus.<br>

### Machine Learning	
-  [Prediction Boston Housing Prices](https://github.com/iim-am/Portofolio/blob/master/Machine%20Learning/Boston-housing/boston_housing.ipynb) : Sebuah model untuk memprediksi nilai rumah tertentu di pasar real estat Boston menggunakan berbagai alat analisis statistik. Mengidentifikasi harga terbaik yang dapat dijual klien dengan menggunakan Machine Learning.<br>
-  [Supervised Learning: Finding donors for Charity](https://github.com/iim-am/Portofolio/blob/master/Machine%20Learning/Supervised%20Learning/finding_donors.ipynb): Menguji beberapa algoritma Superviced Learning untuk membuat model yang secara akurat memprediksi apakah seseorang menghasilkan lebih dari $50.000 untuk mengidentifikasi kemungkinan donor nirlaba fiktif<br>
-  [Unsupervised Learning: Customers Segment](https://github.com/iim-am/Portofolio/blob/master/Machine%20Learning/Unsupervised%20Learning/customer_segments.ipynb): Menganalisis dataset yang berisi data tentang berbagai jumlah pengeluaran tahunan pelanggan dari beragam kategori produk untuk menemukan struktur internal, pola, dan knowlege.<br>

## Micro Project
- Machine Learning with Logistic Regression: Menggunakan Regresi Logistik untuk memprediksi apakah pengguna internet mengklik iklan atau tidak. 
- Machine Learning with K Nearest Neighbours: Menggunakan K Nearst Neighbours untuk mengklasifikasikan beberapa contoh dari kumpulan data palsu menjadi dua kelas target, sambal memilih nilai terbaik untuk K menggunakan metode elbow. 
- Machine Learning with Decision Trees and Random Forest: Menggunakan Decision Trees dan Random Forest untuk memprediksi apakah pemberi pinjaman akan membayar kembali pinjaman mereka. Menggunakan data dari kompetisi kaggle Home Credits.
- Covid 19 in Indonesia: Menggunakan data covid 19 di indonesioa yang tersedia pada kaggle kemudian mengembangkan model regression untuk memprediksi kasus orang yang positif korona di Indonesia. Hasil darii prediksi tersebut kemudian dibandingkan dengan pengumuman setiap hari oleh mentri kesehatan. Nilai Korelasi yang diperoleh 98,99%.  
	
## Project  
#### Grupo Bimbo Inventory Demand
This repository contains my project code and project report for the Grupo Bimbo Inventory Demand Kaggle competition.
The goal of the project was to develop a model that could most accurately forecast inventory demand for Grupo
Bimbo products baed on historical sales data.
#### Competition Information and Data
All information and data can be obtained from the Kaggle competition web page:
https://www.kaggle.com/c/grupo-bimbo-inventory-demand

- #### iPython Notebooks
1. exploratory analysis: 
- Explores product and client data.
- Discovers new features that can be generated from NombreProducto and NombreCliente variables.

2. feature engineering:
- Takes the findings from the exploratory analysis and creates new product and client data sets with additional features.

3. build:
- Load train, test, and modified client and products data.
- Merges modified client and products data into train and test data.
- Adds time series demand features.
- Adds mean of frequencies of id features.
- Encodes categorical variables.
- Removes data before Week 6.
- Writes modified train and test data to CSV.

4. predict: 
- Fits an XGBOOST model to the train data.
- Validate model results on a held-out subset of the train data.
- Generates results for the test data.

5. free-form-visualization:
- Uses Matplotlib to plot weekly sales of the top 4 best-selling products in the train data. 
