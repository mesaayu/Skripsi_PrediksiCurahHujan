# Skripsi_PrediksiCurahHujan

Tugas akhir atau skripsi ini membahas Prediksi Curah Hujan Kota Bogor Menggunakan Algoritma Random Forest Regression. Pembaruan penelitian menggunakan teknik Quantile Transform sebagai transformation untuk mengurangi pengaruh outlier serta metode hyperparameter tuning yaitu Grid Search untuk menemukan hyperparameter terbaik yang digunakan saat melatih dan menguji model. Data yang digunakan diperoleh melalui pusat database online BMKG dengan data Kota Bogor pada tahun 2019-2024. 

Perbandingan antara nilai aktual dan nilai estimasi curah hujan harian (mm) pada bulan September hingga Desember 2021 dapat dilihat pada Gambar dibawah. Pola tersebut menunjukkan beberapa titik estimasi mendekati nilai aktualnya meskipun cenderung terbatas dalam memperkirakan nilai yang sangat tinggi.

<img width="827" height="342" alt="image" src="https://github.com/user-attachments/assets/dc911fd3-aaff-4c5e-9ca6-c6eee1317d43" />

Kemudian, model dengan tuning Grid Search tersebut diterapkan untuk memprediksi curah hujan harian dalam setahun kedepan. Data yang diprediksi mulai dari 1 januari 2025 hingga 31 desember 2025. Hasil prediksi menunjukkan pola yang bersifat fluktuatif dengan nilai curah hujan bervariasi antara sekitar 5 mm hingga mendekati 30 mm. Pola ini mencerminkan prediksi bulan juli hingga desember 2025 kedepan berada pada intensitas hujan ringan hingga hujan sedang. 

<img width="850" height="367" alt="image" src="https://github.com/user-attachments/assets/ad485b93-91c2-429a-9711-a4c310d892e0" />

Dalam Skripsi ini, terdapat beberapa rekomendasi yang dapat dikembangkan untuk penelitian selanjutnya; Keterbatasan model dalam memprediksi curah hujan yang tinggi ini disebabkan karena rendahnya korelasi antara fitur dengan target sehingga disarankan menambahkan fitur eksternal seperti evaporasi dan fenomena El-Nino dan La-Nina. Serta, disarankan menerapkan teknik oversampling regresi untuk distribusi yang tidak seimbang  karena model cenderung lebih terlatih pada rentang yang lebih sering muncul atau nilai yang lebih rendah.

