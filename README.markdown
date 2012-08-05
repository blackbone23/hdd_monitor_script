UNTUK CLIENT :

- install python-setuptools dan python-dev
- install git-core
- buat ssh-keycgen
- masukkan ssh keygen di git
- clone repos hdd-monitor-script
- install pip (sudo easy_install pip)
- install psutil (sudo pip install psutil)
- install urllib3 (sudo pip install urllib3)


Cronjob : 

Menggunakan crontab

1. Cron untuk per disk usage dilakukan perhari (file : psutil_disk_usage.py)
2. Cron untuk check persentase hdd dilakukan per 10 menit (file : psutil_disk_usage_alarm.py)


