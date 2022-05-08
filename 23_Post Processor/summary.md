## Resume
Post processors adalah bagian dari test plan yang merupakan sebuah aksi yang berjalan saat proses setelah dilakukan, yang artinya request ke sebuah alamat web. Proses yang dilakukan ini pada umumnya untuk mengekstrak value yang didapatkan dari hasil mengakses dari sebuah alamat web, seperti data-data pada JSON, session atau pada bagian response yang lainnya.

Berapa aturan yang dapat digunakan untuk mengekstrasi JSON rensponse:
- $ : root element (seluruh data json yang didapatkan adalah dolar)
- . : child operator (object) saat ingin mengakses chil dari sebuah object
- [] : child operator (array) untuk mengakses elemen array dari indeksnya
- .. : recursive descent (langsung ke objek) untuk operasi recursive 
- * : wildcard (all things)
- [started:end] : array slice operator borrowed
