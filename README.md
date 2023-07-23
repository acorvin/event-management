# Event Management App

A REST API to handle an event management application. The API will offer the ability to create, update, and delete events based on user authentication. Once authenticated, users can easily manage their events, schedule tasks, and also receive essential email notification on upcoming.

## Features

-   User Registration: Create new user accounts.
-   User Authentication: Securely authenticate users for access to their account.
-   Event Management: Enable users to manage their events efficiently.
-   Task Scheduling: Schedule tasks related to events.
-   Email Notifications: Send essential email notifications to users.

## Prerequisites

-   PHP (>= 7.4)
-   Composer (https://getcomposer.org/)
-   MySQL database
-   Laravel (https://laravel.com/)

## Installation

-   Clone the repository

```
git clone https://github.com/acorvin/event-management.git
```

-   Navigate to the project directory

```
cd event-management
```

-   Install Composer Dependencies

```
composer install

```

-   Generate an app encryption key

```
php artisan key:generate
```

-   Create a new MySQL database for the application
-   Configure the .env file with your database connection details
-   Migrate and seed the database

```
php artisan migrate --seed
```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request. Follow the contribution guidelines for more information.

## License

This project is licensed under the [MIT license](https://opensource.org/licenses/MIT). Feel free to use, modify, and distribute it as per the terms of the license.
