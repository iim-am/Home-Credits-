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
ini merupakan proyek saya yang berisi laporan proyek untuk kompetisi Grupo Bimbo Inventory Demand Kaggle.
Tujuan dari proyek ini adalah untuk mengembangkan model yang dapat memperkirakan permintaan persediaan untuk Grupo dengan sangat akurat
Produk Bimbo didasarkan pada data penjualan historis.
#### Data dan informasi  kompetisi
Semua informasi dan data dapat diperoleh dari halaman web kompetisi Kaggle:
https://www.kaggle.com/c/grupo-bimbo-inventory-demand

#### iPython Notebooks
1. exploratory analysis: 
   - Explore produk dan data klien.
   - Menemukan fitur baru yang dapat dihasilkan dari variabel NombreProducto dan NombreCliente.
   
2. feature engineering:
   - Mengambil temuan dari explore analisis kemudian membuat produk baru dan dataset klien dengan fitur tambahan.

3. build:
   - menjalankan data train, test kemudian memodifikasi data klien dan data products.
   - Menggabungkan data klien dan produk yang dimodifikasi menjadi data train dan data test.
   - Menambahkan time series demand feature.
   - Menambahkan rata - rata frekuensi fitur ID.
   - Membuat kode variabel kategori.
   - Menghapus data sebelum minggu ke 6.
   - Menulis data train dan test yang dimodifikasi ke CSV.

4. predict: 
   - cocokan dengan model XGBOOST untuk data train.
   - validasi result model pada subset data train.
   - Generates results untuk data test.

5. free-form-visualization:
   - Gunakan Matplotlib untuk merencanakan penjualan mingguan dari 4 produk terlaris teratas di data kereta.
