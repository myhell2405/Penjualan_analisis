# 📊 Analisis Data Penjualan Ritel Sederhana (EDA)

Proyek ini bertujuan untuk menganalisis data transaksi penjualan harian menggunakan Python, Pandas, dan visualisasi data interaktif di Jupyter Notebook sebagai bagian dari portofolio Data Analytics.

---

## 🗃️ Dataset

Dataset tersimpan dalam berkas penjualan.csv yang berisi rekaman transaksi penjualan dengan skema atribut:

| Kolom | Tipe | Deskripsi |
|---|---|---|
| **Tanggal** | String / Date | Waktu transaksi pembelian |
| **Produk** | String | Nama item produk terjual |
| **Kategori** | String | Klasifikasi produk (Makanan / Minuman / dsb.) |
| **Harga** | Integer | Harga satuan per produk (IDR) |
| **Jumlah** | Integer | Kuantitas unit yang dibeli |

---

## 🛠️ Tools & Library

- **Python 3.10+**
- **Jupyter Notebook**
- **Pandas** (Data manipulation, feature engineering)
- **Matplotlib & Seaborn** (Data visualization & charts)

---

## 🔍 Tahapan Analisis (Exploratory Data Analysis)

1. **Feature Engineering**: Menghitung metrik penerimaan Total = Harga × Jumlah.
2. **Top Selling Analysis**: Mengidentifikasi produk terlaris berdasarkan kuantitas dan total pendapatan.
3. **Category Breakdown**: Menghitung kontribusi persentase penjualan tiap kategori barang.
4. **Trend Analysis**: Menelaah pola penjualan harian untuk evaluasi performa penjualan.

---

## 📁 Struktur Berkas

`	ext
Penjualan_analisis/
├── eda_penjualan.ipynb       # Jupyter Notebook eksplorasi dan visualisasi data
├── penjualan.csv             # Data transaksi penjualan mentah
├── penjualan_analisis.csv    # Dataset hasil transformasi dan penambahan fitur
├── .gitignore                # Aturan pengabaian berkas cache/lingkungan
└── README.md                 # Dokumentasi proyek
`

---

## 👤 Pengembang

**Helmy Akrim, S.Kom**  
*Sarjana Sistem Informasi \| Data & Systems Analyst*