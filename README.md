# Computer Setup Guide

---
### [Xcode](https://developer.apple.com/xcode/download/):
- Install [Xcode](https://developer.apple.com/xcode/download/) – this needs to be installed for terminal/CLI stuff


### [Homebrew](http://brew.sh/):
Install [Homebrew](http://brew.sh/)
- Install php 5.6: ```brew install homebrew/php/php56```


### AWS CLIs:

- Install [```awscli```](http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-set-up.html)  
- Install [```ebcli```](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html)
 

### [ChefDK](https://downloads.chef.io/chef-dk/mac/):
- Install [```chefDK```](https://downloads.chef.io/chef-dk/mac/) – only do this for Chef development


### [Composer](https://getcomposer.org/):

- Install [```composer```](https://getcomposer.org/):

- ```sh
  coreyshelton ~$ php -r "readfile('https://getcomposer.org/installer');" > composer-setup.php
  coreyshelton ~$ php -r "if (hash_file('SHA384', 'composer-setup.php') === '7228c001f88bee97506740ef0888240bd8a760b046ee16db8f4095c0d8d525f2367663f22a46b48d072c816e7fe19959') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
  coreyshelton ~$ php composer-setup.php
  coreyshelton ~$ php -r "unlink('composer-setup.php');"
  coreyshelton ~$ mv composer.phar /usr/local/bin/composer
  coreyshelton ~$ composer --version
  ```

  If the ```composer —version``` doesn’t work then you may need to create an alias via:

  ```sh
  coreyshelton ~$ alias composer='/usr/local/bin/composer.phar'
  coreyshelton ~$ composer --version
  ```

### [MySQL Workbench](http://dev.mysql.com/downloads/workbench/):
- Go to http://dev.mysql.com/downloads/workbench/


### [Postman](https://www.getpostman.com/):
- Go to https://www.getpostman.com/


### [CyberDuck](https://cyberduck.io/?l=en):
- Go to https://cyberduck.io/?l=en


### [Atom](https://atom.io/):
- Go to https://atom.io/


### [FileZilla](https://filezilla-project.org/):
- Go to https://filezilla-project.org/


### [Sequel Pro](http://www.sequelpro.com/):
- Go to http://www.sequelpro.com/
