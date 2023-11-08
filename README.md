Tugas 7

## Pertanyaan
1. Apa perbedaan utama antara stateless dan stateful widget dalam konteks pengembangan aplikasi Flutter?

Perbedaan antara stateless dengan stateful widget adalah stateless widget tidak dapat berubah-rubah atau tidak dinamis sehingga jika sudah dibuat, maka tidak ada perubahan data yang bisa dilakukan secara dinamis seperti perubahan data tabel, mengambil input pengguna dan semacamnya.

2. Sebutkan seluruh widget yang kamu gunakan untuk menyelesaikan tugas ini dan jelaskan fungsinya masing-masing.

Widget yang digunakan pada tugas ini ada widget wrapper yang berguna untuk supaya pagenya bisa di scroll, widget text untuk menampilkan tulisan dan widget untuk menampilkan children secara vertikal.

3. Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step (bukan hanya sekadar mengikuti tutorial)

Untuk mengimplementasikan checklist diatas, pertama-tama saya membuat class HomePage yang merupakan stateless widget dan juga membuat class Inventory yang memiliki atribut nama dan icon. Lalu saya membuat class Inventory card yang berguna sebagai card yang bisa dipencet seperti button, dan membuat snack bar dengan menerapkan onTap di dalam cardnya. Lalu pada class homepage saya membuat list dari inventory untuk menyimpan semua card atau button yang diinginkan. Lalu pada build di homepage saya membuat pagenya dan memunculkan card yang sudah dibuat tadi.