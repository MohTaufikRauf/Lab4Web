## Nama     : Moh. Taufik Rauf
## NIM      : 312010151
## Kelas    : TI.20.A.1

---
# BOX ELEMENT
Element HTML dapat dianggap sebagai sebuah Box atau kotak. Box tersebut digunakan untuk
membuat layout web. Pada dasarnya semua element HTML adalah box dengan beberapa perbedaan.
Ada yang floating ada juga yang tanpa floating.

Langkah pertama membuat Box Element.

Persiapkan text editor misalnya VSCode.

Buatlah dokumen HTML dengan nama file lab4_box.html, lalu masukan contoh kode berikut.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Element</title>
</head>
<body>
    <header>
        <h1>Box Element</h1>
    </header>
</body>
</html>
```

Kemudian tambahkan kode untuk membuat box element dengan tag div seperti berikut.
```
<section>
    <div class="div1">Div 1</div>
    <div class="div2">Div 2</div>
    <div class="div3">Div 3</div>
</section>
```
Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element, seperti berikut.
```
<style>
    div {
        float:left;
        padding: 10px;
    }
    .div1 {
        background: rgb(94, 94, 94);
    }
    .div2 {
        background: rgb(56, 56, 56);
    }
    .div3 {
        background: rgb(36, 36, 36);
    }
</style>
```
Kemudian buka browser untuk melihat hasilnya.

Berikut contoh tampilannya

