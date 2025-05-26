# Book Store

A simple Book Store web application built with Laravel (PHP) and Vite. This project demonstrates a basic CRUD (Create, Read, Update, Delete) system for managing books and users.

---

## 📺 Demo Video

<div align="center">
  
[![Book Store Laravel Demo](https://github.com/noobdevsam/book-store-laravel-project/blob/master/resources/Screenshot2025-05-22.png)](https://youtu.be/MxATPW3Ew_E?feature=shared)

</div>

> _Click the image above to watch the demo on YouTube!_


---

## Features
- User authentication (register, login, logout)
- Book management (add, edit, delete, list books)
- Database migrations and seeders
- RESTful controllers
- Blade templating for views
- Modern frontend tooling with Vite

## Project Structure
- `app/Models/` — Eloquent models for Book and User
- `app/Http/Controllers/` — Controllers for handling web requests
- `database/migrations/` — Database schema migrations
- `database/seeders/` — Seeders for populating the database
- `resources/views/` — Blade templates for UI
- `public/` — Public assets and entry point
- `routes/web.php` — Web routes
- `config/` — Application configuration
- `tests/` — Pest and PHPUnit tests

## Getting Started

### Prerequisites
- PHP >= 8.1
- Composer
- Node.js & npm

### Installation
1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd book-store
   ```
2. Install PHP dependencies:
   ```sh
   composer install
   ```
3. Install Node.js dependencies:
   ```sh
   npm install
   ```
4. Copy the example environment file and set your configuration:
   ```sh
   cp .env.example .env
   php artisan key:generate
   ```
5. Run database migrations and seeders:
   ```sh
   php artisan migrate --seed
   ```
6. Start the development server:
   ```sh
   php artisan serve
   ```
7. In a separate terminal, start Vite for frontend assets:
   ```sh
   npm run dev
   ```

Visit [http://localhost:8000](http://localhost:8000) to view the application.

## Testing
Run tests with:
```sh
php artisan test
```
Or using Pest:
```sh
./vendor/bin/pest
```

## License
This project is open-source and available under the [MIT license](LICENSE).
