# lab5web
## Nama : Zalfa Dewi Zahrani
## Nim : 312210320
## Kelas : TI.22.A3
## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat folder baru dengan nama ```lab5_javascript```
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
4. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org
## Langkah-langkah praktikum
Persiapan membuat dokumen HTML dengan nama file ```lab5_javascript.html``` seperti berikut.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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

## Output

![Screenshot (261)](https://github.com/zalfadz05/lab5web/assets/115516617/135c16cc-03b0-48c1-b058-c1725e90964a)

## Javasript Dasar
### Pemakaian ```Alert``` sebagai property window.

```
<html>
    <head>
        <title>alert box</title>
    </head>
    <body>
        <script language = "javascript">
        <!--
            window.alert("ini merupakan pesan untuk anda");
            //-->
        </script>
    </body>
</html>
```
## Output

![Screenshot (262)](https://github.com/zalfadz05/lab5web/assets/115516617/159a3f70-e259-4390-b699-79c9e1245a14)

### Pemakaian method dalam objek.

```
<html>
    <head>
        <title>skrip javascript</title>
    </head>
    <body>
        percobaan memakai javascript:<br>
        <script language = "javascript">
            <!--
                document.write("selamat mencoba javascript<br>");
                document.write("semoga sukses!");
                //-->
        </script>
    </body>
</html>
```

## Output

![Screenshot (263)](https://github.com/zalfadz05/lab5web/assets/115516617/3c670b3f-0006-4700-9411-eb2cc44f4ffd)

### Pemakaian Prompt

```
<html>
    <head>
        <title>pemasukan data</title>
    </head>
    <body>
        <script language = "javascript">
            <!--
                var nama = prompt("siapa nama anda?","masukkan nama anda");
                document.write("hai, "+ nama);
                //-->
        </script>
    </body>
</html>
```

## Output

![Screenshot (264)](https://github.com/zalfadz05/lab5web/assets/115516617/19cad251-1b74-4a4c-96db-83a2c04e404a)

![Screenshot (265)](https://github.com/zalfadz05/lab5web/assets/115516617/ea4dd96c-7b78-4208-95bf-aa1e90a92251)

### Pembuatan fungsi dan cara pemanggilannya

```
<html>
    <head>
        <title>contoh program javascript</title>
        <script language="javascript">
            function pesan(){
                alert ("memanggil javascript lewat body onload")
            }
        </script>
    </head>
    <body onload="pesan"()>
    </body>
</html>
```

## Dasar Pemrograman di Javascript
### Operasi dasar aritmatika

```
<html>
    <head>
        <title>contoh program javascript</title>
        <script language="javascript">
            function test (val1,val2)
            {
                document.write("<br>"+"perkalian : val1*val2 "+"<br>")
                document.write(val1*val2)
                document.write("<br>"+"pembagian : val1/val2 "+"<br>")
                document.write(val1/val2)
                document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
                document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
                document.write(val1-val2)
                document.write("<br>"+"modulus : val1%val2 "+"<br>")
                document.write(val1%val2)
            }
        </script>
    </head>
    <body>
        <h3>contoh program javascript</h3>
        <input type="button" name="button1" value="aritmetic" onclick=test(9,4)>
    </body>
</html>
```

## Output

![Screenshot (266)](https://github.com/zalfadz05/lab5web/assets/115516617/64dbac0e-e1f2-4a81-915b-9c8a87d7f63b)

### Seleksi kondisi (if..else)

```
<html>
    <head>
        <title>contoh if-else</title>
    </head>
    <body>
        <script language = "javascript">
            <!--
                var nilai = prompt("nilai (0-100): ",0);
                var hasil = "";
                if (nilai >= 60)
                hasil = "lulus";
                else
                hasil = "tidak lulus";
                document.write("hasil: " + hasil);
                //-->
        </script>
    </body>
</html>
```

## Output

![Screenshot (267)](https://github.com/zalfadz05/lab5web/assets/115516617/01f75249-ba45-49ec-aa60-16c2c6eff68d)

![Screenshot (268)](https://github.com/zalfadz05/lab5web/assets/115516617/fe35635e-8b16-4a5c-9938-152e1e43afe8)

![Screenshot (269)](https://github.com/zalfadz05/lab5web/assets/115516617/405eb665-8211-447e-b4d0-e9dd5609379e)

![Screenshot (270)](https://github.com/zalfadz05/lab5web/assets/115516617/451494c8-ed1a-4bda-ba6c-2b062e1bf7ad)

### Penggunaan ```operator switch``` untuk seleksi kondisi

```
<html>
    <head>
        <title>contoh program javascript</title>
        
        <script language="javascript">
            function test ()
            {
                val1=window.prompt("input nilai (1-5):")
                switch (val1)
                {
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
        <h3>contoh program javascript</h3>
        <input type="button" name="button1" value="switch" onclick=test()>
    </body>
</html>
```

## Output

![Screenshot (270)](https://github.com/zalfadz05/lab5web/assets/115516617/c5db3890-bcfa-4328-803f-f3da557fc694)

![Screenshot (271)](https://github.com/zalfadz05/lab5web/assets/115516617/24fa625c-8663-489b-a4f5-ed9707bc8549)

![Screenshot (273)](https://github.com/zalfadz05/lab5web/assets/115516617/7bfeba64-36c0-49b4-94d0-0fa885a48468)

![Screenshot (274)](https://github.com/zalfadz05/lab5web/assets/115516617/ca01ea21-4dbf-4f21-b2b1-5375f1e5a4cf)

## Pembuatan Form

### Form ```Input```

```
<html>
    <head>
        <script language="javascript">
            function test () {
                var val1=document.kirim.T1.value
                if (val1%2==0)
                    document.kirim.T2.value="bilangan genap"
                else
                    document.kirim.T2.value="bilangan ganjil"
            }
        </script>
    </head>
    <body>
        <form method="POST" name="kirim">
            <p>BIL <input type="text" name="T1" size="20">
            MERUPAKAN BIL <input type="text" name="T2" size="20"></p>
            <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
        </form>
    </body>
</html>
```

## Output

![Screenshot (275)](https://github.com/zalfadz05/lab5web/assets/115516617/f8c4884d-877e-43c0-b91f-5e4380a69137)

![Screenshot (276)](https://github.com/zalfadz05/lab5web/assets/115516617/04799b1e-675a-4e49-8eba-59432771a8db)

### Form ```Button```

```
<html>
    <head>
        <title>objek document</title>
    </head>
    <body>
        <script language="javascript">
            <!--
                function ubahWarnaLB(warna) {
                    document.bgColor = warna;
                }
                function ubahWarnaLD(warna) {
                    document.fgColor = warna;
                }
                //-->
        </script>

        <h1>tes</h1>
        <form>
            <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
            <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
            <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
            <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
        </form>
        <script language="javascript">
            <!--
                document.write("Dimodifikasi terakhir pada " +
                document.lastModified);
                //-->
        </script>
        
    </body>
</html>
```

## Output

![Screenshot (277)](https://github.com/zalfadz05/lab5web/assets/115516617/7b1b90e6-5a74-433a-a7b0-4b95f608d2d6)

## HTML ```DOM```

Pilihan menggunakan ```checkBox``` dengan perhitungan otomatis

![dom](https://github.com/zalfadz05/lab5web/assets/115516617/049065b6-bdd4-4b51-95da-a1b9be2bc65b)

## Output

![Screenshot (279)](https://github.com/zalfadz05/lab5web/assets/115516617/a0aaffe4-c889-4bc6-aa76-b6e9cde3818a)

## Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form.

![code hd](https://github.com/zalfadz05/lab5web/assets/115516617/d21b5a31-3263-4750-ade9-ee9f0f48ec98)

![codehome](https://github.com/zalfadz05/lab5web/assets/115516617/c1fd649e-260c-41bc-b981-170f593f0092)

![css](https://github.com/zalfadz05/lab5web/assets/115516617/ba3582fa-a3b4-40b6-a586-7c87ae2ebf7a)

## Output

![Screenshot (281)](https://github.com/zalfadz05/lab5web/assets/115516617/511ca790-747e-4645-8b9f-b03f9575765c)

