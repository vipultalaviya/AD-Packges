# 📦 Box Packaging Laravel Web Application

A Laravel-based web application for custom box packaging orders. This platform allows customers to browse box types, customize packaging, place orders, and track their status — ideal for packaging businesses offering custom printed or plain box solutions.

# 🚀 Features

* Browse and filter various box types
* Custom dimension & print input
* Quote request and order submission
* Order management
* Admin dashboard to manage products and orders
* User authentication & profile management
* Responsive design

# ⚙️ Installation

* **Clone the repository** <br>
    git clone https://github.com/vipultalaviya/AD-Packges <br>
    cd AD-Packges

* **Install dependencies** <br>
     composer install

* **Copy .env and generate app key** <br>
     cp .env.example .env <br>
     php artisan key:generate

* **Configure .env** <br>
    Update the following fields in your .env file: <br>
    DB_DATABASE=your_db_name <br>
    DB_USERNAME=your_db_user <br>
    DB_PASSWORD=your_db_password
     
* **Run migrations and seed database** <br>
    Make sure your database is created before running migrations.<br>
    php artisan migrate --seed
   
* **Serve the application** <br>
    php artisan serve <br>
    The app will be available at: http://localhost:8000

# 🔧 Common Artisan Commands
| Task                     | Command                            |
| ------------------------ | ---------------------------------- |
| Generate application key | `php artisan key:generate`         |
| Run database migrations  | `php artisan migrate`              |
| Rollback last migration  | `php artisan migrate:rollback`     |
| Seed database            | `php artisan db:seed`              |
| Serve app on localhost   | `php artisan serve`                |
| Clear application cache  | `php artisan cache:clear`          |
| Clear config cache       | `php artisan config:clear`         |
| Clear route cache        | `php artisan route:clear`          |
| Create controller        | `php artisan make:controller Name` |
| Create model             | `php artisan make:model Name`      |
| Create migration         | `php artisan make:migration Name`  |



