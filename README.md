# Tugas-III

Pendahuluan 


Tugas 2 PKSJ - Ganjil 2016/2017

Pendahuluan

Tugas 2 adalah tugas kedua yang harus di selesaikan sebagai salah satu syarat penilaian pada matakuliah Perancangan Keamanan & Sistem Jaringan (PKSJ) Semester Ganjil 2016/2017, TeknikInformatika ITS, Surabaya

AnggotaKelompok

• Dewi Kartika 5113100008

• M.Sholaudin 5112100075

• FauzanAdim 5113100101

Dasar teori :

OS yang digunakan

![alt tag](https://github.com/PKSJTeam/Tugas-II/blob/master/Tools/ubuntu1.jpg)

• Ubuntu Server adalah salah satu varian dari distro linux Ubuntu. Dalam pembahasan kali ini dan pembahasan selanjutnya, saya akan membahas tentang perintah CLI di Linux dan seting server menggunakan ubuntu 12.10. Namun sebelum membahas lebih jauh tentang Ubuntu server akan saya kenalkan dulu apa itu ubuntu server dalam format FAQ sehingga lebih mudah di pahami.

Tools yang digunakan :

![alt tag](https://github.com/PKSJTeam/Tugas-III/blob/master/Picture/cuckoo-logo.jpg)

a. Cuckoo Sandbox adalah salah satu sistem atau perangkat yang digunakan untuk menganalisis sebuah suspect dalam bentuk malware, atau bahasa keren nya Malware Analysis Research Toolkit (MART). Cuckoo Sandbox merupakan perangkat yang gratis atau dalam bahasa lain Open Source. Cara kerja dari Cuckoo Sandbox ini adalah dengan memantau segala kejadian yang mungkin di ditimbulkan oleh sebuah malware yang secara sengaja di run di sebuah environtment yang terisolasi.

![alt tag](https://github.com/PKSJTeam/Tugas-III/blob/master/Picture/virtualbox.png)

b. Virtual Box merupakan software virtualisasi yang digunakan untuk menginstal OS “Operating System” atau bahasa indonesianya Sistem Operasi. Jadi kalian semua dapat menginstal sistem operasi lain di dalam sistem operasi yang kalian punya, begituu. Misalnya anda memiliki sistem operasi Ms. Windows yang terpasang pada komputer anda, maka anda dapat pula menjalankan sistem operasi lain pada Ms.Windows yang anda punya.

![alt tag](https://github.com/PKSJTeam/Tugas-III/blob/master/Picture/windows_xp-100154667-large.png)

c. Windows xp adalah salah satu OS atau salah satu sistem operasi berbasiskan grafis, dibuat oleh Perusahaan Microsoft untuk dapat digunakan pada sebuah komputer, contohnya seperti komputer pribadi maupun rumahan, komputer untuk kegiatan bisnis, notebook, dan pusat media atau Media Center.


Langkah-langkah installasi :
a. Ketikan perintah  sudo apt-get install python python-pip python-dev libffi-dev libssl-dev libxml2-dev libxslt1-dev libjpeg-dev pada terminal untuk installasi packages

![alt tag](https://github.com/PKSJTeam/Tugas-III/blob/master/Picture/pythonnew1.JPG)

b. ketikan perintah sudo setcap cap_net_raw,cap_net_admin=eip /usr/sbin/tcpdump untuk konfigurasi tcpdump

![alt tag](https://github.com/PKSJTeam/Tugas-III/blob/master/Picture/next after tcpdump.JPG)

c. lakukan verifykasi dengan mengetikkan sintax berikut getcap /usr/sbin/tcpdump

![alt tag](https://github.com/PKSJTeam/Tugas-III/blob/master/Picture/getcap.JPG)

d. Installing cuckoo sandbox dengan sintax berikut  git clone git://github.com/cuckoosandbox/cuckoo.git

e. useradd cuckoo di gunakan untuk membuat user baru untuk cuckoo 

![alt tag](https://github.com/PKSJTeam/Tugas-III/blob/master/Picture/adduser.JPG)

f. Installing virtual box dengan sintax sudo apt-get install virtualbox

![alt tag](https://github.com/PKSJTeam/Tugas-III/blob/master/Picture/virtualbox.JPG)

g. lakukan perintah berikut untuk menambahkan user cuckoo ke virtualbox sudo usermod -a -G vboxusers cuckoo



