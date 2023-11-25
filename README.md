# WEB-SERVER
# SERVICE
- SSH
- APACHE2 ( Web Server )
- PHPMyAdmin ( Control Database )
- MySQL
- WEBMIN ( Control Panel )
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
   - "sudo nano /var/www/realaditya.com/profil.html" ( Tampilan Profil )
5. Install WebMin
   - "sudo apt install webmin"
   - "sudo ufw allow 10000" ( Mengakses Port 10000 )
   - Access Web "https://your_server:10000" ( Digunakan Untuk Monitoring & Control Panel )
6. Install PHPMyAdmin
   - "sudo apt install php"
   - "sudo apt install phpmyadmin php-mbstring php-zip php-gd php-json php-curl"
   - "https://your_domain_or_IP/phpmyadmin" ( Digunakan Untuk Akses Control Database )
