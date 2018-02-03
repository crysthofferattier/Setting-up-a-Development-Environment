# Setting up a Development Environment
Setting up a web/mobile development environment in a Linux distribution.

## Getting Started
[Ubuntu](https://www.ubuntu.com/download/desktop) - Ubuntu 16.04.1 LTS

### Prerequisites
* Basic command line knowledge in Linux
* Internet connection

## Built With

* [NodeJS](https://nodejs.org/en/about/) - NodeJS 8.x LTS
* [PHP](https://secure.php.net/) - PHP 7.0
* [Java](https://www.java.com/pt_BR/) - Java 9
* [Composer](https://getcomposer.org/) - Dependency Manager for PHP
* [NPM](https://www.npmjs.com/) - Package manager for JavaScript
* [Git](https://git-scm.com/) - Version control system 


## Installation Guide
This installation guide provides instructions on how to manually install and configure software on a web server.

### PHP 7.0

```
$ sudo apt-get install php7.0
```

### Java 9

```
$ sudo add-apt-repository ppa:webupd8team/java
$ sudo apt-get install oracle-java9-installe
$ sudo apt-get install oracle-java9-set-default
```

### MySQL

```
$ sudo apt-get install mysql-server
$ mysql_secure_installation
```


### NodeJS

NodeJS installation guide [link](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions)

```
$ curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
$ sudo apt-get install -y nodejs
$ sudo apt-get install -y build-essential
```

### Composer

Composer installation guide [link](https://getcomposer.org/download/)

```
$ php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
$ php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
$ php composer-setup.php
$ php -r "unlink('composer-setup.php');"
$ mv composer.phar /usr/local/bin/composer
```

### Git

Git installation guide [link](https://getcomposer.org/download/)

```
$ php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
$ php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
$ php composer-setup.php
$ php -r "unlink('composer-setup.php');"
$ mv composer.phar /usr/local/bin/composer
```


## Authors

* **Crysthoffer Amira Ratier** - *Initial work* - ![Linkedin](https://www.linkedin.com/in/crysthofferatier/)
