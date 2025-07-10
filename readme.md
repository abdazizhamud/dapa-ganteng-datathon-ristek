# Analisis Sentimen Ulasan Aplikasi Halodoc Menggunakan Model Convolutional Neural Network (CNN) dengan Metode Lexicon-Based Labeling

---

## Anggota Kelompok

* Hamud Abdul Aziz - Universitas Padjadjaran
* Hafizh Fadl Muhammad - Universitas Padjadjaran
* Dafa Ghani Abdul Rabbani - Universitas Padjadjaran

---

## Abstrak

{Halodoc adalah salah satu platform layanan kesehatan digital yang paling populer di Indonesia. Namun, tingginya jumlah ulasan negatif di Google Play Store menunjukkan bahwa masih terdapat tantangan dalam kualitas layanan yang diberikan. Penelitian ini bertujuan untuk melakukan analisis sentimen terhadap ulasan pengguna aplikasi Halodoc yang diambil dari Google Play Store. Dengan menggunakan pendekatan pemrosesan teks dan klasifikasi berbasis rule-based, kami memetakan sentimen pengguna serta mengidentifikasi aspek layanan yang paling banyak dikeluhkan. Visualisasi wordcloud, distribusi rating, dan analisis frekuensi kata menunjukkan bahwa masalah utama berkaitan dengan layanan dokter, sistem pembayaran, dan respons customer service. Rekomendasi perbaikan layanan kemudian disusun berdasarkan hasil analisis. Penelitian ini diharapkan dapat menjadi masukan bagi pengembang Halodoc dalam meningkatkan kualitas layanan yang berkelanjutan.
}

---

## Dataset

Dataset ulasan aplikasi Halodoc yang digunakan dalam proyek ini diperoleh dari **Hugging Face**. Detail lebih lanjut mengenai dataset dapat diakses melalui tautan berikut:

[**Link Dataset Hugging Face**](https://huggingface.co/datasets/kangdap/halodoc-app-review/viewer)



---

## Cara Menggunakan (Clone Repositori)

Untuk menjalankan dan mereplikasi proyek ini di lingkungan lokal Anda, ikuti langkah-langkah berikut:

1.  **Clone repositori ini:**

    ```bash
    git clone https://github.com/abdazizhamud/dapa-ganteng-datathon-ristek.git
    ```

    
2.  **Masuk ke direktori proyek:**

    ```bash
    cd dapa-ganteng-datathon-ristek
    ```

3.  **Instal dependensi yang diperlukan:**

    Python yang digunakan: Python 3.10
    ```bash
    pip install -r requirements.txt
    ```


4.  **Buka notebook Jupyter:**

    ```bash
    jupyter notebook
    ```

    Setelah itu, navigasikan ke file `.ipynb` yang berisi laporan dan implementasi kode Anda untuk memulai analisis.

---

## Struktur Proyek

* `halodoc.ipynb`: File Jupyter Notebook (`.ipynb`) utama yang mendetailkan analisis, implementasi model, dan hasil.
* `requirements.txt`: Daftar pustaka Python yang diperlukan untuk menjalankan proyek.
* `README.md`: Berkas ini, memberikan gambaran umum proyek.