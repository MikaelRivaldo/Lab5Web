# Lab5Web

Langkah-langkah Praktikum

Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Mengenal JavaScript</title>
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

`Untuk hasilnya akan seperti ini:`

![tampilan awal](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/44bb6ff6-91e8-41d7-9d1b-2aa29ebf7432)

# Selanjutnya membuat Pemakaian Alert sebagai property window

Untuk sourcodenya bisa menggunakan dibawah ini:

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>alert box</title>
</head>
<body>
    <!-- Pemakaian Alert sebagai property window -->
    <script language = "javascript">
        window.alert("ini merupakan pesan untuk anda")
    </script>
</body>
</html>
```

`Untuk hasilnya akan seperti ini:`

![tampilan alert](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/09cd029f-b596-4e09-b79e-e3a4f60801ea)

# Selanjutnya Pemaikain Menthod Dalam Objek

Untuk sourcodenya bisa menggunakan dibawah ini:

```html
<!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>skrip javascript</title>
        </head>
        <body>
            percobaan memakai javascript:<br>
            <script language = "javascript">
                document.write("selamat mencoba javascript<br>");
                document.write("semoga sukses!");
            </script>
        </body>
    </html>
```

`Untuk hasilnya akan seperti ini:`

![tampilan menthod](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/a0282e24-6d28-4ae0-91a4-220213ba9292)

# Selanjutnya Pemakaian Prompt

Untuk sourcodenya bisa menggunakan dibawah ini:

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>pemasukan data</title>
    </head>
    <body>
        <script language = "javascript">
            var nama = prompt("siapa nama anda?", "masukkan nama anda");
            document.write("hai, " + nama);
        </script>
    </body>
</html>
```

`Untuk hasilnya akan seperti ini:`

![tampilan promp](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/14edc0f8-83e8-4bc0-80c6-fdb11811ec71)

# Selanjutnya Operasi Dasar Aritmatika

Untuk sourcodenya bisa menggunakan dibawah ini:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contoh program JavaScript</title>
    <script language = "javascript">
        function test (val1, val2){
            document.write("<br>" + "perkalian : val1 * val2" + "<br>")
            document.write(val1*val2)
            document.write("<br>" + "pembagian : val1 / val2" + "<br>")
            document.write(val1/val2)
            document.write("<br>" + "penjumlahan : val1 + val2" + "<br>")
            document.write(val1+val2)
            document.write("<br>" + "pengurangan : val1 - val2" + "<br>")
            document.write(val1-val2)
            document.write("<br>" + "modulus : val1 % val2" + "<br>")
            document.write(val1%val2)
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
</body>
</html>
```

`Untuk hasilnya akan seperti ini:`

![tampilan seleksi if else](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/ac4e755b-8b25-4432-99b4-8d173acf068f)

`Setelah di ok maka hasilnya akan seperti ini`

![tampilan hasil if else](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/529749d2-480e-431f-8b5e-61016b78706e)

# Selanjutnya Penggunaan Operator Switch Untuk Seleksi Kondisi

Untuk sourcodenya bisa menggunakan dibawah ini:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contoh program javascript</title>

    <script language = "javascript">
        function test (){
            val1 = window.prompt("input nilai (1-5)")
            switch (val1){
                case "1" : 
                    document.write("bilangan satu")
                    break
                case "2" : 
                    document.write("bilangan dua")
                    break
                case "3" : 
                    document.write("bilangan tiga")
                    break
                case "4" : 
                    document.write("bilangan empat")
                    break
                case "5" : 
                    document.write("bilangan lima")
                    break
                default : 
                    document.write("bilangan lainnya")
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```

`Untuk hasilnya akan seperti ini:`

![tampilan hasil operator switch](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/ca775eec-24cb-4578-bfce-d6bf30489133)

# Selanjutnya Pembuatan Form

Untuk sourcodenya bisa menggunakan dibawah ini:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form input</title>

    <script language="javascript">
        function test () {
            var val1 = document.kirim.T1.value
            if (val1%2==0)
                document.kirim.T2.value = "bilangan genap"
            else   
                document.kirim.T2.value = "bilangan ganjil"
        }
    </script>
</head>
<body>
    <form method="POST" name="kirim">
        <p>BIL <input type="text" name="T1" size="20">
        MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" name="B1" value="TEBAK" onclick=test()></p>
    </form>
</body>
</html>
```

`Untuk hasilnya akan seperti ini:`

![tampilan form](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/cb9d131e-f835-4144-b31f-8662d2af3238)

# Selanjutnya Form Bottom

Untuk sourcodenya bisa menggunakan dibawah ini:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Objek document</title>
</head>

<body>
    <script language="JavaScript">
        <!--
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
        //
        -->
    </script>

    <h1>tes</h1>
    <form>
        <input type="button" value="Latar Belakang Hijau" onClick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onClick="ubahWarnaLB('WHITE')">
        <input type="button" value="Text Kuning" onClick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Text Biru" onClick="ubahWarnaLD('BLUE')">
    </form>
    <script language="JavaScript">
        <!--
        document.write("Dimodifikasi terakhir pada " +
            document.lastModified);
        //
        -->
    </script>
</body>

</html>
```
`Untuk hasilnya akan seperti ini:`

![tampilan form button](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/02d1e61e-f60f-4250-b531-91add8613eff)

# Selanjutnya HTML DOM

Untuk sourcodenya bisa menggunakan dibawah ini:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Daftar Menu</title>
    <script>
        function hitung(ele) {
            var total = document.getElementById('total').value;
            total = (total ? parseInt(total) : 0);
            var harga = 0;

            if (ele.checked) {
                harga = ele.value;
                total += parseInt(harga);
            } else {
                harga = ele.value;
                if (total > 0)
                    total -= parseInt(harga);

            }

            document.getElementById('total').value = total;
        }
    </script>
</head>

<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />Ayam Goreng Rp. 5.000</label><br />
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />Tempe Goreng Rp. 500</label><br />
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />Tempe Dadar Rp. 2.500</label><br />
    <strong>Total bayar: Rp. <input id="total" type="text" /></strong>
</body>

</html>
```
`Untuk hasilnya akan seperti ini:`

![tampilan daftar menu](https://github.com/MikaelRivaldo/Lab5Web/assets/115770247/8fa489f2-dfb9-48f0-b730-9b4d98d7dcf5)

