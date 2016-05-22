# Resume Node JS

## Filosofi
Node JS di tulis dengan bahasa C, C++ dan Node JS. NodeJS adalah sebuah platform untuk membangun real-time application. Node JS menggunakan teknik non-blocking jadi setiap eksekusi dilakukan secara independen. NodeJS dapat menangani event input-output server, dengan kata lain NodeJS dapat memungkinkan para developer Javascripts untuk membuat event-driven servers dalam JavaScript. 

## Kelebihan
+ Karena menggunakan teknik non-blocking Node JS dapat berjalan sangat cepat.
+ Node JS memiliki banyak library.
+ Cocok digunakan dengan Mongo dan Angular karena sama-sama menggunakan JavaScript.


## Kekurangan
+ Karena menggunakan teknik non-blocking sangat sulit menggatur perintah yang dependent, contoh-nya ketika kita membutuhkan data dari dua database, yang mana eksekusi database ke 2 bergantung pada hasil dari eksekusi database ke 1.


## Struktur
### Threading
Node JS beroprasi dengan single thread, menggunakan non-blocking I/O, dengan begini Node JS bisa menghandle banyak request tanpa secara langsung tanpa menggunakan context switching. Jadi setiap fungsi yang menggunakan I/O harus menggunakan callback function jadi aplikasi tidak akan terganggu oleh proses I/O. 

### Package Management
npm (Node Package Manager) adalah package manager yang telah terinstall ketika kita menginstall Node JS. npm digunakan untuk mengatur library yang dipakai dalam Node JS.

## Contoh Penggunaan Node JS
+ Aplikasi Chating.
+ Aplikasi Real-Time.

[Node JS Website.] (https://nodejs.org/en/)

