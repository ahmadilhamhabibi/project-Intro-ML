# Analisis Hubungan Usia Pemain Sepakbola dan Menit Bermain

## Introduction
Dalam dunia sepakbola, manajer dan pelatih seringkali perlu membuat keputusan penting mengenai komposisi tim dan pengaturan pemain selama pertandingan. Salah satu aspek penting dalam pengambilan keputusan ini adalah memahami bagaimana usia seorang pemain dapat memengaruhi jumlah menit bermainnya di lapangan. Masalah ini memiliki dampak signifikan pada strategi tim, pengelolaan pemain, dan evaluasi performa individu.

Project ini penting karena dapat memberikan wawasan yang berharga kepada tim sepakbola, pelatih, dan manajer dalam pengambilan keputusan. Mengetahui hubungan antara usia pemain dan menit bermain dapat membantu tim dalam pengaturan rotasi pemain, manajemen kelelahan, dan pembuatan strategi permainan yang lebih baik. Hal ini juga dapat membantu dalam pengembangan pemain muda dengan cara yang lebih efektif.

## Related Work
- Paper 1: “The Age-Performance Relationship in Major League Baseball: Does One’s Age Predict One’s Performance?”
- Paper 2: “Effects of Age on Athletic Performance: Implications for the Athletic Talent Identification and Development”
- Paper 3: “The impact of player’s age on physical demands of European soccer”

## Dataset 
Data diperoleh dari FBREF, penelitian ini menggunakan data pemain La Liga tahun 2021–2022.

## Exploratory Data Analysis
EDA adalah langkah penting yang memberikan pemahaman tentang data yang akan kita analisis. Dalam konteks ini, kita akan fokus pada bagaimana usia pemain berkorelasi dengan menit bermain mereka. Usia pemain paling muda adalah 16 tahun, paling tua 40 tahun, dengan rata-rata usia adalah 26 tahun. Rata-rata menit bermain adalah 1217 menit, dengan menit bermain tertinggi adalah 3420 menit atau bermain penuh selama 90 menit dalam 38 pertandingan.

## Metode
### Linear Regeression
Metode Linear Regression adalah salah satu teknik statistik yang digunakan untuk menganalisis hubungan antara dua variabel atau lebih. Kali ini metode Linear Regression digunakan untuk memahami dan mengukur hubungan antara dua variabel, yaitu “Usia” (Age) dan “Menit Bermain” (Minutes Played) dalam konteks pemain sepakbola.
Berikut adalah penjelasan tentang bagaimana metode Linear Regression digunakan untuk melihat hubungan antara Usia dan Menit Bermain:
- Variabel Independen (X): Usia (Age) adalah variabel independen, yang merupakan variabel yang digunakan untuk memprediksi atau menjelaskan variabel dependen (yaitu, Menit Bermain).
- Variabel Dependen (Y): Menit Bermain (Minutes Played) adalah variabel dependen, yang merupakan variabel yang ingin kita pahami bagaimana hubungannya dengan usia.
- Model Linear Regression: Model Linear Regression mencoba untuk memodelkan hubungan antara Usia dan Menit Bermain sebagai garis lurus (linear).

## Experiment
Dalam eksperimen ini, penelitian mencoba untuk memperluas model regresi linear sederhana yang awalnya hanya menggunakan usia (Age) sebagai prediktor tunggal terhadap menit bermain. Eksperimen kali ini mencoba menambahkan dua variabel baru, yaitu Usia Kuadrat (Age_squared) dan Usia Pangkat Tiga (Age_cubed), dengan tujuan untuk melihat apakah dengan memasukkan variabel-variabel ini dapat meningkatkan pemahaman tentang hubungan antara usia dan menit bermain pemain sepakbola.

## Result
Hasil penelitian menunjukkan bahwa ada hubungan yang linear antara usia dan menit bermain. Namun saat kita menambahkan variabel Age_squared ke dalam model regresi linear, model tersebut memperlihatkan peningkatan kualitas dalam menjelaskan hubungan antara usia dan menit bermain. Namun, ketika variabel Age_cubed ditambahkan, model tersebut menjadi tidak relevan lagi, menunjukkan bahwa penambahan variabel Age_cubed tidak memberikan peningkatan yang signifikan dalam pemahaman hubungan tersebut.

## Conclusion
Dalam penelitian ini, kami menjalankan analisis regresi linear untuk memahami hubungan antara usia pemain sepakbola dan menit bermain. Kami memulai dengan model regresi linear sederhana yang hanya menggunakan variabel usia sebagai prediktor tunggal. Hasil awal menunjukkan bahwa model tersebut dapat menjelaskan sebagian variasi dalam menit bermain, namun terdapat indikasi bahwa hubungan ini mungkin lebih kompleks daripada yang dapat dijelaskan oleh model linear sederhana. Kemudian, kami melakukan eksperimen dengan menambahkan dua variabel baru, yaitu Age_squared dan Age_cubed ke dalam model regresi. Hasil eksperimen ini mengungkapkan bahwa penambahan variabel Age_squared secara signifikan meningkatkan kemampuan model dalam menjelaskan hubungan antara usia dan menit bermain. Age_squared juga memberikan pemahaman lebih baik tentang hubungan non-linear yang mungkin ada. Namun, penambahan variabel Age_cubed tidak memberikan manfaat yang signifikan dalam pemahaman hubungan ini. Model dengan variabel Age_cubed menjadi tidak relevan, menunjukkan bahwa penambahan variabel tersebut tidak diperlukan dalam analisis.

## Future Work
Proyek ini merupakan contoh penerapan Machine Learning sederhana dalam sepakbola. Dengan Linear Regression kita bisa mencari hubungan menit bermain dengan jumalah gol dan assist bagi penyerang, serta hubungan jumlah penyelamatan dengan menit bermain bagi penjaga gawang. Dalam course Soccormatics juga diberikan contoh penerapan Machine Learning lainnya, seperti: Logistic Regression untuk memprediksi Expected Goal, dan Poisson Regression untuk memprediksi hasil atau skor pertandingan.

## References
- pacmann.io
- soccermatics.readthedocs.io
- The Age-Performance Relationship in Major League Baseball: Does One’s Age Predict One’s Performance?
- Effects of Age on Athletic Performance: Implications for the Athletic Talent Identification and Development
- The impact of player’s age on physical demands of European soccer
