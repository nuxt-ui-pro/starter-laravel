# Laravel Starter Template

[![Nuxt UI Pro](https://img.shields.io/badge/Made%20with-Nuxt%20UI%20Pro-00DC82?logo=nuxt&labelColor=020420)](https://ui.nuxt.com/pro)

This Laravel starter is based on [laravel/vue-starter-kit](https://github.com/laravel/vue-starter-kit) and demonstrate how to use [Nuxt UI Pro](https://ui.nuxt.com/pro) in a [Laravel](https://laravel.com/) application using [Inertia.js](https://inertiajs.com/).

- [Documentation](https://ui.nuxt.com/getting-started/installation/pro/vue)

## Setup

Make sure to install the dependencies:

```bash
pnpm install
```

Copy the example environment file to create your .env file:

```bash
cp .env.example .env
```

Generate a new application key for your Laravel application:

```bash
php artisan key:generate
```

Set up your database by running the migrations:

```bash
php artisan migrate
```

## Development Server

Start the development server on `http://localhost:8000`:

```bash
composer run dev
```
