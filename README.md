
# Data Preproccessing

Mengubah ke format yang mempunyai kegunaan juga sangat tepat, dimana hal ini terjadinya dari sebuah teknik yang digunakan untuk mengubah data mentah.

Ini projek skrip pemrograman pada bahasa python terhadap library pandas, dimana sebuah data mentah akan diubah menjadi sangat efisien dan berguna terhadap teknik yang digunakan.

Penjelasan Penyelesaian Data Preprocessing di Skrip:

- `import pandas as pd`: Ini mengimpor pustaka pandas dan memberinya alias 'pd'.
- `dataset = pd.read_csv('arxiv_papers.csv')`: Ini membaca file CSV 'arxiv_papers.csv' dan membuat DataFrame pandas bernama 'dataset'.
- `dataset`: Baris ini hanya menampilkan seluruh DataFrame 'dataset'
- `dataset.head()`: Baris ini menampilkan 5 baris pertama dari DataFrame 'dataset'.
- `dataset.tail()`: Menampilkan 5 baris terakhir dari DataFrame 'dataset'.
- `dataset.info()`: Menampilkan informasi mengenai DataFrame 'dataset', termasuk jumlah baris dan kolom, tipe data setiap kolom, dan jumlah memori yang digunakan.
- `dataset.isnull().sum()`: Ini menampilkan jumlah nilai yang hilang (NaN) di setiap kolom DataFrame 'dataset'.
- `dataset = dataset.dropna()`: Ini akan menghapus semua baris dalam DataFrame 'dataset' yang berisi nilai yang hilang dan menetapkan DataFrame yang dihasilkan kembali ke 'dataset'.
- `dataset.isnull().sum()`: Ini menampilkan jumlah nilai yang hilang (NaN) di setiap kolom DataFrame 'dataset' yang telah diperbarui.
- `dataset.describe()`: Ini menampilkan statistik ringkasan untuk setiap kolom numerik dalam DataFrame 'dataset', termasuk jumlah, rata-rata, deviasi standar, nilai minimum, dan nilai maksimum.

Alur dari Skrip digunakan:
- Impor pustaka pandas dan beri nama alias 'pd'.
- Baca file CSV 'arxiv_papers.csv' dan buat DataFrame pandas bernama 'dataset'.
- Tampilkan seluruh DataFrame 'dataset'.
- Tampilkan 5 baris pertama dari DataFrame 'dataset'.
- Menampilkan 5 baris terakhir dari DataFrame 'dataset'.
- Menampilkan informasi tentang DataFrame 'dataset', termasuk jumlah baris dan kolom, tipe data setiap kolom, dan jumlah memori yang digunakan.
- Menampilkan jumlah nilai yang hilang (NaN) di setiap kolom DataFrame 'dataset'.
- Hapus setiap baris dalam DataFrame 'dataset' yang berisi nilai yang hilang dan tetapkan DataFrame yang dihasilkan kembali ke 'dataset'.
- Menampilkan jumlah nilai yang hilang (NaN) di setiap kolom DataFrame 'kumpulan data' yang telah diperbarui.
- Menampilkan statistik ringkasan untuk setiap kolom numerik dalam DataFrame 'dataset', termasuk jumlah, rata-rata, deviasi standar, nilai minimum, dan nilai maksimum.

Sitasi:
- [1] https://stackoverflow.com/questions/62980409/df-isnull-sum-is-still-showing-values-as-null-even-though-i-dropped-na-value
- [2] https://note.nkmk.me/en/python-pandas-nan-judge-count/
- [3] https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dropna.html
- [4] https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.isnull.html
- [5] https://pandas.pydata.org/docs/user_guide/missing_data.html
- [6] https://www.geeksforgeeks.org/python-pandas-dataframe-dropna/
- [7] https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html
- [8] https://www.datacamp.com/tutorial/pandas-read-csv
- [9] https://realpython.com/pandas-python-explore-dataset/
- [10] https://towardsdatascience.com/data-cleaning-with-python-and-pandas-detecting-missing-values-3e9c6ebcf78b
- [11] https://realpython.com/python-data-cleaning-numpy-pandas/
- [12] https://miamioh.edu/centers-institutes/center-for-analytics-data-science/students/coding-tutorials/python/data-cleaning.html

## 🔗 Link Data Diri
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anugrahak)


## Authors

- [@aanggaanugrahhakk](https://github.com/aanggaanugrahhakk)


## Identitas Authors

Nama: Anugrah AK.

NIM: 202131037

Kelas: C
