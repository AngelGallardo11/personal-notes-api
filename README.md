# personal-notes-api

This project is a Laravel application for managing personal notes via a RESTful API. It allows users to create, read, update, and delete notes. Each note contains a title, author, date and time, body, and classification.

## Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/personal-notes-api.git
cd personal-notes-api

## Setup Instructions
1. Clone the repository:
```bash
git clone https://github.com/yourusername/personal-notes-api.git
cd personal-notes-api
```
2. Install dependencies:
```bash
composer install
```
3. Set up environment variables:
Create a `.env` file in the root directory and add:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```
4. Run the migrations:
```bash
php artisan migrate
```
5. Start the server:
```bash
php artisan serve
```
The server will run at: `http://localhost:8000`
