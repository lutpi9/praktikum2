## Laporan Praktikum 2 (Lutpiah)
* Latihan 1 dan 2:
<p align="left">
  <img src="/foto/latihan12.png" width="500">
</p>

    print("Hello!")
    print("UPB belajar Python!")

Perintah ***print*** memungkinkan Anda mencetak kata atau perintah dengan Python.

    # variabel
    a = 20
    b = 700

    # cetak dan hitung variabel
    print("Nilai pertama:", a)
    print("Nilai kedua:", b)
    print("Hasil dari kedua nilai:", a + b)

***a = *** dan ***b = *** adalah variabel dan bilangan bulat. 
***, a + b*** adalah perintah dalam Python untuk menambahkan variabel yang terdaftar.

* Latihan 3:
<p align="left">
  <img src="/foto/latihan3.png" width="400">
</p>

    # input nilai variabel bersifat intenger
    n = int(input("Masukan nilai n: "))
    t = int(input("Masukan nilai t: "))
    
    # cetak nilai variabel
    print("Variabel n:", n)
    print("Variabel t:", t)
    
    # cetak hasil operasi kedua variabel dengan format string
    print("Hasil penggabungan {0} & {1}: %d".format(n, t) % (n + t))
    
    # konversi nilai variabel
    n = int(n)
    t = int(t)
    print("Hasil penjumlahan {0} + {1}: %d".format(n, t) % (n + t))
    print("Hasil pembagian {0} / {1}: %d".format(n, t) % (n / t))

***int*** memiliki efek mengatur sifat perintah menjadi bilangan bulat. 
***input*** berfungsi untuk memasukkan kata atau angka yang diinginkan. 
Fungsi ***, n*** dan ***, t***  untuk mengatur variabel yang telah ditentukan sebelumnya. 
Fungsi ***{0}*** dan ***{1}***  untuk memanggil variabel secara berurutan. 
***%d*** adalah hasil yang ditentukan dalam ***.format***.
