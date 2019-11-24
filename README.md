a.	Cara mendownload git
1.	Download aplikasi git di (http://git-scm.com)
2.	Klik unduh untuk windows
3.	Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit
4.	Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah “git –version”

b.	Cara menambahkan Global Config
1.	Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi user.name dan user.email dengan cara buka git bash
2.	Dengan perintah “git config --global user.name “nama_user” untuk membuat user name
3.	Lalu “git config --global user.email “nama_user” untuk membuat email

c.	Cara Membuat Reposiory Local
1.	Buka direktory aktif, misal: d:\labs_pemrograman1 (buka menggunakan Windows Explorer) 
2.	klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash, sehingga muncul git bash commad 
3.	Buat direktory project praktikum pertama dengan nama latihan1 
4.	Dengan ketikan “mkdir latihan1” untuk membuat agar terbentuk satu direktori baru di dalamnya
5.	Lalu dengan “cd latihan1” untuk masuk ke direktori Latihan1

d.	Cara Membuat Reposiory Local
1.	Jalankan perintah “git init”, untuk membuat repository local.
2.	Repository baru berhasil di inisialisasi, dengan terbentuknya satu direktori hidden dengan nama .git 
3.	Pada direktori tersebut, semua perubahan pada working directory akan disimpan

e.	Cara Menambahkan File baru pada repository
1.	Untuk membuat file dapat menggunakan text editor, lalu menyimpan filenya pada direktori aktif (repository) 
2.	Disini kita akan coba buat satu file bernama README.md (text file) ketikan “echo “#Latihan 1” >> README.md”
3.	File README.md berhasil dibuat
4.	Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah “git add”.
5.	 File README.md berhasil ditambahkan.

f.	Cara Commit (Menyimpan perubahan ke database)
1.	Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah “git commit -m “komentar commit”
2.	Perubahan berhasil disimpan.
g.	Cara Membuat repository server
1.	Server reopsitory yang akan kita gunakan adalah http://github.com buka dengan browser
2.	Anda harus membuat akun terlebih dahulu. Gunakan user name dan email yang tadi didaftarkan di git
3.	Pada laman github, klik tombol start a project, 
4.	 Dari menu (icon +) klik New Repository
5.	Isi nama repositorynya, misal: labpy1.
6.	lalu klik tombol Create repository

h.	cara Menambahkan Remote Repository
1.	Untuk menambahkan remote repository server, gunakan perintah “git remote add origin [url]” masukan url yang ada pada github yang telah dibuat

i.	Cara Push (Mengirim perubahan ke server)
1.	Untuk mengirim perubahan pada local repository ke server gunakan perintah git push. “git push -u origin master”
2.	Perintah ini akan meminta memasukkan username dan password pada akun github.com
3.	Jika berhasil Buka halaman github.com, arahkan pada repositorinya. 
4.	Maka perubahan akan terlihat pada laman tersebut.

j.	Cara Clone Repository
Untuk melakukan cloning, gunakan perintah git clone [url]
