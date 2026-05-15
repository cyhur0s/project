# Proyek Analisis Data E-Commerce

## Deskripsi Proyek

Proyek ini merupakan analisis data e-commerce untuk memahami performa bisnis berdasarkan revenue, review score, pertumbuhan transaksi bulanan, perilaku pelanggan, dan distribusi transaksi berdasarkan wilayah.

Analisis dilakukan menggunakan dataset e-commerce yang terdiri dari data orders, customers, products, order items, payments, reviews, dan product category translation.

## Pertanyaan Bisnis

1. Kategori produk apa yang mengalami penurunan total revenue terbesar pada Q3 2018 dibandingkan Q2 2018?
2. Produk kategori apa yang memiliki jumlah order tertinggi namun review score di bawah rata-rata selama tahun 2018?
3. Bagaimana pertumbuhan jumlah transaksi bulanan Month-over-Month sepanjang tahun 2017 hingga 2018?

## Tahapan Analisis

Proyek ini mencakup:

- Data Wrangling
- Assessing Data
- Cleaning Data
- Exploratory Data Analysis
- Visualization & Explanatory Analysis
- RFM Analysis
- Geospatial Analysis
- Clustering sederhana menggunakan manual grouping dan binning
- Conclusion & Recommendation

## Struktur Folder

```text
Submission/
├── dashboard/
│   ├── dashboard.py
│   └── main_data.csv
├── E-Commerce Public Dataset/
│   ├── customers_dataset.csv
│   ├── orders_dataset.csv
│   ├── order_items_dataset.csv
│   ├── order_payments_dataset.csv
│   ├── order_reviews_dataset.csv
│   ├── products_dataset.csv
│   └── product_category_name_translation.csv
├── Proyek_Analisis_Data.ipynb
├── README.md
└── requirements.txt

