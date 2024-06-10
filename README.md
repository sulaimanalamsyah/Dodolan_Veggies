# Laravel 9 & PHP 8 - Aplikasi E-Commerce (Dodolan Veggies)

## Sumber

Aplikasi ini terinspirasi dari :

```bash
  https://github.com/abdulaziz-m5u/ecommerce-youtube.git
```

## Langkah Clone

Clone Projek

```bash
  git clone https://github.com/andhanuprakoso/ecommerce nama-projek
```

Menuju Folder Clone

```bash
  cd nama-projek
```

-   Salin .env.example file ke folder nama-projek dengan nama file .env dan edit kebutuhan database disini

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

#### Informasi Login Admin

-   email = admin@example.com
-   password = 123

#### Pemrograman Web II

- Projek ini bertujuan untuk memenuhi kebutuhan projek tugas dari mata kuliah Pemrograman Web II
- Projek ini mengambil inspirasi dari ecommerce-youtube milik Abdul Aziz
