a. What is amqp?
- AMQP (Advanded Message Queuing Protocol) adalah protokol perangkat lunak yang dirancang untuk mendukung komunikasi yang efisien, handal, dan aman antara berbagai aplikasi atau sistem yang terhubung dalam arsitektur berbasis message queuing.

b. What it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for? 
String guest:guest@localhost:5672 adalah string untuk koneksi pada AMQP server. guest:guest menandakan username dan juga password untuk servernya. localhost merupakan hostname dari servernya dan 5672 merupakan port number yang digunakan ketika server dijalankan (port number default AMQP)

![alt text](image.png)
Screen capture ketika mensimulasikan subscriber yang lambat