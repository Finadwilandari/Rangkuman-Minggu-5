# 15 Agustus 2022-19 Agustus 2022

>React adalah library JavaScript untuk membangun antarmuka pengguna.
React digunakan untuk membangun aplikasi satu halaman.
React memungkinkan kita untuk membuat komponen UI yang dapat digunakan kembali.

Contoh:

Memasukkan metode ReactDOM yang benar untuk merender elemen React ke DOM:

>ReactDOM.
(myElement, document.getElementById('root'));

create-react-app adalah cara yang didukung secara resmi untuk membuat aplikasi React.

Node.js diperlukan untuk menggunakan create-react-app.

Caranya dengan membuka terminal pada direktori yang ingin kita buat aplikasinya. Lalu kita menjalankan perintah ini untuk membuat aplikasi React bernama my-react-app:

>npx create-react-app my-react-app

create-react-app akan mengatur semua yang kita butuhkan untuk menjalankan aplikasi React.

Lalu jalankan perintah ini untuk pindah ke direktori my-react-app:

>cd my-react-app

Selanjutnya Jalankan perintah ini untuk menjalankan aplikasi React my-react-app:

>npm start

<img src="screenshot_myfirstreact.png" alt="100">

Sebelum memulai React.JS, kita harus memiliki pengalaman menengah dalam:
HTML
CSS
JavaScript

<b> React JSX </b>

JSX adalah singkatan dari JavaScript XML.
JSX memungkinkan kita untuk menulis HTML di React. JSX membuatnya lebih mudah untuk menulis dan menambahkan HTML di React.
>Dalam react js terdapat Ekstensi file  yaitu 'jsx, JSX dikembangkan untuk  digunakan pada react, yang dimana dapat menuliskan html dalam javasript file. Setiap JSX hanya dapat menerima 1 parent dan harus penulisan function diawali dengan huruf kapital.

JSX memungkinkan kita untuk menulis elemen HTML dalam JavaScript dan menempatkannya di DOM tanpa metode.
>createElement() 


<b> React Components </b>

Komponen adalah bit kode yang independen dan dapat digunakan kembali. Mereka melayani tujuan yang sama seperti fungsi JavaScript, tetapi bekerja secara terpisah dan mengembalikan HTML.
>Komponen juga memerlukan metode render(), metode ini mengembalikan HTML.

<b> React Class </b>

Contoh:
>const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<Car />);

<b> React Props </b>

Cara lain untuk menangani properti komponen adalah dengan menggunakan Props.

>Komponen React Class memiliki built-in state object. State object adalah tempat menyimpan nilai properti yang dimiliki komponen. Saat state object berubah, komponen dirender ulang.





