# SWITCHING

NAMA : RIANDA SAPUTRA
NIM : 09030582226018

ALAT DAN BAHAN 
 
Alat dan Bahan yang diperlukan dalam praktikum Jaringan Komputer ini adalah : 
 
1.	Sebuah PC atau Laptop 
2.	Software Jaringan ‘Cisco Packet Tracer’ 
 
 
SWITCH 
 
Switch merupakan perangkat jaringan yang bekerja pada OSI Layer 2, Data Link Layer. dia bekerja sebagai penyambung / concentrator dalam Jaringan. Switch mengenal MAC Adressing shingga bisa memilah paket data mana yang akan di teruskan ke mana. Dan switch ini digunakan sebagai repeater/penguat. Berfungsi untuk menghubungkan kabel- kabel UTP ( Kategori 5/5e ) komputer yang satu dengan komputer yang lain. Dalam switch biasanya terdapat routing, routing sendiri berfungsi untuk batu loncat untuk melakukan koneksi dengan komputer lain dalam LAN. 
Switch dapat diartikan sebagai sebuah alat jaringan yang melakukan bridging transparan (penghubung segementasi banyak jaringan dengan forwarding berdasarkan alamat MAC). 
Switch jaringan dapat digunakan sebagai penghubung komputer atau router pada satu area yang terbatas, switch juga bekerja pada lapisan data link, cara kerja switch hampir sama seperti bridge, tetapi switch memiliki sejumlah port sehingga sering dinamakan multi-port bridge. 
Switch dapat dikatakan sebagai multi-port bridge karena mempunyai collision domain dan broadcast domain tersendiri, dapat mengatur lalu lintas paket yang melalui switch jaringan. 
Cara menghubungkan komputer ke switch sangat mirip dengan cara menghubungkan komputer atau router ke hub. Switch dapat digunakan langsung untuk menggantikan hub yang sudah terpasang pada jaringan. 
Fungsi Switch adalah untuk melakukan bridging transparan sebagai penghubung segmentasi dari banyak jaringan dengan mem-forward berdasarkan alamat MAC. Switch juga sebagai penghubung beberapa alat untuk membentuk suatu Local Area Network (LAN). 
CARA KERJA SWITCH 
 
Cara Kerja Switch yaitu menerima dan menganalisa seluruh isi paket sebelum meneruskannya ke tujuan. Switch memeriksa satu persatu paket untuk mengetahui adanya kerusakan pada paket tersebut dan mencegahnya agar tidak mengganggu jaringan. Switch mengalokasikan bandwidth secara penuh untuk setiap portnya. Komputer pengguna akan selalu memiliki bandwidth secara penuh seberapapun komputer yang ada. Switch bekerja di lapisan Data Link dan Setiap port didalam swith memiliki domain collision sendiri- sendiri. Switch melakukan transmisi secara 2 arah (Full duplex). 
LANGKAH KERJA 
![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/588f84e1-9cdb-4873-bd03-befd95fe6cf4)

 
 
-	Persiapkan 2 buah PC dan 1 buah Switch. 
-	Pasang kabel penghubung antara PC 0 ke Switch dan PC 1 ke Switch.
-	![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/34b04dd8-d01f-47a6-840b-b08b70c5384f)
 
 
 
-	Double click pada PC 0 sehingga muncul jendela baru, seperti berikut - 	Click pada tab Desktop sehingga muncul tampilan sebagai berikut.
-	![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/9b5281a3-8937-45d3-b282-60f07da2d6cd)

 
 
 
-	Click pada tab IP Configuration, untuk mengatur alamat IP pada PC 0.
-	![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/7cb94007-6af5-4fa5-8664-39eff93c433a)

 
 
 
-	Isikan Alamat IP dan Subnet Mask pada PC 0 dengan alamat seperti dibawah ini dan kosongkan kolom Default Gateaway dan DNS server.
-	![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/2a314e63-086d-4bbd-bf5d-1704f43cbc6e)

 
 
-	Lakukan hal serupa pada PC 1 tetapi dengan konfigurasi alamat IP yang berbeda dengan PC 0, tetapi Subnet Mask nya biarkan sama. Selain itu tetap kosongkan kolom Default Gateaway dan DNS server. 
 ![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/0552d6eb-1dfd-4b8c-948c-3c823fbb3183)

 
 
-	Setelah mengkonfigurasi IP maka 3 buah device tersebut akan saling terhubung ditandai dengan dot / node yang berwarna hijau.
-	![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/e9745e83-170c-41fa-a155-e24b3860642c)

 
 
 
-	Untuk melakukan testing pada jaringan tersebut, kita dapat melakukan “ping” 
-	Caranya dengan double clik salah satu dari dua PC (antara PC 0 atau PC 1) dan clik pada tab Desktop. 
-	Kemudian pilih tab Command Prompt dan akan muncul jendela seperti di bawah ini.
-	![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/8c62a330-5c5f-40b3-a18c-c7bab9c96426)

 
 
 
-	Kemudian ketik “PING (alamat IP tujuan) “ ; Contoh nya adalah ‘PING 192.168.123.2’ maka jaringan kita telah terhubung, akan jadi seperti di bawah ini.
-
-	![image](https://github.com/Riandasaputra122/SWITCHING/assets/150990509/263c2b25-9c3a-4221-bfe8-35497f8e246e)

 
 
