# Tentang Project Academic Performance Analysis

Mata Kuliah: Data Science

## Judul:

Analisis dan Prediksi Faktor Penentu Prestasi Akademik Siswa Menggunakan Metode Regresi, Klasifikasi, dan Clustering

## Anggota Kelompok:

| No  | Nama               |    NIM     | Kelas |
|:---:|:-------------------|:----------:|:-----:|
|  1  | Deni Permana       | 2210512015 | DS-B  |
|  2  | Diaz Fahreza Akbar | 2210512069 | DS-B  |

## Sumber Data:

Cortez, P. (2008). Student Performance [Dataset]. UCI Machine Learning Repository (<https://doi.org/10.24432/C5TG7T>).

## Tujuan:

-   Mengidentifikasi faktor utama yang memengaruhi prestasi akademik siswa.
-   Memberikan rekomendasi berbasis data untuk membantu sekolah meningkatkan kualitas pembelajaran.
-   Memahami pola kelompok siswa untuk merancang intervensi yang sesuai.

## Kebermanfaatan:

-   Memberikan insight kepada pendidik mengenai faktor risiko dan potensi keberhasilan siswa.
-   Membantu perencanaan strategi peningkatan prestasi berdasarkan hasil prediksi dan segmentasi siswa.

## Pemilihan Model

### Regresi:

-   Model: Linear Regression atau Random Forest Regression.

-   Tujuan: Memprediksi nilai akhir siswa (G3) berdasarkan fitur seperti studytime, absences, dan famrel.

### Klasifikasi:

-   Model: Decision Tree atau Logistic Regression.

-   Tujuan: Mengelompokkan siswa ke dalam kategori prestasi ("rendah", "sedang", "tinggi"). Transformasi: Kategori ditentukan dengan threshold nilai G3:

    -   Rendah: G3 \< 10

    -   Sedang: 10 \<= G3 \< 15

    -   Tinggi: G3 \>= 15.

### Clustering:

-   Model: K-Means atau Hierarchical Clustering.

-   Tujuan: Mengidentifikasi pola tersembunyi dalam kelompok siswa berdasarkan fitur seperti studytime, freetime, dan famrel.
