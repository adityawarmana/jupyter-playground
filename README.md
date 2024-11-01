# Tutorial TensorFlow untuk Klasifikasi MNIST

Tutorial ini memberikan pengenalan dasar penggunaan TensorFlow untuk membangun model neural network yang mampu melakukan klasifikasi gambar tulisan tangan dari dataset MNIST.

## Dataset
MNIST adalah dataset gambar tulisan tangan angka dari 0 hingga 9, dengan 60,000 gambar untuk data latih dan 10,000 gambar untuk data uji.

## Langkah-langkah dalam Notebook
1. **Persiapan Lingkungan**: Menginstall dan mengimport pustaka yang diperlukan.
2. **Persiapan Dataset**: Memuat dataset MNIST dan membaginya menjadi data latih dan data uji.
3. **Membangun Model**: Menggunakan API Keras di TensorFlow untuk membuat model neural network sederhana.
4. **Melatih Model**: Melakukan training model dengan data latih dan memvalidasi dengan sebagian data.
5. **Evaluasi Model**: Menguji model menggunakan data uji untuk mengukur akurasi.
6. **Prediksi Data Baru**: Melakukan prediksi pada beberapa contoh dari data uji.

## Cara Menjalankan
- Buka notebook ini di Google Colab, Jupyter Notebook, atau editor lainnya yang mendukung format `.ipynb`.
- Pastikan untuk menginstall TensorFlow jika belum terpasang dengan menjalankan:
  ```python
  !pip install tensorflow matplotlib
  ```

## Hasil yang Diharapkan
Notebook ini akan menunjukkan proses pembuatan model klasifikasi sederhana dengan akurasi yang baik untuk dataset MNIST. Pada bagian akhir, Anda akan melihat hasil prediksi dari model pada beberapa gambar contoh.

## Lisensi
Proyek ini bersifat open-source dan bebas digunakan untuk pembelajaran.
