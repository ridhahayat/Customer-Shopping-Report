# Customer Shopping Report

## Business Understanding

Perusahaan ritel ingin memahami perilaku konsumen dan pola pembelian untuk meningkatkan strategi pemasaran, mengoptimalkan penempatan produk, serta efisiensi operasional.

### Tujuan Bisnis:
- Mengetahui kategori produk yang paling banyak menghasilkan pendapatan.
- Mengidentifikasi pola belanja berdasarkan waktu (musiman, bulanan).
- Menganalisis perbedaan perilaku belanja berdasarkan gender dan usia.
- Menentukan shopping mall dengan performa terbaik.
- Mengevaluasi efektivitas metode pembayaran.

### Rumusan Masalah:
- Produk atau kategori apa yang paling banyak memberikan kontribusi terhadap total pendapatan?
- Bagaimana pola pembelian pelanggan berdasarkan waktu dan demografi?
- Mall mana saja yang menunjukkan performa penjualan terbaik?
- Metode pembayaran apa yang paling sering digunakan oleh pelanggan?

---

## Dataset

Dataset yang digunakan adalah `customer_shopping_data.csv` yang memuat informasi transaksi pelanggan. Beberapa fitur utama:

- `Invoice ID`: ID transaksi
- `Branch`: Kode cabang/mall
- `Customer type`: Tipe pelanggan (Member/Normal)
- `Gender`, `Age`: Demografi
- `Product line`: Kategori produk
- `Unit price`, `Quantity`: Detail pembelian
- `Tax`, `Total`: Nilai transaksi
- `Date`, `Time`: Informasi waktu
- `Payment`: Metode pembayaran
- `Rating`: Feedback dari pelanggan

---

## Data Preparation & Cleaning

Beberapa langkah penting dalam preprocessing:
- Pengecekan missing values dan duplikat
- Konversi tipe data pada kolom waktu (`Date`, `Time`)
- Pembuatan kolom tambahan: hari, bulan, jam
- Koreksi format numerik dan string

---

## Exploratory Data Analysis (EDA)

Visualisasi dan analisis yang dilakukan mencakup:
- **Distribusi demografi** pelanggan (gender, usia)
- **Kategori produk** terlaris dan kontribusi terhadap pendapatan
- **Performa cabang/shopping mall**
- **Waktu belanja favorit** pelanggan (jam, hari, bulan)
- **Preferensi metode pembayaran**
- **Korelasi antar variabel** menggunakan heatmap

---

## Insight Penting

- **Fashion accessories dan Food & beverages** merupakan kategori paling menguntungkan.
- **Puncak transaksi terjadi di siang hari** dan meningkat di akhir pekan.
- **Shopping mall "C" memiliki performa penjualan terbaik.**
- Pelanggan pria cenderung membeli dalam kuantitas lebih tinggi dibanding wanita.
- **E-wallet menjadi metode pembayaran paling populer.**

---

## Tools & Library

- Python (Pandas, NumPy)
- Matplotlib & Seaborn (visualisasi)
- Jupyter Notebook

---

## Kesimpulan & Rekomendasi

- Fokus promosi pada kategori produk unggulan seperti *Fashion Accessories*.
- Optimalisasi stok dan tenaga kerja di jam sibuk (sekitar pukul 13.00–15.00).
- Pengembangan fitur loyalitas berbasis e-wallet dan preferensi belanja masing-masing demografi.
- Evaluasi strategi cabang dengan performa rendah agar selaras dengan mall yang sukses.

---

