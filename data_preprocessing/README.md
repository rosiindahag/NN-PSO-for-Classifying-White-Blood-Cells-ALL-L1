Data preprocessing contains :
1. Labelling
   Label yang digunakan untuk output berupa label angka. Output yang akan didefinisikan pada dataset terdiri dari 3 jenis output, yaitu :
   - Output 1
     Output 1 digunakan untuk mendefinisikan output pada NN-PSO tahap 1. Keluaran NN-PSO tahap 1 berupa label 0 = non-lymphoid, dan label 1 = lymphoid. Non-lymphoid terdiri dari sel darah putih selain jenis limfoid (limfoblas dan limfosit), sedangkan lymphoid terdiri dari sel darah putih jenis limfoid (limfoblas dan limfosit).
   - Output 2
     Output 2 digunakan untuk mendefinisikan output pada jenis klasifikasi model multiclass. Keluaran model classifier multiclass berupa label 0 = non-lymphoblast, label 1 = lymphoblast. dan label 2 = non-lymphoid. Seperti yang telah dijelaskan sebelumnya, non-lymphoid terdiri dari sel darah putih selain jenis limfoid (limfoblas dan limfosit), sedangkan lymphoid terdiri dari sel darah putih jenis limfoid (limfoblas dan limfosit). Namun pada model multiclass, jenis lymphoid dibedakan lagi menjadi lymphoblast dan non-lymphoblast. Non-lymphoblast ini merupakan kelompok jenis limfoid selain lymphoblast. Pada kasus ini, non-lymphoblast yang masuk kedalam dataset adalah lymphocyte.
   - Output 3
     Output 3 digunakan untuk mendefinisikan output pada NN-PSO tahap 2. Keluaran NN-PSO tahap 2 berupa label 0 = non-lymphoblast, dan label 1 = lymphoblast. Non-lymphoblast terdiri dari sel jenis limfoid selain lymphoblast. Pada kasus ini, non-lymphoblast yang masuk kedalam dataset adalah lymphocyte.

2. Normalization
   Metode normalisasi yang digunakan ialah metode min-max normalization dimana metode ini menggunakan nilai 1 sebagai nilai maksimal, nilai 0 sebagai minimal, dan nilai diantara 0 dan 1 untuk nilai lainnya
   
3. Splitting data into data training and testing
   Dataset dipisahkan menjadi data training sebanyak 80% dari total dataset dan data testing sebanyak 20% dari total dataset

4. Saving data training and testing
   Data training dan testing disimpan untuk digunakan pada algoritma seleksi fitur dan klasifikasi.
