# Forecasting Inflation BI Rates

Author : [**Abel K Widodo**](https://abelkristanto.github.io/about/)

Date : December 2023

Data Source : [Bank Indonesia](https://www.bi.go.id/id/statistik/indikator/data-inflasi.aspx)

Dalam notebook ini kita akan melakukan analisa time series dari data univariate inflasi yang dari tahun 2023 sampai dengan November 2023. Dalam hal ini, ada beberapa catatan yang bisa kita lakukan:

1. Periksa dan buat deret waktu stasioner, karena deret waktu harus dibuat stasioner sebelum kita dapat menggunakan ARIMA untuk prediksi. Jika deret waktu tidak stasioner, perlu dilakukan stasionarisasi melalui differencing atau transformasi. 
2. Pilih urutan optimal: Gunakan plot ACF dan PACF untuk menentukan urutan terbaik dengan pendekatan langkah demi langkah.
3. Kembangkan model: Kita akan melakukan prediksi dengan periode yang ditentukan (tergantung pada kebutuhan). Metode autoregresif berfungsi baik dalam meramalkan beberapa periode ke depan.
4. Validasi model: Bandingkan nilai yang diprediksi dengan nilai aktual dalam sampel validasi dengan metrik evaluasi dasar (AIC, RMSE, MAE, dll.).
   
![image](https://github.com/AbelKristanto/Forecasting-Inflation/assets/58840455/698ef8c2-f7f9-4868-b7a0-e1e96512bfc6)


![inflation](https://github.com/AbelKristanto/Forecasting-Inflation/assets/58840455/f63ba3e7-1315-4044-b6f5-f334924107e1)
