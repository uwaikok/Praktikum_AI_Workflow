# Praktikum_AI_Workflow
2306144_Rifki A.D
Pembuatan Data Penjualan

Data berisi kolom: Tanggal, Produk, Jumlah Terjual, Stok, dan Harga Satuan.
Data ini kemudian disimpan sebagai file CSV.
Pembacaan dan Pemrosesan Data

CSV dibaca kembali ke dalam DataFrame menggunakan Pandas.
Dihitung Total Penjualan dan Keuntungan (dengan asumsi biaya produksi per unit adalah 10.000).
Data dicek apakah ada nilai kosong.
Instalasi dan Penggunaan Scikit-Learn

Instalasi scikit-learn untuk analisis lebih lanjut.
Model Prediksi Stok dengan Decision Tree

Fitur: Jumlah Terjual dan Stok
Target: Apakah stok kurang dari 5 atau tidak.
Model Decision Tree digunakan untuk memprediksi apakah stok cukup atau tidak.
Model diuji dengan train-test split (80-20), dan hasil akurasinya adalah 100% (mungkin karena dataset kecil).
