# Prediksi Risiko Kredit untuk Pengambilan Keputusan Pinjaman: Meningkatkan Akurasi dan Efisiensi dalam Proses Penilaian
## Overview
Pada kesempatan ini saya akan dilibatkan dalam projek dari sebuah lending company. Saya akan berkolaborasi dengan berbagai departemen lain dalam projek ini untuk menyediakan solusi teknologi bagi company tersebut. Saya diminta untuk membangun model yang dapat memprediksi credit risk menggunakan dataset yang disediakan oleh company yang terdiri dari data pinjaman yang diterima dan yang ditolak. Selain itu Saya juga perlu mempersiapkan media visual untuk mempresentasikan solusi ke klien.

## Problem Statement
Company ingin membangun model yang dapat memprediksi risiko kredit dari aplikasi pinjaman yang diterima dan ditolak. Dengan adanya model ini, perusahaan berharap dapat meningkatkan keakuratan dalam menilai kelayakan pinjaman dan meningkatkan efisiensi dalam proses pengambilan keputusan.

## Business Metrics
- Tingkat Akurasi Prediksi: Persentase prediksi yang benar dari keseluruhan prediksi.
- Tingkat Presisi: Persentase aplikasi pinjaman yang ditolak secara benar dari total aplikasi yang sebenarnya beresiko.

## Objectives
1. Membangun model Machine Learning yang dapat memprediksi risiko kredit dengan akurasi yang tinggi.
2. Mengoptimalkan presisi model dalam mengidentifikasi aplikasi pinjaman yang berisiko.

Berdasarkan sifat masalah yang telah dijelaskan, yakni memprediksi risiko kredit dari data historis aplikasi pinjaman yang diterima dan ditolak, jenis supervised learning yang dapat kita gunakan adalah classification. Kita ingin mengklasifikasikan aplikasi pinjaman sebagai "berisiko" atau "tidak berisiko". Dalam konteks ini, model akan dilatih menggunakan data yang sudah diberi label (misalnya, status pinjaman) untuk memprediksi label kelas dari data baru yang belum pernah dilihat sebelumnya.

## Steps
1. Memahami Data: Pelajari dataset secara menyeluruh, periksa struktur data, identifikasi fitur-fitur penting, dan cek apakah ada nilai yang hilang atau perlu diproses.
2. Eksplorasi Data: Lakukan analisis statistik deskriptif dan visualisasi data untuk memahami pola dan relasi antar fitur dalam dataset.
3. Preprocessing Data: Lakukan preprocessing data seperti penanganan nilai yang hilang, normalisasi, dan pengkodean (jika perlu) untuk mempersiapkan data sebelum digunakan dalam pelatihan model.
4. Pemilihan Model: Pilih model klasifikasi yang sesuai dengan masalah yang ada. Contoh model yang bisa dipertimbangkan antara lain adalah Decision Trees, Random Forests, Logistic Regression, dan Support Vector Machines.
5. Pelatihan Model: Latih model menggunakan data pelatihan untuk mempelajari pola dalam data.
6. Evaluasi Model: Evaluasi kinerja model menggunakan metrik yang sesuai, seperti akurasi, presisi, recall, dan F1-score.
7. Optimisasi Model: Lakukan penyetelan parameter (jika diperlukan) untuk meningkatkan kinerja model.
8. Presentasi Solusi: Buat media visual yang jelas dan komunikatif, seperti grafik atau dashboard, untuk mempresentasikan hasil analisis dan prediksi model kepada klien atau pemangku kepentingan.
