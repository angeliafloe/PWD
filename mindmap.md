<!DOCTYPE HTML>
<html lang="id">
   
# Mindmap Tech Stack Backend: Node.Js (Angel V, Angelia F. P., Nabiel)
<br>
<h1>Apa Itu Node.js?</h1>
<br>
<p align="justify">Node.js adalah sebuah platform dengan basis JavaScript, di mana adalah lingkungan runtime yang memungkinkan eksekusi kode JavaScriptdi luar browser. Node.js digunakan dalam mengembangkan aplikasi web dengan skala besar dan cepat, ini karena berbasis arsitektur event-driven dan non-blocking I/O. Efisiensi menjadikan Node.js terkenal sebab memungkinkan pengembang memanfaatkan JavaScript untuk mengeksekusi kode di server. Node. js turut banyak digunakan dalam menyokong aplikasi dengan penanganan data real-time, memungkinkan juga dalam pembuatan aplikasi yang skalabel dan berperforma tinggi.</p>

<p align="justify">Meski Node.js adalah platform basis JavaScript, keduanya memiliki perbedaan pada penggunaannya, yakni:
JavaScript: untuk mengembangkan sisi klien dari aplikasi web
Node.js: untuk menjalankan JavaScript di sisi server</p>
<br>
Node.js tepat digunakan pada saat:
<br><br>
<p align="justify">
1. Melakukan pengembangan aplikasi real-time, seperti aplikasi chatting
<br>
2. Pembangunan API untuk sistem yang besar
<br>
3. Saat memerlukan pengolahan data seketika dan sinkronisasi cepat
</p>
<br>
Fungsi Node.js:
<br><br>
1. Pengembangan server-side
<br>
2. Real-time application
<br>
3. Sebagai API
<br>
4. Pengembangan aplikasi sisi klien dan server dengan JavaScript
<br><br>
<h1>Komponen Node.js</h1>
<br>
<p align="justify">1. Javascript V8: sebuah kompiler yang dibentuk menggunakan bahasa C++, dengan komponen ini input berupa kode JavaScript dapat di compile menjadi kumpulan kode dalam tingkat assembly. Ada 3 komponen pada JavaScript: compiler (mengubah JavaScript menjadi bahasa pemrograman lain sesuai kebutuhan developer), optimizer (tool untuk mengoptimalkan aplikasi baru), dan garbage collector (memudahkan aplikasi lama ke penyimampanan agar kinerja Node.js tetap ringan) </p>
<p align="justify">2. Libuv Library: berfungsi mengoperasikan asynchronous I/O input maupun output dan main event loop dalam Node.js.</p>
<p align="justify">3. Design Pattern: tool untuk menyusun kode dengan cara memungkinkan developer mendapatkan beberapa kelebihan (waktu pengembangan lebih cepat, kode yang dapat digunakan kembali, dst). Dalam Node.js terdapat dua jenis, object pool (kumpulan objek yang dapat digunakan untuk task tertentu) dan facade (tools memberi tampilan antarmuka untuk body kode, sehingga meringankan beban developer).</p>
<br>
<h1>Kekurangan dan Kelebihan Node.js</h1>
<br>
Kelebihan Node.js
<br><br>
<p align="justify">1. Performa Tinggi
<br>
-> Kinerja tinggi dan kemampuan menangani banyak koneksi dengan bersamaan, berkat penggunaan mesin JavaScript V8 Chrome yang efisien</p>
<p align="justify">2. Pengembangan Cepat
<br>
-> Memungkinkan JavaScript di seluruh stack yang dapat mempercepat pengembangan aplikasi.</p>
<p align="justify">3. Skalabilitas
<br>
-> Scalable dan dapat dengan mudah dikonfigurasi untuk menangani peningkatan traffic. Microservices dan model event-driven Node.js membuatnya mudah untuk menskalakan aplikasi secara horizontal dengan menambahkan lebih banyak server.</p>
<p align="justify">4. Efisiensi Sumber Daya
<br>
-> Dikarenakan menggunakan sumber daya CPU dn memori secar efisien sehingga tepat untuk aplikasi yang perlu berjalan di server dengan sumber daya terbatas.</p> 
<p align="justify">5. Banyak Pilihan Framework & Library
<br>-> Menjadikan dapat menemukan framework dan library untuk berbagai keperluan, seperti pengembangan web, API, microservices, dan real-time applications.</p>
<p align="justify">6. Open Source
<br>
-> Platform gratis untuk digunakan dan dimodifikasi, ini juga berarti bahwa ada banyak komunitas pengembang yang berkontribusi pada pengembangan platform, sehingga dapat membantu meningkatkan kualitas dan kecepatan pengembangan.</p>
<br>
Kekurangan Node.js
<br><br>
<p align="justify">1. Kurang Matang
<br>
-> Ini karena platform ini relatif baru dibandingkan dengan platform back-end lain. Platform masih berada pada tahap pengembangan (tidak semua fitur yang dibutuhkan ada untuk membangun aplikasi kompleks)</p>
<p align="justify">2. Kurang Dukungan untuk Beberapa Bahasa Pemrograman
<br>
-> Node.js hanya mendukung JavaScript
<br>
<p align="justify">3. Keamanan
<br>
-> Node.js adalah platform yang berjalan pada JavaScript, di mana memiliki beberapa kerentanan keamanan. Perlu berhati-hati saat digunakan karena secara keamanan masih rentan.
<br>   
<p align="justify">4. Kurangnya Dukungan dari Perusahaan Besar
<br>
-> Node.js belum banyak diadopsi perusahaan besar dibandingkan platform back-end lainnya, ini berarti akan lebih sulit untuk menemukan pengembang Node.js yang berpengalaman dan mendapatkan dukungan perusahaan besar. 
<br>
</p>
<br>
<h1>Tren Node.js di 2025</h1>
<br>
<ul>
<li> Developing Real-Time Apps Using Node.Js </li>
- Aplikasi real-time untuk aktivitas online adalah pusat dari pengembangan Node.js. Dengan tingkat keterlibatan pengguna yang tinggi, aplikasi real-time menyediakan serangkaian fitur canggih serta kecepatan. Aplikasi ini mencakup fitur seperti obrolan real-time, integrasi media sosial, server iklan, fitur bursa saham, dan lainnya.
<li> Deploying GraphQL in Node.Js Apps </li>
- GraphQL adalah bahasa kueri yang memungkinkan akses mudah ke berbagai database melalui satu endpoint, menyederhanakan komunikasi dibanding metode tradisional. Dikembangkan oleh Facebook pada 2012 dan dirilis ke publik pada 2015, GraphQL sangat berguna dalam mengelola data besar dari berbagai sumber secara bersamaan.
<li> Integrating Artificial Intelligence and Machine Learning (ML) </li>
- Node.js mendukung teknologi AI dan ML dengan baik berkat arsitektur non-blocking, kemampuan real-time, efisiensi dalam streaming data, dan kompatibilitas dengan arsitektur mikroservices.
<li>Serverless Architecture</li>
- Node.js dikenal dengan arsitektur serverless, yang memungkinkan pengembangan aplikasi tanpa perlu mengelola server. Arsitektur ini mengurangi ketergantungan pada perangkat keras, menekan biaya pengembangan, serta meningkatkan kualitas kode dan fleksibilitas.
<li>Microservice Architecture</li>
- Dalam pendekatan arsitektur ini, aplikasi dibangun sebagai kumpulan layanan yang dapat diterapkan dan diskalakan secara independen, masing-masing menangani fungsi bisnis tertentu. Pendekatan ini selaras dengan pengembangan Node.js, memungkinkan bisnis berinovasi dan berkembang lebih efisien.
</ul>
<br><br>
<h1>Perusahaan yang menggunakan Node.js</h1>
<br>
<img src="Netflix-1.jpg" width="500px" height="300px">
<h2>Netflix</h2>
<p align="justify"> Netflix sendiri juga menggunakan Node.js sehingga saat streaming film smooth dan tidak ada buffer. Node.js digunakan untuk mengatur server mereka yang padat sehingga meskipun diakses banyak orang dengan bersamaan akan tetap berjalan. </p>
<br><br>
<img src="e1906d9b-540d-4ebd-b432-a8cf00472848-cover.png" width="500px" height="300px">
<h2>Figma</h2>
<p align="justify"> Mengapa di figma kita dapat berkolaborasi secara real time dengan lancar? itu karena adanya pemakaian Node.js sehingga dapat memastikan setiap perubahan desain bisa ditampilkan di device yang lain. </p>
<br><br>
<img src="logo-linkedin-icon-1536.png" width="300px" height="300px">
<h2>LinkedIn</h2>
<p align="justify"> Node.js juga dipakai dalam LinkedIn untuk membuat aplikasi mereka lebih cepat dan responsif sehingga membuat pengalaman browsing, kirim pesan atau mencari kerjaan lebih smooth. </p>
<br><br>
<p align="justify">
<h1>Resources:</h1>
<br>
Antaweb. 2024. Apa Itu Node JS? Kenali Kelebihan, Kelemahan dan Fungsinya. https://antaweb.co.id/apa-itu-node-js-kenali-kelebihan-kelemahan-dan-fungsinya/
<br>
Dewaweb Team. 2024. Apa itu Node.js? Cara Kerja, Fungsi, & Manfaatnya. https://www.dewaweb.com/blog/mengenal-node-js/
<br>
Oliver, A. 2024. Mengenal Node.js, Salah Satu Platform Application Developer Terbaik. https://glints.com/id/lowongan/node-js-adalah/
<br>
Putri, F. 2024. Apa Itu Node Js? Definisi, Fungsi, Proses Kerja, & Contoh. https://dibimbing.id/blog/detail/apa-itu-node-js-definisi-fungsi-proses-kerja-contoh
</p>
</html>

