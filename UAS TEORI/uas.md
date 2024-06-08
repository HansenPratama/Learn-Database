01.Querry Demo : <br>

SELECT nama_user
FROM user
WHERE jenis_kelamin="P"
ORDER BY nama_user ASC
<p align="center">
  <img width="1176" height="472" src="">
</p>

02.Querry Soal : <br>

SELECT nama_user, tanggal_lahir
FROM user
WHERE jenis_kelamin="L"
ORDER BY tanggal_lahir DESC;
<p align="center">
  <img width="1176" height="472" src="">
</p>

03.Course Join : <br>

SELECT
  kursus.judul,
  SUM(transaksi.total) AS total
FROM kursus
JOIN detail_transaksi ON detail_transaksi.id_kursus=kursus.id
JOIN transaksi ON detail_transaksi.id_transaksi=transaksi.id
WHERE transaksi.status = 'Completed'
GROUP BY kursus.judul
ORDER BY total DESC;
<p align="center">
  <img width="1176" height="472" src="">
</p>

04.Hewan Join : <br>

SELECT
  user.nama,
  SUM(pelayanan.harga) AS total
FROM reservasi
JOIN user ON user.id = reservasi.id_user
JOIN pelayanan ON reservasi.id_pelayanan = pelayanan.id
WHERE reservasi.status = 'Completed'
GROUP BY user.nama
ORDER BY total DESC
LIMIT 1;
<p align="center">
  <img width="1176" height="472" src="">
</p>

05.Hewan Reservasi

SELECT jenis_peliharaan, COUNT(jenis_peliharaan) AS total
FROM reservasi
GROUP BY jenis_peliharaan;
<p align="center">
  <img width="1176" height="472" src="">
</p>
