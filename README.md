# Online Food Ordering System

Welcome to the Online Food Ordering System, a web-based application that allows users to browse restaurants, select dishes from their menus, and place orders. The system also provides administrative capabilities for adding and removing restaurants and managing menus.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Technologies Used](#technologies-used)
- [License](#license)

## Features

1. **User Interface:**
   - Browse a list of restaurants.
   - View restaurant details, including available menus.
   - Select dishes and place orders.

2. **Admin Panel:**
   - Add new restaurants to the system.
   - Remove existing restaurants.
   - Manage restaurant menus.

## Installation

To set up the Online Food Ordering System locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/JoyNgaru/online-food-ordering-system.git
    ```

2. Set up the database:
    - Import the provided SQL file (`database.sql`) into your MySQL database.

3. Configure the database connection:
    - Open `config/config.php` and update the database credentials accordingly.

4. Start the development server:
    - You can use PHP's built-in server:
        ```bash
        php -S localhost:8000
        ```
        Visit `http://localhost:8000` in your browser.

## Usage

1. **User:**
   - Visit the application.
   - Browse restaurants and their menus.
   - Select desired dishes and place an order.

2. **Admin:**
   - Access the admin panel at `http://localhost:8000/admin`.
   - Log in using the provided credentials.
   - Add new restaurants, remove existing ones, and manage menus.

## Contributors

- [Joy Ng'aru](https://github.com/JoyNgaru) - Front End Software Engineer
- [Joram Oloo](https://github.com/Joram21) - Backend Software Engineer

Feel free to contribute by submitting issues or pull requests!

## Technologies Used

- PHP
- MySQL
- CSS
- JavaScript

## License

This project is licensed under the [MIT License](LICENSE).

Thank you for using the Online Food Ordering System! If you encounter any issues or have suggestions, please feel free to open an [issue](https://github.com/JoyNgaru/online-food-ordering-system/issues).
