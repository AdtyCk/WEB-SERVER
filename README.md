# WEB-SERVER
# SERVICE
- SSH
- APACHE2 (Web Server)
  ![image](https://github.com/AdtyCk/WEB-SERVER/assets/148180105/17b7854e-fde8-468a-a44f-ab247320a5eb)

- PHP
- MySQL
- WEBMIN (MONITORING)
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
   - Access Web "https://your_server:10000" ( digunakan untuk mengakses webmin dan memonitoring server )
