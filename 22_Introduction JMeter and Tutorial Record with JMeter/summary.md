## Resume
Apache JMeter adalah perangkat lunak sumber terbuka, terbuat dari aplikasi java yang dirangcang untuk memuat uji perilaku fungsional dan mengukur kinerja situs web. Awalnya dirancang untuk aplikasi web pengujian beban sekarang sudah berkembang untuk fungsi-fungsi pengembang yang lainnya.

Keuntungan menggunakan Apache JMeter:
- Open Source: Dapat melihat kode dari aplikasi JMeter, jika ada masalah maka dapat melihat sendiri permasalahan tersebut terjadi dibagian mana. JMeter dibuat dengan user interface yang akan kita dapatkan adalah aplikasi pada umumnya dan tanpa user interface
- Easy to use GUI/Non GUI: Jika menggunakan fitur Non GUI dari maka dapat menggunakan pada sistem berbasis CLI atau command line interface

Komponen2 di JMeter:
- Test Plan: Rencana besar test yang akan dilakukan
- Thread Groups: Kumpulan thread yang menjalankan skenario yang sama
- Samplers: Sebutan untuk request yang akan dikirim ke server
- Config Elements: Elemen yang digunakan untuk konfigurasi atau modifikasi sampler request yang dikirim ke server
- Listener: Merekam apapun yang terjadi yang dihasilkan oleh test
- Timers: Fitur ini akan jalan duluan sebelum semua fitur yang lain berjalan
- Assertions: Seperti assert pada API/Web/Testing merupakan kriteria tambahan apakah pass/tidak
- Pre-post Processors: Fitur yang memproses response data sebelum/sesudah test
