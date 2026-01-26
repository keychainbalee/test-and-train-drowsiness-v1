# Driver Drowsiness Detection (DDD)

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk membangun **model klasifikasi berbasis Deep Learning** yang mampu mendeteksi kondisi **kantuk pengemudi (driver drowsiness)** menggunakan citra wajah. Model dilatih menggunakan **Driver Drowsiness Dataset (DDD)** dari Kaggle dan diimplementasikan dalam bentuk *Jupyter Notebook* (`.ipynb`).

Deteksi kantuk pengemudi sangat penting dalam bidang **keselamatan berkendara**, karena dapat membantu mencegah kecelakaan lalu lintas akibat kelelahan atau mengantuk.

---

## 📂 Dataset

Dataset yang digunakan berasal dari Kaggle:

🔗 **Driver Drowsiness Dataset (DDD)**
[https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd](https://www.kaggle.com/datasets/ismailnasri20/driver-drowsiness-dataset-ddd)

### Isi Dataset

Dataset terdiri dari citra wajah pengemudi dengan dua kelas utama:

* **Drowsy** → Pengemudi mengantuk
* **Non-Drowsy** → Pengemudi tidak mengantuk

Citra dikumpulkan dari berbagai individu dengan variasi pencahayaan, pose wajah, dan ekspresi, sehingga cocok untuk melatih model klasifikasi berbasis CNN.

---

## 🧠 Metode yang Digunakan

* **Preprocessing Citra**

  * Resize gambar
  * Normalisasi pixel
  * Label encoding
* **Ekstraksi Fitur**

  * Menggunakan *Convolutional Neural Network (CNN)*
* **Modeling**

  * CNN dengan beberapa *Conv Layer*, *Pooling*, dan *Fully Connected Layer*
* **Evaluasi Model**

  * Accuracy
  * Loss
  * Confusion Matrix (jika tersedia)

---

## 🛠️ Library dan Tools

Proyek ini menggunakan beberapa pustaka Python berikut:

* `numpy`
* `pandas`
* `matplotlib`
* `opencv-python`
* `tensorflow / keras`
* `scikit-learn`

Pastikan seluruh library telah terinstal sebelum menjalankan notebook.

---

## 🚀 Cara Menjalankan Proyek

1. **Clone atau unduh repository**
2. **Unduh dataset dari Kaggle**

   ```bash
   kaggle datasets download ismailnasri20/driver-drowsiness-dataset-ddd
   ```
3. **Ekstrak dataset** ke direktori proyek
4. **Buka Jupyter Notebook**

   ```bash
   jupyter notebook trainingdrowsinesV1.ipynb
   ```
5. **Jalankan seluruh cell secara berurutan**

---

## 📊 Output yang Dihasilkan

* Model CNN untuk klasifikasi kantuk pengemudi
* Grafik training & validation accuracy
* Grafik training & validation loss
* Prediksi kondisi pengemudi (drowsy / non-drowsy)

---

## 🎯 Tujuan Pembelajaran

* Memahami alur *image classification* menggunakan CNN
* Menerapkan deep learning pada studi kasus dunia nyata
* Mengolah dataset citra untuk kebutuhan Computer Vision

---

## 📌 Catatan

* Akurasi model sangat dipengaruhi oleh jumlah data dan kualitas preprocessing
* Model dapat dikembangkan lebih lanjut menggunakan:

  * Transfer Learning (MobileNet, VGG, ResNet)
  * Real-time detection (OpenCV + Webcam)

---

## 👤 Author

**Muhammad Iqbal Saputra**
D-4 Teknik Informatika
Universitas Harkat Negeri, Tegal

---

## 📜 Lisensi

Dataset mengikuti lisensi dari Kaggle. Proyek ini digunakan untuk **tujuan akademik dan pembelajaran**.
