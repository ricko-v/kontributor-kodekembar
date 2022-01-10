# kontributor
Kami membuka peluang kepada teman-teman untuk dapat berkontribusi ke website https://kodekembar.web.app.

# Table Directory
| directory | keterangan |
| --------- | ---------- |
| posts     | Folder untuk upload postingan |
| penulis   | Folder untuk upload data penulis |
| post_img  | Folder untuk upload keperluan gambar dalam postingan |

# Upload Postingan
Teman-teman dapat mulai berkontribusi dengan membuat folder ```posts/{kategori bahasa}/{judul postingan}``` yang didalamnya terdapat file ```index.md``` dan ```thumb.png```.

contoh isi file ```index.md```:

```yaml
---
title: Apa Itu HTML
slug: apa-itu-html
description: Mari berkenalan dengan HTML.
category: Html
tag: ['HTML', 'html-dasar']
penulis: ricko-v
---

isi postingan teman-teman.
```

Jika didalam postingan teman-teman memerlukan assets gambar, teman-teman dapat menguploadnya di folder ```post_img``` dan cara menuliskan pathnya adalah ```/post_img/{kategori bahasa}/{judul postingan}/{nama gambar.png}```.

# Upload Data Penulis
Sebelum teman-teman membuat atau mengupload postingan, teman-teman harus membuat data diri terlebih dahulu di folder penulis. Teman-teman dapat memulainya dengan membuat folder ```penulis/{username}``` yang didalamnya terdapat file ```index.md``` dan ```thumb.png```.

Contoh isi file ```index.md```:

```yaml
---
nama: Ricko Veriyanto
username: ricko-v
status: Pelajar
facebookID: 100008858555156
github: ricko-v
email: veriyantoricko302@gmail.com
---
```
