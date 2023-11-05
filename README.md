
# E-commerce Website 

Welcome to our E-commerce website built using Laravel. This project is designed to provide a comprehensive platform for online shopping and managing transactions. 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Admin Panel](#admin-panel)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This E-commerce website is developed using the Laravel framework to provide a robust and scalable platform for online shopping. It comes equipped with various features and functionalities to support both users and administrators.

## Features

- User authentication and authorization
- Product browsing and search functionality
- Shopping cart and checkout system
- Order management and tracking
- Admin panel for managing products, orders, and users

## Installation

To set up the E-commerce website on your local machine, follow these steps:

1. **Clone the repository:**
   ```
   git clone https://github.com/mabuya02/Ecommerce-platform.git
   cd e-commerce-laravel
   ```

2. **Install dependencies:**
   ```
   composer install
   ```

3. **Configure environment:**
   - Duplicate `.env.example` file and name it as `.env`.
   - Set your database credentials and other environment-specific configurations in the `.env` file.

4. **Generate application key:**
   ```
   php artisan key:generate
   ```

5. **Run database migrations and seed data:**
   ```
   php artisan migrate
   php artisan db:seed
   ```

6. **Setup file storage:**
   ```
   php artisan storage:link
   ```

7. **Start the development server:**
   ```
   php artisan serve
   ```

## Usage

Once the server is running, open your web browser and navigate to `http://localhost:8000` to access the E-commerce website. You can browse products, add them to the cart, and proceed with the checkout process.

## Admin Panel

To access the admin panel:

- Admin Panel URL: `http://localhost:8000/admin`
- Admin Email/Password: `admin@gmail.com/1111`
- User Email/Password: `user@gmail.com/1111`

The admin panel allows you to manage products, orders, and users efficiently.

## Contributing

We welcome contributions from the community. If you'd like to contribute to this project, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE). You are free to modify and distribute the code as per the terms of the license.

Happy shopping with our E-commerce website built in Laravel!
```
