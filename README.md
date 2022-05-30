Hacking methodology

Extensions
    Foxy proxy
To install 
gobuster
Seclists
Rockyou
nmap


Nmap -T4 -n <IP>
Nmap -sVC -A <IP>
Nmap -p -T4 -n <IP>
  
Http
  check versions
  check commnets
  Robots.txt
  Admin.php
  Login.php
  Gobuster -u <IP> -w /usr/share/wordlists
  
Ftp
  Us: anonymous pw: anonymous
  
Ssh
  
on box
  find / -type -name "*flag*" -exec ls -l {} + 2>/dev/null
