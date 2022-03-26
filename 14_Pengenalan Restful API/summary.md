## Resume
API adalah memungkinkan komunikasi dan pertukaran data antara 2 atau lebih software atau sistem yang terpisah. Tujuannya yaitu untuk mempercepat proses development dengan menyediakan function secara terpisah sehingga developer tidak membuat fitur yang serupa. API membawa sebagai sebuah pesan permintaan kepada pengguna dan memberi tau sistem apa yang harus dilakukan kemudian memberi respon atas permintaan tersebut.
Rest API (Representational State Transfer) yaitu standar arstektur berbasis web sering diterapkan dalam layanan berbasis web yang umumnya menggunakan HTTP sebagai protokol untuk komunikasi data. Rest API berisi aturan atau batasan yang membatasi progammer atau mengakses atau melakukan tindakan2 tertentu pada sebuah database. Jika API adalah penghubung maka REST adalah yang membuat aturan sesuai keinginan progammer dalam merancang web service, simpelnya terdapat request dan respon pada data yang dikirimkan ataupun yang diterima. Data yang digunakan untuk Rest API umumnya berupa JSon. 
HTTP Method berfungsi sebagai protokol respon dari permintaan client dan server. HTTP Method yang sering dipake yaitu:
- Get: Untuk mengambil informasi tentang resource yang telah ditentukan oleh URL secara singkat Get digunakan untuk membaca data
- Put: Untuk mengirim fungsi atau data ke server untuk membuat maupun memperbarui resource. Perbedaan antara 
- Post: Untuk mengirimkan data baru ke server simpelnya yaitu membuat data baru
- Delete: Untuk menghapus data yang ada
Rest API component:
- Method
- URL (Base URL + Path) untuk melakukan request
- Header 
- Body
JSON (Java Script Object Notation) adalah adalah sebuah format data yang digunakan untuk pertukaran dan penyimpanan data
HTTP Response Code:
- 200 (OK) artinya Succes
- 201 (Created) artinya Succes dan resourcenya berhasil dibuat
- 400 (Bad Request) artinya ketika melakukan request Post atau Put yang artinya datanya tidak sesuai atau salah dari formatnya
- 404 (Not Found)
- 401 (Unauthorized)
- 405 (Method Not Allowed)
- 500 (Internal) ada kesalahan di server
