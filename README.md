# Tugas Lab5web
## Profil

| #               | Biodata             |
| --------------- | ------------------- |
| **Nama**        | Rangga Saputra |
| **NIM**         | 312010266           |
| **Kelas**       | TI.20.A.2           |
| **Mata Kuliah** | Pemrograman Web     |

## Langkah1 `persiapan`
1. buat file baru bernama `lab5_javascript.html`
2. tambahkan kode berikut
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pengenalan JavaScript</title>
</head>

<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```
* Maka hasilnya akan seperti ini
![js_dasar](img/javascript1.png)

## Langkah 2 `Alert`
1. Tambahkan kode berikut ke dalam tag `<script>`.

```javascript
window.alert("Ini merupakan pesan untuk anda");
```
* Maka hasilnya akan seperti ini
![alert](img/alert1.png)

## Langkah 3 `Method dalam objek`
1. Tambahkan kode berikut ke dalam tag `<script>`.
2. Tambahkan kode berikut ke dalam tag `<script>`.

```javascript
document.write("Selamat mencoba javascript <br>");
document.write("Semoga Sukses");
```
* Maka hasilnya akan seperti ini
![method1](img/method.png)

## Langkah 4 `Prompt`
1. Tambahkan kode berikut ke dalam tag `<script>`.

```javascript
var nama = prompt("Siapa nama anda?");
document.write("Hai " + nama);
```

2. Saat dijalankan akan meminta suatu inputan yang nanti akan dimasukan kedalam variable `nama`.
* contohnya seperti ini
![propt1](img/propt1.png)

## Langkah 5 `Function`
1. Buat function `pesan()`.

```javascript
function pesan() {
    alert("Memanggil javascript lewat body onload");
}
```

2. Tambahkan atribut pada tag `<body>`.

```html
<body onload="pesan()">
```

3. Maka ketika web load akan seperti berikut.
![function1](img/function1.png)

## Langkah 6 Operasi Aritmatika
1. Buat function `aritmatika()` pada tag `<script>`.
```javascript
function test (val1,val2)
        {
            document.write("<br>"+"perkalian : val1*val2 "+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"pembagian : val1/val2 "+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
            document.write(val1-val2)
            document.write("<br>"+"modulus : val1%val2 "+"<br>")
            document.write(val1%val2)
        }
```
2. buatlah input di dalam tag `body`
```javascript
 <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
```
* sebelum di klik
![aritmatika1](img/aritmatika1.png)

* Sesudah di klik
![aritmatika2](img/aritmatika2.png)