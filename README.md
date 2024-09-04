# 🎉 DEMO Laravel Breeze Log Viewer

Laravel Breeze is a lightweight, minimalistic starter kit for Laravel, providing pre-built authentication scaffolding, views, and controllers to help developers quickly set up user registration, login, and password reset functionality in their Laravel applications.

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### 🚀 Setup

- Create Project

```shell
composer create-project laravel/laravel example-app
```

- Install Package

```shell
composer require opcodesio/log-viewer
```

- Configure Environment

```shell
cp .env.example .env
```

- Vendor Publish

```shell
php artisan vendor:publish --tag=log-viewer-config
```

- Migrate

```shell
php artisan migrate
```

### 🏆 Run

- [http://localhost:8000/log-viewer](http://localhost:8000/log-viewer) username : `admin` password : `admin`

```shell
php artisan serve
```
