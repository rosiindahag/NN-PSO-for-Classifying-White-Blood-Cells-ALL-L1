Model klasifikasi Neural Networks Backpropagation (NN-BP) merupakan model multiclass untuk melakukan klasifikasi dari sel limfoblas dengan sel darah putih lainnya. Output dari model multiclass ini adalah sel limfoblas (label 1), non-limfoblas (label 0), dan non-limfoid (label 2). Pelabelan tersebut dikonversi menjadi bentuk one-hot encoding.
Nilai error diperoleh dari selisih hasil softmax function dengan nilai aslinya.

Parameter yang digunakan pada model ini ialah :
- Learning rate = 0,001
- Jumlah hidden node = 20
- Jumlah output node = 3
- Jumlah input node = jumlah fitur terpilih yang disesuaikan dengan hasil dari seleksi fitur
