

# PRAKTIKUM PEMROGRAMAN WEB 5

## Praktikum

Praktikum javascript pertemuan 7. Praktikum dilakukan dengan mengikuti petunjuk pada modul yang sudah disediakan.

## 1. Konsol

Konsol dapat berfungsi untuk menampilkan output dalam bentuk text maupun digunakan sebagai debugging.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/1_ss.jpg)

Konsol pada browser dapat ditampilkan menggunakan `console.log();` yang nantinya akan tampil pada tab console di dalam developer mode pada browser misalnya chrome.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/1_code.jpg)

## 2. Alert

Alert pada javascript biasanya digunakan untuk memunculkan jendela dialog yang dapat berisi text. Tampilan jendela dialog dibawah ini adalah tampilan default dari browser chrome. Tampilan pada browser lain mungkin berbeda.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/2_ss.jpg)

Untuk menampilkan alert pada javascript dapat menggunakan syntax `window.alert()`.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/2_code.jpg)

## 3. Prompt

Prompt dalam javascript digunakan untuk menampilkan kotak dialog yang meminta user untuk memasukan input.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/3_ss.jpg)

Input yang dimasukan dapat dipakai kembali sebagai variabel.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/3a_ss.jpg)

Prompt dapat ditulis seperti berikut :

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/3_code.jpg)

## 4. Fungsi

Berikut adalah penulisan fungsi pada javascript yang dipanggil melalui atribut `onload` pada tag `<body>`.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/4_ss.jpg)

Alert diatas dipanggil saat halaman sudah selesai di muat dengan menggunakan atribut `onload`.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/4_code.jpg)

## 5. Operator

Operator pada javascript hampir mirip dengan bahasa pemrograman seperti java atau lainnya.

 - ( + ) Penjumlahan
 - ( - ) Pengurangan
 - ( * ) Perkalian
 - ( / ) Pembagian
 - ( % ) Sisa bagi

Tombol yang digunakan pada contoh yang digunakan untuk memanggil fungsi `test(val1, val2)`.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/5_ss.jpg)

Hasil dari operator nilai 9 (val1) dan 4 (val2) :

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/5a_ss.jpg)

Operator dapat ditulis dan ditampilkan secara langsung dengan menggunakan syntax `document.write()`.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/5_code.jpg)

## 6. Kondisi dengan Input

Penulisan kondisi menggunakan `if` dan `else` pada javascript. Contohnya seperti dibawah ini dimana variabel `nilai`  membutuhkan nilai 60 untuk mendapatkan output "**lulus**" dan dibawahnya untuk mendapatkan output "**tidak lulus**".

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/6_code.jpg)

Input pada jendela dialog menggunakan `prompt`.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/6_ss.jpg)

Hasil dari nilai 60 yang di input menghasilkan output "lulus".

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/6a_ss.jpg)


## 7. Switch

Switch digunakan untuk memilih aksi yang akan dilakukan dengan memasukan input.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/7_ss.jpg)

Nilai yang tersedia ada di antara 1 - 5 untuk menghasilkan output yang sudah didefinisikan terlebih dahulu sebelumnya.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/7a_ss.jpg)

Penulisan switch pada untuk menghasilkan output seperti diatas :

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/7_code.jpg)

## 8. Form Input

Fungsi dibawah ini dipanggil menggunakan atribut `onclick=test()` yang ditulis didalam tag `<input>` yang membentuk tombol "TEBAK" dan akan menampilkan output sesuai input yang dimasukan pada input seperti berikut.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/8_code.jpg)

Input "3" yang dimasukan oleh user akan menghasilkan output "bilangan ganjil" yang terdapat pada field input lainnya setelah mengeksekusi tombol "**TEBAK**".

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/8_ss.jpg)

## 9. Form Button

Warna background dan warna text akan berganti saat tombol di eksekusi.
Untuk keterangan waktu modifikasi akan diupdate saat tombol dieksekusi.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/9_ss.jpg)

Fungsi `ubahWarnaLB` dan `ubahWarnaLD` akan dipanggil pada tag `<input>` dengan atribut `type=button` yang terdapat didalam tag `<form>`.

Syntax `document.lastModified` digunakan untuk mengembalikan nilai berupa string yang memiliki output berupa waktu dan tanggal.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/9_code.jpg)

## 10. Checkbox dengan perhitungan otomatis

Input dibawah ini berisi nilai dari harga makanan yang dapat dipilih dengan melakukan check pada checkbox.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/10_ss.jpg)

Nilai yang ada pada input diatas didapat dengan menjalankan fungsi `hitung`. Nilai yang akan dikalkulasi terdapat pada atribut `value` di dalam tag `<input>`.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/10_code.jpg)

## 11. Validasi Input pada form

Validasi input mengharuskan input sesui dengan kondisi yang sudah ditentukan.

![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/11_ss.jpg)

Pada contoh di atas input harus di isi dan akan tampil jendela dialog apabila melakukan submit sebelum input diisi.

Cara kerja kode di bawah ini adalah mengecek terlebih dahulu data yang akan dikirimkan ke alamat tujuan. Tag `<input>` yang mempunyai atribut value `name="nama"` adalah input yang harus di isi oleh user. Jika input tidak di isi data yang dikirimkan adalah kosong dan akan di cek oleh fungsi `validasiInput` sebelum benar-benar dikirim ke alamat "submit.php" pada form html. Fungsi akan mengembalikan nilai `false` jika data yang dikirim kosong dan pengiriman data akan dibatalkan lalu memunculkan jendela dialog dengan pesan "Nama harus diisi!".
 
![enter image description here](https://github.com/antonmartinus72/Lab5Web/raw/main/assets/11_code.jpg)

## Sekian & Terimakasih.