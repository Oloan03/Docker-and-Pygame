# Docker2
#
### Nama dan NIM anggota kelompok :
#### Duta Rega Rolindo Simorangkir - 120140135
#### Basrunki Siburian - 120140007 
#### Gracia Sherianta Br Sitepu - 120140084
#### Noviana Gresita Perangin-Angin - 120140239
#### Oloan Soaloon Napitupulu - 120140097
#### Alief Arrly Prasetyo - 120140207
#
## DINOSAUR
#
## Deskripsi Program Game Dinosaur
Program ini menggunakan modul pygame, dengan menerapkan pemrograman berorintasi objek (PBO). Pada game Dinosaur ini, objek dinosaurus sebagai objek utama yang mampu berlari, menunduk dan melompat untuk melewati rintangan yang terdiri dari kaktus, batu dan burung.

#
## Cara Menjalankan Kontainer
1. Terlebih dahulu menginstal aplikasi docker dan phyton

Cara install docker di ubuntu :
* Masuk/login keserver melalui ssh client.
* Menginstal package yang dibutuhkan dengan perintah : sudo apt-get install curl apt-transport-https ca-certificates software-properties-common
* Menambahkan repistori docker dengan langkah-langkah :
   - Menambahkan GPG key : curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   - Menambahkan repositori dengan cara :
     sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
   - Update Package Database : sudo apt update
   - Kemudian install docker dan cek kembali bahwa aplikasi telah terinstall.
Cara install phyton :
* update your local system's repository list : sudo apt update
* Download the latest version of Python : sudo apt install python3

2. Setelah diinstall kemudian docker mulai dijalankan untuk membuat container
   
#
## Video Demo Kontainer
