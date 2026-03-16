# Tugas Machine Learning - Week 3

Repository ini berisi tugas praktikum Week 3 yang berfokus pada tahapan Data Preprocessing menggunakan Python.

## Materi yang Dipelajari:
1. **Outlier Handling**: Pengecekan distribusi data menggunakan Histogram dan Boxplot, serta penanganan pencilan menggunakan metode Interquartile Range (IQR).
2. **Missing Value Handling**: Analisis persentase data yang hilang dan teknik imputasi menggunakan Median (untuk data numerik) serta Modus (untuk data kategorikal).
3. **Data Encoding**: Mengubah data kategorikal menjadi numerikal menggunakan beberapa teknik:
   - One Hot Encoding (OHE)
   - Label Encoding
   - Mean Encoding
4. **Data Splitting**: Pembagian dataset menjadi Data Train dan Data Test (rasio 80:20) untuk menghindari data leakage.

## Dataset yang Digunakan:
- `california_dataset.csv`
- `company.csv`
- `Telco-Customer-Churn.csv`

* **💻 Instalasi Library (Khusus Pengguna VS Code):**
  Jika menjalankan tugas ini di lokal (VS Code), pastikan telah menginstall library pendukung berikut melalui terminal:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn scipy
