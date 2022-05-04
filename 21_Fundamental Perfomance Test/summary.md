## Resume
Perfomance Test merupakan teknik non functional testing untuk menentukan parameter sistem dalam hal responsif dan stabilitas dibawah berbagai beban atau (beban) load kerja. Performance testing mengukur kualitas atribut dari sistem stabilitas ketahanan dan penggunaan resource. Yang diukur dari perfomance test adalah:
- performa suatu aplikasi sampai suatu batas tertentu
- bukan merupakan funtional test
- bisa berbagai macam bentuk untuk memahami reliability, stability dan availability pada enviromentnya

Type Performance Test:
1. Load Testing adalah pengujian paling sederhana yang dilakukan untuk memahami perilaku sistem dalam keadaan beban tertentu. Hasilnya digunakan untuk mengukur kepentingan bisnis saat transaksi yang kritis dengan memonitor dampak terhadap database, application server, dll.
2. Stres Testing adalah dilakukan untuk mengamati kemampuan dan kestabilan sistem pada saat kondisi ekstrem. Dilakukan bertahap menuju load normal, puncak dan melebihinya, lalu turun untuk melihat proces recovery.
3. Spike Testing, sepertu stress test, namun kenaikan langsung menuju melebihi puncak dilakukan dalam waktu singkat. Jika stress test memberikan waktu untuk scale-out, spike testing tidak.
4. Soak Testing adalah untuk mengetahui realiability ketika tekanan dibawah puncak dalam jangka panjang
5. Smoke Testing adalah dilakukan untuk verify script yang sudah dibuat, apakah sistem dapat menghandle minimal load, tanpa masalah sama sekali. Biasanya hanya 1-2VUs
