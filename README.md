## Admin

username: edgaraspraktika@gmail.com

password: praktika123

### Prerequisites

Composer

Node

XAMPP (apache, mysql, php 7.3)


### Installing

```
cd server
```

```$xslt
composer install
```

```$xslt
cp .env.example .env
```

```$xslt
php artisan key:generate
```

```$xslt
php artisan migrate
```
```$xslt
php artisan db:seed
```

```$xslt
php artisan serve
```
