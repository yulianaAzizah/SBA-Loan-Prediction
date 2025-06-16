# SBA-Loan-Prediction

## BUSINESS BACKGROUND

Small Business Administration (SBA) adalah lembaga yang didirikan di Amerika Serikat pada tahun 1953 untuk mendukung pemilik usaha kecil dan wirausahawan. SBA memberikan layanan berupa pendampingan, pembiayaan, dan dukungan kontrak khusus bagi usaha kecil.

Selama krisis keuangan global 2008, SBA mengalami kerugian besar akibat tingginya gagal bayar pada pinjaman yang dijaminnya. 

Dalam 10 tahun terakhir, sekitar 24,7% pinjaman tidak dilunasi, dengan audit OIG pada 2008 mencatat kerugian SBA sebesar $329 juta.

## PROBLEM STATEMENT
Questions to be answered in this project include:
1.	Bagaimana membangun model klasifikasi risiko default pinjaman yang akurat?
2.	Faktor apa saja yang paling mempengaruhi klasifiaksi lancar/tidak lancar pembayaran pinjaman?
3.	Berapa besar potensial benefit implementasi model? 

## DATA INFORMATION
Dataset  yang digunakan bersumber dari Kaggle. 
Berdasarkan Riwayat Transaksi dari Tahun 1962 - 2014.

Total Data points : 899.164 dengan 27 feature input
Machine Learning Category : Supervised Learning, Target : MIS Status

Setelah dilakukan analisis Feature Selection, 20 Feature akan diterapkan pada model:

## METRIC EVALUATION
Fokus utamanya meminimalkan kesalahan False Negative dan False Positive, karena keduanya dapat berdampak serius bagi bank.

- False Negative (FN): berbahaya bagi bank karena berpotensi menyebabkan kerugian finansial langsung (default)
- False Positive (FP): Bank kehilangan peluang mendapatkan profit dari nasabah yang seharusnya baik, tapi tidak mengalami kerugian langsung.

## RESULT
1.	Hasil Machine Learning:
    Model XGBoost menunjukkan performa terbaik
  	Model mampu memprediksi 96% dari total transaksi secara akurat

2. Faktor yang paling mempengaruhi klasifikasi lancar/tidak lancar pembayaran pinjaman adalah Term (jangka waktu peminjaman)
3. Jika model ini diterapkan SBA setidaknya dapat meningkatkan economic benefit sebesar $ 10.720.399 
