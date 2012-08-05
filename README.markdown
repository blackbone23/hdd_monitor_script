UNTUK CLIENT :

- install python-setuptools dan python-dev
- install git-core
- buat ssh-keycgen
- masukkan ssh keygen di git
- clone repos hdd-monitor-script
- install pip (sudo easy_install pip)
- install psutil (sudo pip install psutil)
- install urllib3 (sudo pip install urllib3)
- login ke ryan.pakar/HDD-Monitoring/hdd_monitor sebagai sysadmin
- buat user baru untuk harddisk yang baru
- logout sysadmin, login sebagai user yang baru
- tambahkan data harddisk utk user yang baru di tab HDD
- jalankan script psutil_partition.py dari command shell user baru(lihat Cara Eksekusi script python dari command shell), untuk menambahkan data partisi harddisk




Cronjob : 

Menggunakan crontab

1. Cron untuk per disk usage dilakukan perhari (file : psutil_disk_usage.py)
2. Cron untuk check persentase hdd dilakukan per 10 menit (file : psutil_disk_usage_alarm.py)

Cara Eksekusi script python dari command shell : 

* Untuk mengeksekusi file python secara manual lakukan perintah
 ./<namafile.py>



