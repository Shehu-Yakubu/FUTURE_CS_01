# WEB APPLICATION SECURITY
Vulnerability assessment of a real-world or open-source web application. The goal is to identify security flaws using ethical hacking tools and OWASP standards.

## DAMN VULNERABLE WEB APP (DVWA) SETUP
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

## SQL Injection Attack
<img width="1915" height="867" alt="SQLI-2" src="https://github.com/user-attachments/assets/03164fea-4621-437c-a12d-00604af05062" />
<img width="900" height="680" alt="SQLI-1" src="https://github.com/user-attachments/assets/858eab31-c44e-4a12-a6e8-518c9606170e" />

## Reflected Cross-Site Scripting (XSS) Attack
<img width="1918" height="826" alt="XSS_S-1" src="https://github.com/user-attachments/assets/a48c997e-fae3-4117-9a66-38360a8f6a13" />
<img width="1918" height="869" alt="XSS_S-2" src="https://github.com/user-attachments/assets/9bc0294a-3170-4c92-b101-69906aa6e24b" />

## Stored Cross-Site Scripting (XSS) Attack
<img width="1919" height="875" alt="XSS_R-2" src="https://github.com/user-attachments/assets/4b5e2fd7-ad0c-4f0d-8334-29f74d570e54" />
<img width="1916" height="833" alt="XSS_R-1" src="https://github.com/user-attachments/assets/9fc94322-6efd-4276-9435-4e4c6278f6b6" />
