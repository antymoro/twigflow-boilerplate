# Twigflow Starter Theme

This is a starter theme with a basic Twig and `index.php` setup. It provides a foundation for building PHP applications with Twig templating.

## Requirements

This starter theme requires the [Twigflow Boilerplate](https://github.com/huncwotdigital/twigflow-boilerplate) to work. Make sure to clone or download the boilerplate and follow its setup instructions.

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/huncwotdigital/twigflow-boilerplate.git
    ```

2. Navigate to the project directory:
    ```sh
    cd twigflow-boilerplate
    ```

3. Install TwigFlow using Composer:
    ```sh
   composer require antymoro/twigflow:dev-main --prefer-stable
    ```

4. Copy the starter theme files into the appropriate directories within the boilerplate.

5. Run the application:
    ```sh
    php -S localhost:8000 -t public
    ```

6. Open your browser and navigate to `http://localhost:8000` to see the starter theme in action.

## Features

- Basic Twig templating setup
-  configured with essential middleware and routing
- Ready to extend and customize for your project needs

## License

This project is licensed under the MIT License.