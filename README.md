# WEB-SERVER
# SERVICE
- SSH
- APACHE2 ( Web Server )
- PHP8
- MySQL
- WEBMIN ( Control Panel )
- BIND9 ( Domain Name )
# TOOLS
- Oracle Virtual Box
- ISO Ubuntu Server 22.04 LTS
# PROGRESS AKHIR
1. Install SSH ( Default Ubuntu )
2. Install & Konfigurasi Apache2
   - "sudo apt install apache2"
   - "sudo ufw app list" - "sudo ufw allow 'Apache" - "sudo ufw status"
4. Configurasi HTML Apache2
   - "sudo nano /var/www/realaditya.com/index.html" ( Tampilan Login )
   - "sudo nano /var/www/realaditya.com/dashboard.html" ( Tampilan Profil )
5. Install WebMin
   - https://www.digitalocean.com/community/tutorials/how-to-install-webmin-on-ubuntu-20-04-id
   - "sudo apt install webmin"
   - "sudo ufw allow 10000" ( Mengakses Port 10000 )
   - Access Web "https://your_server:10000" ( Digunakan Untuk Monitoring & Control Panel )
6. Install BIND9 ( 08 Desember 2023 )
   - https://bahasaweb.com/cara-membuat-name-server-di-ubuntu/# 
     - tambahan ( digunakan untuk access firewall menggunakan port 53 )
     - sudo iptables -A INPUT -p udp --dport 53 -j ACCEPT
     - sudo iptables -A INPUT -p tcp --dport 53 -j ACCEPT
