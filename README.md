# Implementasi dan Evaluasi CNN From Scratch serta Transfer Learning MobileNetV2 untuk Klasifikasi Citra Cats and Dogs

## Nama Mahasiswa

* Nama: Meutia Mirah Asih
* NIM: 452024618092
* Program Studi: Informatika

## Deskripsi Singkat Project

Project ini bertujuan untuk membandingkan performa dua pendekatan Deep Learning, yaitu CNN From Scratch dan Transfer Learning menggunakan MobileNetV2, pada tugas klasifikasi citra kucing dan anjing (Cats vs Dogs). Evaluasi dilakukan menggunakan metrik accuracy, loss, grafik pelatihan, dan confusion matrix.

## Library yang Digunakan

* TensorFlow
* NumPy
* Matplotlib
* Scikit-Learn
* Pandas

## Cara Menjalankan Notebook

1. Clone atau download repository.
2. Install seluruh dependency yang terdapat pada file requirements.txt.
3. Jalankan perintah:

```bash
pip install -r requirements.txt
```

4. Buka file notebook menggunakan Jupyter Notebook atau VS Code.
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

| Model                           | Accuracy Testing |
| ------------------------------- | ---------------- |
| CNN From Scratch                | 58,57%           |
| Transfer Learning (MobileNetV2) | 64,29%           |

Hasil eksperimen menunjukkan bahwa MobileNetV2 menghasilkan performa yang lebih baik dibandingkan CNN From Scratch pada dataset Cats and Dogs.

## Kesimpulan Singkat

Berdasarkan hasil pengujian, Transfer Learning menggunakan MobileNetV2 memberikan akurasi yang lebih tinggi, proses pelatihan yang lebih cepat, serta kemampuan generalisasi yang lebih baik dibandingkan CNN From Scratch. Oleh karena itu, Transfer Learning menjadi pendekatan yang lebih efektif untuk dataset dengan jumlah data terbatas.
