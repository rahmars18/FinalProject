# Online Shoppers Purchasing Intention

## Overview 

### Problem
Penggunaan e-commerce mengalami peningkatan dalam beberapa tahun terakhir. Di web perusahaan jumlah pengunjung banyak namun sedikit yang berakhir melakukan transaksi, hanya sekitar 15% saja user yang melakukan transaksi dari semua user yang mengunjungi web. Untuk tetap bertahan di era yang sangat kompetitif ini perusahaan harus dapat menganalisa pola-pola ketertarikan dan perilaku customer dalam berbelanja. Hal tersebut perlu dilakukan karena dapat mempengaruhi nilai revenue perusahaan kedepannya.

### Goals dan Objective
- Memprediksi user yang dapat menghasilkan revenue / potential user
- Menentukan fitur apa yang paling mempengaruhi suatu user untuk melakukan transaksi
- Memberikan hasil Analisa kepada tim bisnis, agar mereka dapat membuat keputusan terbaik bagaimana cara meningkatkan jumlah user yang melakukan transaksi
- Membuat model Machine Learning yang dapat memprediksi user yang memiliki potensi untuk melakukan transaksi, dengan cara membuat segmentasi user mendetail seperti '‘Transaksi', ‘Rencana Membeli', dan ‘Menjelajah'.  Segmentasi ini diharapkan menjadi bahan pertimbangan tim business agar lebih efektif dan efisien. 

### Data

Data dapat dilihat pada `Data/online_shoppers_intention.csv` <br>


Dataset Online Shoppers Purchasing Intention terdiri dari 18 features yang dikelompokan berdasarkan tipe data nya : <br>

| **Numerical data**     | **Categorical data**|
|----------------------- |------------- |
|Administrative | OperatingSystems|
|Administrative_Duration | Browser|
|Informational | Region|
|Informational_Duration | TrafficType|
|ProductRelated | Month|
|ProductRelated_Duration | VisitorType|
|BounceRates | Weekend |
|ExitRates | Revenue|
|PageValues |
|SpecialDay |

Selengkapnya tentang data [here](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset)

## EDA Summary Insight
1. Metode yang digunakan saat ini belum tepat untuk menghasilkan revenue, hal ini tampil dari data bahwa banyaknya jumlah visitor tidak berakhir dengan revenue.
2. Karena jumlah visitor banyak di weekdays, maka program-program dapat diarahkan di hari-hari weekdays.
3. Jumlah new visitor sangat rendah dibandingkan returning, ini mengindikasikan kemungkinan website ini belum cukup dikenal. Karena dengan nilai returning tinggi, maka visitor yang pernah mengunjungi ada kemungkinan kembali datang.Perlu meningkatkan jumlah visitor baru salah satunya dengan cara branding yang lebih luas.
4. Traffic Type , browser dan operating sistem yang digunakan mengerucut pada 2 sampai 3 jenis saja. Perlu dijajaki kemungkinan kerjasama dengan beberapa jenis browser ini saja. Supaya usaha tepat sasaran.

5. Ada bulan-bulan dengan visitor tinggi, perlu dianalisa ada event khususkah selama itu atau ada promo atau materi yang berbeda di momen-momen ini. 




