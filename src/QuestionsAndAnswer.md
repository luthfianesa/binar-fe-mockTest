**Questions**

1. Apa kegunaan JSON pada REST API ?
2. Jelaskan bagaimana REST API Bekerja ?
3. Buat website dengan fungsi :
   A. Login Page
   User bisa melakukan login dengan menggunakan 4 angka, tidak perlu menggunakan username, email, dll
   B. Buat fitur to do list sederhana di homepage
   Harus menggunakan React Redux dan data terkoneksi menggunakan API
   C. Front-End Engineer wajib membuat website menggunakan
   https://jsonplaceholder.typicode.com/ API

**Answers**

1. JSON (Javascript Object Notation) adalah format file berbasis teks terdiri dari pasangan key-value
   yang digunakan pada REST API sebagai format standar untuk pertukaran file antara client (request) dan server (response).
   JSON dapat dipahami oleh manusia dan komputer. Format file berupa .json

Source : - https://www.hostinger.co.id/tutorial/apa-itu-json - https://www.dicoding.com/blog/apa-itu-rest-web-service/

2. Cara REST API bekerja
   Dalam RESTful API terdapat 2 sisi yaitu :
1. REST Client
   Melakukan request data ke REST Server
1. REST Server
   Merespon permintaan dengan menyediakan data ke REST Client

Cara kerjanya :

- Pertama, harus ada REST server yang menyediakan resource / data
- REST client akan membuat HTTP request untuk mengakses data / resource ke REST server dengan format JSON agar dikenali oleh REST server
- Masing - masing data dibedakan oleh global ID atau URIs (Universal Resource Identifiers)
- Jika berhasil, REST server mengembalikan data berupa JSON dan mengubah response menjadi HTML karena manusia yang akan melihat

Kode Status :

1. Kode 200: Success
2. Kode 404: Not Found
3. Kode 500: Server Error

- Kenapa butuh kode status ?
- Karena yang berinteraksi dalam API adalah mesin dengan mesin,
- Server hanya bisa membaca status dari sebuah request apakah sukses atau tidak dari kode status tersebut
- Berbeda dengan manusia yang butuh HTML (Text, Gambar, Warna dll) untuk melihat tampilan response dari server

Source : - https://ngide.net/apa-itu-rest-api - https://www.ayongoding.com/rest-dan-http/
