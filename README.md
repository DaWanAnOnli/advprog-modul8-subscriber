<h1>
  Refleksi
</h1>

<h2>
  No 7
</h2>

<h3>
  a.
</h3>

AMQP adalah singkatan dari Advanced Message Queueing Protocol. AMQP merupakan protokol yang yang dapat men-support komunikasi antara service atau aplikasi. Hal ini memungkinkan banyak komponen pada sistem yang terdistribusi untuk berkomunikasi secara asinkronus. AMQP melakukan hal ini dengan mendefinisikan aturan-aturan pada komunikasi yang kompatibel dengan sistem messaging yang berbeda. Pada AMQP, message (pesan) disimpan sebagai queue (antrian) yang dapat diakses satu per satu oleh pengguna. AMQP digunakan untuk membangun sistem-sistem yang loosely, yang menekankan modularitas dan skalabilitas. 

<h3>
  b.
</h3>

amqp:// : Indikasi bahwa koneksi digunakan menggunakan protokol AMQP.
guest pertama: username default dari amqp.
guest kedua: password default dari amqp.
@localhost:5672 : hostname dan port dari broker AMQP. Localhost berarti menggunakan mesin local, dan 5672 adalah port default untuk AMQP.

Jadi, amqp://guest:guest@localhost:5672 berarti koneksi dilakukan menggunakan protokol amqp, dengan username guest dan password guest, dijalankan di mesin lokal dengan port 5672. 
