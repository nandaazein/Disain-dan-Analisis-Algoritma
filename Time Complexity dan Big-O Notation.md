Difana Nanda Pridhasila Zein

2110131220017
<br>
<br>
<center><h1><b>Time Complexity dan Big-O Notation</h1></b></center>

<p align="center"><img src="foto/jam.jpeg"></p>

<p align="justify">Kompleksitas suatu algoritma dibagi menjadi 2, yaitu <i>Time Complexity</i> dan <i>Space Complexity</i>.</p>
<p align="justify"><b>Time Complexity</b> adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma. Sedangkan <b>Space Complexity</b> adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma. Dan disini kita hanya akan membahas tentang Time Complexity.</p>

## **Algoritma**

~~Algorithm is a word used by programmers when they don't want to explain what they did~~

<p align="justify">Algorithm is a process or set of rules to be followed in calculations or other problem-solving operations, especially by a computer.</p>
<p align="justify">Sederhananya, algoritma adalah serangkaian proses yang dilakukan secara berurutan untuk menyelesaikan sebuah permasalahan.
Algoritma bisa bermacam-macam tergantung kepada siapa yang membuat algoritma tersebut. Namun permasalahannya adalah <b><i>algoritma mana yang lebih efektif dan efisien?</i></b></p>
<p align="justify"><b>Time Complexity Analysis</b> adalah suatu cara sederhana untuk mengetahui berapa lama waktu yang dibutuhkan untuk menjalankan suatu algoritma dengan input tertentu (n). Biasanya lebih dikenal dengan sebutan Big-O Notation. Big O Notation digunakan untuk mengukur tingkat kompleksitas suatu algoritma.</P>

## **So, What’s Big-O Notation?**
<p align="justify">Big-O Notation adalah cara untuk mengubah keseluruhan langkah dari suatu algoritme ke dalam suku-suku aljabar, kemudian mengecualikan konstanta dan koefisien orde rendah yang tidak memiliki dampak besar pada keseluruhan kompleksitas masalah, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.</p>
<p align="center"><img src="foto/contoh.jpeg"></p>

<p align="justify">Sederhananya, semua contoh yang ada diatas mengatakan bahwa <i>“kita hanya akan melihat faktor yang memiliki dampak paling besar terhadap nilai yang dihasilkan oleh algoritma tersebut”</i>.</p>
<p align="justify">Macam - macam <b>time complexity</b>, diantaranya : </p>

## **O(1) — Constant Time**
<p align="justify"><b>Constant Time</b> artinya banyaknya input yang diberikan kepada sebuah algoritma, tidak akan mempengaruhi waktu proses (runtime) dari algoritma tersebut.</p>

<p align="center"><img src="foto/ct.jpeg"></p>
<p align="justify">Berapapun jumlah array yang diberikan kepada fungsi tersebut, dia akan selalu melakukan 1 hal, yaitu mengambil elemen pertama. Itu artinya <b>jumlah input yang diberikan tidak mempengaruhi waktu proses (runtime) dari algoritma tersebut</b>.</p>

<p align="center"><img src="foto/gr1.jpeg"></p>

## **O(log n) — Logarithmic Time**

<p align="justify"><b>Logarithmic Time</b> artinya ketika kita memberikan input sebesar n terhadap sebuah fungsi, jumlah tahapan yang dilakukan oleh fungsi tersebut berkurang berdasarkan suatu faktor. Salah satu contohnya adalah algoritma Binary Search.</p>

<p align="justify"><b>Binary Search</b> adalah algoritma yang kita gunakan dalam mencari posisi nilai dari suatu array dengan cara ‘mengeliminasi’ setengah dari array input untuk mempercepat proses pencarian.</p>

<p align="center"><img src="foto/arr.jpeg"></p>

## **O(n) — Linear Time**

<p align="justify"><b>Linear Time</b> adalah ketika runtime dari fungsi kita berbanding lurus dengan jumlah input yang diberikan. </p>

<p align="center"><img src="foto/arrr.jpeg"></p>

<p align="justify"><b>semakin banyak jumlah input yang diberikan, maka waktu proses/runtime dari fungsi tersebut akan semakin besar.</b></p>

<p align="center"><img src="foto/linear.jpeg"></p>

## **O(n²) — Quadratic Time**

<p align="justify"><b>Quadratic Time</b> adalah ketika runtime dari fungsi kita adalah sebesar n^2, dimana n adalah jumlah input dari fungsi tersebut. Hal tersebut bisa terjadi karena kita menjalankan fungsi linear didalam fungsi linear (n*n).</p>
<p align="center"><img src="foto/arr2.jpeg"></p>

<p align="center"><img src="foto/qua.jpeg"></p>

## **O(2^n) — Exponential Time**

<p align="justify"><b>Exponential Time</b> biasanya digunakan dalam situasi dimana kita tidak terlalu tahu terhadap permasalahan yang dihadapi, sehingga mengharuskan kita mencoba setiap <b>kombinasi</b> dan <b>permutasi</b> dari semua kemungkinan.</p>

<p align="center"><img src="foto/exp.jpeg"></p>

## **Kesimpulan**

<p align="justify">Dengan memahami <b>Big-O Notation</b>, kita akan lebih mudah dalam melihat mana algoritma yang lebih efisien yang bisa kita gunakan untuk menyelesaikan permasalahan yang sedang dihadapi.</p>
