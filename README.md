Analisis Sentimen Maxim - Natural Language Processing

📋 Gambaran Proyek

Proyek ini merupakan implementasi lengkap pipeline Natural Language Processing (NLP) untuk menganalisis sentimen ulasan pengguna aplikasi transportasi online Maxim (com.taxsee.taxsee) dari Google Play Store. Proyek ini mencakup seluruh tahapan analisis teks mulai dari pengambilan data (scraping), pembersihan data (cleaning), hingga klasifikasi sentimen menggunakan algoritma Machine Learning.

🎯 Tujuan Proyek

Mengimplementasikan pipeline End-to-End NLP untuk teks Bahasa Indonesia.

Menganalisis sentimen (Positif/Negatif) dari ulasan pengguna Maxim.

Memahami pola kata yang sering muncul pada keluhan maupun pujian pelanggan.

Membangun model prediksi sentimen otomatis menggunakan Naive Bayes.

🛠️ Teknologi yang Digunakan

Python 3.x

Google Play Scraper: Pengambilan data ulasan dari Play Store.

Pandas & NumPy: Manipulasi dan analisis data tabular.

NLTK: Tokenisasi dan Stopwords Bahasa Indonesia.

Sastrawi: Stemming dan resource bahasa Indonesia (opsional/pendukung).

Scikit-learn: Feature Extraction (TF-IDF) dan Modelling (Naive Bayes).

Matplotlib & Seaborn: Visualisasi data (Bar Chart, Confusion Matrix).

📚 Struktur Proyek

Week 2: Data Scraping & Preprocessing

Tahap pengumpulan data ulasan Maxim dan pembersihan teks.

Teknik: Scraping, Cleaning (Regex), Tokenization, Stopwords Removal.

Week 3: Feature Extraction (TF-IDF)

Mengubah data teks menjadi format numerik agar bisa diproses algoritma.

Teknik: TF-IDF (Term Frequency-Inverse Document Frequency).

Week 4: Modelling & Evaluation

Pembangunan model klasifikasi dan evaluasi performa.

Teknik: Multinomial Naive Bayes, Confusion Matrix, Classification Report.

📊 Dataset

Dataset penelitian ini disimpan pada media penyimpanan eksternal (Google Drive) karena keterbatasan ukuran file pada repositori GitHub. Dataset mencakup file mentah (raw) hingga file yang sudah bersih (clean).

Dataset dapat diakses dan diunduh melalui tautan berikut:
📂 https://drive.google.com/drive/folders/1Zpp6R7zrfo3FNoStqoXnb76kJlHDSzr4?usp=sharing

File dalam dataset:

maxim_raw.csv

maxim_clean_basic.csv

maxim_clean_final.csv

🚀 Cara Penggunaan

1. Instalasi Dependencies

# Install required packages
pip install google-play-scraper Sastrawi textblob seaborn matplotlib scikit-learn pandas nltk

# Download NLTK data
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords')"


2. Persiapan Data

Karena dataset berada di Google Drive:

Unduh semua file .csv dari tautan Google Drive di atas.

Letakkan file-file tersebut dalam satu folder yang sama dengan file notebook (.ipynb).

3. Menjalankan Notebook

Jalankan file notebook utama:

jupyter notebook "Tugas_1A_Maxim_5026221091.ipynb"


📝 Struktur Direktori Repository

Tugas1A_Maxim_Edward/
│
├── Tugas_1A_Maxim_5026221091.ipynb   # Notebook Utama (Pipeline Gabungan)
│
└── README.md                         # Dokumentasi Proyek
