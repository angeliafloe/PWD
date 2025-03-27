# Mindmap Tech Stack Backend: Node.Js

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

### Kekurangan dan Kelebihan
  - Kelebihan
    - Scalability: Backend memungkinkan pengembang untuk mengelola data dan operasi yang kompleks. Ini memungkinkan situs web untuk ditingkatkan dan disesuaikan sesuai dengan pertumbuhan dan kebutuhan bisnis.
    - Keamanan: Backend bertanggung jawab untuk mengelola dan melindungi data sensitif dari serangan. Dengan menggunakan protokol keamanan seperti enkripsi dan otentikasi, backend memastikan bahwa informasi pribadi pengguna aman dan terlindungi.
    - Kecepatan: Backend memiliki peran penting dalam memproses permintaan dari pengguna dan memberikan hasil dengan cepat. Dengan mengoptimalkan kode dan server, pengembang backend dapat memastikan kecepatan dan kinerja yang baik.
  - Kekurangan
    - Kompleksitas: Pemrograman yang kompleks dan membutuhkan pemahaman yang mendalam tentang teknologi dan bahasa pemrograman sehingga menjadi tantangan bagi pengembang yang baru mengenal bidang ini.
    - Keterbatasan Visual: Backend terkait dengan logika dan pemrosesan data di belakang layar, sehingga tidak terlibat dalam aspek visual dan tata letak situs web. Ini bisa menjadi kekurangan bagi mereka yang ingin berkreasi dengan desain dan estetika.
    - Biaya Pengembangan: Backend yang handal dan efisien membutuhkan waktu dan upaya dalam pengembangan, meningkatkan biaya pengembangan situs web, terutama untuk proyek yang kompleks dan membutuhkan fitur yang tinggi.

### Tren Backend di 2025
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
Dewaweb Team. 2024. Apa itu Node.js? Cara Kerja, Fungsi, & Manfaatnya. https://www.dewaweb.com/blog/mengenal-node-js/
Oliver, A. 2024. Mengenal Node.js, Salah Satu Platform Application Developer Terbaik. https://glints.com/id/lowongan/node-js-adalah/
