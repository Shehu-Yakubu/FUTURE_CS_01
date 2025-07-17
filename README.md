# FUTURE_CS_01
Web Application Security Testing

# DAMN VULNERABLE WEB APP (DVWA) SETUP
**Step 1**
1. Cloning the GitHub repo -> https://github.com/digininja/DVWA.git
2. Moving the cloned repo to a specific folder -> sudo mv DVWA /var/www/html
3. Starting an Apache2 web server -> sudo service apache2 start
4. Switching to the cloned DVWA repo -> cd DVWA
5. Copying the config file -> cp config/config.inc.php.dist config/config.inc.php
6. Starting a database -> service mariadb start
<img width="1920" height="1080" alt="DVWA-Setup-1" src="https://github.com/user-attachments/assets/f134ae91-4fc7-42bc-8f48-eabd70a2f071" />

**Step 2**
1. Starting the database -> mysql
2. Creating a database -> create database dvwa;
3. Creating a user with password -> create user dvwa@localhost identified by 'p@ssw0rd';
4. Grant the user access -> grant all on dvwa.* to dvwa@localhost;
5. Flush the user privileges -> flush privileges;
<img width="1920" height="1080" alt="DVWA-Setup-2" src="https://github.com/user-attachments/assets/86867675-c3c2-43b2-8049-c9673de3e2f1" />

**Step 3**
1. Change the database -> use dvwa
<img width="1920" height="1080" alt="DVWA-Setup-3" src="https://github.com/user-attachments/assets/c34a6149-ffb8-42a2-b2be-2c50999e2a79" />

**Step 4**
1. Launching the DVWA login page.
<img width="1920" height="1080" alt="DVWA-Setup-4" src="https://github.com/user-attachments/assets/b3d4d3b7-25f4-4d08-b6d4-1a9976b96653" />

**Step 5**
1. Successful login to the DVWA website.
<img width="1920" height="1080" alt="DVWA-Setup-5" src="https://github.com/user-attachments/assets/f10cce1b-0957-48d5-8134-ced99291f366" />

