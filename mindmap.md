<!DOCTYPE HTML>
<html>
# Mindmap Tech Stack Backend: Node.Js (Angel V, Angelia F. P., Nabil)

### Apa Itu Node.js?
Node.js adalah sebuah platform dengan basis JavaScript, di mana adalah lingkungan runtime yang memungkinkan eksekusi kode JavaScriptdi luar browser. Node.js digunakan dalam mengembangkan aplikasi web dengan skala besar dan cepat, ini karena berbasis arsitektur event-driven dan non-blocking I/O. Efisiensi menjadikan Node.js terkenal sebab memungkinkan pengembang memanfaatkan JavaScript untuk mengeksekusi kode di server. Node. js turut banyak digunakan dalam menyokong aplikasi dengan penanganan data real-time, memungkinkan juga dalam pembuatan aplikasi yang skalabel dan berperforma tinggi.

Meski Node.js adalah platform basis JavaScript, keduanya memiliki perbedaan pada penggunaannya, yakni:
JavaScript: untuk mengembangkan sisi klien dari aplikasi web
Node.js: untuk menjalankan JavaScript di sisi server

Node.js tepat digunakan pada saat:

1. Melakukan pengembangan aplikasi real-time, seperti aplikasi chatting
2. Pembangunan API untuk sistem yang besar
3. Saat memerlukan pengolahan data seketika dan sinkronisasi cepat

Fungsi Node.js:
1. Pengembangan server-side
2. Real-time application
3. Sebagai API
4. Pengembangan aplikasi sisi klien dan server dengan JavaScript
   
### Komponen Node.js
1. Javascript V8: sebuah kompiler yang dibentuk menggunakan bahasa C++, dengan komponen ini input berupa kode JavaScript dapat di compile menjadi kumpulan kode dalam tingkat assembly. Ada 3 komponen pada JavaScript: compiler (mengubah JavaScript menjadi bahasa pemrograman lain sesuai kebutuhan developer), optimizer (tool untuk mengoptimalkan aplikasi baru), dan garbage collector (memudahkan aplikasi lama ke penyimampanan agar kinerja Node.js tetap ringan).
2. Libuv Library: berfungsi mengoperasikan asynchronous I/O input maupun output dan main event loop dalam Node.js.
3. Design Pattern: tool untuk menyusun kode dengan cara memungkinkan developer mendapatkan beberapa kelebihan (waktu pengembangan lebih cepat, kode yang dapat digunakan kembali, dst). Dalam Node.js terdapat dua jenis, object pool (kumpulan objek yang dapat digunakan untuk task tertentu) dan facade (tools memberi tampilan antarmuka untuk body kode, sehingga meringankan beban developer).

### Kekurangan dan Kelebihan Node.js

- Kelebihan Node.js
  
1. Performa Tinggi
-> Kinerja tinggi dan kemampuan menangani banyak koneksi dengan bersamaan, berkat penggunaan mesin JavaScript V8 Chrome yang efisien
   
2. Pengembangan Cepat
-> Memungkinkan JavaScript di seluruh stack yang dapat mempercepat pengembangan aplikasi.
   
3. Skalabilitas
-> Scalable dan dapat dengan mudah dikonfigurasi untuk menangani peningkatan traffic. Microservices dan model event-driven Node.js membuatnya mudah untuk menskalakan aplikasi secara horizontal dengan menambahkan lebih banyak server.
   
4. Efisiensi Sumber Daya
-> Dikarenakan menggunakan sumber daya CPU dn memori secar efisien sehingga tepat untuk aplikasi yang perlu berjalan di server dengan sumber daya terbatas.
   
5. Banyak Pilihan Framework & Library
-> Menjadikan dapat menemukan framework dan library untuk berbagai keperluan, seperti pengembangan web, API, microservices, dan real-time applications.
   
6. Open Source
-> Platform gratis untuk digunakan dan dimodifikasi, ini juga berarti bahwa ada banyak komunitas pengembang yang berkontribusi pada pengembangan platform, sehingga dapat membantu meningkatkan kualitas dan kecepatan pengembangan.
      
- Kekurangan Node.js
  
1. Kurang Matang
-> Ini karena platform ini relatif baru dibandingkan dengan platform back-end lain. Platform masih berada pada tahap pengembangan (tidak semua fitur yang dibutuhkan ada untuk membangun aplikasi kompleks)
   
2. Kurang Dukungan untuk Beberapa Bahasa Pemrograman
-> Node.js hanya mendukung JavaScript

3. Keamanan
-> Node.js adalah platform yang berjalan pada JavaScript, di mana memiliki beberapa kerentanan keamanan. Perlu berhati-hati saat digunakan karena secara keamanan masih rentan.
   
4. Kurangnya Dukungan dari Perusahaan Besar
-> Node.js belum banyak diadopsi perusahaan besar dibandingkan platform back-end lainnya, ini berarti akan lebih sulit untuk menemukan pengembang Node.js yang berpengalaman dan mendapatkan dukungan perusahaan besar.

### Tren Node.js di 2025
  - Muncul arsitektur tanpa server
    - Provider seperti AWS Lambda, Azure Functions, dan Google Cloud Functions memudahkan daari sebelumnya, di mana menerapkan aplikasi tanpa perlu khawatir infrastruktur yang mendasarinya. Dengan serverless dapat menimalisir biaya secara signifikaan dan menyesuaikan diri otomatis dengan permintaan aplikasi.
  - Microservices
    - Pemecahan aplikasi monolitik menjadi layanan lebih kecil dan independent yang dapat dikembangkan, digunakan, dan diskalakan secara mandiri. Pendekatan ini menawarkan kelincahan dan skalabilitas yang lebih besar, sehingga menjadi favorit di kalangan pengembang.
  - AI dan Machine Learning
    - Aplikasi yang memanfaatkan AI untuk memberi pengalaman yang lebih canggih dan personal, termasuk mesin rekomendasi, deteksi penipuan, atau analisis prediksi.
      
### Perusahaan yang menggunakan stack BackEnd
  - LinkedIn
    - Social network terbesar untuk para professional ini memanfaatkan Node Js sebagai backend API untuk aplikasi mobile mereka. Node JS menjadi end point data untuk aplikasi Android dan IOS.
  - Netflix
    -  Situs untuk menonton dengan 33 juta member ini menggunakan Node JS sebagai backend. Selain Node JS, Netflix juga menggunakan Java, Python, dan Cssaandra dalam stacknya.
  -  Spotify
    - Platform tempat mendengarkan, berbagi dan membeli musik yang cukup populer di kalangan masyarakat. Dengan spotify dapat mengakses library musik di mana saja dan perangkat manapun. Spotify menggunakan Django karena backend cepat dan ada dukungan machine learning.

Resources: 
<br>
Antaweb. 2024. Apa Itu Node JS? Kenali Kelebihan, Kelemahan dan Fungsinya. https://antaweb.co.id/apa-itu-node-js-kenali-kelebihan-kelemahan-dan-fungsinya/
<br>
Dewaweb Team. 2024. Apa itu Node.js? Cara Kerja, Fungsi, & Manfaatnya. https://www.dewaweb.com/blog/mengenal-node-js/
<br>
Oliver, A. 2024. Mengenal Node.js, Salah Satu Platform Application Developer Terbaik. https://glints.com/id/lowongan/node-js-adalah/
</html>

