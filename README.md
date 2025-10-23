NAMA : Afnan Dika Ramadhan

NIM : 312410518

Kelas : TI24.A5

Matakuliah : Pemrograman Web

# LAB 5 WEB

💢 Step by Step LAB 5 WEB

1. Buatlah HTML Dasar dan namai file dengan `lab5_javascript.html`

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mengenal Java Script</title>
  </head>
  <body>
    <h1>Pengenalan Java Script</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
      document.write("Hello Word");
      console.log("Hellow Word");
    </script>
  </body>
</html>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/933f33c2c76068c61ee7b05a5565103df396a1b0/LAB5%20image/LAB%205%20TAMPILAN%201.png)

Tampilan code tadi akan seperti ini

2. Buat file baru `alert.html`

```html
<html>
  <head>
    <title>alert box</title>
  </head>
  <body>
    <script language="javascript">
      <!--
      window.alert("ini merupakan pesan untuk anda");
      //-->
    </script>
  </body>
</html>
```

![foto](https://github.com/nanafnan09/Lab5Java/blob/933f33c2c76068c61ee7b05a5565103df396a1b0/LAB5%20image/LAB%205%20Tampilan%202.png)

Code tersebut berfungsi sebagai notifikasi contohnya seperti di gambar ini "ini merupakan pesan untuk anda"

3. Buat File baru `document_write.html`

```html
<html>
  <head>
    <title>skrip javascript</title>
  </head>
  <body>
    percobaan memakai javascript:<br />
    <script language="javascript">
      <!--
      document.write("selamat mencoba javascript<br>");
      document.write("semoga sukses!");
      //-->
    </script>
  </body>
</html>
```
![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/LAB5%20Tampilan%203.png)

Fungsi kode tersebut ialah merintahkan text pada web

4.  Buat file baru `prompt.html`

```html
<html>
  <head>
    <title>pemasukan data</title>
  </head>
  <body>
    <script language="javascript">
      <!--
      var nama = prompt("siapa nama anda?", "masukan nama anda");
      document.write("hai," + nama);
      //-->
    </script>
  </body>
</html>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/Lab%205%20Tampilan%204.png)

Fungsi dari code tersebut akan muncul notifikasi diatas yang dimana jika memasukan nama Contoh `Afnan Dika` setelah memasukan nama akan muncul text `hai,Afnan Dika`

5.  Buat file baru `function_onload.html`

```html
<html>
  <head>
    <title>contoh program javascript</title>
    <script language="javascript">
      function pesan() {
        alert("memanggil javascript lewat body onload");
      }
    </script>
  </head>
  <body onload="pesan()"></body>
</html>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/Lab5%20Tampilan%205.png)

Fungsi code tadi ialah memunculkan notifikasi `Memanggil javascript lewat body onload`

6. Buat file baru `arithmetic.html`

```html
<html>
  <head>
    <title>contoh program javascript</title>

    <script language="javascript">
      function test(val1, val2) {
        document.write("<br>" + "perkalian : val1*val2 " + "</br>");
        document.write(val1 * val2);
        document.write("<br>" + "pembagian : val1/val2 " + "</br>");
        document.write(val1 / val2);
        document.write("<br>" + "penjumlahan : val1+val2 " + "</br>");
        document.write(val1 + val2);
        document.write("<br>" + "pengurangan : val1-val2 " + "</br>");
        document.write(val1 - val2);
        document.write("<br>" + "modulus : val1%val2 " + "</br>");
        document.write(val1 % val2);
      }
    </script>
  </head>
  <body>
    <input
      type="button"
      name="button1"
      value="arithmhetic"
      onclick="test(9,4)"
    />
  </body>
</html>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/Lab%205%20Tampilan%206.png)

Pada tampilan awal ialah tombol untuk mengakses fungsi dari arithmetic

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/Lab%205%20tampilan%206.1.png)

Hasilnya akan memunculkan angka dari Perkalian,Pembagian,Penjumlahan,Pengurangan,Modulus

7. Buat file baru `ifelse.html`

```html
<html>
  <head>
    <title>contoh if-else</title>
  </head>
  <body>
    <script language="javascript">
      <!--
      var nilai = prompt("nilai (0-100):", 0);
      var hasil = "";
      if (nilai >= 60) hasil = "lulus";
      else hasil = "tidak lulus";
      document.write("hasil: " + hasil);
      //-->
    </script>
  </body>
</html>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/LAB%205%20Tampilan%207.png)

Di notifikasi ini berfungsi untuk memasukan nilai dari 0-100

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/Lab%205%20Tampilan%207.1.png)

`Tidak Lulus`,ini yang terjadi jika memasukan angka yang dibawah 60

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/LAB%205%20Tampilan%207.2.png)

`Lulus`,Ini jika memasukan angka yang diatas 60

8. Buat file baru `switch.html`

```html
<html>
  <head>
    <title>contoh program javascript</title>

    <script language="javascript">
      function test() {
        var val1 = window.prompt("input nilai (1-5):");
        switch (val1) {
          case "1":
            document.write("bilangan satu");
            break;
          case "2":
            document.write("bilangan dua");
            break;
          case "3":
            document.write("bilangan tiga");
            break;
          case "4":
            document.write("bilangan empat");
            break;
          case "5":
            document.write("bilangan lima");
            break;
          default:
            document.write("bilangan lainnya");
        }
      }
    </script>
  </head>
  <body>
    <input type="button" name="button1" value="switch" onclick="test()" />
  </body>
</html>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/Lab%205%20Tampilan%208.png)

Fungsi tombol ini ialah untuk mengakses input pada bilangan tertentu 1-5,selain angka maka hasilnya akan `bilangan lainnya`

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/Lab%205%20tampilan%208.1.png)

ini tampilan fungsi input bilangan

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/Lab%205Tampilan%208.3.png)

Inilah hasil jika memasukan angka 5

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/LAB%205%20Tampilan%208.2.png)

Inilah jika menginput bilangan selain 1-5

9. Buatlah file baru `form_input`

```html
<html>
  <head>
    <script language="javascript">
      function test() {
        var val1 = document.kirim.T1.value;
        if (val1 % 2 == 0) document.kirim.T2.value = "bilangan genap";
        else document.kirim.T2.value = "bilangan ganjil";
      }
    </script>
  </head>
  <body>
    <form method="POST" name="kirim">
      <p>
        BIL <input type="text" name="T1" size="20" /> MERUPAKAN BIL
        <input type="text" name="T2" size="20" />
      </p>
      <p><input type="button" value="TEBAK" name="B1" onclick="test()" /></p>
    </form>
  </body>
</html>


```

![foto](https://github.com/nanafnan09/Lab5Java/blob/8d1a424497dd642c934e96411282151bdaeb9de9/LAB5%20image/LAB%205%20Tampilan%209.png)

Tampilan tersebut ialah penginputan bilangan ganjil dan genap jika memasukan angka 1,3,5 maka menjadi ganjil.Jika memasukan angka genap seperti 2,4,6 maka menjadi Bilangan genap 

10. Buatlah file baru `form_button`

```html
<script language="javascript">
  function ubahwarnaLB(warna) {
    document.bgColor = warna;
  }
  function ubahwarnaLD(warna) {
    document.fgColor = warna;
  }
</script>
<body>
  <h1>tes</h1>

  <form>
    <input
      type="button"
      value="Latar Belakang Hijau"
      onclick="ubahwarnaLB('GREEN')"
    />

    <input type="button" value="Teks Biru" onclick="ubahwarnaLD('YELLOW')" />  
  </form>
</body>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/7ba30084ab1ec4a9ca9cadcf6654d5b7617c0deb/LAB5%20image/Cuplikan%20layar%202025-10-23%20234550.png)

Tampilan tersebut terdapat dua tombol yaitu Latar Belakang hijau dan Teks Kuning kedua tombol tersebut ialah mengubah warna background dan text

# HTML DOM

Buat file baru `HTML DOM`

```html
<html>
  <head>
    <title>Daftar Menu</title>
    <script>
      function hitung(ele) {
        var total = document.getElementById("total").value;
        total = total ? parseInt(total) : 0;
        var harga = 0;

        if (ele.checked) {
          harga = ele.value;
          total += parseInt(harga);
        } else {
          harga = ele.value;
          if (total > 0) total -= parseInt(harga);
        }

        document.getElementById("total").value = total;
      }
    </script>
  </head>
  <body>
    <h1>Daftar Menu Makanan</h1>
    <label
      ><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);" />
      Ayam Goreng Rp. 5.000</label
    ><br />
    <label
      ><input type="checkbox" value="500" id="menu2" onclick="hitung(this);" />
      Tempe Goreng Rp. 500</label
    ><br />
    <label
      ><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);" />
      Telur Dadar Rp. 2.500</label
    ><br />
    <strong>Total Bayar: Rp. <input id="total" type="text" /></strong>
  </body>
</html>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/7ba30084ab1ec4a9ca9cadcf6654d5b7617c0deb/LAB5%20image/html%20dom.png)

Fungsi pada kode tadi ialah membuat tombol pada menu makanan lalu jika mengklik salah satu tombol ataupun meng klik semuanya akan terjumlahkan dari hasil semua menu itu tersebut

# Pertanyaan dan Tugas

Jawab

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Contoh Validasi Form</title>
    <script>
      function validateForm() {
        // Ambil nilai dari field
        var nama = document.forms["myForm"]["nama"].value;
        var usia = document.forms["myForm"]["usia"].value;

        // 1. Validasi Nama (Tidak boleh kosong)
        if (nama == "") {
          alert("Nama harus diisi.");
          document.forms["myForm"]["nama"].focus(); // Fokus ke field nama
          return false; // Menghentikan submit form
        }

        // 2. Validasi Usia (Tidak boleh kosong)
        if (usia == "") {
          alert("Usia harus diisi.");
          document.forms["myForm"]["usia"].focus(); // Fokus ke field usia
          return false;
        }

        // 3. Validasi Usia (Harus berupa angka)
        // isNaN (Is Not a Number) akan mengembalikan true jika usia BUKAN angka
        if (isNaN(usia)) {
          alert("Usia harus berupa angka.");
          document.forms["myForm"]["usia"].focus();
          return false;
        }

        // Jika semua validasi lolos
        alert("Form berhasil divalidasi dan siap untuk disubmit!");
        return true;
      }
    </script>
  </head>
  <body>
    <h1>Form Pendaftaran</h1>

    <form
      name="myForm"
      action="/submit-data"
      onsubmit="return validateForm()"
      method="post"
    >
      <label for="nama">Nama:</label><br />
      <input type="text" id="nama" name="nama" /><br /><br />

      <label for="usia">Usia:</label><br />
      <input type="text" id="usia" name="usia" /><br /><br />

      <input type="submit" value="Submit" />
    </form>
  </body>
</html>

```

![foto](https://github.com/nanafnan09/Lab5Java/blob/7ba30084ab1ec4a9ca9cadcf6654d5b7617c0deb/LAB5%20image/LAB%205%20QUIZ.png)

Fungsi pada code diatas ialah memunculkan fungsi pada pengisian form, Difoto tersebut terdapat dua kolom Nama dan Usia jika menginput nama dan usia akan memunculkan notif


