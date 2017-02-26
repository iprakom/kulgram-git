# Panduan Github

1. Clone dulu projectnya, dengan perintah ini :

```
> git clone https://github.com/iprakom/kulgram-git
```

isikan username dan password untuk akun di github.com

2. buat nama panggilan sebagai nama file, diikuti dengan md, contoh: tamami.md, isinya nama dan instansi, contoh :

```
Nama : Tamami
Instansi : BPPKAD Kab. Brebes
```

3. periksa bahwa perubahannya telah dideteksi oleh git dengan perintah :

```
> git status
```

4. Pindahkan nama file yang sudah dibuat ke status staged dengan perintah :

```
> git add tamami.md
```

5. lakukan commit untuk file tamami.md

```
> git commit -m "pertama commit"
```
6. lakukan push ke github dengan perintah berikut :

```
> git push -u origin master
```

7. seharusnya file yang di commit sudah ada di github. selesai.
