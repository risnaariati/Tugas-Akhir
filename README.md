

Proyek ini bertujuan untuk membangun model prediksi curah hujan dengan memanfaatkan algoritma **Artificial Neural Network (ANN)**. Data input diperoleh dari platform **Google Earth Engine (GEE)**, yang menyediakan data iklim dan citra satelit secara global. Studi kasus difokuskan pada wilayah **Kecamatan Tanah Grogot**, Kabupaten Paser, Kalimantan Timur.

## 📌 Tujuan

- Memprediksi curah hujan bulanan secara lebih akurat
- Mengintegrasikan pemanfaatan data GEE dengan model machine learning
- Menguji efektivitas ANN dalam pemodelan data iklim di wilayah studi

## 🧠 Teknologi yang Digunakan

- Python (NumPy, Pandas, Scikit-Learn, Matplotlib)
- PyTorch / TensorFlow (untuk ANN)
- Google Earth Engine (data input iklim dan lingkungan)
- Jupyter Notebook

## 📊 Dataset

- **Total Precipitation (Curah Hujan)**
- **Temperature (Suhu Permukaan)**
- **NDVI (Vegetasi)**
- Data diekstraksi dari Google Earth Engine untuk periode [tahun] di wilayah Tanah Grogot

## 🔍 Metodologi

1. Pengambilan data iklim melalui Google Earth Engine
2. Pra-pemrosesan dan normalisasi data
3. Pembuatan model Artificial Neural Network
4. Pelatihan dan evaluasi model
5. Visualisasi hasil prediksi vs aktual

## 📈 Hasil

Model menunjukkan performa yang cukup baik dalam memprediksi curah hujan dengan tingkat kesalahan yang rendah (MAPE / RMSE). Hasil ini dapat digunakan sebagai dasar dalam pengambilan keputusan terkait pengelolaan air dan pertanian di wilayah tersebut.


