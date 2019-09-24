# ToDoList-Laravel
A sample task list application using Laravel


## Install composer in Windows

### There is two way to install Composer

- Install Composer **via command line without installer**
```
1. php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
2. php -r "if (hash_file('sha384', 'composer-setup.php') === '48e3236262b34d30969dca3c37281b3b4bbe3221bda826ac6a9a62d6444cdb0dcd0615698a5cbe587c3f0fe57a54d8f5') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
3. php composer-setup.php
4. php -r "unlink('composer-setup.php');"			
```	

- Install Composer **via window installer** 
```
Download installer from "https://getcomposer.org/download/"
```

## Install composer in Mac

```
$ curl -sS https://getcomposer.org/installer | php

$ chmod +x composer.phar

$ mv composer.phar /usr/local/bin/composer

$ composer

```


## Quick Installation

```
git clone https://github.com/thinei/ToDoList-Laravel.git

cd quickstart

composer install

php artisan migrate

php artisan serve

```
