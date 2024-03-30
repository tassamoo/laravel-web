### Installing laravel

1. Install php 8.3
```bash
sudo apt install php8.3 php-xml php-curl
```

2. Install Composer
```bash
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === 'dac665fdc30fdd8ec78b38b9800061b4150413ff2e3b6f88543c636f7cd84f6db9189d43a81e5503cda447da73c7e5b6') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```

3. Install node.js
```bash
# installs NVM (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
# download and install Node.js
nvm install 21
# verifies the right Node.js version is in the environment
node -v # should print `v21.7.1`
# verifies the right NPM version is in the environment
npm -v # should print `10.5.0`
```

4. Install mysql & phpmyadmin
```bash
https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-phpmyadmin-on-ubuntu-22-04
```

5. Install php extension
```bash
sudo apt-get install php-mcrypt php-openssl php-mbstring php-tokenizer php-zip php-xml
```


