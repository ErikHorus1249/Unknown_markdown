whois : https://who.is/whois/landyachtzbikes.com

23.1.35.90

dải IP: NS1.A2HOSTING.COM 162.159.25.95
        NS2.A2HOSTING.COM 162.159.24.221
        NS3.A2HOSTING.COM 162.159.25.82
        NS4.A2HOSTING.COM 162.159.24.227, 
        
người quản lý : 
DNS : 

theHarvester

`$ theHarvester -d landyachtzbikes.com -l 500 -b google`

mail.landyachtzbikes.com:185.148.46.57
www.landyachtzbikes.com:185.148.46.57

nmap : sudo nmap -O 185.148.46.57 
21/tcp   open  ftp
25/tcp   open  smtp
53/tcp   open  domain
80/tcp   open  http
110/tcp  open  pop3
143/tcp  open  imap
443/tcp  open  https
465/tcp  open  smtps
587/tcp  open  submission
993/tcp  open  imaps
995/tcp  open  pop3s
2525/tcp open  ms-v-worlds
3306/tcp open  mysql
5432/tcp open  postgresql

`nikto -h 185.148.46.57 -ssl`
