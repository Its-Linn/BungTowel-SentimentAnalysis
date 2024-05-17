# BungTowel-SentimentAnalysis
Analisis Sentimen di Twitter Terhadap Bung Towel, menggunakan TextBlob Polarity / Lexicon Match

## Dataset
Data Diperoleh dari Hasil Crawling di Twitter dengan TweetHarvest

## Process
1. Pre Processing Data dengan Tweet-Processor (Tokenisasi, Stemming, dll)
2. Translating Data to EN dengan Deep-Translator
3. Hitung Polarity Dengan TextBlob dan Labeling
4. Train Naive Bayes Classifier Dengan Data
5. kemudian Klasifikasi Ulang Dataset

## Note
Data yang digunakan hanya berjumlah 200 baris dengan hasil akaurasi model NBC 0.73 atau 73%
