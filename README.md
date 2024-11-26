# Scraping SatuSehat Project A

## Deskripsi
Proyek ini bertujuan untuk mengumpulkan, menganalisis, dan memvisualisasikan data terkait aplikasi **SatuSehat** dari ulasan pengguna di **Google Play Store** dan artikel berita. Proses meliputi scraping data, analisis sentimen, Named Entity Recognition (NER), clustering, dan pembuatan visualisasi untuk mendapatkan insight tentang persepsi pengguna dan fitur aplikasi ini.

---

## Fitur
- **Scraping Data Ulasan Pengguna**
  - Mengambil ulasan dari Google Play Store menggunakan `google_play_scraper`.
  - Menyimpan data ulasan untuk analisis lebih lanjut.
  
- **Analisis Sentimen**
  - Menggunakan `TextBlob` untuk menentukan polaritas dan subjektivitas ulasan.
  - Analisis dibagi berdasarkan waktu (sebelum dan setelah 1 Maret 2023).
  
- **Named Entity Recognition (NER)**
  - Menemukan entitas penting seperti nama, lokasi, dan organisasi dalam teks ulasan dan artikel.

- **Clustering**
  - Mengelompokkan data berdasarkan pola untuk menemukan insight baru.

- **Visualisasi**
  - Membuat grafik seperti histogram, scatter plot, dan word cloud.

---

## Teknologi
- **Python Libraries**
  - `google_play_scraper`, `TextBlob`, `scikit-learn`, `matplotlib`, `seaborn`, `nltk`, `transformers`
- **BERT Model**
  - Fine-tuned model: `cahya/bert-base-indonesian-1.5G`
- **Tools**
  - Jupyter Notebook, Google Colab
