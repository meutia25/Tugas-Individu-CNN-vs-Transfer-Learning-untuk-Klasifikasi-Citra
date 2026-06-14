# Implementasi dan Evaluasi CNN From Scratch serta Transfer Learning MobileNetV2 untuk Klasifikasi Citra

## Nama Mahasiswa

* Nama: Meutia Mirah Asih
* NIM: 452024618092
* Program Studi: Teknik Informatika

## Deskripsi Singkat Project

Project ini bertujuan untuk membandingkan performa dua pendekatan Deep Learning, yaitu CNN From Scratch dan Transfer Learning menggunakan MobileNetV2. CNN From Scratch diimplementasikan menggunakan dataset CIFAR-10 yang terdiri dari 10 kelas objek, sedangkan Transfer Learning menggunakan MobileNetV2 diterapkan pada dataset Cats vs Dogs. Evaluasi dilakukan menggunakan metrik accuracy, loss, confusion matrix, serta visualisasi grafik pelatihan.

## Library yang Digunakan

* TensorFlow
* NumPy
* Matplotlib
* Scikit-Learn
* Pandas
* Seaborn

## Cara Menjalankan Notebook

1. Clone atau download repository.
2. Install seluruh dependency yang terdapat pada file requirements.txt.
3. Jalankan perintah:

```bash
pip install -r requirements.txt
```

4. Buka file notebook menggunakan Jupyter Notebook, VS Code, atau Google Colab.
5. Jalankan seluruh cell secara berurutan.

## Struktur Folder Project

```text
project/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
└── laporan.pdf
```

## Ringkasan Hasil Eksperimen

| Model                           | Dataset      | Accuracy Testing             |
| ------------------------------- | ------------ | ---------------------------- |
| CNN From Scratch                | CIFAR-10     | (isi sesuai hasil pengujian) |
| Transfer Learning (MobileNetV2) | Cats vs Dogs | 64,29%                       |

Hasil eksperimen menunjukkan bahwa Transfer Learning menggunakan MobileNetV2 mampu memberikan performa yang baik pada dataset Cats vs Dogs, sedangkan CNN From Scratch digunakan untuk mempelajari klasifikasi multi-kelas pada dataset CIFAR-10.

## Kesimpulan Singkat

CNN From Scratch berhasil diterapkan pada dataset CIFAR-10 untuk melakukan klasifikasi 10 kelas objek. Transfer Learning menggunakan MobileNetV2 berhasil diterapkan pada dataset Cats vs Dogs dan memperoleh performa yang baik dengan proses pelatihan yang lebih efisien. Hasil ini menunjukkan bahwa Transfer Learning dapat menjadi solusi yang efektif ketika memanfaatkan model yang telah dilatih sebelumnya, sementara CNN From Scratch memberikan pemahaman yang lebih mendalam mengenai proses pembelajaran jaringan saraf konvolusional.
