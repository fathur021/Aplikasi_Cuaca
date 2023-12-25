# Aplikasi Ruang Obrol
#Deskripsi 

Aplikasi Prediksi Cuaca
Aplikasi Prediksi Cuaca adalah program sederhana yang memberikan informasi prediksi cuaca berdasarkan lokasi 
yang dimasukkan. Dibangun menggunakan Node.js dan Express untuk sisi server, serta HTML, CSS, dan JavaScript (Fetch API) untuk sisi klien.

## Langkah Awal

### Persyaratan

1. install node.js

### Instalasi

1. Klon repositori:

    ```bash
    git clone https://github.com/fathur021/Aplikasi_Cuaca.git
    ```

2. Masuk ke direktori proyek:

    ```bash
    cd aplikasiCuaca
    ```

3. Install dependensi:

    ```bash
    npm install express
    npm install hbs
    npm install path
    npm install postman-request
    npm install nodemon

    ```

### Fitur Utama
Prediksi Cuaca: Dapatkan informasi terkini tentang cuaca, termasuk deskripsi cuaca, suhu saat ini, index UV, dan visibilitas berdasarkan lokasi yang Anda masukkan.

## Penggunaan Nodemailer

## Konfigurasi:
1. Dapatkan kunci API dari Mapbox untuk layanan geocoding. Update file utils/geocode.js dengan kunci API tersebut.
2. Dapatkan kunci API dari Weatherstack untuk layanan prediksi cuaca. Update file utils/prediksiCuaca.js dengan kunci API tersebut.

## Endpoint API
1. Endpoint: GET /infocuaca
2. Deskripsi: Memberikan prediksi cuaca berdasarkan lokasi yang diberikan.
3. Permintaan Query:
   address: Lokasi yang ingin dicari prediksi cuacanya.
4. Respon:
   sukses:
    ```bash
    {
    "prediksiCuaca": "Info Cuaca: [Deskripsi Cuaca]. Suhu saat ini adalah [Suhu] derajat. Index UV adalah [Index UV] nm. Visibilitas [Visibilitas] kilometer",
    "lokasi": "Nama Lokasi",
    "address": "Alamat Lokasi"
    }

    ```
    gagal:
    ```bash
    {
    "error": "Pesan Kesalahan"
    }

    ```
   
    
## Kontak

Jika Anda memiliki pertanyaan atau umpan balik, jangan ragu untuk menghubungi:

- Email: fathur00013@gmail.com


---

 




