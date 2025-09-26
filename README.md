# EDA-Amazon-Sales-Product
📊 Analisis Data Eksplorasi (EDA): Dataset Penjualan Amazon
📝 Deskripsi Singkat
Proyek ini bertujuan untuk melakukan Analisis Data Eksplorasi (EDA) pada dataset penjualan produk di Amazon. Tujuannya adalah untuk menemukan pola dan wawasan kunci terkait kategori produk, harga, diskon, dan rating pelanggan. Analisis ini merupakan proyek akhir untuk bulan pertama dalam program belajar mandiri Data Science.

💾 Dataset
Dataset yang digunakan adalah "Amazon Sales Dataset" yang tersedia di Kaggle. Dataset ini awalnya terdiri dari 1465 baris dan 16 kolom. Setelah proses pembersihan data, dataset final yang digunakan untuk analisis terdiri dari 1462 baris dan 14 kolom.

Sumber: https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset (<-- Ganti dengan link yang benar jika berbeda)

🛠️ Tools yang Digunakan
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Jupyter Notebook

⚙️ Alur Kerja Analisis
Proyek ini mengikuti langkah-langkah standar dalam proses analisis data:

1. Data Cleaning: Memperbaiki tipe data yang tidak sesuai (misalnya, harga dan rating yang terbaca sebagai teks), menangani nilai yang hilang (null values), menghilangkan data yang tidak valid, dan menghapus kolom-kolom yang tidak relevan (img_link, product_link).

2. Exploratory Data Analysis (EDA): Menjawab pertanyaan-pertanyaan kunci yang telah dirumuskan melalui analisis univariat dan    bivariat.

Interpretasi & Kesimpulan: Menarik kesimpulan dari hasil analisis dan temuan visual.

🔑 Temuan Kunci (Key Findings)
Berikut adalah beberapa wawasan utama yang ditemukan dari analisis ini:

1. Distribusi Rating Sangat Positif: Mayoritas produk dalam dataset ini memiliki rating di kisaran 4.0 hingga 4.5, menunjukkan bahwa data cenderung berisi produk-produk yang disukai pelanggan.

2. Kategori Produk Dominan: Kategori Computers & Accessories (dan berbagai sub-kategorinya) adalah yang paling banyak muncul dalam dataset, menandakan popularitasnya.

3. Korelasi Diskon & Rating Lemah: Tidak ditemukan adanya korelasi yang signifikan antara besaran persentase diskon dengan rating yang diberikan pelanggan (skor korelasi ~ -0.1). Hal ini menunjukkan bahwa diskon besar tidak secara langsung menjamin rating yang lebih tinggi atau lebih rendah.

4. Popularitas Produk: Berdasarkan jumlah rating, produk 'Sounce Bluetooth Wireless...' ' adalah yang paling populer di kalangan pelanggan dalam dataset ini.

💡 Kesimpulan
Analisis ini berhasil mengidentifikasi karakteristik utama dari dataset penjualan Amazon. Temuan menunjukkan bahwa dataset ini didominasi oleh produk-produk berkualitas tinggi (berdasarkan rating) dan kategori elektronik. Untuk analisis selanjutnya, bisa dilakukan penggalian lebih dalam pada data teks (seperti review_content) untuk melakukan analisis sentimen dan menemukan alasan di balik rating yang diberikan pelanggan.