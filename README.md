# SEMANTIC-HTML
Zainal Arifin - 2205101059

## ANALISIS KODE
## HTML

### 1. Struktur Dokumen HTML
- **Sebelum Revisi**: Tag `<html>`, `<head>`, dan `<body>` tidak ada.
- **Sesudah Revisi**: Ditambahkan tag `<html>`, `<head>`, dan `<body>` yang melengkapi struktur dasar HTML, sehingga kode lebih terstruktur dan sesuai standar HTML5.

### 2. Penggunaan Elemen Metadata
- **Sebelum Revisi**: Tidak ada metadata yang disertakan.
- **Sesudah Revisi**: Ditambahkan metadata penting, yaitu:
  - `<meta charset="UTF-8">` untuk mendefinisikan encoding karakter.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` untuk responsivitas di perangkat seluler.
  - `<title>` untuk judul halaman yang akan muncul di tab browser.
  
  Metadata ini membantu mesin pencari dan browser memahami konten halaman dengan lebih baik, serta membuat halaman lebih ramah perangkat seluler.

### 3. Link Eksternal untuk CSS
- **Sebelum Revisi**: Tidak ada link ke file CSS eksternal.
- **Sesudah Revisi**: Ditambahkan `<link rel="stylesheet" href="./assets/styles/style.css">` untuk menghubungkan halaman HTML ke file CSS eksternal.

  Ini memungkinkan penataan tampilan halaman menggunakan file CSS terpisah, yang umumnya membuat pengelolaan dan pembaruan tampilan lebih mudah.

### 4. Struktur HTML5 dan Elemen Semantik
- **Sebelum Revisi**: Struktur sudah menggunakan elemen semantik HTML5 seperti `<header>`, `<nav>`, `<section>`, dan `<footer>`, namun tidak dikelilingi oleh `<html>`.
- **Sesudah Revisi**: Elemen semantik tetap digunakan tetapi kini berada di dalam elemen `<html>` dan `<body>`, yang lebih sesuai dengan standar HTML.

### 5. Kesesuaian Standar HTML5
- **Sebelum Revisi**: Tidak sepenuhnya sesuai standar HTML5 karena elemen `<html>`, `<head>`, dan `<body>` yang mendasar belum ada.
- **Sesudah Revisi**: Kode lebih sesuai dengan standar HTML5 karena telah ditambahkan elemen-elemen dasar HTML5 dan metadata penting.

---

## CSS

### 1. Pengaturan Margin pada Body
- **Sebelum Revisi**: Pada elemen `body`, terdapat pengaturan `margin: 10px;`.
- **Sesudah Revisi**: Pengaturan `margin: 10px;` dihilangkan.
  
  **Dampak**: Dengan menghilangkan margin pada `body`, elemen-elemen di dalam body sekarang akan menempel pada tepi layar, yang mungkin memberi lebih banyak ruang tetapi dapat memengaruhi tata letak keseluruhan jika margin tersebut dibutuhkan untuk estetika atau keterbacaan.

### 2. Struktur dan Urutan CSS
- **Sebelum Revisi**: Deklarasi CSS untuk elemen-elemen `nav`, `header`, `section`, dan `footer` ditempatkan di awal sebelum elemen `body`.
- **Sesudah Revisi**: Deklarasi untuk elemen `body` ditempatkan di awal, diikuti oleh deklarasi untuk elemen `header`, `nav`, `section`, dan `footer`.
  
  **Dampak**: Pengaturan ini lebih rapi dan umum digunakan karena biasanya properti untuk elemen `body` dideklarasikan terlebih dahulu sebagai dasar layout halaman, kemudian diikuti elemen-elemen yang lain. Ini juga membuat kode lebih mudah dibaca dan diikuti secara hierarki.

