* MUHAMMAD FIRMAN EL ARIF
* 17.01.53.2028

# MANAJEMEN-MEMORY
## 1. WORST-FIT
  
 * Worst fit akan mencari lubang terbesar. Sebagaimana best fit kita harus mencari dari keseluruhan daftar kecuali jika daftar tersebut telah terurut berdasarkan ukuran. Strategi ini menghasilkan sisa lubang terbesar. Berdasarkan gambar diatas jika blok berukuran 2 dibutuhkan maka berdasarkan worst fit akan memilih lubang pada alamat 28 yaitu lubang terbesar yang cukup menampung permintaan proses tersebut.
  
 ## CAPTURE DOKUMENTASI WORST-FIT
 ![alt text](https://github.com/elarif12/MANAJEMEN-MEMORY/blob/master/worstfit%20hasil.png?raw=true "Capture1")
  
## 2. BEST-FIT
 
 * Best fit mencari dari keseluruhan daftar (kecuali jika daftar tersebut telah terurut berdasarkan ukuran), dan memilih lubang terkecil yang cukup untuk menampung proses yang bersangkutan. Daripada harus memecah sebuah lubang besar, yang mungkin saja dapat lebih bermanfaat nantinya, best fit mencari lubang dengan ukuran yang hampir sama dengan yang dibutuhkan oleh proses. Strategi ini menghasilkan sisa lubang terkecil. Kekurangan best fit jika dibandingkan dengan first fit adalah lebih lambat karena harus mencari ke seluruh tabel tiap kali dipanggil. Berdasarkan gambar diatas jika blok berukuran 2 dibutuhkan maka berdasarkan best fit akan memilih lubang pada alamat 18 yaitu lubang terkecil yang cukup menampung permintaan proses tersebut.
 
 ## CAPTURE DOKUMENTASI BEST-FIT
 ![alt text](https://github.com/elarif12/MANAJEMEN-MEMORY/blob/master/bestfithasil.png?raw=true "Capture2")
 
 ## 3. FIRST-FIT
 
  * Memory manager akan mencari sepanjang daftar yang berisi besarnya ukuran memori yang dibutuhkan oleh proses dalam antrian beserta ukuran memori yang tersedia pada saat itu. Setelah menemukan lubang yang cukup besar (ruang memori dengan ukuran lebih besar dari ukuran yang dibutuhkan oleh proses bersangkutan), lubang itu lalu dipecah menjadi 2 bagian. Satu bagian untuk proses tersebut dan bagian lain digunakan untuk memori yang tak terpakai, kecuali tentu saja jika memang ukuran ruang memori tersebut sama besar dengan yang dibutuhkan oleh proses. First fit ini merupakan algoritma yang bekerja dengan cepat karena proses pencariannya dilakukan sesedikit mungkin
  
 ## CAPTURE DOKUMENTASI FIRST-FIT
 ![alt text](https://github.com/elarif12/MANAJEMEN-MEMORY/blob/master/firsthasil.png?raw=true "Capture3")
