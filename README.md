# Dork7ee
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhwkCw4hjxnBTZ74DbQpEfIy-Bae-8CLhdkrN7dAViBWHCYW87fqC36EHPH5qdG0iesuXvsHSk3ldLTIaiUxPo7C9FUtBAt1RZP-Vtn_r4xFU4_cQ5cctiv23PeDlI6XavMlCtVxzN3mBIyksqUDo-i8FKriApBLqy00s77j9HDnRyLpkLTjGnEQOlqKGs/s320/Screenshot_2023-09-24-13-09-23-83_84d3000e3f4017145260f7618db1d683-picsay.jpg" alt="Awalan"><br>
Mengambil URL dari daftar Halaman Google menggunakan Query (Google Dork) dan menyimpan url yang di dapat ke dalam file hasil.txt

# Pemasangan & Menjalankan
pkg upgrade && pkg upgrade
pkg install python<br>
pkg install git<br>
git clone https://github.com/Darkskull777/Dork7ee<br>
cd Dork7ee<br>git pull<br>
pip install -r requirements.txt<br>
python run.py

# Pengertian Kolom
<b>Masukan query pencarian:</b>
Disini input suatu Pesan yang ingin Anda temukan di suatu URL. Bisa menggunakan Google Dork!<br>
<b>Contoh:</b> <br>site:dpr.go.id filetype:pdf
<br>inurl:id= ext:php site:go.id intext:"berita"<br>
inurl:/hello-world intext:"Welcome to WordPress. This is your first post."<br><br><b>Pilih mesin pencarian (Google/Bing/Yandex):</b><br>Kolom ini menawarkan kamu untuk memilih Browser Mesin Pencarian yang ingin Anda gunakan. Jika anda ingin menggunakan Mesin Pencarian Google kamu bisa mengisi kolom ini dengan <b>google</b>, dan jika ingin menggunakan mesin pencarian Bing kamu bisa mengisi kolom nya dengan menulis <b>bing</b>, begitu pun dengan Yandex kamu bisa mengetik <b>yandex</b> jika ingin menggunakan mesin pencarian Yandex.<br><br><b>Masukkan jumlah halaman (default 100):</b><br>Disini kamu bisa memasukkan Jumlah halaman yang ingin kamu ambil, Kamu bisa memasukkan angka 1 hingga berapapun. Dan ingat jangan terlalu memasukkan sebuah angka yang berlebihan!<br><br>
<b>Apakah Anda ingin menggunakan User-Agent opsional? (y/n):</b><br>
Disini Anda ingin menggunakan User Agent Pribadi milik Anda sendiri, atau menggunakan User Agent bawaan program. Jika ingin menggunakan User Agent milik Anda Isi dengan <b>y</b>, Dan jika ingin memakai User Agent bawaan Program Anda bisa meng Isi dengan <b>n</b>.
<br><br>
<b>Masukkan User-Agent Anda:</b><br>
Kolom ini akan ditampilkan jika Anda mengisi <b>y</b> pada saat pemilihan User-Agent. Dan pada kolom ini Anda bisa meng Input User-Agent yang ingin Anda gunakan<br>
<b>Contoh:</b><br><b>1.</b> 
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/94.0.4606.61 Safari/537.36<br><b>2.</b> Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:91.0) Gecko/20100101 Firefox/91.0<br><b>3.</b> Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Safari/14.1.2<br><b>4.</b> Mozilla/5.0 (iPhone; CPU iPhone OS 15_0 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/15.0 Mobile/15E148 Safari/604.1<br><b>5. </b>Mozilla/5.0 (Linux; Android 10; SM-G960U) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/94.0.4606.61 Mobile Safari/537.36
<br><br><b>Apakah kamu ingin menggunakan proxy? (y/n):</b><br>Disini kamu bisa memilih <b>y</b> jika ingin menggunakan Proxy milik anda sendiri, Dan jika tidak mempunyai Proxy anda bisa memilih <b>n</b> untuk menjalankan Program tanpa menggunakan proxy.<br><br><b>Masukkan proxy HTTP:</b><br>Kolom ini akan muncul jika kamu memilih <b>y</b> pada saat pertanyaan ingin menggunakan proxy. Di kolom ini kamu bisa mengisi alamat proxy HTTP milik kamu contoh nya <b>http://972.5.48.6293:80</b>, Gunakan <b>http://</b> beserta <b>port</b><br><br><b>Apakah ingin menggunakan proxy HTTPS? (y/n):</b><br>Pada kolom ini kamu bisa menggunakan Proxy HTTPS milik sendiri, isi dengan <b>y</b> jika ingin menggunakan Proxy HTTPS dan isi dengan <b>n</b> jika tidak ingin menggunakan Proxy HTTPS.<br><br><b>Masukkan proxy HTTPS:</b><br>Kolom ini akan muncul jika kamu memilih <b>y</b> pada saat pertanyaan ingin menggunakan proxy https?. Di kolom ini kamu bisa mengisi alamat proxy HTTPS milik kamu contoh nya <b>https://972.5.48.6293:80</b>, Gunakan <b>https://</b> beserta <b>port</b>
# Panduan
Jika sudah mengisi semua Kolom Anda tinggal menunggu hingga pemrosesan Selesai.<br>Maka hasil dari URL yang anda dapatkan akan disimpan kedalam file bernama <b>hasil.txt<br></b><br>
<img src="https://b.top4top.io/p_28223qu0n0.png" alt="Hasil"><br>
Berikut adalah contoh hasil Scrap dari 100 Halaman dengan Query yang di Input, Mendapatkan 300++ url pdf file dari Situs Resmi Pemerintahan Indonesia<br><br><b>Ingat. hasil url apapun yang ditampilan itu tergantung Query yang kalian Input!
