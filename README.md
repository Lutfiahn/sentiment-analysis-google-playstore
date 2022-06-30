# NLP domain about sentiment analysis of Dana Aplication from Google Play Store

1. Pada tahapan data acquisition, menggunakan teknik scraping pada Google Play Store yang bertujuan untuk pengambilan data secara otomatis dari reviews pengguna aplikasi Dana, dengan jumlah 600 dataset
2. Setelah itu melakukan data exploration hasil dari google scraping, dan menggunakan sampling 100 100 dataset untuk sentimen positif dan negatifnya
3. Tahap selanjutnya yaitu prepocessing data, proses menyeleksi data text agar terstruktur tergantung dengan kondisi data text. Pada proses ini, kami menggunalan tahapan yaitu case folding, stopword removal dan stemming
4. Untuk mengetahui frekuensi kata yang sering muncul pada ulasan. Maka, dilakukan WordCloud untuk sentimen positif dan negatifnya
5. Pada tahap modelling, menggunakan model ML Linear SVC. Untuk vectorizernya digunakan TfidfVectorizer. Nilai akurasi yang didapatkan yaitu 61%, artinya nilai rendah disebabkan karena word normalizer atau pada koreksi kata tambahan tidak maksimal, sehingga penggunaan kata tidak baku dan kesalahan penulisan kata maupun singkatan pada kebiasaan pengguna Dana tidak ditangani dengan baik
6. Tahap terakhir, melakukan prediksi dengan memasukan reviews dan didapatkan sentimen yang sesuai

Berikut adalah WordCloud sentimen negatif hasil dari review pengguna Dana
![sentiment negatif](https://user-images.githubusercontent.com/96588066/176737418-63cfb98b-52f4-48a6-90c0-56b37771008b.png)
