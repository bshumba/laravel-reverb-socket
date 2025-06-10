<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Simple Reverb App

This is a simple Laravel Reverb app created for reference purposes. It demonstrates how to use Laravel Reverb for real-time broadcasting using WebSockets.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd <your-project-folder>
2. Copy the example environment file and set up your environment:
    ```bash
    Copy
    Edit
    cp .env.example .env
3. Install PHP dependencies:
    ```bash
    Copy
    Edit
    composer install
4. Generate the application key:
    ```bash
    Copy
    Edit
    php artisan key:generate
5. (Optional) Configure your database by updating the .env file if needed.

# Running the Application
## In separate terminal windows/tabs, run the following commands:

1. Start the Laravel development server:
    ```bash
    Copy
    Edit
    php artisan serve
2. Start the Vite dev server (for frontend assets):
    ```bash
    Copy
    Edit
    npm run dev
3. Start the Laravel Reverb WebSocket server:
    ```bash
    Copy
    Edit
    php artisan reverb:start
    Start the queue worker:

    bash
    Copy
    Edit
    php artisan queue:work
