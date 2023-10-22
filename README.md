
# Data Preproccessing

Mengubah ke format yang mempunyai kegunaan juga sangat tepat, dimana hal ini terjadinya dari sebuah teknik yang digunakan untuk mengubah data mentah.

Ini projek skrip pemrograman pada bahasa python terhadap library pandas, dimana sebuah data mentah akan diubah menjadi sangat efisien dan berguna terhadap teknik yang digunakan.

Penjelasan Penyelesaian Data Preprocessing:

```python
import pandas as pd
dataset = pd.read_csv('arxiv_papers.csv')
```
- Baris pertama mengimport library pandas dan memberikan alias pd.
- Baris kedua membaca file csv dengan nama 'arxiv_papers.csv' dan menyimpannya ke dalam variabel dataset.

```python
dataset
```
- Menampilkan seluruh isi dataset.

```python
dataset.head()
```
- Menampilkan 5 baris pertama dari dataset.

```python
dataset.tail()
```
- Menampilkan 5 baris terakhir dari dataset.

```python
dataset.info()
```
- Menampilkan informasi mengenai dataset, seperti jumlah baris dan kolom, tipe data, dan jumlah nilai null pada setiap kolom.

```python
dataset.isnull().sum()
```
- Menampilkan jumlah nilai null pada setiap kolom dataset.

```python
dataset = dataset.dropna()
```
- Menghapus baris yang memiliki nilai null dari dataset.

```python
dataset.isnull().sum()
```
- Menampilkan jumlah nilai null pada setiap kolom dataset setelah baris yang memiliki nilai null dihapus.

```python
dataset.describe()
```
- Menampilkan ringkasan statistik dari dataset, seperti rata-rata, standar deviasi, nilai minimum, kuartil, dan nilai maksimum dari setiap kolom.

Dari skrip tersebut, dapat disimpulkan bahwa langkah-langkah data preprocessing yang dilakukan adalah menghapus baris yang memiliki nilai null pada dataset.

Citations:
[1] https://www.datacamp.com/tutorial/pandas-read-csv
[2] https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html
[3] https://realpython.com/pandas-python-explore-dataset/
[4] https://realpython.com/python-data-cleaning-numpy-pandas/
[5] https://pandas.pydata.org/docs/dev/getting_started/intro_tutorials/02_read_write.html
[6] https://stackoverflow.com/questions/42165649/pandas-read-csv-filenotfounderror-file-b-xe2-x80-xaaetc-despite-correct-pat


## 🔗 Link Data Diri
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anugrahak)


## Authors

- [@aanggaanugrahhakk](https://github.com/aanggaanugrahhakk)


## Identitas Authors

Nama: Anugrah AK.

NIM: 202131037

Kelas: C
