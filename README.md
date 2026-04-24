# Games Data Cleaning

## Deskripsi

Project ini bertujuan untuk membersihkan dan memperbaiki data kotor pada informasi mengenai beberapa game.

## Tujuan

- Menampilkan data game dari file CSV
- Melakukan deteksi kerusakan data, ketidakkonsistenan, dan memutuskan solusi.
- Memperbaiki data yang rusak dan tidak konsisten.
- Mengubah tipe data agar sesuai dengan jenis datanya.
- Mengkonversi format tanggal rilis agar seragam.
- Menghapus data yang tidak relevan atau duplikat
- Menyimpan file hasil pembersihan dalam format CSV

## Dataset

Dataset `games_dirty.csv` berisi informasi:

- Judul game
- Rating
- Tahun rilis

## Tools yang digunakan

- Python
- pandas
- Jupyter Notebook

## Analisis yang dilakukan

- Deteksi duplikat data
- Deteksi data yang hilang
- Deteksi data yang tidak konsisten
- Deteksi data yang tidak relevan

## Insight

- Beberapa data yang mengalami kerusakan antara lain:
  - Rating yang berupa string
  - Tahun rilis yang tidak sesuai dengan format tanggal
  - Adanya karakter tambahan pada data
  - Adanya data duplikat
  - Adanya data yang tidak relevan

## Cara Menjalankan

1. Install Python
2. Install library: pip install pandas jupyter
3. Jalankan file `analysis.ipynb`

## 👤 Author

Ryan
