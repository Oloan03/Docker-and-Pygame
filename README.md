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

### Cara install docker di ubuntu :
* Masuk/login keserver melalui ssh client.
* Menginstal package yang dibutuhkan dengan perintah : sudo apt-get install curl apt-transport-https ca-certificates software-properties-common
* Menambahkan repistori docker dengan langkah-langkah :
   - Menambahkan GPG key : curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   - Menambahkan repositori dengan cara :
     sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
   - Update Package Database : sudo apt update
   - Kemudian install docker dan cek kembali bahwa aplikasi telah terinstall.

### Cara install phyton :
* update your local system's repository list : sudo apt update
* Download the latest version of Python : sudo apt install python3

2. Setelah diinstall kemudian docker mulai dijalankan untuk membuat container
* clone repositori game script yang akan dijalankan pada docker dan pindahkan py game script ke folder download.
* melakukan pembangunan image py game script yang telah didownload sebelumnya.
* selanjutnya jalankan perintah image untuk melihat daftar image pada local storage.
* Jalankan container dengan perintah make run linux ,perintah menjalankan disesuaikan dengan os digunakan.

#
## Gambar
![WhatsApp Image 2022-05-27 at 21 53 24](https://user-images.githubusercontent.com/90511661/170735199-34d5e868-8745-4158-8dd9-0c4cb62f1e1b.jpeg)

![WhatsApp Image 2022-05-27 at 21 53 27](https://user-images.githubusercontent.com/90511661/170735183-46597018-e356-452a-98f6-98b5c50e3bee.jpeg)

![WhatsApp Image 2022-05-27 at 21 53 21](https://user-images.githubusercontent.com/90511661/170735195-02aa6806-1125-4a53-8f2d-3be09440c336.jpeg)

![WhatsApp Image 2022-05-27 at 21 53 22](https://user-images.githubusercontent.com/90511661/170735197-46e126aa-c98b-4255-bff8-44b9b94aea84.jpeg)

![WhatsApp Image 2022-05-27 at 21 53 26](https://user-images.githubusercontent.com/90511661/170735202-41680345-afb1-47a4-9b33-98a066ff0c26.jpeg)

![WhatsApp Image 2022-05-27 at 21 53 31](https://user-images.githubusercontent.com/90511661/170735189-31778536-ab0a-45b4-8259-9bc7841820ad.jpeg)
#
## Video Demo Kontainer
