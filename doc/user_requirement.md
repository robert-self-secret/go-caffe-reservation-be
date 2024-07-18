# Kebutuhan Pengguna

---

## Deskripsi

[nama aplikasi] merupakan sebuah aplikasi untuk melakukan reservasi meeting room, co-working space, dan event space, pada cafe atau restaurant.

## Fitur

- Pengguna dapat melakukan autentikasi seccara multi role (customer & owner) - `cutomer`merupakan pengguna yang akan melakukan reservasi tempat - `owner`merupakan pengguna yang memiliki atau menyewakan tempat kepada customer
  <br>
- Customer dapat memiliki data pengguna sebagai berikut:
  - username
  - email
  - password
  - photo profile
  - App Point
    <br>
- Owner dapat memili data pengguna sebagai berikut:
  - username
  - email
  - password
  - no rekening
    <br>
- Owner dapat melakukan CRUD tempat reservasi, data tempat reservasi sebagai berikut:
  - nama tempat
  - deskripi
  - alamat tempat [provinsi, kabupaten/kota, kecamatan, desa/kelurahan, keterangan lanjut]
  - foto tempat
  - harga tempat [per jam]
  - status atau kuantitas ketersediaan tempat
  - categori tempat, meliputi: [meeting room, co-working space, event space]
    <br>
- Customer dapat melakukan pencarian tempat berdasarkan nama, dengan beberapa filter meliputi:
  - category
  - lokasi tertentu
  - harga
  - lokasi terdekat
    <br>
- Customer dapat melakukan reservasi tempat
  - dapat mengatur waktu dan tanggal reservasi
    <br>
- Customer dapat melakukan pembayaran reservasi tempat menggunakan beberapa metode pembayaran:
  - e-wallet
  - online banking atau virtual account
  - App Point
    <br>
- Customer dapat melakukan pembatalan reservasi:
  - Pembatalan reservasi dapat dilakukan pada rentang waktu tertentu
  - Uang pembayaran reservasi akan dikembalikan berupa App Point jika pembatalan tempat masih dalam jangka waktu yang telah ditentukan
    <br>
- Customer dapat melakukan review tempat
  - Dapat memberikan komentar berupa text dan gambar
  - Dapat memberikan rating berupa tombol bintang
