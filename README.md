# Symfony 6 email

<img src="https://jorgebenitezlopez.com/github/symfony.jpg">
<img src="https://img.shields.io/static/v1?label=PHP&message=Symfony&color=green">

# Requisitos

- Symfony CLI: https://symfony.com/download
- PHP 8.3.0: https://www.php.net/manual/en/install.php
- Composer: https://getcomposer.org/download/
- Symfony 6.4: https://symfony.com/releases/6.4

# Instalación de Symfony y paquetes

- symfony new symfony-6-email --version=6.4
- cd symfony-6-email
- composer require symfony/mailer
- composer require symfony/maker-bundle --dev
- Hago controlador php bin/console make:controller email
- Añador en el .env el email
- Creo el servicio
- Lo importo en el controlador y uso el servicio para enviar un email.