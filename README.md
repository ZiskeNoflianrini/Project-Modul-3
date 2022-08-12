# Project-Modul-3


1. Business Problem Understanding <br>
   Bisnis e-commerce cenderung tidak konstan (berubah-ubah) sehingga menyebabkan problem yang serius yaitu customer loss. Customer loss/ Customer churn pada ecommerce diartikan customer yang berhenti berbelanja di aplikasi ecommerce ini. Studi menunjukkan bahwa cost untuk menambah customer baru lebih tinggi dibandingkan dengan mempertahankan customer lama. Maka dari itu, dibuat model machine learning untuk memprediksi customer churn ini agar perusahaan dapat melakukan tindakan preventif kepada customer yang diprediksi akan churn.

2. Data Understanding <br>
   Data e-commerce customer churn ini imbalance, lalu terdapat missing value, serta terdapat outlier yang harus diberikan treatment sebelum melakukan modelling.
   
3. Machine Learning  <br>
   Setelah diuji coba semua model (base model dan ensamble model) hasil yang didapatkan kurang memuaskan, sehinggan dilakukan resampling. Hasil paling baik yaitu menggunakan model ensamble (model Random Forest dan model XGBoost) dengan resampling RandomUnderSampler. Lalu, setelah dilakukan hyperparametertuning, diambil hasil terbaik yaitu model XGBoost.
   
4. Conclusion <br>
   Perusahaan akan lebih untung jika melakukan prediksi terlebih dahulu kepada customer yang akan churn.

5. Recommendation <br>
   Harus dilakukan pencarian feature yang lebih berkaitan lagi terhadap customer churn dan riset lebih dalam lagi untuk mencari tahu alasan customer churn.
