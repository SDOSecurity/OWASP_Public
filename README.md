Hi You,

There are 10 hidden flags, try to find them all.

1. Information Disclouser
2. Weak Credentials
3. Reflected Cross Site Scripting
4. SQL Injection
5. Encrypted Cookie
6. User Enumeration
7. Weak Encryption

Install it on your Linux environment:

You need to have Apache agent running with PHP support. 

1. sudo apt-get update -y
2. sudo apt-get install apache2 -y
3. sudo apt-get install php -y
4. sudo apt-get install -y php-{bcmath,bz2,intl,gd,mbstring,mcrypt,mysql,zip} && sudo apt-get install libapache2-mod-php  -y
5. sudo service apache2 start
6. cd ~/ && mkdir Workspace
7. git clone https://github.com/SDOSecurity/OWASP_Public.git
8. cd OWASP_Public
9. firefox index.html

Good Luck.

info@sdo-security.com
