# ChrEn (EMNLP 2020) -- Data

## Structure

```
|__ raw/ --> raw data, including data sources, dialect, etc.
     |__ parallel_data.xlsx  --> parallel data
     |__ monolingual_data.xlsx --> monolingual data
|__ parallel/ -->  parallel data splits
     |__ train.chr, train.en  --> training set
     |__ dev.chr, dev.en --> in-domain development set
     |__ test.chr, test.en --> in-domain testing set
     |__ out_dev.chr, out_dev.en --> out-of-domain development set
     |__ out_test.chr, out_test.en --> out-of-domain testing set
|__ monolingual/  --> Cherokee and English monolingual data
     |__ chr  --> Cherokee monolingual data (from monolingual_data.xlsx)
     |__ en5000, en10000, en20000, en50000, en100000  --> English monolingual data (from News Crawl 2017)
```