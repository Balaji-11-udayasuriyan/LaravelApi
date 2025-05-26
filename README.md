# Laravel External User API Integration
## task4

This project integrates a third-party API (https://jsonplaceholder.typicode.com/users) to fetch and manage external users in a Laravel app.

## Features

- Fetch user data from JSONPlaceholder API
- Display user list with name, email, and address
- Search users by name
- Handle API fetch errors
- Store users in database
- Sync periodically using Laravel Scheduler


## Installation

Follow these steps to install and run the Laravel project locally:

1. Clone the repository and navigate into it:
   git clone https://github.com/balaji-11-udayasuriyan/LaravelApi
   cd LaravelApi

2. Install PHP dependencies using Composer:
   composer install

3. Setup environment configuration:
   cp .env.example .env
   Then open the .env file and update your database credentials and other settings as needed.
4. store the api into the database
   php artisan fetch:api-users


6. Generate application key:
   php artisan key:generate

7. Run database migrations:
   php artisan migrate

8. Start the development server:
   php artisan serve

9. Access the app:
   Open your browser and visit http://localhost:8000
