# Lab 1 Web Programming

Repository ini berisi hasil praktikum **Pemrograman Web** pada materi **HTML Dasar**.

## Identitas

* **Nama:** Mu'ammar Kadafi
* **NIM:** 312510192
* **Program Studi:** Teknik Informatika
* **Mata Kuliah:** Pemrograman Web

## Tujuan Praktikum

Praktikum ini bertujuan untuk memahami dasar-dasar HTML dan cara membuat halaman web sederhana. Pada praktikum ini dipelajari struktur dasar dokumen HTML, penggunaan heading, paragraf, pemformatan teks, gambar, hyperlink, daftar, dan komentar dalam HTML.

## Tools yang Digunakan

* Visual Studio Code
* Google Chrome
* HTML5

## Proses Praktikum

### 1. Membuat Folder dan File HTML

Langkah pertama adalah membuat folder kerja dengan nama `praktikum-1-html-dasar`. Selanjutnya, dibuat file `index.html` sebagai halaman utama.

Struktur dasar HTML yang digunakan adalah sebagai berikut:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Belajar HTML</title>
</head>
<body>

</body>
</html>
```

### 2. Membuat Paragraf

Selanjutnya, ditambahkan beberapa paragraf menggunakan tag `<p>`.

```html
<p>Ini adalah paragraf pertama.</p>
<p>Ini adalah paragraf kedua.</p>
```

### 3. Menambahkan Heading

Heading digunakan untuk memberikan judul dan subjudul pada halaman. Pada praktikum digunakan tag `<h1>` dan `<h2>`.

```html
<h1>Judul Utama</h1>
<p>Ini adalah paragraf pertama.</p>

<h2>Subjudul</h2>
<p>Ini adalah paragraf kedua.</p>
```

### 4. Melakukan Pemformatan Teks

Teks pada halaman HTML kemudian diformat menggunakan beberapa tag, seperti `<b>`, `<strong>`, `<i>`, dan `<u>`.

Selain itu, dilakukan eksperimen menggunakan tag pemformatan lainnya, seperti:

* `<em>` untuk memberikan penekanan pada teks.
* `<mark>` untuk menandai atau menyoroti teks.
* `<small>` untuk membuat teks berukuran lebih kecil.
* `<del>` untuk menunjukkan teks yang dihapus.
* `<ins>` untuk menunjukkan teks yang ditambahkan.

### 5. Menambahkan Gambar

Sebuah gambar disiapkan dan disimpan di dalam folder `images`. Gambar kemudian ditampilkan menggunakan tag `<img>` dengan atribut `src` dan `alt`.

```html
<img src="images/foto.jpg" alt="Foto kegiatan praktikum">
```

Atribut `src` digunakan untuk menentukan sumber gambar, sedangkan `alt` digunakan untuk memberikan teks alternatif apabila gambar tidak dapat ditampilkan.

### 6. Membuat Hyperlink

Selanjutnya, dibuat file `halaman2.html` sebagai halaman kedua. Hyperlink digunakan untuk menghubungkan halaman satu dengan halaman lainnya.

Contoh hyperlink ke halaman internal:

```html
<a href="index.html">Dasar HTML</a>
<a href="halaman2.html">Halaman 2</a>
```

Selain itu, dibuat hyperlink menuju website eksternal:

```html
<a href="https://www.google.com">Website Eksternal</a>
```

### 7. Membuat Daftar

Pada praktikum juga digunakan `unordered list` dan `ordered list`.

Contoh `unordered list`:

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

Contoh `ordered list`:

```html
<ol>
    <li>Mempelajari HTML</li>
    <li>Mempelajari CSS</li>
    <li>Mempelajari JavaScript</li>
</ol>
```

### 8. Menambahkan Komentar

Komentar digunakan untuk memberikan penanda atau keterangan pada kode HTML tanpa ditampilkan pada halaman web.

```html
<!-- Judul utama halaman -->
<h1>Belajar HTML</h1>
```

### 9. Membuat Halaman Ketiga

Selanjutnya, dibuat file `halaman3.html`. Halaman tersebut kemudian dihubungkan dengan `index.html` dan `halaman2.html` menggunakan hyperlink.

Dengan demikian, ketiga halaman dapat saling terhubung melalui tautan yang telah dibuat.

## Hasil Praktikum

Hasil praktikum berupa beberapa halaman web sederhana yang terdiri atas:

* `index.html` sebagai halaman utama.
* `halaman2.html` sebagai halaman kedua.
* `halaman3.html` sebagai halaman ketiga.
* Folder `images` untuk menyimpan gambar yang digunakan pada halaman web.

Ketiga halaman tersebut memiliki hyperlink yang memungkinkan pengguna berpindah dari satu halaman ke halaman lainnya.

## Kesimpulan

Berdasarkan praktikum yang telah dilakukan, dapat dipahami bahwa HTML digunakan untuk membangun struktur dasar sebuah halaman web. Beberapa elemen dasar HTML yang dipelajari meliputi deklarasi `DOCTYPE`, heading, paragraf, pemformatan teks, gambar, hyperlink, daftar, dan komentar.

Praktikum ini juga memberikan pemahaman mengenai cara membuat beberapa halaman HTML dan menghubungkannya menggunakan hyperlink sehingga membentuk sebuah website sederhana.
