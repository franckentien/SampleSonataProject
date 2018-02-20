# SampleSonata

## Presentation

This project is the most basic project with Sonata Bundle in Symfony 3.4 

I create a new project and import some of sonata Bundle 

## Bundle installed

```
sonata-project/admin-bundle              The missing Symfony Admin Generator
sonata-project/block-bundle              Symfony SonataBlockBundle
sonata-project/cache                     Cache library
sonata-project/classification-bundle     Symfony SonataClassificationBundle
sonata-project/core-bundle               Symfony SonataCoreBundle
sonata-project/datagrid-bundle           Symfony SonataDatagridBundle
sonata-project/doctrine-extensions       Doctrine2 behavioral extensions
sonata-project/doctrine-orm-admin-bundle Symfony Sonata / Integrate Doctrine ORM into the SonataAdminBundle
sonata-project/easy-extends-bundle       Symfony SonataEasyExtendsBundle
sonata-project/exporter                  Lightweight Exporter library
sonata-project/formatter-bundle          Symfony SonataFormatterBundle
sonata-project/intl-bundle               Symfony SonataIntlBundle
sonata-project/media-bundle              Symfony SonataMediaBundle
sonata-project/news-bundle               Symfony SonataNewsBundle
sonata-project/notification-bundle       Symfony SonataNotificationBundle
sonata-project/user-bundle               Symfony SonataUserBundle
```

## How to use 

- Import the project on your computer.

- Install the vendor with composer : `php .\composer.phar install`

- Create Database: `php bin/console doctrine:database:create`

- Generate Database : `php .\bin\console doctrine:schema:update --force`

- Create an Admin : `php bin/console fos:user:create --super-admin`

- Enjoy!

To use the sonata Bundle you need to go on `web/app_dev.php/admin` and login with the admin acount
