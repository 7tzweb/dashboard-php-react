# About

This project is a Full Stack Task manager built with ReactJS & LARAVEL

# Testing
You can create a new account or logIn using these credentials:
email: tsohar@gmail.com
password:12345678

## Features

- Login & Register using jwt_token
- Simple CRUD on Tasks (for the connected user)
- Simple three card show counts of Active, onGoing and Done Tasks

## Technologies Used

### Front-end
- JavaScript
- ReactJS
- Context
- HTML
- CSS
- react-router
- axios
- styled-components
- react-toastify

### Back-end
- LARAVEL
- jwt-auth



## Getting Started

To get started with this project, clone the repository to your local machine and install the dependencies for both FRONT and BACK:

git clone 

### install front-end

 ```cd task_manager_front ```
 ```npm install```


Once the dependencies are installed, start the development server
Ps: change the `baseURL` in utils/constants to your laravel endpoint (when you run it)

### install back-end

Before you begin, ensure you have met the following requirements:


Before you begin, ensure you have met the following requirements:

-   **PHP:** Your server should have PHP installed. You can download it from [php.net](https://www.php.net/).

-   **Composer:** Make sure you have Composer installed on your system. If not, you can download it from [getcomposer.org](https://getcomposer.org/).

-   **MySQL Database:** You need a MySQL database to run this project. If you don't have MySQL installed, you can download it from [MySQL Downloads](https://dev.mysql.com/downloads/).

-   **Web Server:** You can use Apache or Nginx as your web server to host the Laravel application.

Then Follow these steps to set up and run the project locally:


1. Navigate to the project directory:

    ```bash
    cd task_manager_back
    ```

3. Install project dependencies

    ```bash
    composer install
    ```

4. Create a .env File::
    ```bash
    cp .env.example .env
    ```
5. Update .env file (db Connection etc..)
    -   [You can use my Existing tables](https://github.com/OthmanSemlali/full-stack-task-manager/blob/main/task_manager.sql).

6. Generate the application key:
    ```bash
    php artisan key:generate
    ```
7. Generate JWT Secret Key:
    ```bash
    php artisan jwt:secret
    ```
8. Clear Configuration Cache::
    ```bash
    php artisan config:cache
    ```

9.Start dev server
    ```
    php artisan serve
    ```

10. start frontend 
 ```cd task_manager_front ```
 ```npm install```
