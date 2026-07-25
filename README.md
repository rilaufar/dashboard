# Dashboard Analisis Performa Akademik Siswa

## Deskripsi Proyek

Dashboard Analisis Performa Akademik Siswa merupakan aplikasi visualisasi data yang dikembangkan untuk membantu pihak sekolah dalam memantau faktor-faktor yang memengaruhi prestasi akademik siswa. Dashboard ini dibuat menggunakan bahasa pemrograman Python dengan memanfaatkan berbagai pustaka analisis data dan visualisasi.

Dataset yang digunakan berasal dari Kaggle, yaitu **Student Performance Factors**, yang berisi berbagai informasi mengenai kebiasaan belajar, kehadiran, motivasi, dukungan keluarga, aktivitas fisik, serta nilai ujian siswa.

Melalui dashboard ini, pengguna dapat melakukan eksplorasi data secara visual sehingga lebih mudah dalam memahami kondisi akademik siswa dan mendukung pengambilan keputusan berbasis data.

---

## Tujuan

Proyek ini bertujuan untuk:

- Menampilkan informasi akademik siswa secara visual.
- Mengidentifikasi faktor-faktor yang memengaruhi nilai ujian siswa.
- Membantu pihak sekolah dalam melakukan monitoring performa akademik.
- Menyediakan dashboard yang mudah dipahami oleh pengguna.

---

## Pengguna Dashboard

Dashboard ini dirancang untuk digunakan oleh:

- Kepala Sekolah
- Wakil Kepala Sekolah Bidang Kurikulum
- Guru Bimbingan dan Konseling (BK)
- Wali Kelas

---

## Dataset

**Nama Dataset**

Student Performance Factors

**Sumber Dataset**

https://www.kaggle.com/datasets/lainguyn123/student-performance-factors

Dataset terdiri dari berbagai variabel yang berkaitan dengan performa akademik siswa, seperti:

- Hours Studied
- Attendance
- Previous Scores
- Motivation Level
- Internet Access
- School Type
- Teacher Quality
- Family Income
- Sleep Hours
- Physical Activity
- Tutoring Sessions
- Gender
- Exam Score

---

## Fitur Dashboard

Dashboard menampilkan beberapa indikator utama, yaitu:

- Total Siswa
- Rata-rata Nilai Ujian
- Rata-rata Kehadiran
- Rata-rata Jam Belajar

Visualisasi yang disediakan meliputi:

- Distribusi Nilai Siswa
- Hubungan Jam Belajar dengan Nilai
- Hubungan Kehadiran dengan Nilai
- Nilai Berdasarkan Gender
- Nilai Berdasarkan Jenis Sekolah
- Heatmap Korelasi
- Feature Importance menggunakan Random Forest

---

## Tools dan Library

Bahasa Pemrograman:

- Python

Library yang digunakan:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Notebook dikembangkan menggunakan:

- Google Colaboratory

---

## Struktur Proyek

```
Dashboard-Student-Performance/
│
├── StudentPerformanceFactors.csv
├── Dashboard_Analisis_Performa_Siswa.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## Cara Menjalankan

### 1. Clone Repository

```bash
git clone https://github.com/rilaufar/dashboard.git
```

### 2. Masuk ke Folder Proyek

```bash
cd dashboard
```

### 3. Install Library

```bash
pip install -r requirements.txt
```

### 4. Jalankan Notebook

Buka file:

```
Perancangan_Dashboard_Ansharil_Aufar.ipynb
```

menggunakan:

- Google Colab
- atau Jupyter Notebook

---

## Hasil Analisis

Dashboard menghasilkan beberapa informasi penting, antara lain:

- Persebaran nilai siswa.
- Hubungan antara jam belajar dan nilai ujian.
- Pengaruh tingkat kehadiran terhadap hasil belajar.
- Perbandingan nilai berdasarkan gender dan jenis sekolah.
- Faktor-faktor yang paling memengaruhi nilai ujian berdasarkan Feature Importance.

Informasi tersebut dapat dimanfaatkan oleh pihak sekolah sebagai dasar dalam menyusun strategi peningkatan kualitas pembelajaran.

---


## Author

**Ansharil Aufar**

Program Magister Informatika  
Konsentrasi Sains Data  
Universitas Islam Indonesia

---

## Lisensi

Proyek ini dikembangkan untuk memenuhi tugas mata kuliah Data Insight. Dataset yang digunakan merupakan dataset publik dari Kaggle.
