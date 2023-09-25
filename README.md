Nama  : Rafif Isdarufa Athallah

NIM   : 312210299

Kelas : TI.22.A3

---

## Pengertian HTML

HTML adalah bahasa yang digunakan untuk membuat halaman web. Bayangkan HTML sebagai "kerangka" atau "struktur" dari sebuah halaman web. Ini memungkinkan kita untuk menentukan judul, teks, gambar, tautan, dan elemen-elemen lainnya pada sebuah halaman. HTML digunakan oleh peramban web (seperti Chrome, Firefox, dan lainnya) untuk menafsirkan dan menampilkan konten web dengan cara yang dapat kita lihat dan interaksi secara online. Jadi, singkatnya, HTML adalah dasar dari hampir semua halaman web yang kita temui di internet.


---

## Latihan

- Buat file HTML baru dengan nama `lab1_tag_dasar.html` dan tambah tag dasar dokumen HTML
- Buka file tersebut pada laman web browser misalnya Chrome, Firefox, dan Edge
- Untuk membuat sebuah paragraf dalam HTML, gunakan tag `<p>` dan diisi dengan teks yang diinginkan

```html
  <!-- Paragraf Pertama -->
  <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
  
   <!-- Paragraf Kedua -->
  <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>
```

- Simpan perubahannya dan lakukan refresh pada laman web browser untuk melihat hasilnya

![Screenshot_2023-09-26-06-02-15-393-edit_com android chrome](https://github.com/zangetsuuuu/Lab1Web/assets/115514467/5cea923b-64d6-4df2-9fbd-e999aca42ad2)

- Untuk mengatur paragraf tersebut, gunakan atribut `align` yang bisa diisi dengan beberapa value yang berbeda seperti `justify, right, left, center`

```html
  <!-- Paragraf Pertama -->
  <p align="center">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
  
   <!-- Paragraf Kedua -->
  <p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>
```

- Simpan perubahannya dan lakukan refresh pada laman web browser untuk melihat hasilnya

![Screenshot_2023-09-26-06-04-56-991-edit_com android chrome](https://github.com/zangetsuuuu/Lab1Web/assets/115514467/a0ac39c2-90a5-42fb-acf2-d66da692a045)

- Untuk membuat judul dalam HTML, gunakan tag `<h1>` sampai `<h6>` yang masing-masing memiliki ukuran yang berbeda dan dapat digunakan sesuai kebutuhan

```html
  <!-- Judul Paragraf Pertama -->
  <h1>Belajar Dasar HTML</h1>
  
  <!-- Judul Paragraf Kedua -->
  <h2>Paragraf pada HTML</h2>
```

- Simpan perubahannya dan lakukan refresh pada laman web browser untuk melihat hasilnya

![Screenshot_2023-09-26-06-11-33-921-edit_com android chrome](https://github.com/zangetsuuuu/Lab1Web/assets/115514467/3b7d1eb5-a611-4290-a630-0c0dc8eb4005)

- Untuk memformat teks dalam HTML, ada berbagai tag yang dapat digunakan seperti `<b>, <strong>, <i>, <em>, <mark>, <small>, <del>, <ins>, <sub>, <sup>` yang masing-masing memiliki kegunaan yang berbeda

```html
  <h1>Belajar Dasar HTML</h1>
  <p>Kami sedang belajar <span style="background-color: yellow;">HTML dasar</span>, pada matakuliah <b>Pemograman Web</b> di Prodi <i>Teknik Informatika </i> <u>Universitas Pelita Bangsa.</u>  Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>
 
  <h2>Paragraf Pada HTML</h2>
  <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>
```

- Simpan perubahannya dan lakukan refresh pada laman web browser untuk melihat hasilnya

![Screenshot_2023-09-26-06-16-56-079-edit_com android chrome](https://github.com/zangetsuuuu/Lab1Web/assets/115514467/1173b2a9-6cfe-460f-8881-93a341d82185)

- Untuk menyisipkan gambar dalam HTML, siapkan terlebih dahulu sebuah gambar yang telah didownload, atau bisa menggunakan URL dari gambar yang terdapat di internet dan gunakan tag `<img>` dengan atribut `src` yang berisi path atau URL gambar
- Gambar akan muncul akan muncul sesuai ukuran aslinya. Untuk mengatur ukurannya bisa menggunakan atribut `width` dan `height` 

```html
  <!-- Sub Judul Gambar -->
  <h3>Menambahkan Gambar</h3>
  
  <!-- Menambahkan Gambar Pada Dokumen -->
  <img src="https://ecampus.pelitabangsa.ac.id/pb/img/logo_perguruanTinggi_1.png" title="Logo Universitas Pelita Bangsa" width="200">
```

- Simpan perubahannya dan lakukan refresh pada laman web browser untuk melihat hasilnya

![Screenshot_2023-09-26-06-24-28-171-edit_com android chrome](https://github.com/zangetsuuuu/Lab1Web/assets/115514467/4f53f574-fe27-4da9-8da6-dc5cb44a924b)

- Untuk menambahkan *hyperlink* dalam HTML, gunakan tag `<a>` dengan atribut `href` yang berisi link

```html
  <!-- Menambahkan Link Navigasi -->
  <nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
  </nav>
```

- Simpan perubahannya dan lakukan refresh pada laman web browser untuk melihat hasilnya

![IMG_20230926_062805](https://github.com/zangetsuuuu/Lab1Web/assets/115514467/c4747b94-a28d-416e-bee5-6e130f3f12b2)

---

### Sekian, terimakasih.
