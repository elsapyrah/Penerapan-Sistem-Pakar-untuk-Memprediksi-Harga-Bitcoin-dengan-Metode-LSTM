# Penerapan-Sistem-Pakar-untuk-Memprediksi-Harga-Bitcoin-dengan-Metode-LSTM

# Deskripsi Proyek
LSTM adalah jenis jaringan saraf yang dirancang untuk membantu komputer belajar dari data yang memiliki urutan waktu, seperti harga saham. 

Arsitektur LSTM:
<img width="489" height="345" alt="image" src="https://github.com/user-attachments/assets/03cff8d3-e897-4556-8d7d-10f4cdea9842" />


 
Mengembangkan model prediksi harga Bitcoin menggunakan Long Short-Term Memory (LSTM) berdasarkan data historis. Model dirancang dengan dua lapisan (50 neuron per lapisan) dan lookback period 300 hari, serta dilatih menggunakan optimizer Adam dan loss function MSE. Proyek ini memperlihatkan potensi deep learning dalam sistem pakar untuk analisis dan prediksi pasar kripto.

# Data
Data yang digunakan dalam penelitian ini merupakan data historis pergerakan harga Bitcoin dalam USD, yang diambil dari platform Kaggle. Dataset mencakup periode dari 1 Februari 2015 hingga 29 April 2024 dan disajikan dalam bentuk tabel dengan 20 atribut yang mewakili berbagai aspek harga dan indikator teknis. 

# Evaluasi
1. Mean Squared Error (MSE)  
2. Root Mean Squared Error (RMSE) 

# Hasil
<img width="392" height="204" alt="image" src="https://github.com/user-attachments/assets/c422b8f8-c53f-44e5-91f6-6471e577f64f" />

Grafik prediksi harga Bitcoin USD menunjukkan kesesuaian dengan data sebenarnya. Kesimpulannya, model LSTM ini berhasil memprediksi pergerakan harga Bitcoin USD dengan tingkat akurasi yang dapat diterima. Terlihat bahwa prediksi hari ke-301 atau pada 25 Januari 2025, harga Bitcoin USD cenderung turun pada rentang harga 60.000 USD

