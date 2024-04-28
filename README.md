<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

1.Перечислите список composer-пакетов, которые использует фреймворк Laravel после установки.
"require-dev": {
        "fakerphp/faker": "^1.23",
        "laravel/pint": "^1.13",
        "laravel/sail": "^1.26",
        "mockery/mockery": "^1.6",
        "nunomaduro/collision": "^8.0",
        "phpunit/phpunit": "^11.0.1",
        "spatie/laravel-ignition": "^2.4"
    },
2.Изучите директорию config и опишите какие файлы хранятся в этой директории.
1. **app.php**: Основной файл конфигурации приложения Laravel.
2. **database.php**: Конфигурация базы данных.
3. **mail.php**: Конфигурация для отправки почты.
4. **queue.php**: Конфигурация очередей.
5. **filesystems.php**: Конфигурация для работы с файловой системой.
6. **cache.php**: Конфигурация кэширования.
7. **session.php**: Конфигурация сессий.
8. **auth.php**: Конфигурация аутентификации.
9. **services.php**: Конфигурация сторонних сервисов.
10. **logger.php**: Конфигурация для логгирования.
3.В какой директории хранятся основные файлы (классы) с бизнес-логикой приложения?
**app**
