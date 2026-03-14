# E-Commerce Data Analysis & Dashboard 📊

## Deskripsi Proyek
Proyek ini merupakan analisis data komprehensif pada dataset E-Commerce publik. Tujuan utama dari proyek ini adalah untuk menganalisis dan memahami distribusi metode pembayaran yang digunakan oleh pelanggan, serta mengidentifikasi kategori produk dengan performa transaksi tertinggi. Proyek ini mencakup proses *data wrangling*, *exploratory data analysis* (EDA), dan pembuatan *dashboard* interaktif menggunakan Streamlit.

## Pertanyaan Bisnis
1. Bagaimana distribusi penggunaan metode pembayaran berdasarkan kategori produk?
2. Bagaimana distribusi total transaksi berdasarkan metode pembayaran secara keseluruhan?
3. Bagaimana perbandingan jumlah transaksi antara 5 kategori produk dengan transaksi tertinggi?
4. Manakah kategori yang memiliki jumlah transaksi terbanyak?
5. Bagaimana distribusi metode pembayaran pada kategori produk dengan jumlah transaksi terbanyak?

## Arsitektur & Teknologi
* **Bahasa Pemrograman:** Python 3.9+
* **Manipulasi Data:** Pandas, NumPy
* **Visualisasi Data:** Matplotlib, Seaborn
* **Dashboard/Aplikasi Web:** Streamlit

## Struktur Direktori
```text
├── dashboard/
│   ├── dashboard.py
│   └── Dataframe_proyek_analisis_data.csv
├── data/
│   ├── order_items_dataset.csv
│   ├── order_payments_dataset.csv
│   ├── product_category_name_translation.csv
│   └── products_dataset.csv
├── Proyek_Analisis_Data E-Commerce Dataset V2.ipynb
├── requirements.txt
└── README.md
```

## Setup Environment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run steamlit app
```
streamlit run dashboard.py
```
