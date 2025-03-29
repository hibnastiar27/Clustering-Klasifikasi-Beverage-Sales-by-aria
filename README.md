# Clustering & Klasifikasi Beverage Sales

Repository ini merupakan project sumbission dari dicoding

Saya menggunakan data set berikut
[Dataset Beverage Sales](https://www.kaggle.com/datasets/sebastianwillmann/beverage-sales)


dikarenakan dataset terlalu besar jadi link dataset untuk Clustering dan Dataset untuk Klasifikasi / hasil dari clustering saya taro di drive berikut 
[Dataset Clustering & Klasifikasi](https://)

# Struktur Folder

```
├── Submission.zip
    ├── [Clustering] Submission Akhir BMLP_Nur Aria Hibnastiar.ipynb
    └── [Klasifikasi] Submission Akhir BMLP_Nur Aria Hibnastiar.ipynb
    └── Dataset_clustering.csv
    └── Dataset_inisiasi.csv
```

# Penilaian

Submission Anda akan dinilai oleh reviewer dengan skala 1–5 berdasarkan dari parameter yang ada. Anda dapat menerapkan beberapa saran untuk mendapatkan nilai tinggi. Berikut sarannya.

1. Menggunakan dataset dengan **minimal 2500 baris**.
2. Menggunakan **minimal 5 fitur** untuk proses clustering dengan **campuran numerikal dan kategorikal**.
3. **Menerapkan feature selection** pada tahap clustering untuk memilih fitur terbaik dan membandingkan silhoutte score dengan sebelum menggunakan feature selection.
4. Evaluasi akhir pada clustering harus mencapai **nilai silhouette score minimal 0.70**.
5. Mengimplementasikan **2 algoritma klasifikasi** yang berbeda untuk membandingkan performa model.
6. Meningkatkan **akurasi dan F1-Score** pada **training serta testing** set **minimal 92%**.

# Submission yang Tidak Sesuai Kriteria

- **Tidak melampirkan file** yang diminta pada ketentuan berkas submission.
- **Tidak menggunakan template** yang disediakan.
- **Memasukan kolom ID** untuk dimasukan ke dalam data training.
- Tidak menampilkan/memiliki nilai **silhouette score**.
- **Tidak memberikan penjelasan** mengenai hasil clustering.
- Tidak menggunakan **dataset dan label dari hasil clustering**.
- Model klasifikasi **tidak menampilkan akurasi dan F1-Score pada training set serta testing set**.
- Tidak diperbolehkan menggunakan platform atau metode **AutoML**, seperti berikut.
    - PyCaret
    - Auto-sklearn
    - Google Cloud AutoML 
    - H2O Driverless AI (dari H2O.ai)
    - Microsoft Azure Automated Machine Learning
    - TPOT (Tree-based Pipeline Optimization Tool)
    - DataRobot
    - RapidMiner Auto Model
    - Amazon SageMaker Autopilot
    - IBM Watson AutoAI