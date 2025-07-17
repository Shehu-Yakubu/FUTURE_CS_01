# FUTURE_CS_01
Web Application Security Testing

# DAMN VULNERABLE WEB APP (DVWA) SETUP
**Step 1**
1. Cloning the GitHub repo.
2. Moving the cloned repo to a specific folder.
3. Starting an Apache2 web server.
4. Switching to the cloned DVWA repo.
5. Copying the config/config.inc.php.dist file into the config/config.inc.php file.
6. Starting a database.

**Step 2**
1. Starting the database -> mysql
2. Creating a database -> create database dvwa;
3. Creating a user with password -> create user dvwa@localhost identified by 'p@ssw0rd';
4. Grant the user access -> grant all on dvwa.* to dvwa@localhost;
5. Flush the user privileges -> flush privileges;

**Step 3**
1. Change the database -> use dvwa

**Step 4**
Launching the DVWA login page.

**Step 5**
Successfully logged in to the DVWA website.
