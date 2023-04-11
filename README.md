# Web-Scrapping using Beautifulsoup

Projek ini dikembangkan sebagai salah satu capstone project dari Algoritma Academy Data Analytics Specialization. Deliverables yang diharapkan dari projek ini adalah melakukan simple webscrapping untuk mendapatkan informasi. Untuk step by step guide. Kita juga akan memanfaatkan flask dashboard sederhana untuk menampilkan hasil scrap dan visualisasi kita.

## Dependencies

- beautifulSoup4
- pandas
- flask
- matplotlib

Atau cukup menginstall requirements.txt dengan cara berikut

```python
pip install -r requirements.txt
```

## Rubics

- Environment preparation (2 points)
- Finding the right key to scrap the data  & Extracting the right information (5 points)
- Creating data frame & Data wrangling (5 points)
- Creating a tidy python notebook as a report. (2 points)
- Implement it on flask dashboard (2 points)


## What You Need to Do

* Silahkan mencoba melakukan scraping soal di bawah menggunakan `beautiful soup` di notebook terlebih dahulu.
* Silahkan buka notebook template pada capstone ini dan isi sesuai dengan arahan yang ada. Pastikan memberikan analisa yang dibutuhkan pada notebook tersebut.
* File di repo ini adalah skeleton yang dapat digunakan untuk membuat flask dashboard sederhana.
* Silahkan isi di bagian yang masih kosong.
* Isi fungsi `scrap` dengan proses scraping yang sudah dilakukan di notebook. 

```python
table = soup.find(___)
tr = table.find_all(___)
```

* Isi bagian ini untuk menyimpan hasil scrap yang telah dibuat menjadi sebuah dataframe.

```python
df = pd.DataFrame(name of your tupple, columns = (name of the columns))
```

* Terakhir menggunakan fungsi `scrap` dengan cara mengisi bagian berikut dengan link web yang di-scrap.

```python
df = scrap(___) #insert url here
```

* Kita juga dapat bermain dengan UI nya pada `index.html` yang dimana kita dapat mengikuti comment yang ada untuk mengetahui bagian mana yang dapat diubah. 

### The Final Mission

Pada captsone kali ini, dapat memilih salah satu soal ini untuk dikerjakan.

1. (Easy) Data Volume Penjualan Ethereum dari `https://www.coingecko.com/en/coins/ethereum/historical_data?start_date=2022-01-01&end_date=2023-03-30#panel`

   * Dari halaman tersebut carilah `Date`, dan `Volume`.
   * Buat lah plot pergerakan volume perdagangan dari Ethereum. 

2. (Medium) Data kurs US Dollar ke rupiah dari `https://www.exchange-rates.org/history/IDR/USD/T`

    * Dari halaman tersebut carilah `harga harian`, dan `tanggal`
    * Bualah plot pergerakan kurs USD 
    
3. (Hard) Data pekerjaan data di indonesia pada  `https://www.kalibrr.id/job-board/te/data/1`

    * Dari Halaman tersebut carilah `title pekerjaan` , `lokasi pekerjaan` , `tanggal pekerjaan di post dan dealine submit permohonan`, dan `perusahaan`
    * tariklah 15 halaman
    * Buatlah plot dari jumlah pekerjaan berdasarkan lokasi.


Happy learning! 
