# FtpDrive 
Berguna untuk mengubah Sftp menjadi map drive diwindows 10

Install https://github.com/billziss-gh/winfsp
Install https://github.com/billziss-gh/sshfs-win

Kemudian untuk memasukan ftp menjadi drive berikut ini carnaya:

#
buka windows explorer

klik kanan ``This PC`` 

pilih Map Network Drive

pada bagian kolom folder ketik: \\sshfs\username@host

contoh: \\sshfs\ucup@109.66.102.100
  
jangan lupa centang ``connect using different credentials`` jika server ftp mu menggunakan username dan password.

Selesai, nanti muncul folder yg ada didalam server ftp didalam explorer pc kamu.

#

<img src="https://github.com/billziss-gh/winfsp/raw/master/doc/cap.gif" height="450"/>

