# mynotes

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/e_s827HM)
| Name           | NRP        | Kelas     |
|---|---|---|
| Farras Abdurrazaq Ar-Rasyid            | 5025241091        | A |



## Put your topology config image here!

<img width="1643" height="899" alt="gambar" src="https://github.com/user-attachments/assets/03920812-6ef4-4abf-8874-544cb9199d20" />


## Put your GNS3 Project file here!

[Link project](https://drive.google.com/file/d/1HKyi4gv9uPjhkxHyyDoy50ywSUJXiNFz/view?usp=sharing) 

<br>

## Soal 1

> Setup Topo

> _Document the results of the subnet grouping that has been created._

**Answer:**

- Screenshot

  Lune:
  
  <img width="525" height="215" alt="gambar" src="https://github.com/user-attachments/assets/5ccdca95-179b-40aa-bb27-a0262b46f4d4" />

  Sciel:
  
  <img width="567" height="302" alt="gambar" src="https://github.com/user-attachments/assets/3dc85013-02c1-4695-aa52-a7aa625e01f7" />
  
  Gustave:
  
  <img width="529" height="282" alt="gambar" src="https://github.com/user-attachments/assets/47d21226-7030-4862-b5fc-7c5529d3b3ab" />

  Renoir:
  
  <img width="532" height="287" alt="gambar" src="https://github.com/user-attachments/assets/f39e4f82-c548-41bd-ab19-9163ce2f6cab" />

  Verso:
  
  <img width="535" height="278" alt="gambar" src="https://github.com/user-attachments/assets/177eacb5-cdff-4497-9874-fb576a12c52f" />

  Alicia:
  
  <img width="530" height="277" alt="gambar" src="https://github.com/user-attachments/assets/85302049-99a9-47f1-91da-6a680b8abf79" />

  Esquie:
  
  <img width="523" height="280" alt="gambar" src="https://github.com/user-attachments/assets/8d082977-f48b-43f7-87ba-1e3cc8e9206f" />

  Monocco:
  
  <img width="557" height="273" alt="gambar" src="https://github.com/user-attachments/assets/2d0395e8-f428-408f-aac3-e3401e6d28a1" />

  Maelle:
  
  <img width="542" height="289" alt="gambar" src="https://github.com/user-attachments/assets/38cdb450-7746-4e1e-9d97-962a67101b96" />

- Explanation

  Subnet diatur sesuai gambar pada soal pertama dengan prefiks IP 10.25.x.x dengan Webserver pada subnet 10.25.2.x, DNS pada subnet 10.25.3.x, Proxy pada subnet 10.25.4.x, dan client pada 10.25.5.x

<br>

## Soal 2

> Buatlah konfigurasi untuk domain 
> **lune33.com** → ke IP node Lune , 
> **sciel33.com** → ke IP node Sciel ,
> **gustave33.com** → ke IP node Gustave 
> pada DNS Master Renoir. Kemudian konfigurasikan node Verso sebagai DNS Slave yang bekerja untuk DNS Master Renoir.

> _Dns Configuration , on  the DNS Master (Renoir)_
> _lune33.com → IP of node Lune ,_
> _sciel33.com → IP of node Sciel ,_
> _gustave33.com → IP of node Gustave_
> _Configure Verso as the DNS Slave that works with DNS Master Renoir._

**Answer:**

- Screenshot
  Konfigurasi domain:
  
  <img width="903" height="599" alt="gambar" src="https://github.com/user-attachments/assets/1ee607ff-54d2-4b0f-85f6-700468c982dc" />

  Isi IP masing masing file domain:
  
  <img width="902" height="330" alt="gambar" src="https://github.com/user-attachments/assets/6124770e-a8b6-4cff-b5d3-26e7a6bd321c" /> 
  <img width="903" height="326" alt="gambar" src="https://github.com/user-attachments/assets/ec6db5bc-3379-4410-a152-d1586f9e0ae7" />
  <img width="902" height="351" alt="gambar" src="https://github.com/user-attachments/assets/de7523fc-de39-4b9d-a511-8252d104a1c1" />


  Masukkan nameserver di setiap client:
  
  <img width="511" height="234" alt="gambar" src="https://github.com/user-attachments/assets/0082e8a0-65ca-4ae1-8e97-08a5fd9c4d4c" />
  <img width="507" height="218" alt="gambar" src="https://github.com/user-attachments/assets/9b79d5a5-9675-4c9f-bfd2-191a2ff268e9" />
  <img width="489" height="234" alt="gambar" src="https://github.com/user-attachments/assets/cc80f822-fd7c-470b-af46-50c140a6b793" />

  Tambah konfigurasi reverse DNS
  
  <img width="557" height="95" alt="gambar" src="https://github.com/user-attachments/assets/d272d5da-ea12-4624-bc91-d8d4045eb7f3" />
  <img width="898" height="603" alt="gambar" src="https://github.com/user-attachments/assets/8e206203-9c55-4b00-9de0-2f2eb2dd2e14" />

  Tambah CNAME

  <img width="895" height="349" alt="gambar" src="https://github.com/user-attachments/assets/a91fa725-c2b9-4525-b5e5-3924eb316e19" />
  <img width="901" height="348" alt="gambar" src="https://github.com/user-attachments/assets/22cd90e7-2000-4434-b554-49288ef6f2b8" />
  <img width="901" height="368" alt="gambar" src="https://github.com/user-attachments/assets/e07c0acd-9709-43c9-a491-3e2f4c2e355f" />

  Tambahkan DNS Slave
  
  <img width="900" height="640" alt="gambar" src="https://github.com/user-attachments/assets/d2ad56d7-0b17-4596-9469-57ed10328171" />

  Config pada DNS Slave
  
  <img width="892" height="644" alt="gambar" src="https://github.com/user-attachments/assets/dbf8147f-a099-4014-b6b5-dbcec41f0502" />

  Nameserver client

  <img width="558" height="275" alt="gambar" src="https://github.com/user-attachments/assets/14edbcf8-959b-4e84-8763-ccb290c333ba" />
  <img width="534" height="268" alt="gambar" src="https://github.com/user-attachments/assets/fcbe5012-ed1f-4dbf-91cf-c13586c9594d" />
  <img width="532" height="272" alt="gambar" src="https://github.com/user-attachments/assets/90b53185-a6b6-4419-b6c2-e54719b5d755" />

- Explanation

  Pada file /etc/bind/named.conf.local pada node Renoir yang akan menjadi DNS master ditambahkan domain yang akan dipakai, tipe, dan direktori file yang akan dgunakan.

  Pada masing-masing file domain diatur domain, serial, dan IP yang merujuk ke webserver masing-masing domain.

  Setiap client dikonfigurasi nameserver agar bisa berkomunikasi dengan DNS master (Renoir)

  Tambah zone yang berfungsi sebagai reverse DNS untuk memertakan IP menjadi domain sesuai indeks

  Semua webserver ditambah CNAME www. sebagai alias

  Semua zone pada named.conf.local diberi notify dan allow-transfer untuk tersambung dengan DNS Slave

  named.conf.local pada node Verso (DNS Slave) diisi dengan semua domain yang sama dengan type slave, dan masters yang merujuk kepada IP DNS Master

  Setiap client dikonfigurasi nameserver agar bisa berkomunikasi dengan DNS slave (Verso)
<br>

## Soal 3

> Tambahkan subdomain alias berupa exp.lune33.com yang mengarah ke alamat lune33.com dan exp.sciel33.com yang mengarah ke alamat sciel33.com (HINT: CNAME). Selain itu, tambahkan konfigurasi untuk melakukan reverse DNS lookup untuk domain gustave33.com

> _Subdomain Configuration,_ 
> _Add alias subdomains (HINT: CNAME)._
> _exp.lune33.com → alias to lune33.com_
> _exp.sciel33.com → alias to sciel33.com_
> _Also, configure reverse DNS lookup for the domain gustave33.com._

**Answer:**

- Screenshot

Menambahkan CNAME di lune33 dan sciel33

<img width="904" height="404" alt="gambar" src="https://github.com/user-attachments/assets/4b32f2b6-8b3e-4cb2-8746-4276e9ef4bf2" />
<img width="901" height="406" alt="gambar" src="https://github.com/user-attachments/assets/de518e4b-547b-4084-84db-ff4de8daf0e2" />


- Explanation

Menambahkan Subdomain 'exp.xxxxx.com' dengan CNAME di kedua file lune33.com dan sciel33.com 

<br>

## Soal 4

> Buatlah subdomain berupa expedition.gustave33.com dan delegasikan subdomain tersebut dari Renoir ke Verso dengan alamat IP tujuan adalah node Gustave. Kemudian, matikan Renoir dan coba lakukan ping ke semua domain dan subdomain yang telah dikonfigurasikan pada nomor 2, 3, dan 4.

> _Create a subdomain expedition.gustave33.com and delegate it from Renoir to Verso, with the target IP being node Gustave.Then, turn off Renoir and try pinging all domains and subdomains configured in tasks 2, 3, and 4 to verify delegation works correctly._

**Answer:**

- Screenshot

Record delegasi di DNS Master

<img width="901" height="600" alt="gambar" src="https://github.com/user-attachments/assets/678387c7-bb58-4203-bd2e-2d185ca98603" />

Setup named.conf.options di DNS Master dan DNS Slave

<img width="906" height="600" alt="gambar" src="https://github.com/user-attachments/assets/44465fb6-f3b2-4b33-819e-aa33c4099c40" />
<img width="901" height="601" alt="gambar" src="https://github.com/user-attachments/assets/ac476db3-ba60-4eae-ad11-841efb4653a9" />

Delegasi pada local di DNS Slave

<img width="908" height="604" alt="gambar" src="https://github.com/user-attachments/assets/c7de7b78-d930-4fb0-b2a0-89eb3e1357b8" />

File delegasi expedition.gustave33.com

<img width="899" height="605" alt="gambar" src="https://github.com/user-attachments/assets/b21fafa9-9cd8-4e7d-a8b1-8b563c76fe76" />

TESTING DOMAIN

www.lune33.com

<img width="902" height="227" alt="gambar" src="https://github.com/user-attachments/assets/e9670155-951a-42d3-a413-6e6c67d7becb" />

sciel33.com

<img width="898" height="184" alt="gambar" src="https://github.com/user-attachments/assets/de0e18fd-dd84-48ba-b683-15c45e4f666f" />

www.gustave33.com

<img width="897" height="208" alt="gambar" src="https://github.com/user-attachments/assets/9131907f-ec46-4b95-8d28-5316ae1ee35f" />

expedition.gustave33.com

<img width="890" height="233" alt="gambar" src="https://github.com/user-attachments/assets/ac0473af-cb09-4972-b2e6-3d9b2cfe5aa7" />

exp.lune33.com

<img width="894" height="186" alt="gambar" src="https://github.com/user-attachments/assets/dbb7a3da-e0bf-422e-bbfd-a817f62976e6" />

exp.sciel33.com

<img width="898" height="226" alt="gambar" src="https://github.com/user-attachments/assets/2bd37b56-d451-4f1a-8d5e-7be895a8f021" />

- Explanation

Menambahkan IP DNS Slave pada file gustave33.com untuk delegasi subdomain

Mengatur optiions pada kedua DNS server

Menambahkan zone subdomain 'expeditions.gustave33.com' dan diatur sebagai master pada node Verso

Mengatur file 'expeditions.gustave33.com' untuk menyimpan IP dari node gustave di node Verso

Lima screenshot sebagai bukti bahwa ping dapat tersambung ke IP yang sesuai dengan domain yang di ping setelah menghidupkan kedua DNS server lalu mematikan DNS Master

<br>

## Soal 5

> Konfigurasi node Lune, Sciel, dan Gustave agar berfungsi sebagai web server Nginx yang akan menyajikan halaman profil, dimana halaman profil akan berbeda untuk setiap node. Dari folder berikut, gunakan profile_lune.html untuk menyajikan halaman profil di node Lune, profile_sciel.html untuk menyajikan halaman profil di node Sciel, dan profile_gustave.html untuk menyajikan halaman profil di node Gustave. Konfigurasikan Nginx di setiap node untuk menyimpan custom access log ke file /tmp/access.log dan error log ke file /tmp/error.log. 

> _Configure Lune, Sciel, and Gustave as Nginx web servers serving profile pages, where each node has a unique profile page:_
> _- Use profile_lune.html for Lune_
> _- Use profile_sciel.html for Sciel_
> _- Use profile_gustave.html for Gustave_
> _In each web server, Configure Nginx to store custom logs:_
> _- Access log: /tmp/access.log_
> _- Error log: /tmp/error.log_

**Answer:**

- Screenshot

Memasukkan html ke server

<img width="897" height="600" alt="gambar" src="https://github.com/user-attachments/assets/6dd73382-4192-4ad1-95ae-f69b2c79e754" />
<img width="904" height="599" alt="gambar" src="https://github.com/user-attachments/assets/74b7cb43-91f1-45e0-adb7-0cbf59df07c1" />
<img width="905" height="607" alt="gambar" src="https://github.com/user-attachments/assets/bfb266ff-2609-4777-b4f9-cd287bcf7f53" />

Config Access log dan error log

<img width="903" height="598" alt="gambar" src="https://github.com/user-attachments/assets/765b17e0-a9df-4a40-b439-1863a140068d" />
<img width="911" height="607" alt="gambar" src="https://github.com/user-attachments/assets/afbed10c-e75a-461a-b3d3-0d7a2aa7da7e" />
<img width="902" height="603" alt="gambar" src="https://github.com/user-attachments/assets/a2d2a298-2c6b-4eab-a3d6-217237dd2687" />




- Explanation
Paste semua isi HTML dari yang sudah diberikan soal ke dalam '/var/www/html/html.index' masing masing webserver

Pada '/etc/nginx/sites-available/default' ditambahkan access_log dan error_log serta path dari kedua log tersebut

<br>

## Soal 6

> Setelah website berhasil dideploy pada masing-masing node web server dan halaman dapat menampilkan profil yang sesuai,  buatlah custom access log ke file /tmp/access.log di masing-masing node web server menggunakan format log tertentu seperti di bawah:
> - Tanggal dan waktu akses dalam format standar log.
> - Nama node yang sedang diakses.
> - Alamat IP klien yang mengakses website.
> - Metode HTTP dan URI yang diakses oleh klien.
> - Status respons HTTP yang diberikan oleh server.
> - Jumlah byte yang dikirimkan dalam respons.
> - Waktu yang dihabiskan oleh server untuk menangani permintaan.
> - Contoh format log yang sesuai:
>   [01/Oct/2024:11:30:45 +0000] Jarkom Node Lune Access from 192.168.1.15 using method "GET /resep/bayam HTTP/1.1" returned status 200 with 2567 bytes sent in 0.038 seconds

> _After successfully deploying each website and verifying the correct profile page is displayed, create a custom access log in /tmp/access.log on each web server using the following format:_
> _- Date and time of access (standard log format)_
> _- Name of the node being accessed_
> _- IP address of the client accessing the website_
> _- HTTP method and URI accessed by the client_
> _- HTTP response status code_
> _- Number of bytes sent in the response_
> _- Time taken by the server to process the request_
> _- Example Log Format:_
> _[01/Oct/2024:11:30:45 +0000] Jarkom Node Lune Access from 192.168.1.15 using method "GET /resep/bayam HTTP/1.1" returned status 200 with 2567 bytes sent in 0.038 seconds_

**Answer:**

- Screenshot
  Format log:
  
  <img width="795" height="111" alt="gambar" src="https://github.com/user-attachments/assets/8d45fb7f-020d-4255-87fb-5718579bd4e0" />


- Explanation

Menambahkan format access log ke dalam file '/etc/nginx/sites-available/default'

<br>

## Soal 7

> Gustave merupakan web server yang tidak disarankan untuk dilihat oleh publik. Maka dari itu, ubahlah konfigurasi nginx sehingga halaman profil Gustave menjadi hanya bisa di akses melalui port 8080 dan 8888.

> _The Gustave web server should not be publicly accessible.
Modify the Nginx configuration so that Gustave’s profile page can only be accessed through ports 8080 and 8888._

**Answer:**

- Screenshot

  <img width="408" height="97" alt="gambar" src="https://github.com/user-attachments/assets/6f33b5cb-9de4-4115-aa38-711992235e71" />
  
- Explanation

Pada file '/etc/nginx/sites-available/default' listen diubah menjadi 8080 dan 8888 dari 80 agar web hanya bisa diakses melalui port 8080 dan 8888

<br>

## Soal 8

> Untuk mempermudah program ekspedisi, maka node Lune, Sciel, Gustave sepakat untuk membuat halaman informasi dengan konten yang sama. Maka dari itu, buatlah lagi 1 server block di dalam konfigurasi nginx yang akan menyajikan file HTML ini. Namun, mereka ingin menyajikan halaman informasi tersebut di port yang berbeda-beda, yaitu Lune menggunakan port 8000, Sciel menggunakan port 8100, dan Gustave menggunakan port 8200.

> _To simplify coordination for the expedition program, Lune, Sciel, and Gustave agree to create a shared information page with the same content. Add one more server block in each node’s Nginx configuration that serves this HTML file 
Each node should serve the information page on a different port:_
> _- Lune → port 8000_
> _- Sciel → port 8100_
> _- Gustave → port 8200_

**Answer:**

- Screenshot

  File html informasi

<img width="543" height="25" alt="gambar" src="https://github.com/user-attachments/assets/09a686e7-778a-499a-9b67-65130cfbc394" />
<img width="903" height="610" alt="gambar" src="https://github.com/user-attachments/assets/e94c529c-ce5e-4361-b0a1-5b99abd81001" />

    
  Server block:
  
  <img width="896" height="459" alt="gambar" src="https://github.com/user-attachments/assets/9a5edb46-964e-45d6-a813-b1dc3e453386" />
  <img width="903" height="304" alt="gambar" src="https://github.com/user-attachments/assets/f7db580b-ebcf-490d-b32e-236b097c77db" />
  <img width="901" height="303" alt="gambar" src="https://github.com/user-attachments/assets/0c42daf5-24d3-45d9-b4a1-c9aaf5af784f" />

- Explanation

HTML dipaste dari soal dan dimasukkan ke direktori '/etc/www/html/informasi.html'

Membuat server block baru dengan pengaturan yang sama dan mengubah listen menjadi '8000', '8100', dan '8200' untuk server lune, sciel, dan gustave agar html informasi hanya bisa di akses pada port yang sesuai

<br>

## Soal 9

> Untuk mempermudah akses ke profil tiap anggota ekspedisi, buatlah 1 domain lagi yaitu "expeditioners.com" yang akan mengarah ke Alicia. Lalu, untuk mencegah overload dari salah satu web server, konfigurasikan reverse proxy Alicia agar bisa forward request ke server yang sesuai berdasarkan URL profile yang diminta oleh klien dengan ketentuan sebagai berikut:
> -  Request untuk “expeditioners.com/profil_lune” harus dialihkan ke halaman profil web server Lune.
> -  Request untuk “expeditioners.com/profil_sciel” harus dialihkan ke halaman profil web server Sciel.
> -  Request untuk “expeditioners.com/profil_gustave” harus dialihkan ke halaman profil web server Gustave.
> Jika terdapat request ke URL selain profil yang ditentukan, reverse proxy akan mengalihkan ke halaman informasi pada web server Lune.

> _To make it easier to access each member’s profile, create a new domain “expeditioners.com” that points to Alicia. "
Configure Alicia’s reverse proxy (Nginx) to forward requests to the correct web server based on the requested URL, with the following rules:_
> _- Request URL expeditioners.com/profil_lune, Forward To Lune’s profile page_
> _- Request URL expeditioners.com/profil_sciel, Forward To Sciel’s profile page_
> _- Request URL expeditioners.com/profil_gustave, Forward To Gustave’s profile page_
> _- Any other URL, Forward To Lune’s information page_

**Answer:**

- Screenshot

Tambahkan zone expeditioners

<img width="897" height="163" alt="gambar" src="https://github.com/user-attachments/assets/aa787b60-be64-433b-8c38-ba42fd188b46" />

file expeditioners

<img width="903" height="604" alt="gambar" src="https://github.com/user-attachments/assets/03b57d21-4f66-4737-8d94-f4d491d670b2" />

tambahkan zone di DNS Slave

<img width="903" height="119" alt="gambar" src="https://github.com/user-attachments/assets/33f60915-0924-4e10-bd77-0890f7860eb1" />

Setup reverse proxy dan forwarding

<img width="895" height="597" alt="gambar" src="https://github.com/user-attachments/assets/52b251b5-c501-4d9a-9463-122447921be8" />



- Explanation

 Pada DNS master buat zone baru untuk domain 'expeditioners.com' dan pada file domain, IP yang digunakan adalah IP dari proxy Alicia
 
 Tambahkan zone domain 'expeditioners' pada DNS Slave agar domain masih bisa diakses jika DNS master tidak aktif
 
 Pada Node Alicia (proxy) atur servername sebagai 'expeditioners.com' dan location profil yang berisi proxy pass untuk melakukan forwarding ke webserver sesuai lanjutan alamat 'expeditioners' ke domain/IP webserver yang sesuai. Jika alamat tidak ada yang sesuai maka secara default akan di arahkan ke page informasi khususnya pada domain lune33 melalui port 8000

<br>

## Soal 10

> Untuk mendistribusikan traffic halaman informasi, atur Reverse Proxy Alicia agar dapat membagi pekerjaan kepada web server Lune, Sciel, dan Gustave secara optimal menggunakan algoritma Round-robin. Pastikan target pembagian load merupakan halaman informasi, bukan halaman profil masing-masing web server.

> _To distribute traffic for the information page, configure the reverse proxy (Alicia) to use Round-robin load balancing between the three web servers: Lune, Sciel, and Gustave.
Ensure that only the information page is included in the load-balancing configuration - not the profile pages._

**Answer:**

- Screenshot

Menambahkan upstream untuk round robin halaman informasi

<img width="404" height="132" alt="gambar" src="https://github.com/user-attachments/assets/e380b01d-d191-47f7-801e-41d89ba23749" />

URL selain profil akan diarahkan ke halaman informasi

<img width="904" height="74" alt="gambar" src="https://github.com/user-attachments/assets/deb7f01b-eeef-4758-979e-04ac19625f01" />


- Explanation

membuat upstream agar round robin dapat terjadi antar ketiga webserver untuk page informasi dengan server berisi domain serta port yang digunakan masing masing webserver

URL selain profil salahsatu dari ketiga domain akan diarahkan ke upstream info_servers yang sebelumnya berisi domain dan port yang membuka informasi.html menggunakan proxy_pass

<br>
  
## Problems
Masalah yang saya temui dalam praktikum ini adalah beberapa bagian dari modul tidak memiliki resource yang cukup untuk mengerjakan semua soalpraktikum sehingga harus membaca referensi dari sumber lain
## Revisions (if any)
