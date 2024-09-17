# Basic Data Encrypting dan Decrypting menggunakan BCTextEncoder

**BCTextEncoder** adalah library yang digunakan untuk melakukan enkripsi dan dekripsi data berbasis teks menggunakan teknik symmetric encryption (enkripsi simetris). Dengan symmetric encryption, kunci yang digunakan untuk mengenkripsi data juga digunakan untuk mendekripsi data, sehingga kunci ini harus dijaga dengan baik untuk mencegah akses yang tidak sah.

Berikut adalah konsep dasar enkripsi dan dekripsi menggunakan BCTextEncoder:

## 1. Enkripsi (Encrypting Data)
Enkripsi adalah proses mengubah data asli (plaintext) menjadi bentuk tidak terbaca (ciphertext) agar informasi tersebut terlindungi. BCTextEncoder menggunakan algoritma enkripsi untuk mengubah teks menjadi bentuk terenkripsi dengan menggunakan kunci tertentu.
Langkah pertama untuk melakukan Encrypting text adalah dengan memasukkan plaintetx kedalam text box lalu klik `Encode`
![11](https://github.com/user-attachments/assets/d2e41a81-030b-4125-b0c7-19d83d17b584)
Lalu kita diminta untuk membuat password untuk encrypt dan decrypt nanti
![12](https://github.com/user-attachments/assets/a8df4dd2-3d2f-4896-af72-928a9407316f)

Jika berhasil maka output atau hasil encrypt text kita akan muncul di kolom bawah seperti di gambar.
![15](https://github.com/user-attachments/assets/b44bce15-6935-4301-816a-ebacb35ae404)

## 2. Dekripsi (Decrypting Data)
Dekripsi adalah kebalikan dari enkripsi. Dengan dekripsi, ciphertext diubah kembali menjadi bentuk asli (plaintext) menggunakan kunci yang sama yang digunakan untuk enkripsi. Tanpa kunci yang benar, ciphertext tidak bisa dikembalikan ke plaintext.
Untuk melakukan Decrypting text kita perlu menghapus plain text yang ada di text box, jika sudah kita klik tombol `Decode`
![13](https://github.com/user-attachments/assets/90953f62-d3a8-41d7-8d9a-64070ff2c611)
masukkan password yang telah kita buat ketika melakukan encrypting text sebelumnya 
![14](https://github.com/user-attachments/assets/04fd20ce-ae5b-4ea8-b13f-eb2648bb7c56)

Jika sudah maka encrypt data akan diubah menjadi plaintext kembali
![15](https://github.com/user-attachments/assets/202b8062-b1db-4b46-b75c-4e6fae50b002)
