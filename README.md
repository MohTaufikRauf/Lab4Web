## Nama     : Moh. Taufik Rauf
## NIM      : 312010151
## Kelas    : TI.20.A.1

---
# Box Element
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

![menambahkan_gambar](img/Box%20Element.png)

Mengatur Clearfix Element
Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk
mengaturnya.
Tambahkan element div lainnya seteleah div3 seperti berikut.
```
<div class="div4">Div 4</div>
```
Kemudian atur property clear pada CSS, seperti berikut.
```
.div4 {
    background-color: rgb(32, 32, 32);
    clear: left;
    float: none;
}
```
Selanjutnya buka browser dan refresh kembali.

Berikut contoh tampilannya.

![menambahkan_gambar](img/menamahkan%20Div4.png)

Lakukan eksperimen terhadap penggunaan property clear dengan nilai lainnya (left, both, right),
dan amati perubahannya.

Berikut contoh perubahannya.

![menambahkan_foto](img/menakukan%20perubahan%20pada%20clear.png)

# Layout Sederhana
