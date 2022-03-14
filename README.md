# Telco-Customer-Churn
Ini adalah portfolio pertama saya yang berisi tentang exploratory data analysis (EDA) pada dataset Telco-Customer-Churn. Dalam portofolio ini, saya menggunakan bahasa python mulai dari data cleansing, statistical summary, univariate analysis, multivariate analysis, hingga memberikan kesimpulan menggunakan group-by aggregation terhadap dataset Telco-Customer-Churn.

## Kesimpulan
### 1. Sebaran pelanggan potensi Churn :
- Pelanggan Usia Lanjut (SeniorCitizen == 1) 476 rows
- Pelanggan yang berlangganan bulanan (COntract == Month-to-month) 1655 rows
- Pelanggan single (Partner == No) 1200 rows
- Pelanggan yang tidak memiliki tanggungan (Dependent == No) 1543 rows
- Pelanggan yang memakai layanan sambungan Fiber Optic (InternetService == Fiber optic) 1297 rows
- Pelanggan yang memakai Paperless Billing via Electronic Checking (PaperlessBilling == Yes & PaymentMethod == Electronic Checking) 867 rows
- Pelanggan yang tidak memakai Paperless Billing via Electronic Checking (PaperlessBilling == No & PaymentMethod == Electronic checking) 204 rows
- Pelanggan yang berlangganan dengan tenor +-17 bulan atau 1-1,5 tahun (avg_tenure == 17.98)
### 3 feature yang harus dievaluasi terlebih dahulu supaya potensi Churn Yes bisa berkurang secara signifikan :
- Pelanggan yang berlangganan bulanan (COntract == Month-to-month) 1655 rows
- Pelanggan yang tidak memiliki tanggungan (Dependent == No) 1543 rows
- Pelanggan yang memakai layanan sambungan Fiber Optic (InternetService == Fiber optic) 1297 rows
kenapa saya hanya mengambil 3 feature yang dievaluasi terlebih dahulu? disini saya mengikuti Prinsip pareto, percaya bahwa 80% hasil dari kinerja merupakan buah dari 20% upaya yang telah dilakukan. Sehingga 3 features dirasa menjadi prioritas untuk dilakukan evaluasi lebih lanjut. mengingat total Churn Yes sebanyak 1869 rows dari 7032 data.
