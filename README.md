# PHP Native Template

This is a simple PHP native template project with a basic MVC (Model-View-Controller) structure. It is designed to be a starting point for building PHP applications without any frameworks.

## Project Structure

```bash
app/
├── App/
│   ├── Config.php         # Application configuration
│   ├── Database.php       # Database connection handling
│   ├── Router.php         # Routing logic
│   └── View.php           # View rendering logic
├── Controller/
│   └── HomeController.php # Controller for handling home page requests
├── Middleware/
│   ├── AuthMiddleware.php # Middleware for authentication checks
│   └── Middleware.php     # Base middleware class
├── Models/
│   └── HomeModel.php      # Data model for the home page
├── View/
│   └── interface/
│       └── home.php       # View template for the home page
public/
├── index.php              # Entry point for the application
vendor/                    # Composer dependencies (auto-generated)
composer.json              # Composer configuration file
composer.lock              # Locked versions of installed dependencies
```

## Features

- **MVC Structure**: Organized with Models, Views, and Controllers.
- **Routing System**: A simple routing mechanism to handle requests.
- **Middleware Support**: Includes basic middleware for authentication and other checks.
- **Database Connection**: Contains a basic database connection class.

## Requirements

- PHP 7.4 or higher
- Composer (for dependency management)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Chandra2004/native-template.git
   ```

2. Install dependencies using Composer:

   ```bash
   composer install
   ```

3. Configure your environment variables or update `Config.php` for database settings.

4. Run the application by starting a local server:

   ```bash
   php -S localhost:8000 -t public
   ```

5. Open your browser and go to `http://localhost:8000` to view the application.

## Usage

- Controllers are located in the `app/Controller` directory. Add new controllers as needed.
- Views are stored in the `app/View/interface` directory. Create additional view templates here.
- The routing system is defined in `app/Router.php`. Modify it to add new routes for your application.

If you have any questions or need further assistance, feel free to reach out to me:

## Social Media
- **Instagram**: [@chandratriantomo.2077](https://www.instagram.com/chandratriantomo.2077)
- **WhatsApp**: [085730676143](https://wa.me/6285730676143)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
