# OWASP-JUICE-SHOP
INJECTION 

SQL Injection (SQLi) merupakan jenis serangan injeksi yang memungkinkan untuk mengeksekusi statement SQL yang berbahaya. Statement yang digunakan ini dapat mengontrol server database di belakang aplikasi web.

Hacker dapat melakukan otentikasi dan otorisasi halaman web atau aplikasi web dan mengambil konten dari seluruh database SQL. Mereka juga dapat menggunakan SQL Injection untuk menambah, mengubah, dan menghapus catatan dalam database.

Serangan SQL Injection ini dapat menarget semua website yang memanfaatkan SQL database, seperti MySQL, PostgreSQL, SQL Server, dan lainnya

A.	Download OWASP
Mengunduh rilis terbaru OWASP Juice Shop dari halaman resmi Github.
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/99ac8a9f-4b3b-4653-be74-e3b6e4428d71)

Kita perlu mengekstrak isinya karena kita mengunduh file dalam format zip.
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/e1dbdf7d-408c-4fd2-8e51-fe973bb01ea6)


B.	Install NodeJS Dan NPM
Menyalin Alamat tautan untuk “NodeJS untuk sistem Linux x64” dan menggunakan syntax dibawah ini untuk mengunduh film disistem.
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/98ad4172-b2b7-4094-bc52-287f6ffde2ee)

Ekstrak file yang kita download menggunakan perintah tar.
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/17e994ff-1e64-4867-b71e-6b87a0b1f131)

Menyalin file dari folder yang baru diekstrak ke directori /usr untuk menginstal nodeJS dan NPM disistem kita.
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/d9665e7d-dbb3-41d8-91c0-27896ce8eef5)

NodeJS dan NPM sudah diinstal kemudian untuk melihat versi dengan perintah sbb:
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/475c9a2d-4433-4bee-9ff4-015feebb8aaa)

C.	Install Ketergantungan Node
Kembali ke OWASP Juice Shope yang di ekstrak. Gunaka cd perintah untuk  mengubah directori ke folder tersebut dan jalankan perintah untuk menginstal paketNode yang diperlukan untuk menjalankan OWASP Juice Shop.
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/b121593f-653b-45a4-9371-5739b6ac91a7)

Jalankan perintah dibawah ini untuk menjalankan OWASP Juice Shop
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/616bd207-baaa-4675-8dc1-1362278e77d8)
Perintah ini akan memulai aplikasi web pada port 3000. Namun jika ada aplikasi lain yang berjalan pada port tersebut, anda akan melihat opsi untuk menggunakan port lain seperti 3001. Lucurkan brouser dengan URL http://localhost:3000/ untuk mengakses aplikasi web.

D.	Bender Login
Bender login adalah login menggunakan akun email alyufa@juice-sh.op menggunakan injection.
1.	Masuk kehalaman login dengan melakukan klik account pada bagian navbar lalu klik login
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/45ef278f-89d4-4df2-af8a-fe4b0824d94b)

2.	Selanjutnya pada halaman login ini masukkan email alyufa@juice-sh.op dan dengan password diisi dengan inputan acak. Untuk melakukan injection tambahkan ' -- yang dimana maksud dari inputan tersebut adalah digunakan untuk menonaktifkan argumen query sql setelahnya atau melakukan comment jadi kita dapat menonaktifkan kondisi pengecekan passwordnya
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/1ba7f354-9d31-4ac0-8e9e-4cc1d0d33644)

3.	Submit login form, maka kita akan berhasil masuk sebagai user bender 
![image](https://github.com/vyann/OWASP-JUICE-SHOP/assets/150219466/97c9f442-c17b-4e57-8b07-c13ddc71e1f6)

