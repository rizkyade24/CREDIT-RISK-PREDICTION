# 🏦 CREDIT RISK PREDICTION NOTEBOOK 🏦 # Precision=1.0 # Accuracy=0.938

Proyek ini bertujuan untuk mengembangkan model machine learning yang dapat melakukan prediksi terkait risiko kredit pada calon peminjam. Risiko kredit merupakan faktor penting dalam pengambilan keputusan oleh lembaga keuangan, bank, atau perusahaan peminjaman lainnya. Dengan menggunakan data historis peminjam, model akan dilatih untuk mengidentifikasi kelayakan calon kreditur.

Metode:

Pengumpulan Data: Data historis peminjam, termasuk informasi pribadi, riwayat kredit, dan faktor-faktor lain yang relevan, akan dikumpulkan dan digunakan sebagai data pelatihan model.

Pra-pemrosesan Data: Data akan diproses dan dibersihkan untuk mengatasi missing values, outlier, dan mengkonversi data kategorikal menjadi bentuk numerik.
Pemodelan: Model XGBoost (Extreme Gradient Boosting) akan digunakan untuk melakukan pelatihan menggunakan data yang telah diproses. Model ini dipilih karena kemampuannya dalam mengatasi permasalahan klasifikasi seperti prediksi risiko kredit.

Evaluasi Model: Setelah proses pelatihan, model akan dievaluasi menggunakan berbagai metrik evaluasi seperti akurasi, precision, recall, F1 score, dan lainnya.

Penyimpanan Model: Model yang telah dilatih akan disimpan dalam bentuk file pickle sehingga dapat digunakan kembali untuk prediksi di masa mendatang.

Aplikasi Web: Model yang telah disimpan akan diintegrasikan ke dalam aplikasi web. Pengguna dapat memasukkan data calon peminjam melalui formulir pada aplikasi web dan model akan memberikan prediksi tentang risiko kredit dari calon peminjam tersebut.

Prediksi Risiko Kredit: Pengguna aplikasi web akan menerima hasil prediksi risiko kredit yang ditampilkan secara jelas dan mudah dipahami.

Manfaat:

Meningkatkan efisiensi proses pengambilan keputusan terkait pemberian kredit.
Memberikan panduan yang lebih akurat dalam menilai risiko kredit calon peminjam.
Mengurangi risiko kredit macet dan meningkatkan keamanan portofolio peminjaman.
Dengan proyek ini, diharapkan pengguna dapat dengan lebih cerdas dan efektif dalam mengelola risiko kredit, serta meningkatkan kualitas pengambilan keputusan terkait pemberian kredit kepada calon peminjam.

About Dataset
Detailed data description of Credit Risk dataset:

| Feature Name  | Description |
| ------------- | ------------- |
| person_age  | Age  |
| person_income  | Annual Income  |
| person_home_ownership  | Home ownership  |
| person_emp_length  | Employment length (in years)  |
| loan_intent  | Loan intent  |
| loan_grade  | Loan grade  |
| loan_amnt  | Loan amount  |
| loan_int_rate  | Interest rate |
| loan_status  | Loan status (0 is non default 1 is default)  |
| loan_percent_income  | Percent income  |
| cb_person_default_on_file  | Historical default  |
| cb_preson_cred_hist_length	  | Credit history length  |
