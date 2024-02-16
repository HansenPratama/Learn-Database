Jalankan Apache dan MySQL  
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/c4nVeRF.jpeg">
</p>

Buka localhost pada browser
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/1Jn7Zrz.jpeg">
</p>

Buat Database baru dengan nama penjualan_produk
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/kCdoRPu.jpeg">
</p>

Import file SQL 
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/C1X5mCU.jpeg">
</p>

Nama database penjualan_produk muncul dalam daftar database
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/lSa7gL2.jpeg">
</p>

Diagram database penjualan_produk
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/l5A2l14.png">
</p>

List data barang
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/nHQjwcz.png">
</p>

SOAL 1
Tambahkan data penjualan sebagaimana berikut 
1.	kode_penjualan = 3
2.	tgl = 8 Februari 2021
3.	kasir = Dini
4.	total_penjualan = 10.000
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/LxUH0JM.png">
</p>

SOAL 2
Tambahkan data penjualan sebagaimana berikut 
1.	kode_penjualan = 2
2.	tgl = 10 Februari 2021
3.	kasir = Dini
4.	total_penjualan = 20.000
<p align="center">
  <img width="460" height="300" src="https://i.imgur.com/qW5VQP4.png">
</p>

SOAL 3 
Solusi untuk soal nomor 2 adalah mengganti kode penjualan dari 2 menjadi 4 karena kode penjualan tidak dapat di duplikat
<p align="center">
  <img width="460" height="300" src="">
</p>

SOAL 4
![image](https://github.com/HansenPratama/Learn-MyPHP-Admin/assets/160198005/b2e00c08-9ddc-4bb4-9ca3-223f75cbf1c9)
Data dapat ditambahkan tetapi nominal harga berubah menjadi 5

SOAL 5
Solusi untuk soal nomor 4 adalah dengan menghapus tanda titik “.” 
Pada nominal dari 5.000 menjadi 5000
![image](https://github.com/HansenPratama/Learn-MyPHP-Admin/assets/160198005/67a74193-3e3b-41a4-904a-fbde469d97d6)

SOAL 6
Duplikasi : duplikasi data terjadi ketika ada lebih dari satu baris dalam tabel yang memiliki nilai yang sama pada beberapa kolom, pada soal diatas contohnya, terdapat nilai yang sama pada kolom kode penjualan sehingga data tidak dapat ditambahkan.
Inkonsisten data : Inkonsistensi data adalah munculnya data yang tidak konsisten pada kolom yang sama dalam satu atau beberapa file data yang dihubungkan.

SOAL 7
Tambahkan data detail_penjualan sebagaimana berikut <SOAL 7>
- kode_penjualan = 2
- kode_barang = 3
- harga = 5.000
- jumlah = 5
![Screenshot 2024-02-16 080441](https://github.com/HansenPratama/Learn-MyPHP-Admin/assets/160198005/a115b57f-ae77-4563-b4a4-ae31876f36ed)
Data tidak dapat ditambahkan karena data dengan kode_penjualan 2 telah ada sebelumnya/duplikat

Penghapusan garis hubung antara tabel penjualan dan detail_penjualan
![Screenshot 2024-02-15 204650](https://github.com/HansenPratama/Learn-MyPHP-Admin/assets/160198005/04dde220-dc6f-40a1-9b0c-05f3ad37b504)

Data tetap bisa ditambahkan 
![Screenshot 2024-02-16 093809](https://github.com/HansenPratama/Learn-MyPHP-Admin/assets/160198005/d1cc2a84-b462-4f65-8341-d23b3a9229e2)

