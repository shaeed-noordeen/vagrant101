In this repository, I've created two virtual machines; DB and APP. These will
run in the same virtual box. The DB has mongodb installed and app has DB_HOST
set in the environment.

> - Last login: Tue Nov 30 18:08:42 2021 from 10.0.2.2
vagrant@ubuntu-xenial:~$ systemctl status mongodb
● mongodb.service - An object/document-oriented database
   Loaded: loaded (/lib/systemd/system/mongodb.service; enabled; vendor preset:
   Active: active (running) since Tue 2021-11-30 17:55:45 UTC; 15min ago
     Docs: man:mongod(1)
 Main PID: 3585 (mongod)
    Tasks: 10
   Memory: 42.5M
      CPU: 3.225s
   CGroup: /system.slice/mongodb.service
           └─3585 /usr/bin/mongod --config /etc/mongodb.conf

