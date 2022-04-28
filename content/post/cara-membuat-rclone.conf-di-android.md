---
title: "Cara membuat Rclone.conf di Android dengan Aplikasi RCX"
date: 2022-04-19T19:23:24+07:00
draft: false
tags:
  - Rclone
  - Cloud
---

## Apa itu RCX?

> RCX adalah aplikasi yang digunakan untuk cloud file manager yang dibuat oleh Rclone

sebelum ke tutorial kamu harus mendownload aplikasinya :
- `RCX Android` https://github.com/x0b/rcx/releases

disaat tulisan ini dibuat saya menggunakan versi *rcx-v1.12.2-x86_64-release.apk*

jika sudah, install dan kemudian buka aplikasinya
klik tanda +
![01](https://telegra.ph/file/8b77da5316b6751681ab2.jpg)

sebagai contoh disini saya akan menggunakan dropbox untuk cloudnya, jika kamu ingin menggunakan cloud lain silahkan sesuai keinginan, `NEXT`.
![01](https://telegra.ph/file/5048a756942ea8d84c850.jpg)

kemudian Name nya isi dropbox `App Client Id` dan `App Client Secret` dibiarkan kosong saja, klik `NEXT`.
![01](https://telegra.ph/file/03075860f4907fad0ee1a.jpg)

selanjutnya tab akan terbuka otomatis, saya sarankan alihkan ke Browser chrome untuk loginnya, isi username dan passwordnya dan klik `Sign in`
![01](https://telegra.ph/file/89561689b293444658d57.jpg)

Klik `Allow`
![01](https://telegra.ph/file/5bc10dfd89aa15dfd3683.jpg)

Nah, jika tampilannya sudah seperti ini berarti sudah sukses di autorisasi dengan cloud dropboxnya. Tekan tombol Home di Android kalian 
![01](https://telegra.ph/file/c78cdc06935f92f4e3cb6.jpg)

dan buka kembali aplikasi RCX, Klik tanda garis-garis 3 diatas kiri
![01](https://telegra.ph/file/8b7c65c654ef8fa3aba29.jpg)

klik `Export Rclone Config`
![01](https://telegra.ph/file/3c479f2706bd6c1671e76.jpg)

simpan di folder manapun yang kamu inginkan, disini saya simpan di folder X, `SIMPAN`
![01](https://telegra.ph/file/145d70cb190031637d2c6.jpg)

BERHASIL!!! kamu sudah membuat rclone.conf
![01](https://telegra.ph/file/0d02c25f676a452e73391.jpg)

