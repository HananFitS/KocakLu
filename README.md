# KocakLu

# Tugas Besar 2 IF3070 Dasar Inteligensi Artifisial
## Implementasi Algoritma Pembelajaran Mesin

### Kelompok TUCIL 2 55 & 52
#### Group Number: 31

Group Members:
- Muhammad Fadhil Atha (18221003)
- Nicholas Francis Aditjandra (18221005)
- Hanan Fitra Salam (18222133)
- Salsabila Azzahra (18222139)

Spesifikasi Tugas Besar:
Pembelajaran mesin merupakan salah satu cabang dari kecerdasan buatan yang memungkinkan sistem untuk belajar dari data dan membuat prediksi atau keputusan tanpa diprogram secara eksplisit.

Pada tugas ini, Anda diminta untuk mengimplementasikan algoritma pembelajaran mesin yang telah kalian pelajari di kuliah, yaitu KNN dan Gaussian Naive-Bayes pada dataset PhiUSIIL Phising URL Dataset.

Untuk informasi lebih lengkap bisa cek di bagian doc dengan nama file:

Spesifikasi Tugas Besar 2 IF3070 Dasar Inteligensi Artifisial 2024_2025.docx

## Cara melakukan run
    import pandas as pd
    import numpy as np
    from sklearn.model_selection import train_test_split
    from sklearn.naive_bayes import GaussianNB
    from sklearn.metrics import classification_report, accuracy_score
    from sklearn.preprocessing import LabelEncoder
    import joblib
    from google.colab import drive
    from collections import defaultdict
    from sklearn.base import BaseEstimator, TransformerMixin
    from sklearn.preprocessing import MinMaxScaler
    from sklearn.utils import resample
    from sklearn.pipeline import Pipeline
    from sklearn.neighbors import KNeighborsClassifier

## Dataset yang digunakan:
Kami menggunakan dataset train sebagai dataset utama yang digunakan untuk training dan testing. Dataset test digunakan untuk mengevaluasi performa model.

## Pembagian Tugas:

| Nama | NIM | Tugas |
| --- | --- | --- |
| Muhammad Fadhil Atha | 18221003 | Data cleaning & Naive Bayes |
| Nicholas Francis Aditjandra | 18221005 | Data Preprocessing |
| Hanan Fitra Salam | 18222133 | KNN |
| Salsabila Azzahra | 18222139 | Data cleaning |

## Attachment:
- [Hasil model](https://drive.google.com/drive/folders/1B865JgEohIhpIINODF0Uo5_bjV4nsJJx?usp=sharing)