#latihanvcs1
#latihanvcs1


**Nama : Muhammad Romdhon**

**Kelas : TI.20.A.1**

**NIM : 312010434**

# LANGKAH-LANGKAH PENGGUNAAN GIT

* Download git terlebih dahulu,dengan link berikut:[clic here](https://git-scm.com/)

![download](foto/git.png)

* setelah file terdownload silahkan lakukan instalasi dengan referensi berikut ini: [Git Instalation guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

![git](foto/15.png)

* setelah installasi selesai,buka GitBash pada menu di windows, dan lakukan pengecekan versi,dengan mengetik syntax berikut :

`git --version`

![version](foto/version1.png)

* jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisadi gunakan Langkah pertama kita mengkonfirmasikan user name dan email di git, dengan mengetikan syntax berikut :

`git commit --global user.name"masukan nama anda"`

`git commit --global user.email "masukin email anda"`

![name](foto/global.png)

* buat akun di GitHub,seperti contoh dibawah ini. Dan lakukan verifikasi akun melalui email yang sudah terdaftar.

* jika akun GitHub sudah selesai dibuat dan di verifikasi, proses selanjutnya silahkan buat Repository seperti gambar dibawah ini :

**Penjelasan**

* Repository Name : (Silahkan isi nama repository yan diinginkan seperti contoh saya ingin membuat repository Latihanvcs3)

* Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)

* Public / Private : (Pilih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)

* Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda

* Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.

* Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan

![repository](foto/repository.png)

* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :

![hasil](foto/hasilRepository.png)

* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk *me-remote* repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link *URL git* kita di Github, dengan cara tekan tombol **Code** lalu klik *Copy*.

![link](foto/link.png)

* Setelah *Link URL git kita tercopy*, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih **Git Bash Here**.

![gitbash](foto/gitbash.png)

*Pop Up Command Prompt* **(CMD)** akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut :

git clone [URL](https://github.com/Muhammadromdhon/latihan-vcs1.git) pada contohnya, saya akan memasukan git clone

![clone](foto/clone.png)

* Setelah proses cloning selesai, pada saat ini kita masih pada folder awal, kita harus masuk kedalam folder yang telah dicloning tadi yaitu LatihanVCS dengan mengetikkan syntax berikut : cd Latihanvcs1/

![cd](foto/cd.png)

* Saat ini kita sudah masuk kedalam folder *LatihanVCS*, Silahkan edit file README.md yang ada di File Explorer. Bisa menggunakan Text Editor *(Sublime Text, Notepad, Notepad++, Visual Studio Code)*. Edit sesuai dengan keinginan.

![notepad](foto/notepade.png)

Setelah file README.md diedit, silahkan Simpan file tersebut dengan cara **CTRL+S atau File -> Save**

* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash **(CMD)**. Ketik pada Git Bash seperti berikut ini :

`git add .`

![add](foto/gitadd.png)

* Setelah selesai melakukan git add . langkah berikutnya kita akan melakukan *commit*. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini :

`git commit`

![commit](foto/commit.png)

* Git commit telah selesai di lakukan. Untuk saat ini akan melakuka Git Push, Git Push berfungsi untuk mengirimkan perubahan file setelah di commit ke remote repository. Silahkan ketik pada App Git Bash seperti berikut :

`git push`

![push](foto/push.png)

* Semua proses telah selesai, silahkan kembali ke Web Browser untuk melihat perubahan yangtelah di commit dan push dari remote.

![hasil](foto/hasill.png)

**Sekian terima Kasih**