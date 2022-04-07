# APA ITU TAG FORM?

Tag _form_ adalah sebuah tag padat HTML yang biasanya digunakan untuk 'membugkus' tag `input` yang nantinya akan digunakan untuk mengolah data (Biasanya untuk memasukkan / mengubah data ke dalam database).

Tag `form` ini memiliki beberapa atribut di dalamnya, yaitu:

- `action`: Untuk mengarahkan kemana data - data yang ada akan di olah.
- `method`: Untuk menentukan _method_ apa yang akan digunakan ketika mengolah data.
- `entype`: Untuk menentukan apakah data akan di tampilkan atau tidak pada form yang harus di lakukan encoding ketika submit ke server.

Adapun contoh penulisan kodenya adalah:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <form action="data.php" method="post">
      <!-- Isi konten yang biasanya berupa tag input -->
      <label>Masukkan Username</label>
      <input type="text" placeholder="Masukkan Username" />
      <label>Masukkan Password</label>
      <input type="password" placeholder="Masukkan Password" />
    </form>
  </body>
</html>
```

PENJELASAN:
Kode diatas berarti apapun data yang dimasukkan oleh user akan di olah pada halaman `data.php` dan memiliki method `post`.

\*CATATAN PENTING:
Untuk penjelasan mengenai bagaimana cara mengolah data, apa itu method 'post', ada apa saja method - method yang ada selain 'post' tidak akan kita bahas pada materi pembelajaran HTML ini. Jadi, pada materi ini kita hanya akan membahas mengenai apa itu tag form, bagaimana cara penulisannya dan biasa digunakan untuk apa saja tag ini. Selain itu, untuk materi mengenai tag `<input>` akan kita bahas lebih lanjut pada materi khusus tentang tag _input_ ini.

Nah, sekian penjelasan singkat dari saya mengenai tag form ini, semoga kalian dapat dengan mudah memahaminya dan juga membuat kalian menjadi semakin giat dan bersemangat dalam mempelajar HTML ini.

Terimakasih dan selamat belajar...😊
