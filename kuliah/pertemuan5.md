

Arti method writer

1. a)Point (x,y)

Memasukan data berbentuk point kedalam shp dan seluruh data harus format ESRI=1

1. b)Poly ([a,b],[c,d])

Memasukan data geospasial berbentuk polygon atau polyline. Polygon yaitu sekumpulan garis yang kembali ke titik awal sedangkan polyline adalah sekumpulan garis yang tidak kembali ke titik awal.

1. c)Field (&#39;kota&#39;,&#39;1&#39;,&#39;40&#39;)

Membuat atribut tabel bernama kota dengan tipe data varchar panjang 40 karakter jika ingin tambah field maka panggil kembali method field. Contoh field (&#39;Budaya&#39;,&#39;C&#39;,&#39;40&#39;)

1. d)Record(&#39;Bandung&#39;)

Mengisi tabel yang hanya 1 field dengan value &#39;Bandung&#39; jika data dua field maka record (&#39;Bandung&#39;,&#39;kota&#39;)

1. e)Save (&#39;namafile&#39;)

Menyimpan file shapefile di komputer

Contoh :

POINT

a.point(10,12)

POLYLINE

a.poly(parts[[1,5],[5,5],[3,3]])

shapeType.shapefile(polyline)

POLYGON

a.poly (parts[[1,5],[5,5],[5,1]])

Kesimpulan dan Saran

Berdasarkan uraian di atas maka teknik atau format penulisan dalam membuat data geospasial berbeda-beda dan disesuaikan dengan jenis data yang akan dibuat. Saran untuk belajar membuat data geospasial harus memahami struktur penulisan dalam bahasa pemrograman python.

