## Pada kegiatan ini kali ini, buatlah model Neural Network sederhana untuk melakukan klasifikasi biner dengan data berikut [Income Dataset](https://drive.google.com/drive/folders/1JNncgt0SFx8aP4C7NAN7wBonFRvH-k1n?usp=sharing) 

Dataset tersebut merupakan data tabular tentang pendapatan, dengan jumlah data sebanyak 43.958 dan jumlah fitur 15. Anda diminta untuk mengklasifikan mana yang memiliki pendapatan dibawah dan diatas 50k.

### Load Data & Preprocessing
<ol>
  <li>Load data train.csv dari link dataset yang diberikan</li>
  <li>Tampilkan 5 data teratas dan 5 data terbawah</li>
  <li>Tampilkan ringkasan statistik dari data tersebut</li>
  <li>Lakukan proses preprocessing data</li>
  <li>Lakukan splitting antara fitur dan target</li>
  <li>Lakukan splitting data menjadi 80% data train dan 20% data test</li>
</ol>

### Modelling
Buat arsitektur model dengan kriteria berikut:
<ol>
  <li>Gunakan 1 input layer, 1 hidden layer dan 1 output layer</li>
  <li>Gunakan aktifasi sigmoid pada output layer</li>
  <li>Compile model menggunakan loss *binary_crossentropy* dan metrics accuracy</li>
  <li>Lakukan proses training minimal 100 epocht</li>
</ol>

### Evaluasi
<ol>
  <li>Lakukan evaluate model</li>
  <li>Buatlah report klasifikasi beserta dengan keterangan labelnya.</li>
  <li>Dapat akurasi minimal 85%</li>
  <li>Lakukan ujicoba predict dengan data test.csv yang ada di link dataset yang diberikan</li>
</ol>
