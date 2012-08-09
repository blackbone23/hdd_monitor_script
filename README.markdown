UNTUK CLIENT :

- install python-setuptools dan python-dev
- install git-core
- buat ssh-keycgen
- masukkan ssh keygen di git
- clone repos hdd-monitor-script
- install pip (sudo easy_install pip)
- install psutil (sudo pip install psutil)
- install urllib3 (sudo pip install urllib3)
- install php5-cli
- install cron
- login ke ryan.pakar/HDD-Monitoring/hdd_monitor sebagai sysadmin
- buat user baru untuk harddisk yang baru
- logout sysadmin, login sebagai user yang baru
- tambahkan data harddisk utk user yang baru di tab HDD

- tanamkan ssh key public server di setiap client : 
	- lakukan install ssh server di client (sudo apt-get install openssh-server)
	- lakukan ssh ke client dari server (ssh <user_client>@<IP_client>)
	- buat file authorized_keys di folder .ssh (nano authorized_keys)	
	- tambahkan ssh key public server di file authorized_keys (ssh key ada di .ssh/id_rsa.pub)
	- logout ssh, lakukan ssh kembali. Jika tidak diminta password maka tutorial bagian ini berhasil.



- jalankan script psutil_partition.py dari command shell user baru(lihat Cara Eksekusi script python dari command shell), untuk menambahkan data partisi harddisk




Cronjob : 

Menggunakan crontab

1. Cron untuk per disk usage dilakukan perhari (file : psutil_disk_usage.py)
2. Cron untuk check persentase hdd dilakukan per 10 menit (file : psutil_disk_usage_alarm.py)

Cara Eksekusi script python dari command shell : 

* Untuk mengeksekusi file python secara manual lakukan perintah
 ./<namafile.py>



