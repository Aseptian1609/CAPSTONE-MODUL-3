# CAPSTONE-MODUL-3

# * ECOMMERCE CUSTOMER CHURN *

BY ADHITIA SEPTIAN 

Outline :
- Business Problem
- Data Understanding
- Data Cleaning
- Data Analysis
- Data Preprocessing and Feature Engineering
- Modeling
- Conclusion and Recommendation

Business Problem 

Latar Belakang 
Customer churn atau tingkat keluar pelanggan adalah salah satu indikator kunci dari kesuksesan bisnis 
ecommerce. Tingkat keluar pelanggan yang tinggi dapat mengakibatkan kerugian finansial yang signifikan 
dan mengurangi citra merek.

Sebuah ecommerce customer churn bertujuan untuk menganalisis perilaku pelanggan dan mengidentifikasi 
faktor-faktor yang menyebabkan mereka meninggalkan layanan atau toko online. Berikut adalah beberapa 
langkah yang dapat Anda ikuti dalam menjalankan proyek ecommerce customer churn.

Siapa saja yang mengalami Customer Churn

Semua pelaku bisnis ecommerce

Problem Statement

Pelanggan meninggalkan atau menghentikan hubungan mereka dengan bisnis ecommerce, yang mengakibatkan
hilangnya pendapatan dan pada akhirnya menurunnya pertumbuhan bisnis. 
Faktor yang berkontribusi terhadap keputusan pelanggan untuk meninggalkan adalah pelayanan pelanggan 
yang buruk, kualitas produk yang rendah, harga yang tinggi, opsi pengiriman yang tidak nyaman atau 
tidak dapat diandalkan, dan persaingan dari bisnis ecommerce lainnya.

Goals 
Untuk meningkatkan retensi pelanggan dan mengurangi kehilangan pelanggan dalam bisnis ecommerce, 
sehingga bisnis dapat tumbuh dan berkembang dengan baik dalam jangka panjang. Dan juga untuk memahami 
penyebab churn atau kehilangan pelanggan dalam bisnis ecommerce dan menemukan cara untuk mengurangi 
tingkat churn tersebut.

Analytic Approach
Pendekatan analitik yang dilakukan berupa pembuatan, evaluasi, dan implementasi model machine learning 
klasifikasi yang dapat memprediksi apabila pelanggan akan *churn* atau tidak berdasarkan riwayat data 
sebelumnya. 

Metric Evaluation
|       | N-Prediction| P-Prediction |
| --- | --- | --- |
| **N-Actual**     | True Positive | False Positive |
| **P-Actual**      | False Negative | True Positive |

Target :  
0 : Pelanggan tidak Churn  
1 : Pelanggan Churn

Type 1 error : False Positive  
Konsekuensi: Biaya penawaran khusus yang dikeluarkan oleh perusahaan menjadi sia-sia.

Type 2 error : False Negative  
Konsekuensi: Pelanggan melakukan Churn dan tidak lagi menggunakan layanan perusahaan.

Berdasarkan konsekuensinya, langkah yang tepat untuk pemilihan model adalah model yang mengurangi 
hilangnya pelanggan loyal, tetapi tetap memperhatikan pengeluaran biaya pemasaran untuk pelanggan
yang kurang tepat. Recall dan precision yang diseimbangkan dari kelas positif (Pelanggan *churn*). 
Metrik yang akan digunakan adalah F1 Score. 


