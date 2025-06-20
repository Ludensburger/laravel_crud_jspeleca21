# Laravel 11 CRUD Application with Authentication

A simple CRUD (Create, Read, Update, Delete) application built with Laravel 11, featuring user authentication and product management.

## Features

- User Authentication (Username-based)
    - Register
    - Login
    - Logout

- Product Management
    - Create new products
    - View product listings
    - Update existing products
    - Delete products
    - Image upload functionality

- Bootstrap-based UI
- Form validation
- Flash messages for operations

## Technical Stack

- PHP 8.x
- Laravel 11
- MySQL
- Bootstrap 5
- HTML/CSS


## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ludensburger/laravel_crud_jspeleca21
   cd https://github.com/Ludensburger/laravel_crud_jspeleca21


2. **Install dependencies**

   ```bash
   composer install
   ```

3. **Create and configure `.env` file**

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Set up your database in `.env`**
   Open the `.env` file and update the database configuration:

   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=laravel_11_crud
   DB_USERNAME=root
   DB_PASSWORD=root
   ```

5. **Create a symbolic link to storage**

   ```bash
   php artisan storage:link
   ```

6. **Run database migrations**

   ```bash
   php artisan migrate
   ```

7. **Start the development server**

   ```bash
   php artisan serve
   ```

## Usage

1. Register a new user account
2. Log in with your credentials
3. Use the navigation to:
     - View all products
     - Create new products
     - Edit existing products
     - Delete products
     - Upload product images

## Lab Activity Details

This project was created as a lab activity for Laravel basics, demonstrating:

- Basic Laravel MVC architecture
- Authentication system implementation
- CRUD operations
- File handling (image uploads)
- Database migrations
- Blade templating
- Form validation
- Route protection with middleware

## Credits

**Created by:** Ryu R. Mendoza  
**School:** University of San Jose - Recoletos
