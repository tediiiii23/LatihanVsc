# NAMA  : TEDI MULYADI
# NIM   : 312110114
# KELAS : TI.21.C.1
# TUGAS : BAHASA PEMROGRAMAN

### PERTANYAAN :

•   Buatlah satu repositories LATIHAN VCS  

•   Buat file README.md, lalu isi file tersebut dengan penjelasan ( tutorial ) cara penggunaan git, dan langkah-langkahnya lengkapi juga dengan screenshot prosesnya

### JAWABAN :

### Install git 
&nbsp;&nbsp;&nbsp;&nbsp;Langkah yang pertama install software git pada link ini https://git-scm.com/install/. Kemudian sesuaikan dengan sistem operasi yang digunakan, misalnya windows 32/64bit setelah di download maka lakukan instalasi software seperti pada umumnya sampai selesai.
### Penggunaan dasar git 
&nbsp;&nbsp;&nbsp;&nbsp;setelah terinstall pada tahap sebelumnya, selanjutnya terdapat beberapa pilihan software, jalankan software yang namanya gitbash dengan cara :  

•	bisa double klik pada icon gitbash  

•	bisa klik kanan kemudian open  

•	bisa juga run as administrator

Contoh gambarnya :

![gambar](ss/1.png)

### Setelah di jalankan maka akan seperti contoh gambar dibawah :

![gambar](ss/2.png)

### Kemudian lakukan konfigurasi antara git dengan akun github yang telah dibuat, lalu tulis perintah untuk setup nama dan email :
•	git config –global user.name “tediiiii23”  

•	git config –global uuser.email “tedi3106@gmail.com”

![gambar](ss/3.png)

### Penggunaan git hampir sama seperti CMD pada windows. Beberapa perintah dasar git yang sering digunakan di antaranya :

| Perintah gitbash | fungsi | Contoh penggunaan |
|---------------------|------------|-------------|
| `git config --global user.name "user name misalnya pada github"` | Mengatur username Git secara global | git config --global user.name " tediiiii23" |
| `git config --global user.email "email yang digunakan pada github"` | Mengatur email Git secara global | git config --global user.email " tedi3106@gmail.com " |
| `git init` | Membuat repository Git baru di folder saat ini | git init |
| `git clone <url>` | Menyalin repository dari GitHub ke komputer | git clone https://github.com/username/repo.git |
| `git status` | Melihat status perubahan file di repository | git status |
| `git add <nama_file>` | Menambahkan file ke staging area | git add readme.md |
| `git add .` | Menambahkan semua file yang berubah ke staging | git add . |