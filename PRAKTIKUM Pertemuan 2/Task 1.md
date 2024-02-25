PRAKTIKUM 1 / TASK 1

> Ada dua tabel yang mungkin digunakan bisnis kecil untuk memproses pesanan produknya. Tabel pertama adalah tabel info pelanggan, sehingga setiap catatan mencakup nama pelanggan, alamat, informasi pengiriman dan penagihan, nomor telepon, dan informasi kontak lainnya. Setiap bit informasi (setiap atribut) ada di kolomnya sendiri, dan database memberikan ID unik (kunci) untuk setiap baris. Di tabel kedua—tabel pesanan pelanggan—setiap catatan menyertakan ID pelanggan yang melakukan pemesanan, produk yang dipesan, jumlah, ukuran dan warna yang dipilih, dan seterusnya—tetapi bukan nama pelanggan atau informasi kontak.

> Kedua tabel ini hanya memiliki satu kesamaan: kolom ID (kunci). Namun karena kolom umum tersebut, database relasional dapat membuat hubungan antara kedua tabel. Kemudian, ketika aplikasi pemrosesan pesanan perusahaan mengirimkan pesanan ke database, database dapat menuju ke tabel pesanan pelanggan, mengambil informasi yang benar tentang pesanan produk, dan menggunakan ID pelanggan dari tabel tersebut untuk mencari penagihan dan pengiriman pelanggan. informasi dalam tabel info pelanggan. Gudang kemudian dapat menarik produk yang benar, pelanggan dapat menerima pengiriman pesanan tepat waktu, dan perusahaan dapat menerima pembayaran.

> Gambarkan kasus tersebut dalam bentuk table data relasional

<p align="center">
  <img width="560" height="300" src="https://i.imgur.com/ixkaegq.png">
</p>
