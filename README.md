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

## TUGAS 8
### Navigator.push dan Navigator.pushReplacement
Navigator push dan push replacement berguna untuk switch screen ke suatu screen lainnya. Namun perbedaannya adalah jika kita menggunakan Navigator push, maka route screen yang lama tidak dihapus, sehingga kita bisa kembali ke route yang lama. Lain hal dengan navigator push replacement, route screen yang lama dihapus dan kita tidak bisa kembali ke route yang lama.

### Widgets yang digunakan
- Container, berguna untuk mengatur lokasi widgets
- Text, berguna untuk menampilkan text
- Column, Row, berguna untuk menata widgets dalam bentuk kolom atau baris
- Form, berguna untuk membuat form
- TextFormField, berguna untuk menyimpan input text sebuah form
- DropdownButton, berguna untuk membuat dropdown
- Padding, berguna untuk memberikan padding pada suatu widget agar lebih rapi
- TextButton, button yang berisi text, dapat digunakan untuk mensubmit form
- ListTile, widget yang sangat berguna untuk menampilkan sebuah informasi dalam format tertentu
- SingleChildScrollView, berguna agar suatu widget dapat ditampilkan jika melebih layar dengan scroll
- Card, digunakan untuk membantu menampilkan data budget

### Jenis event Flutter
- onPressed, terjadi ketika dipencet
- onTap, terjadi ketika ditap
- onSaved, terjadi ketika form disave
- onChanged, terjadi ketika text form field berubah isinya

### Implementasi 
1. Membuat drawer.dart, data.dart, form.dart, dan budget.dart
2. data.dart berisikan tentang data budget ynag sudah disimpan
3. form.dart berisikan tentang form untuk menambah budget
4. drawer.dart berisikan untuk navigator halaman lain
5. budget.dart adalah suatu class yang menandakan class pada pengisian budget 
6. pada drawer terdapat 3 children berupa tombol yang akan melakukan `pushReplacement` ke halaman yang sesuai dengan tombol masing-masing.