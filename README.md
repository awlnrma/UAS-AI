# Liver Ailment Prediction Using Random Forest

# Deskripsi Proyek
Penyakit hati merupakan salah satu penyakit kronis yang berdampak besar terhadap kualitas hidup dan angka harapan hidup. Berdasarkan data WHO, jumlah penderita penyakit hati meningkat dari waktu ke waktu di seluruh dunia, termasuk Indonesia.
Proyek ini bertujuan untuk membangun model prediksi penyakit hati menggunakan algoritma Random Forest. Dengan memanfaatkan dataset yang memuat berbagai fitur medis, model ini diharapkan dapat membantu dalam proses deteksi dini gangguan hati. Selain itu, proyek ini juga mencakup deployment model agar dapat digunakan secara praktis oleh pengguna umum.

#  Dataset
- Nama Dataset: [Liver Patient Dataset (India)](https://www.kaggle.com/datasets/uchiljaspreet/liver-patient-dataset)
- Sumber: Kaggle
- Jumlah Fitur: 10+ fitur medis (termasuk usia, jenis kelamin, kadar enzim, dll)
- Tujuan: Klasifikasi pasien apakah mengidap penyakit hati atau tidak

# Alur Proyek
1. Membaca Dataset
   - Menggunakan library `pandas` untuk membaca file CSV sebagai input data.
2. Pre-processing Data
   - Menangani nilai kosong
   - Transformasi fitur kategorikal (encoding)
   - Menghapus data duplikat
3. Simpan Data
   - Dataset hasil pre-processing disimpan kembali dalam file CSV sebagai versi bersih.
4. Data Splitting
   - Membagi dataset menjadi data latih dan data uji.
5. Training Model
   - Melatih model menggunakan algoritma Random Forest pada data latih.
6. Random Forest
   - Menggunakan metode ensemble dari beberapa Decision Tree untuk meningkatkan akurasi dan kestabilan prediksi.
7. Trained Model
   - Model yang telah dilatih digunakan untuk evaluasi dan deployment.
8. Testing
   - Menggunakan data uji untuk mengukur performa model.
9. Evaluasi Model
   - Evaluasi menggunakan metrik akurasi dan confusion matrix.
10. Deployment
    - Model dideploy menggunakan Streamlit untuk memudahkan prediksi oleh pengguna.

# Hasil
Berdasarkan hasil uji coba, algoritma Random Forest menunjukkan kinerja yang sangat baik dalam memprediksi kemungkinan penyakit liver dengan tingkat akurasi yang tinggi. Algoritma ini mampu mengenali pola dalam data medis yang kompleks, termasuk hubungan antar faktor seperti:
- Usia  
- Jenis Kelamin  
- Total Bilirubin  
- Direct Bilirubin  
- Alkaline Phosphotase  
- Alamine Aminotransferase  
- Aspartate Aminotransferase  
- Total Proteins  
- Albumin  
- Albumin and Globulin Ratio  

Dengan kemampuannya menangani data berukuran besar dan banyak fitur, Random Forest menjadi salah satu alat bantu diagnosis yang andal. Hasil prediksi dari model ini diharapkan dapat:
- Mendukung tenaga medis dalam pengambilan keputusan klinis
- Membantu pasien dalam memahami risikonya lebih awal, sehingga dapat melakukan tindakan pencegahan atau pengobatan yang tepat waktu

# Tools dan Library
- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Streamlit (untuk deployment)

> *Kata kunci: Decision Tree, Penyakit Hati, Prediksi, Random Forest*
