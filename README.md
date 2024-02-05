<h1>Stage-1</h1>

# Exploratory Data Analysts

## 1. Churn Customer dengan Estimasi Gaji Rendah

Mayoritas customer yang churn adalah customer dengan estimasi gaji rendah (<60k).

### Rekomendasi:

a. Fokus ke retention program untuk customer berpenghasilan rendah, misal penawaran diskon atau cashback untuk produk tabungan.
b. Tingkatkan financial literacy customer kelas menengah bawah agar lebih loyal.

## 2. Usia dan Churn

Pelanggan yang memutuskan untuk tidak melanjutkan layanan (churn) cenderung berada dalam kelompok usia 40-60 tahun. Ini mungkin mengindikasikan bahwa faktor-faktor seperti perubahan kebutuhan finansial atau pendekatan pensiun mungkin mempengaruhi keputusan mereka untuk meninggalkan bank.

## 3. Skor Kredit dan Balance

Pelanggan yang churn dalam kelompok usia ini cenderung memiliki skor kredit di bawah 600, tetapi dengan balance yang lebih besar. Hal ini dapat menunjukkan bahwa meskipun mereka memiliki dana yang signifikan dalam akun mereka, mereka mungkin tidak puas dengan layanan atau menemukan opsi yang lebih menguntungkan di tempat lain.

## 4. Tenure dan Produk

Pelanggan yang churn biasanya memiliki tenure di bawah 2.5 tahun, menunjukkan bahwa mereka tidak lama menjadi pelanggan sebelum memutuskan untuk berhenti. Rata-rata mereka memiliki satu produk, yang bisa menandakan bahwa pelanggan mungkin tidak sepenuhnya terlibat dengan berbagai layanan yang ditawarkan bank.

## 5. Kartu Kredit dan Keaktifan

Sebagian besar pelanggan yang churn memiliki kartu kredit dan cenderung tidak aktif. Ketiadaan interaksi yang berkelanjutan dengan bank bisa jadi merupakan indikator kuat dari kemungkinan churn.

## 6. Penghasilan dan Gender

Penghasilan yang diperkirakan untuk pelanggan yang churn berada di bawah 500.000, dan meskipun laki-laki mendominasi jumlah pelanggan secara keseluruhan, proporsi wanita yang churn lebih tinggi. Ini mungkin mengindikasikan bahwa ada faktor-faktor spesifik yang menyebabkan ketidakpuasan di kalangan wanita yang perlu ditangani oleh bank.

## 7. Geografi

Meskipun Prancis memiliki jumlah pelanggan yang paling banyak, presentase pelanggan yang churn cenderung lebih rendah dibandingkan dengan Spanyol dan Jerman. Ini menunjukkan bahwa mungkin ada faktor regional yang mempengaruhi keputusan pelanggan untuk bertahan atau churn.

## 8. Korelasi Variabel Age dan Balance

Berdasarkan heatmap, variabel Age dan Balance berkorelasi positif dengan variabel Exited.

## 9. Hasil Regresi Linear

Hasil dari regresi linear menunjukkan bahwa variabel Age memiliki pengaruh sebesar 0.01 terhadap kemungkinan churn, sedangkan variabel Balance memiliki pengaruh sebesar 0.0000007 terhadap kemungkinan churn.

 <h1>Stage-2</h1>

# Panduan Proses Preprocessing Data

Pada tahap preprocessing data, langkah-langkah berikut telah dilakukan:

1. **Penanganan Nilai yang Hilang, Duplikat, dan Outlier:**

    - Tidak ditemukan nilai yang hilang atau duplikat dalam data.
    - Outlier ditangani menggunakan metode Z-Score atau IQR.

2. **Normalisasi dan Standarisasi Data:**

    - Variabel numerik dinormalisasi dan distandarisasi untuk persiapan analisis lebih lanjut.
    - Normalisasi dipilih untuk pemrosesan masa depan.

3. **Pengkodean Fitur:**

    - Data kategori diubah menjadi bentuk numerik menggunakan One Hot Encoding.

4. **Penanganan Ketidakseimbangan Kelas:**

    - Ketidakseimbangan kelas diatasi dengan oversampling untuk menyeimbangkan distribusi antara pelanggan yang berpindah dan yang tetap.

5. **Pemilihan dan Ekstraksi Fitur:**
    - Pemilihan dan ekstraksi fitur dilakukan untuk menyempurnakan dataset untuk pemodelan.
    - Fitur tambahan seperti interaksi antara usia dan jumlah produk, rasio saldo terhadap gaji yang diestimasi, lama pelanggan, dan frekuensi transaksi direkomendasikan untuk meningkatkan analisis.

## Kesimpulan

Kesimpulan ini menyoroti pendekatan yang komprehensif dalam menyiapkan dataset untuk analisis yang mendalam, memastikan akurasi dalam tahap pemodelan dan analisis selanjutnya.
