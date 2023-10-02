Nama  : Muhamad David Ali

Kelas : TI.22.A1

NIM   : 312210291
#

# Lab1
**Intruksi Praktikum**
**1**. Persiapkan text editor misalnya **VSCode**
![Screenshot 2023-09-28 135330](https://github.com/Luxcario/Lab1/assets/116184002/c53fa646-d903-4065-8fd3-d37d041f5a86)

**2**. Buat file baru dengan nama **Lab1_tag_dasar.html**
![Screenshot 2023-09-27 204959](https://github.com/Luxcario/Lab1/assets/116184002/5231e253-4237-4f78-8fd4-6ed145774953)

**3**. Buat stuktur dasar dari dokumen HTML.
```
   <!DOCTYPE html>
   <html>
   <head>
       <title>Tag HTML Dasar</title>
   </head>
   <body>
    
   </body>
  </html>
```
   ![Screenshot 2023-09-28 140024](https://github.com/Luxcario/Lab1/assets/116184002/82460ec9-ad68-40cd-9029-4ac276aeac0e)

buka file tersebut, Run Without Debugging, pada web browser misalnya Chrome.
![image](https://github.com/Luxcario/Lab1/assets/116184002/c6ee6928-e67c-42cb-939a-a6bc5a004f01)

Hasil
![image](https://github.com/Luxcario/Lab1/assets/116184002/062cfc4a-e5fe-460a-9b90-e8605b0bdabc)

**4**. Ikuti Langkah-langkah praktikum yang akan dijelaskan berikutnya.
   
   4.1.1 **Membuat Paragraf**
   tag untuk membuat paragraf
   ```
   <p></p>
   ```
   
   ![image](https://github.com/Luxcario/Lab1/assets/116184002/51081125-df06-4a74-9982-1e1288834fdb)
   
   Buat Tag didalam body
   
   ![image](https://github.com/Luxcario/Lab1/assets/116184002/a05ab051-3ced-4a28-b18c-bb103517c865)
   

   Kembali ke browser lalu refresh maka hasilnya akan seperti ini 
   ![image](https://github.com/Luxcario/Lab1/assets/116184002/da92e610-c9b3-412e-9ef2-873e06b32fe3)


```
<!-- --> (hanya sebagai tanda bukan TAG).
```
   
   4.1.2 **Memasukkan atribut**
```
<p align="center"></p>
```
untuk membuat paragraf menjadi Rata Tengah
![image](https://github.com/Luxcario/Lab1/assets/116184002/1f6b37fb-e07e-4aa4-923b-95fba0a233f5)

Kembali ke browser lalu refresh maka hasilnya akan seperti ini
![image](https://github.com/Luxcario/Lab1/assets/116184002/ff58c733-5a39-42d2-b346-77f5a6f9fe12)

   
   4.2
   **Menambahkan Judul**
```
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
```
Fungsi = membuat sebuah Teks/judul bercetak tebal, dan semakin besar angka maka hasilnya akan semakin kecil. TAG ini berbeda dengan
```
<p></p>
```

masukkan Tag

```
<h1>Judul</h1>
```
![image](https://github.com/Luxcario/Lab1/assets/116184002/77573f5d-ec7a-488d-ab59-194bd101edf8)

kembali ke browser, lalu refresh maka hasilnya akan seperti ini
![image](https://github.com/Luxcario/Lab1/assets/116184002/c4e37671-dbb9-41a9-865b-c84885aa92cd)

4.3

**Memformat Teks**

Memformat teks menggunaka Tag, contoh tag:
```
<b>untuk cetak Tebal</b>
<i>untuk cetak miring</i>
<mark>untuk memberi tanda pada teks</mark>
<ins>untuk memberi garis bawah pada teks</ins>
```
contoh
![image](https://github.com/Luxcario/Lab1/assets/116184002/aa8634b7-216c-4d4f-ae5e-13ba4d79803f)

kembali ke browser lalu refresh kembali, hasil
![image](https://github.com/Luxcario/Lab1/assets/116184002/c930d50a-8637-4341-9a8f-c4417584ba82)

4.4 **Menambahkan Gambar**
Langkah pertama masukkan gambar pada folder yang sama dengan file html.

![image](https://github.com/Luxcario/Lab1/assets/116184002/a3b85300-3628-4957-9e2f-fabcecc6ffef)

maka akan langsung tampil pada file di VSCode

![image](https://github.com/Luxcario/Lab1/assets/116184002/821edb6c-075a-4338-8343-7fe3dd2e56e9)

Masukkan Tag dan atribut untuk menampilkan gambar pada browser
```
<img src="link gambar" title="nama gambar"/>
```
![image](https://github.com/Luxcario/Lab1/assets/116184002/a3763d63-9190-407c-8f69-ab83593d17b0)

kembali pada browser lalu refresh, hasilnya
![image](https://github.com/Luxcario/Lab1/assets/116184002/f7118ee2-ba93-4514-8acf-a8d875db3f32)

untuk mengatur ukuran dari gambar gunakan tag berikut :
```
width="untuk lebar"
height="untuk tinggi"
```
contoh :
![image](https://github.com/Luxcario/Lab1/assets/116184002/a2816bf9-9c95-4e7a-89fe-8c27465a4bd7)

kembali ke browser lalu refresh, hasilnya
![image](https://github.com/Luxcario/Lab1/assets/116184002/8a9e5801-c2cd-4200-987d-dd745aab2588)

sesuaikan ukuran sesuka hati masing-masing.









4.5
**Tag Anchor dan Hyperlink**

Link atau Hyperlink merupakan elemen HTML yang berfungsi untuk menghubungkan satu halaman 
web dengan halaman web yang lain, baik internal maupun eksternal.
Link juga dapat menghubungkan beberapa bagian pada halaman yang sama atau disebut sebagai 
Anchor. 
Elemen link ini dapat diklik sehingga akan membuka halaman atau bagian sesuai dengan URL yang 
diberikan pada link tersebut.
Untuk membuat Hyperlink atau Anchor menggunakan tag <a> dengan menambahkan atribut href 
sebagai penentu URL yang dimaksud.

Masukkan pada body, contoh: 

```
<nav>
    <a href="Lab_tag_dasar.html">Dasar HTML</a>
</nav>
```
note : Lab_tag_dasar.html adalah file pertama, jika project yang akan dibuat memiliki dua jendela maka masukkan sesuai pada file ke 2 yang dibuat seperti gambar dibawah.

```
<hr></hr>
```
untuk  membuat garis bawah.

![image](https://github.com/Luxcario/Lab1/assets/116184002/b1a56603-4623-4bde-a503-06924e8a40f5)

pada gambar diatas ada 3 link pada atribut, link ke 3 adalah link dari luar, untuk memasukkannya hanya perlu mengcopy alamat link pada website seperti contoh diatas yaitu link 'google'

kembali pada browser lalu refresh, hasil

![image](https://github.com/Luxcario/Lab1/assets/116184002/d4285ede-506c-4667-901d-c56904e01885)

pada gambar diatas memiliki 3 link, apabila mengklik 'Halaman 2' maka akan berpindah jendela, apa bila mengkilik 'Halaman Web Eksternal' maka akan berpindah ke web yang di masukkan pada atribut 'href'

**5**Lakukan validasi dokumen html dengan mengakses https://validator.w3.org/

**Jawab Pertanyaan Berikut**

![Screenshot 2023-10-02 212251](https://github.com/Luxcario/Lab1/assets/116184002/0c917d5c-ea25-45ea-b14c-e8ed8a6ee91e)

1. Saya membuat halaman

 ![image](https://github.com/Luxcario/Lab1/assets/116184002/3349bb08-d8ae-4e47-b4ff-f37b9d58d6d5)
 ![Screenshot 2023-10-02 233351](https://github.com/Luxcario/Lab1/assets/116184002/e4e6ed37-039d-44bf-a5e8-15c85ce193be)

 hasil:
![image](https://github.com/Luxcario/Lab1/assets/116184002/11c10977-6029-4365-905a-3f94ec797cd6)

2. ```
   <p>
   ```
   Fungsinya untuk membuat baris paragraf
   
   ```
   <br/>
   ```
   Fungsinya untuk mengganti baris pada paragraf
   
   contoh :
   
   ![Screenshot 2023-10-02 212012](https://github.com/Luxcario/Lab1/assets/116184002/ebf09a1c-46a9-478d-a15f-20df369dcbb9)
   
   Hasil :
   
   ![Screenshot 2023-10-02 212023](https://github.com/Luxcario/Lab1/assets/116184002/5e693dd7-f94d-47e9-91dc-26480a4787f2)

3. Atribut **title** berfungsi untuk judul pada gambar ketika crosshair/anak panah mouse diarahkan pada gambar maka akan muncul nama yang dimasukkan pada atribut **title**, sedangkan **alt** berfungsi sebagai deskripsi gambar jika gambar eror atau tidak ada maka akan menampilkan nama yang dimasukan pada atribut **alt**.

   contoh:
ketika gambar tidak eror

![Screenshot 2023-10-02 213129](https://github.com/Luxcario/Lab1/assets/116184002/1a8a877a-7109-4c6d-9db4-9a90bbb65447)

hasil:

![image](https://github.com/Luxcario/Lab1/assets/116184002/9b1a1c56-236a-40b3-9830-9fa86ed9e980)



jika logo/gambar tidak ada/eror

![image](https://github.com/Luxcario/Lab1/assets/116184002/f2c85e74-178e-4847-998d-0f9ca35183eb)

hasil

![image](https://github.com/Luxcario/Lab1/assets/116184002/0146ec49-8669-42c8-8b2a-1d02f5568667)

4. Tidak harus menggunakan height dan width, sesuai dengan ukuran asal dari gambar, apabila ingin memperbesar/kecil gambar cukup (gambar sempurna) dengan salah satu dari atribut itu sudah cukup, namun apabila menggunkanan salah satu dari atribut gambar tidak sempurna maka diharuskan menggunakan kedua atribut tersebut lalu menyesuaikan ukurannya bisa dengan ukuran px atau %.

5. _self   : ini adalah default. URL action akan dibuka di halaman yang sedang aktif.

   _blank  : ini adalah default. URL action akan dibuka di halaman yang sedang aktif.

   _parent : URL action akan dibuka pada parent frame (jika suatu dokumen dimuat dalam <iframe>)

   _top    : URL action akan dibuka pada frame paling atas (jika suatu dokumen dimuat dalam <iframe> bertingkat)


   

   

