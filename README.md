# PHP Learning

### DevStack

> OS: Fedora Linux  
> Language: PHP  
> Database:  
> Framework: Symfony, Foundation CSS  
> Code Editor: VSCode

### VSCode

> [VSCode](https://code.visualstudio.com/)

#### VSCode - Extentions

> [PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)  
> [PHP IntelliSense](https://marketplace.visualstudio.com/items?itemName=zobo.php-intellisense)  
> [PHP Debug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug)

### PHP on Fedora

> [FedoraProject](https://developer.fedoraproject.org/tech/languages/php/php-installation.html)

1. Install: PHP

```bash
sudo dnf install php-cli
```

2. Install: PHPUnit for unit tests or Composer to manage dependencies of PHP projects

```bash
sudo dnf install phpunit composer
```

3. Install: phpSQL

```bash
sudo dnf install php-mysqli
```

### Symfony Framework on Fedora

> [FedoraProject - PHP Symfony](https://developer.fedoraproject.org/start/sw/web-app/php-symfony.html)  
> [Symfont Docs](https://symfony.com/doc/current/setup.html)

1. Install: Symfony Framework

```bash
sudo dnf install php-symfony
```

2. Install: PHP Composer

> [Composer](https://getcomposer.org/download/)

```bash
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === 'dac665fdc30fdd8ec78b38b9800061b4150413ff2e3b6f88543c636f7cd84f6db9189d43a81e5503cda447da73c7e5b6') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
```

3. Install: Install Symfony CLI

```bash
curl -1sLf 'https://dl.cloudsmith.io/public/symfony/stable/setup.rpm.sh' | sudo -E bash

sudo dnf install symfony-cli
```

4. Star Symfony server in background or normal

```bash
symfony server:start
symfony server:start -d
```

### Foundation Framework

> [Foundation CSS](https://get.foundation/)

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/foundation-sites@6.8.1/dist/css/foundation.min.css"
  crossorigin="anonymous"
/>
<script src="https://cdn.jsdelivr.net/npm/foundation-sites@6.8.1/dist/js/foundation.min.js" crossorigin="anonymous"></script>
```
