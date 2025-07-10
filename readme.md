# Analisis Sentimen Ulasan Aplikasi Halodoc Menggunakan Model Convolutional Neural Network (CNN) dengan Metode Lexicon-Based Labeling

---

## Anggota Kelompok

* Hamud Abdul Aziz - Universitas Padjadjaran
* Hafizh Fadl Muhammad - Universitas Padjadjaran
* Dafa Ghani Abdul Rabbani - Universitas Padjadjaran

---

## Abstrak

{isi abstraksi nanti}

---

## Dataset

Dataset ulasan aplikasi Halodoc yang digunakan dalam proyek ini diperoleh dari **Hugging Face**. Detail lebih lanjut mengenai dataset dapat diakses melalui tautan berikut:

[**Link Dataset Hugging Face**](https://huggingface.co/datasets/[nama_dataset_halodoc_di_huggingface])



---

## Cara Menggunakan (Clone Repositori)

Untuk menjalankan dan mereplikasi proyek ini di lingkungan lokal Anda, ikuti langkah-langkah berikut:

1.  **Clone repositori ini:**

    ```bash
    git clone [https://github.com/](https://github.com/)[nama_pengguna_github_anda]/[nama_repositori_anda].git
    ```

    *(**Catatan:** Ganti `[nama_pengguna_github_anda]` dan `[nama_repositori_anda]` dengan nama pengguna GitHub dan nama repositori Anda yang sebenarnya.)*

2.  **Masuk ke direktori proyek:**

    ```bash
    cd [nama_repositori_anda]
    ```

3.  **Instal dependensi yang diperlukan:**

    Sangat disarankan untuk membuat *virtual environment* terlebih dahulu.

    ```bash
    pip install -r requirements.txt
    ```

    *(**Catatan:** Pastikan Anda memiliki file `requirements.txt` yang berisi daftar semua pustaka Python yang digunakan dalam proyek, seperti `tensorflow` atau `pytorch` (sesuai pilihan framework Anda), `pandas`, `numpy`, `scikit-learn`, `nltk`, `sastrawi`, dll.)*

4.  **Buka notebook Jupyter:**

    ```bash
    jupyter notebook
    ```

    Setelah itu, navigasikan ke file `.ipynb` yang berisi laporan dan implementasi kode Anda untuk memulai analisis.

---

## Struktur Proyek

* `notebooks/`: Berisi file Jupyter Notebook (`.ipynb`) utama yang mendetailkan analisis, implementasi model, dan hasil.
* `data/`: Direktori untuk menyimpan dataset (jika diunduh secara lokal).
* `models/`: Direktori untuk menyimpan model CNN yang telah dilatih.
* `utils/`: (Opsional) Berisi skrip Python pendukung untuk pra-pemrosesan data, fungsi pembantu, dll.
* `requirements.txt`: Daftar pustaka Python yang diperlukan untuk menjalankan proyek.
* `README.md`: Berkas ini, memberikan gambaran umum proyek.