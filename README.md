# counter_7
Nama 	: Nyoo Steven
NPM 	: 2106630050
Kelas 	: PBP D

## Stateless widget dan stateful widget
Stateless widget merupakan widget yang tidak pernah berubah.  Ketika sebuah widget dapat berubah ketika terdapat user yang berinteraksi dengan widget tersebut disebut dengan stateful widget. Contoh dari Stateless widget adalah Icon, IconButton. Stateful widget ada Checkbox, Radio, Slider, InkWell, Form, dll.

## Widget yang Digunakan
`Scaffold`: widget utama yang menjadi struktur layout halaman aplikasi dan sebagai wadah untuk menampung semua widget lainnya pada halaman aplikasi
`AppBar`: widget yang berfungsi untuk menampilkan app bar sebuah halaman aplikasi, umumnya diletakkan pada bagian paling atas dari sebuah halaman aplikasi dan dapat berisi widget lain
`Text`: widget yang berfungsi untuk menampilkan teks pada halaman aplikasi
`Center`: widget yang berfungsi untuk menampilkan child widget-nya menjadi di tengah
`Column`: widget yang berfungsi untuk menampilkan children widget-nya secara vertikal
`Row`: widget yang berfungsi untuk menampilkan children widget-nya secara horizontal
`FloatingActionButton`: widget yang berfungsi untuk menampilkan tombol yang dapat mengeksekusi suatu fungsi tertentu ketika ditekan oleh pengguna
`Icon`: widget yang berfungsi untuk menampilkan icon tertentu yang sudah predefined
`MaterialApp`: widget yang dijalankan pertama kali ketika eksekusi fungsi main() dan berfungsi untuk wrapping widget lain yang diimplementasikan dengan Material Design pada halaman aplikasi
## setstate
`setState()` merencanakan suatu pembaruan ke suatu state objek komponen. Ketika state berubah, komponen merespons dengan me-render ulang.

## Const dan Final
Final adalah sebuah cara untuk meng identifikasi sebuah variable dapat diganti nialinya(mutable) atau tidak dapat diganti nilainya (immutable). 
Const adalah sebuah cara untuk meng identifikasi sebuah variable dapat diganti nialinya(mutable) atau tidak dapat diganti nilainya (immutable). 

### Implementasi
1. Membuat proyek counter7
2. Menambahkan widget row pada floatingActionButton
3. Menambah floatingActionButton widget di row, sehingga ada 2 floatingActionButton
4. Menambah fungsi decrement yang mengurangi nilai counter
5. Melakukan binding pada onPressed bada dua button Increment dan Decrement
6. Ketika _counter>0 maka dexrement dapat dilakukan
7. Jika _counter ganjil maka widget Text akan mengeluarkan ganjil, dan sebaliknya.
8. Lakukan git add, commit, push