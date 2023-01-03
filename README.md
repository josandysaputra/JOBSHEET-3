# JOBSHEET-3

TOPOLOGI JARINGAN LOKAL DAN WIFI
TUJUAN

1) Mahasiswa dapat memahami cara kerja protokol topologi jaringan lokal yang memanfaatkan Wi-Fi untuk berkomunikasi.
2) Mahasiswa dapat merancang topologi jaringan yang memanfaatkan Wi-Fi untuk penerapan Wireless Sensor Network (WSN) dan Internet of Things (IoT).
3) Mahasiswa dapat memilih dan menggunakan topologi jaringan yang tepat sesuai dengan kondisi lapangan untuk penerapan WSN dan IoT.

ALAT DAN BAHAN

1) ESP32
2) Breadboard
3) Servo
4) Kabel jumper
5) Sensor DHT 11, RFID
6) LED (5) dan Push Button (3)
7) Resistor 330,1K, 10K Ohm (3)

TEORI SINGKAT

Wireless Fidelity atau yang lebih awam kita sebut wifi adalah suatu teknologi yang menggunakan gelombang radio dalam rentang 2,4GHz sampai dengan 5GHz untuk menghubungkan perangkat seperti PC/laptop, smartphone, dan perangkat microcontroller seperti ESP32 dan ESP8266 ke jaringan lokal wireless untuk bisa mengakses internet. Untuk dapat melakukan akses internet tersebut,maka perangkat elektronik diatas perlu berada dalam satu titik akses atau hotspot jaringan nirkabel sehingga terhubung dengan wifi. Pada umumnya jaringan wifi dapat menjangkau hingga 20 meter didalam ruangan dan lebih dari 20 meter untuk di luar ruangan. Pada awal kemunculannya, wifi hanya digunakan sebagai perangkat nirkabel pada jaringan LAN (Local Area Network) akan tetapi karena pesatnya teknologi di zaman sekarang wifi menjadi kebutuhan sehari-hari untuk akses jaringan internet dan IoT.Berbagai data yang kita minta atau kirimkan melalui wifi didistribusikan melalui gelombang radio di udara. Supaya data tersebut bisa terbaca maka harus ada yang namanya wireless adaptor yang menghubungkan ke wifi. Gelombang radio yang berwujud sinyal ini lalu dikirim menuju router yang fungsinya untuk memecahkan kode. Setelah terbaca maka data dikirim ke jaringan internet yang memanfaatkan koneksi ethernet. Karena jaringan wifi ini bekerja dua arah maka tiap data yang diterima dalam waktu yang sama menjadi kode pada tiap paket data lalu dikirim kembali dalam bentuk sinyal radio yang diterima adaptor komputer nirkabel.

A. ESP32 Wi-Fi Modes dan Wifi-Scan
1. Buka Arduino IDE dan upload script program berikut ke ESP32 untuk melakukan scan jaringan Wi-Fi buka serial monitor dan dokumentasikan outputnya.
![job3a2](https://user-images.githubusercontent.com/121847212/210314137-91f2d065-b15e-4def-923c-67cd85bbff04.png)

B. Menghubungkan ESP32 dengan Jaringan Wi-Fi
1.Buatlah program seperti script dibawah ini, kemudian upload program tersebut ke ESP32 buka serial monitor, kemudian dokumentasikan outputnya.
![Screenshot (49)](https://user-images.githubusercontent.com/121847212/210315217-0f980165-35cf-4e46-987b-aa5f4d14bd28.png)

C. Menghubungkan Kembali (Re-connect) ESP32 dengan Jaringan Wi-Fi
1.Buatlah program seperti script dibawah ini, kemudian upload program tersebut ke ESP32 Buka serial monitor, kemudian matikan paket data sebentar hingga koneksi 
ESP32 dengan jaringna Wi-Fi terputus. Setelah itu, nyalakan lagi paket data Dokumentasikan proses yang terjadi.
![Screenshot (50)](https://user-images.githubusercontent.com/121847212/210315274-83c9ea6c-a005-4c4c-bf91-6628e08c2b03.png)

D. Mengganti Hostname ESP32
1. Buatlah program seperti script dibawah ini, kemudian upload program tersebut ke ESP32 uka serial monitor, kemudian aktifkan mode koneksi Wi-Fi pada SmartPhone atau Laptop. Lakukan scan dan lihat daftar jaringan Wi-Fi yang tersedia Dokumentasikan hasil keluarannya.
![Screenshot (60)](https://user-images.githubusercontent.com/121847212/210315518-af433d5d-eae5-437d-9d0b-02a18fb68f17.png)

E. Mengirim Data Sensor ke Database
1.Buatlah script program seperti berikut ini Upload program di atas. Kemudian buka serial monitor untuk mengetahui IP 
Address ESP32. Akses IP Address ESP32 pada browser laptop.
![job3e](https://user-images.githubusercontent.com/121847212/210321283-abc4b58f-6923-41a1-9a2f-59f73f7fb01f.jpeg)
