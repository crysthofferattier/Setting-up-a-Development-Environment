# Setting up a Development Environment
Setting up a web/mobile development environment in a Linux distribution.

## Getting Started
[Ubuntu](https://www.ubuntu.com/download/desktop) - Ubuntu 16.04.1 LTS

### Prerequisites
* Basic command line knowledge in Linux
* Internet connection

## Built With

* [Java](https://www.java.com/pt_BR/) - Java SE Development Kit 9
* [PHP](https://secure.php.net/) - PHP 7.0
* [NodeJS](https://nodejs.org/en/about/) - NodeJS 8.x LTS
* [Composer](https://getcomposer.org/) - Dependency Manager for PHP
* [MySql](https://www.mysql.com/) - MySql server
* [NPM](https://www.npmjs.com/) - Package manager for JavaScript
* [Git](https://git-scm.com/) - Version control system
* [Sublime Text](https://www.sublimetext.com/) - Sublime Text is a sophisticated text editor for code, markup and prose
* [PhpStorm](https://www.jetbrains.com/phpstorm/) - IDE for PHP development
* [Eclipse](http://www.eclipse.org/downloads/packages/eclipse-ide-java-ee-developers/oxygen2) - IDE for Java development

## Installation Guide
This installation guide provides instructions on how to manually install and configure software on a web server.

### Java 9

```
$ sudo add-apt-repository ppa:webupd8team/java
$ sudo apt-get install oracle-java9-installer
$ sudo apt-get install oracle-java9-set-default
```

### PHP 7.0

```
$ sudo apt-get install php7.0
```

### NodeJS 8.9.4

NodeJS installation guide [link](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions)

```
$ curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
$ sudo apt-get install -y nodejs
$ sudo apt-get install -y build-essential
```

### Composer 1.6.3

Composer installation guide [link](https://getcomposer.org/download/)

```
$ php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
$ php -r "if (hash_file('SHA384', 'composer-setup.php') === '544e09ee996cdf60ece3804abc52599c22b1f40f4323403c44d44fdfdd586475ca9813a858088ffbc1f233e9b180f061') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
$ php composer-setup.php
$ php -r "unlink('composer-setup.php');"
$ mv composer.phar /usr/local/bin/composer
```


### MySQL 5.7.21

```
$ sudo apt-get install mysql-server
$ mysql_secure_installation
```

### Git 2.7.4

Git installation guide [link](https://git-scm.com/download/linux)

```
$ sudo apt-get install git
```

### Sublime Text 3

Git installation guide [link](https://git-scm.com/download/linux)

```
$ wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
$ sudo apt-get install apt-transport-https
$ echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
$ sudo apt-get update
$ sudo apt-get install sublime-text
```


## Authors

* **Crysthoffer Amira Ratier** - *Initial work* - ![Linkedin](https://www.linkedin.com/in/crysthofferatier/)
