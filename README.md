NAMA: Bagas Ari Pradana

KELAS: TI.21.C5

Nim:312110485

# PENGGUNAAN GIT

APA ITU GIT ? Git adalah salah satu sistem pengontrol versi (Version ControlSystem) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds. Pengontrol versi bertugas mencatat setiap perubahan pada fileproyek yang dikerjakan oleh banyak orang maupun sendiri. Git dikenal juga dengan distributed revision control (VCS terdistribusi),artinya penyimpanan database Git tidak hanya berada dalam satutempat saja.

INSTALASI GIT

Download Git, buka website resminya Git (git-scm.com). Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit. Selamat, Git sudah terinstal di Windows. Untuk mencobanya,silahkan buka CMD atau PowerShell, kemudian ketik perintah TUTORIAL MENGGUNAKAN GIT Perintah Dasar Git
-git init, perintah untuk membuat repository local

-git add, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.

-git commit, perintah untuk menyimpan perubahan kedalam database git.

-git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository.

-git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.

-git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)

-git pull, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository

Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut:

$git config --global user.name "username"

$git config --global user.email "email"

![Screenshot (67)](https://user-images.githubusercontent.com/92848203/138758628-e37a7fb6-3961-45ae-961e-8c35487899e8.png)

$git init
Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
![Screenshot (70)](https://user-images.githubusercontent.com/92848203/138758793-a6f80b8a-ee61-4e40-b363-3f122d87e253.png)

$echo "Latihan-VCS" >> README.md

Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" Dan yang ada di dalam tanda kutip " " itu nama project kita dan jangan sama setiap kali kita upload project
$git commit -m "First Project" Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url) git remote add origin https://github.com/bagas-312110485/Latihan-VCS.git

$git branch -M main
Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push Perintah ini akan meminta Username dan Password pada akun github mu
![Screenshot (72)](https://user-images.githubusercontent.com/92848203/138759585-d70831cf-0c33-422b-8bdb-62cd20af615e.png)

# Selesai
