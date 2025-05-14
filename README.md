a. What is amqp?

> AAMQP (Advanced Message Queuing Protocol) adalah sebuah protokol open-standard yang dirancang untuk memungkinkan sistem perangkat lunak berkomunikasi satu sama lain melalui pesan, terlepas dari bahasa pemrograman atau platform yang digunakan. AMQP biasa digunakan dalam sistem antrian pesan (message queue) seperti RabbitMQ, yang mendukung komunikasi asynchronous antar layanan dalam arsitektur microservices atau event-driven. AMQP menjamin pengiriman pesan yang andal dengan fitur seperti queue, routing, publish/subscribe, dan transaksi.

b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what
is the second guest, and what is localhost:5672 is for?

Pada string koneksi guest:guest@localhost:5672, bagian pertama "guest:guest" menunjukkan username dan password yang digunakan untuk mengautentikasi ke broker AMQP (misalnya RabbitMQ), dalam hal ini username-nya adalah "guest" dan password-nya juga "guest". Bagian "localhost:5672" menunjukkan bahwa koneksi dilakukan ke server RabbitMQ yang berjalan di komputer lokal (localhost) pada port 5672, yang merupakan port default untuk protokol AMQP. Kombinasi ini memungkinkan aplikasi terhubung ke message broker lokal menggunakan kredensial default.