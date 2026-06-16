# JUDUL PROJECT PCD
## Nama Anggota
###  Naylarifa Maulida Asri : F1D02410019
###  MELANI PUTRI ZAHARI  : F1D02410073
###  I MADE PRIYANDIKA ADIYATMA PUTRA SARI : F1D02410008

# Project Overview
Project ini merupakan implementasi Pengolahan Citra Digital (PCD) untuk melakukan klasifikasi varietas beras berdasarkan dataset gambar. Dataset yang digunakan terdiri dari lima kelas utama, yaitu:

- Arborio
- Basmati
- Ipsala
- Jasmine
- Karacadag

Tujuan utama dari project ini adalah membandingkan beberapa tahapan preprocessing citra untuk melihat pengaruhnya terhadap hasil ekstraksi fitur dan performa model klasifikasi. Proses klasifikasi dilakukan dengan memanfaatkan fitur tekstur dari citra menggunakan metode **Gray Level Co-occurrence Matrix (GLCM)**, kemudian hasil fiturnya digunakan untuk melatih beberapa model machine learning.

Model klasifikasi yang digunakan dalam project ini adalah:
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest

Project ini tidak hanya berfokus pada nilai akurasi akhir, tetapi juga pada pemilihan preprocessing yang sesuai, proses ekstraksi fitur, serta analisis hasil evaluasi model. Terdapat empat kombinasi preprocessing yang dibandingkan, mulai dari preprocessing sederhana hingga yang lebih kompleks dengan operasi morfologi.

---

# Kombinasi Preprocessing

| Percobaan | Tahapan Preprocessing |
|-----------|----------------------|
| Percobaan 1 | Grayscale → Resize → Median Filter |
| Percobaan 2 | Grayscale → Resize → Histogram Equalization → Median Filter |
| Percobaan 3 | Grayscale → Resize → Median Filter → Sobel → Roberts |
| Percobaan 4 | Grayscale → Resize → Median Filter → Sobel → Roberts → Thresholding → Closing → Opening |

---