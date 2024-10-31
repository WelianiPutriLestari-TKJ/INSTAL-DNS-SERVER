# INSTAL-DNS-SERVER
Instalasi aplikasi DNS server root@smkmanusa:# apt-get install bind9 dnsutils è masukkan cd 1 dan cd 2 Konfigurasi server DNS (file bernama.conf) root@smkmanusa:# nano /etc/bind/named.conf.default-zones Edit pada baris: zone "smkmanusa.sch.id" { ketik master; file "/etc/bind/db.manusa"; }; zona "1.30.172.in-addr.arpa" { ketik master;
