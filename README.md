# Travel Insurance

### Latar Belakang

Asuransi perjalanan adalah jenis asuransi yang memberikan perlindungan selama kita melakukan perjalanan baik di dalam negeri maupun di luar negeri. Beberapa negara bahkan telah mewajibkan para pelancong untuk memiliki asuransi perjalanan, misalnya negara-negara di Eropa dan Amerika. Besarnya premi tergantung dari pertanggungan yang diinginkan, lama perjalanan, dan tujuan perjalanan. Sebuah perusahaan yang bergerak di bidang asuransi perjalanan ingin mengetahui pemegang polis yang akan mengajukan klaim pertanggungan. Data pemegang polis pada perusahaan asuransi merupakan data historis yang terdiri dari tujuan, produk asuransi, dan lain sebagainya.

Target:

- 0 (No)  : Tidak melakukan klaim

- 1 (Yes) : Melakukan klaim

### Perumusan Masalah

Bagaimana melakukan analisis pelanggan menggunakan data (travel insurance) untuk mengidentifikasi dan memprediksi pelanggan yang memiliki risiko tinggi dalam mengajukan klaim?

Ini salah satu contoh risiko pada (travel insurance):
- Jika semakin lama pemegang polis berada di luar negeri, semakin besar kemungkinan mereka menghadapi kejadian yang membutuhkan klaim asuransi, seperti kehilangan bagasi atau kehilangan dokumen penting seperti parpor dll.

- Jika mengalami kecelakaan atau penyakit yang memerlukan perawatan medis selama perjalanan. Biaya medis di luar negeri bisa sangat mahal.

### Tujuan

Untuk memprediksi pelanggan yang akan klaim agar perusahaan dapat menetapkan premi yang sesuai dengan risiko yang terkait dan mengelola (travel insurance) mereka secara efektif.




### Analisis

- Analisis data historis untuk memahami pola dan tren yang ada.
- Melakukan pemrosesan data seperti membersihkan dan mengisi nilai yang hilang, mengkonversi variabel kategorikal menjadi numerik jika diperlukan.
- Memilih fitur-fitur yang paling relevan dalam memprediksi klaim asuransi perjalanan.
- Membagi data menjadi set pelatihan (training set) dan set pengujian (testing set).
- Menggunakan algoritma pembelajaran mesin seperti (decision tree classifier), (random forest classifier) atau algoritma lain yang sesuai untuk melatih model prediksi.
- Melakukan evaluasi model menggunakan (confusion matrix) yang tepat.

### Metric Evaluation

- Type 1 error : False Positive  
Type 1 Error (False Positive): Dalam konteks ini, Type 1 error mengacu pada kasus di mana model memprediksi bahwa seseorang akan melakukan klaim (1/Yes), tetapi pada kenyataannya orang tersebut tidak melakukan klaim (0/No).

- Type 2 error : False Negative  
Type 2 Error (False Negative): Dalam konteks ini, Type 2 error mengacu pada kasus di mana model memprediksi bahwa seseorang tidak akan melakukan klaim (0/No), padahal pada kenyataannya mereka sebenarnya akan melakukan klaim (1/Yes).
