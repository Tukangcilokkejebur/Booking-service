Cara Menjalankan 

Bisa Clone Project Dengan cara

```bash
  git clone https://github.com/Tukangcilokkejebur/Booking-service
```
Ke direktori project

```bash
  cd Booking-service
```

-   Edit database di env.example atau hapus example (sesuaikan dengan database di sql )

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

#### Login

-   email = admin@example.com
-   password = 123
