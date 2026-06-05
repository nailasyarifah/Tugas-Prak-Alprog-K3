# Post-Test-PrakAlprog-K3
# 📊 Student AI Usage Analysis

## 👥 Kelompok 3 - Kelas F
## 🎯 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis pola penggunaan teknologi Artificial Intelligence (AI) oleh siswa berdasarkan dataset *Student AI Usage*. Analisis dilakukan menggunakan Python dengan bantuan library Pandas, NumPy, Matplotlib, dan Seaborn untuk memperoleh wawasan mengenai kebiasaan penggunaan AI, pengaruhnya terhadap performa akademik, serta distribusi karakteristik pengguna.

---

## 📂 Dataset

Dataset yang digunakan berisi informasi mengenai:

* Umur siswa (`age`)
* Jenjang pendidikan (`education_level`)
* Durasi belajar harian (`study_hours_per_day`)
* Durasi penggunaan layar harian (`daily_screen_time_hours`)
* Nilai sebelum menggunakan AI (`grades_before_ai`)
* Nilai setelah menggunakan AI (`grades_after_ai`)
* Aplikasi AI yang digunakan (`ai_tool_used`)
* Tujuan penggunaan AI (`purpose_of_ai`)
* Status penggunaan AI (`uses_ai`)

---

# 📈 Analisis yang Dilakukan

## 🥧 Kategori A - Agregasi

### Frekuensi Tujuan Penggunaan AI

Menganalisis frekuensi kemunculan tujuan utama siswa dalam memanfaatkan teknologi AI (`purpose_of_ai`) dan menampilkannya dalam bentuk Pie Chart.

**Tujuan:**

* Mengetahui alasan utama siswa menggunakan AI.
* Mengidentifikasi kebutuhan penggunaan AI yang paling dominan.

---

## 📊 Kategori B - Tren / Filter

### Pengguna Gemini untuk Research

Melakukan penyaringan data siswa yang:

* Berusia lebih dari 17 tahun
* Menggunakan AI Tool **Gemini**
* Memiliki tujuan penggunaan AI untuk **Research**

Kemudian hasil ditampilkan menggunakan Bar Chart.

**Tujuan:**

* Mengidentifikasi karakteristik pengguna Gemini untuk kebutuhan penelitian akademik.

---

## 📉 Kategori C - Korelasi

### Daily Screen Time vs Academic Performance

Menganalisis hubungan antara:

* `daily_screen_time_hours`
* `grades_after_ai`

menggunakan Scatter Plot.

**Tujuan:**

* Mengetahui apakah durasi penggunaan layar memiliki hubungan dengan performa akademik setelah memanfaatkan AI.

---

## 📦 Kategori D - Distribusi

### Distribusi Nilai Berdasarkan AI Tool

Menganalisis distribusi nilai akademik akhir (`grades_after_ai`) berdasarkan AI Tool yang digunakan menggunakan Boxplot.

**Tujuan:**

* Membandingkan persebaran nilai siswa berdasarkan platform AI yang digunakan.
* Mengidentifikasi kemungkinan outlier.

---

## 🛠️ Tools & Libraries

* Python
* Jupyter Notebook / Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* GitHub

---

## 📁 Struktur Repository

```text
Student-AI-Usage-Kelompok3/
│
├── README.md
├── Student_AI_Usage.csv
├── Analisis_Kelompok3.ipynb
│
├── visualisasi/
│   ├── pie_chart.png
│   ├── bar_chart.png
│   ├── scatter_plot.png
│   └── boxplot.png
│
└── infografis/
    └── infografis_kelompok3.png
```

---

## 📌 Kesimpulan

Melalui analisis dataset Student AI Usage, diperoleh gambaran mengenai pola penggunaan AI oleh siswa, tujuan penggunaan yang paling dominan, hubungan antara durasi penggunaan teknologi dengan performa akademik, serta distribusi hasil belajar berdasarkan platform AI yang digunakan.

---

## Anggota dan Jobdesk Kelompok 
1. Afifah Putri Meylani	(21060125120005):
   - Membuat pengodean grafik Kategori B pada file Jupyter Notebook.
   - Mengedit dan menyusun desain infografis untuk story instagram 
3. Dinatun Khima		(21060125120009):
   - Membuat pengodean grafik Kategori D pada file Jupyter Notebook.
   - Mengedit dan menyusun desain infografis untuk story instagram 
4. Arika Azhar Paramadin		(21060125120010):
   - Membuat pengodean grafik kategori C pada file Jupyter Noteboook.
   - Membuat desain PPT infografis untuk LinkedIn.
6. Naila Syarifah		(21060125120023):
   - Mengelola repositori GitHub dan upload berkas.
   - Membuat desain PPT infografis untuk LinkedIn.
8. Ina Ria Kamilah		(21060125120036):
   - Membuat pengodean grafik Kategori A pada file Jupyter.
   - Membuat desain PPT infografis untuk LinkedIn.
   - Melakukan finalisasi pengodean grafik gabungan (Subplots 2x2).
