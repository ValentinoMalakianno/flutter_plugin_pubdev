## Praktikum Manajemen Plugin

### Valentino Malakianno
### 3G
### 2141720099

#### Langkah 1: Buat Project Baru
Buatlah sebuah project flutter baru dengan nama flutter_plugin_pubdev. Lalu jadikan repository di GitHub Anda dengan nama flutter_plugin_pubdev.

![](ss/1.png)

#### Langkah 2: Menambahkan Plugin
Tambahkan plugin auto_size_text menggunakan perintah berikut di terminal

![](ss/2.png)

Jika berhasil, maka akan tampil nama plugin beserta versinya di file pubspec.yaml pada bagian dependencies.

![](ss/8.png)

#### Langkah 3: Buat file red_text_widget.dart
Buat file baru bernama red_text_widget.dart di dalam folder lib lalu isi kode seperti berikut.

![](ss/3.png)

#### Langkah 4: Tambah Widget AutoSizeText
Masih di file red_text_widget.dart, untuk menggunakan plugin auto_size_text, ubahlah kode return Container() menjadi seperti berikut.

![](ss/4.png)

Setelah Anda menambahkan kode di atas, Anda akan mendapatkan info error. Mengapa demikian? Jelaskan dalam laporan praktikum Anda!

Jawab : Karena variabel text tidak dideklarasikan.

#### Langkah 5: Buat Variabel text dan parameter di constructor
Tambahkan variabel text dan parameter di constructor seperti berikut.

![](ss/5.png)

#### Langkah 6: Tambahkan widget di main.dart
Buka file main.dart lalu tambahkan di dalam children: pada class _MyHomePageState

![](ss/6.png)

Run aplikasi tersebut dengan tekan F5, maka hasilnya akan seperti berikut.

![](ss/7.png)

### Tugas Praktikum

1. Selesaikan Praktikum tersebut, lalu dokumentasikan dan push ke repository Anda berupa screenshot hasil pekerjaan beserta penjelasannya di file README.md!

2. Jelaskan maksud dari langkah 2 pada praktikum tersebut! 

Jawab : flutter pub add auto_size_text" adalah perintah yang digunakan dalam Flutter untuk menambahkan sebuah paket atau library ke proyek Flutter. Perintah ini ditujukan untuk menambahkan paket bernama "auto_size_text" ke proyek Flutter.

3. Jelaskan maksud dari langkah 5 pada praktikum tersebut! 

Jawab: Kode ini menambahkan variabel text ke dalam class RedTextWidget. Variabel ini akan digunakan untuk menentukan teks yang akan ditampilkan oleh widget ini.

4. Pada langkah 6 terdapat dua widget yang ditambahkan, jelaskan fungsi dan perbedaannya! Jelaskan maksud dari tiap parameter yang ada di dalam plugin auto_size_text berdasarkan tautan pada dokumentasi ini ! 

Jawab :

Kotak pertama (Container) berwarna kuning dan berisi teks yang telah disesuaikan tampilannya (dalam widget bernama RedTextWidget).

Kotak kedua (Container) berwarna hijau dan berisi teks biasa tanpa penyesuaian khusus (dalam widget bernama Text).

Perbedaannya terletak pada tampilan dan gaya teks yang digunakan. Kotak pertama menggunakan widget yang di buat sendiri untuk menampilkan teks dengan gaya tertentu, sementara kotak kedua menggunakan teks biasa tanpa gaya tambahan.

5. Jelaskan maksud dari tiap parameter yang ada di dalam plugin auto_size_text berdasarkan tautan pada dokumentasi ini ! 

Jawab: 

Parameter biasanya digunakan untuk mengkonfigurasi dan menyesuaikan perilaku widget tersebut. Ini bisa termasuk parameter untuk mengatur teks yang ditampilkan, gaya teks, jumlah maksimum baris, efek overflow, dan banyak lagi.