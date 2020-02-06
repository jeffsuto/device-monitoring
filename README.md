<a name="dinamiot"/>
# Dinamiot
Dinamiot merupakan web dashboard dan web server untuk monitoring perangkat IoT. Dengan menambahkan perangkat baru di website, pengguna akan mendapatkan endpoint API untuk digunakan sebagai akses perangkat IoT ke web server. Pada web ini, setiap perangkat memilki dashboardnya sendiri. Terdapat dua kategori untuk komponen perangkat, yaitu komponen dengan jenis analog dan digital, contohnya: Generator memiliki 3 komponen yang akan dimonitoring, yaitu: Suhu (analog), Bahan Bakar (analog), Kipas pendingin (digital). Pada dashboard Generator, komponen suhu dan bahan bakar akan ditampilkan dalam bentu Chart Line dan Gauge Chart, sedangkan komponen kipas pendingin akan ditampilkan dalam bentuk panel yang menunjukan status ON atau OFF.

    - [Dinamiot](#dinamiot)
        - [Installation](#installation)
        
## Installation
Pastikan anda sudah memiliki MongoDB PHP Driver. Anda bisa melihat petunjuk instalasi di http://php.net/manual/en/mongodb.installation.php

### Clone Project
```$ https://github.com/jeffsuto/dinamiot.git```
