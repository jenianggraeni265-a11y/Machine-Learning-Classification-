# Machine-Learning-Classification-

# ❤️ Heart Disease Classification Machine Learning

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk membangun model klasifikasi dalam memprediksi kemungkinan seseorang menderita penyakit jantung berdasarkan berbagai fitur medis seperti usia, tekanan darah, kadar kolesterol, dan lainnya.

Dataset yang digunakan merupakan data klinis pasien yang telah diproses dan dianalisis menggunakan beberapa algoritma machine learning untuk مقارنة performa model.

---

## 📊 Dataset

Dataset terdiri dari **1025 observasi** dan **14 variabel**, dengan rincian:

* **Fitur (X):**

  * age → usia
  * sex → jenis kelamin
  * cp → tipe nyeri dada
  * trestbps → tekanan darah
  * chol → kolesterol
  * fbs → gula darah puasa
  * restecg → hasil EKG
  * thalach → detak jantung maksimum
  * exang → angina akibat olahraga
  * oldpeak → depresi ST
  * slope → kemiringan ST
  * ca → jumlah pembuluh darah
  * thal → kondisi thalassemia

* **Target (y):**

  * 0 → tidak memiliki penyakit jantung
  * 1 → memiliki penyakit jantung

---

## 🔍 Exploratory Data Analysis (EDA)

Beberapa analisis yang dilakukan:

* Distribusi target menunjukkan data **seimbang**
* Tidak terdapat **missing values**
* Analisis korelasi menunjukkan beberapa variabel penting seperti:

  * thalach
  * oldpeak
  * cp
  * ca
* Distribusi usia menunjukkan mayoritas pasien berada pada rentang usia menengah hingga lanjut

📌 Insight:
Dataset yang seimbang dan bersih membantu meningkatkan performa model klasifikasi.

---

## ⚙️ Metodologi

### 1. Data Preprocessing

* Split data train dan test (80:20)
* Normalisasi menggunakan **StandardScaler**

### 2. Model yang Digunakan

* 🌲 Random Forest (Bagging)
* 🚀 Gradient Boosting (Boosting)
* 🧠 Neural Network (MLP)
* 🤝 Ensemble (Voting Classifier)

---

## 📈 Hasil Model

| Model             | Accuracy |
| ----------------- | -------- |
| Random Forest     | 98.5%    |
| Gradient Boosting | 93.1%    |
| Neural Network    | 98.5%    |
| Ensemble          | 98.5%    |

---

## 🧠 Evaluasi Model

Contoh confusion matrix (Ensemble):

```
[[102   0]
 [  3 100]]
```

### Interpretasi:

* True Negative: 102
* True Positive: 100
* False Positive: 0
* False Negative: 3

📌 Insight:

* Model sangat baik dalam mengidentifikasi pasien sehat
* Namun masih terdapat sedikit kasus pasien sakit yang tidak terdeteksi (false negative)

---

## 🚀 Insight Penting

* Model memiliki akurasi sangat tinggi (~98.5%)
* Random Forest dan Neural Network memberikan performa terbaik
* Ensemble meningkatkan stabilitas prediksi
* Dataset relatif mudah dipelajari oleh model

⚠️ Dalam konteks medis:
False Negative lebih berbahaya karena pasien sakit tidak terdeteksi

---

## 🛠️ Teknologi yang Digunakan

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📌 Cara Menjalankan

1. Clone repository:

```
git clone https://github.com/username/repository-name.git
```

2. Masuk ke folder:

```
cd repository-name
```

3. Jalankan notebook di Google Colab / Jupyter Notebook

---

## 📎 Pengembangan Selanjutnya

* Hyperparameter tuning
* ROC Curve & AUC
* Feature Importance Analysis
* Cross Validation

---

## 👩‍💻 Author

Jeni Anggraeni
Mahasiswa Statistika

---

## ⭐ Catatan

Proyek ini dibuat untuk keperluan pembelajaran dan eksplorasi machine learning dalam bidang kesehatan.
