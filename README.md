# Sentimen-Analisis-Dengan-LSTM
Analisis sentimen dari scrapping google play store dengan word2vec sebagai embedding dan LSTM sebagai klasifikasi

1.Saya akan melakukan scrapping dari google play store.
2.Selanjutnya saya akan melakukan preprocessing data seperti melakukan cleansing, case folding,       tokenisasi, normalisasi, stopword dan stemming.
3.Lalu data yang telah dilakukan preprocessing akan dilakukan labelling dengan Roberta dari hasil     labelling ini dilanjutkan dengan split data dimana dalam percobaan ini saya menggunakan 20% data    test dan 80% data pelatihan.
4.Lalu setelah displit data maka akan dilakukan embedding yang bertujuan mengubah sebuah kalimat      tersebut membentuk vektor dan dapat dilanjutkan oleh model klasifikasi LSTM.
5.Setelah masuk kedalam model maka akan dilakukan pencarian hyperparameter yang terbaik dari          berdasarkan dari epoch dan batch_sizes serta mnenggunakan optimasi adam dalam pembelajaran ini.
6.Terakhir dari hasil poin 5 akan mendapat hyperparameter terbaik dan nilai akurasi serta meanmpilkan grafik, klasifikasi report dan wordcloud.
