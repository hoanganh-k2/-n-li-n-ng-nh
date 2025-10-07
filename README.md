![Hollux](https://i.postimg.cc/SKm6ZkSy/Screenshot-1355.png)

# Hollux

Hollux is a hotel website that can be used for online reservations. Built using the [TALL Stack](https://tallstack.dev/): [Tailwind CSS 3](https://tailwindcss.com/), [AlpineJS 3](https://alpinejs.dev/), [Livewire 2](https://laravel-livewire.com/), [Laravel 9](https://laravel.com/). I actually made the UI here myself using Tailwind CSS and AplineJS without using any templates at all.

## Roles

There are 3 roles in this application, namely admin, receptionist, and user or guest.

### Admin

![Admin Dashboard](https://i.postimg.cc/FsZCNWYs/Screenshot-1363.png)

Admin can manage room data, facilities, and manage galleries that will be displayed to users or guests.

### Receptionist

![Receptionist Dashboard](https://i.postimg.cc/wxs3CZbL/Screenshot-1365.png)

The receptionist can check the check-in or check-out data from the user or guest and confirm it.

### User

![User Dashboard](https://i.postimg.cc/PqttNF43/Screenshot-1364.png)

The user here is a guest for this Hollux hotel. Users can make online reservations and review facilities and rooms if desired.

## Feature

- Doing room CRUD (Finished)
- Doing facility CRUD (Finished)
- Doing gallery CRUD (Finished)
- Doing user CRUD (Finished)
- Updating the about page via the admin dashboard (Finished)
- Make a reservation (Finished)
- Check reservation data (Finished)
- Do a review (Finished)
- Profile & Setting (Not finished yet)

## 🛠 Cài đặt & Khởi chạy

### 📌 1. Clone repository

```sh
git clone https://github.com/hoanganh-k2/DALN.git
cd ...
```

### 📌 2. Cấu hình môi trường

```sh
cp .env.example .env

```

🎡 Cập nhật file `.env` với thông tin database của bạn.

### 📌 3. Cài đặt các dependencies

```sh
composer install
php artisan key:generate

```



### 📌 4. Cập nhật file .env với thông tin database của bạn:

```sh

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=ten_database
DB_USERNAME=root
DB_PASSWORD=your_password


```

### 📌 5. Tạo database từ seeder

```sh

php artisan migrate --seed

```
### 📌 6. Chạy ứng dụng

```sh
php artisan serve
```

---