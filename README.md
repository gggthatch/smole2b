# Laravel Polling/Survey Application

This is a web-based polling/survey application built with Laravel and MySQL. It allows users to create, distribute, and analyze surveys.

## Installation

1. Clone the repository
```
git clone https://github.com/yourusername/yourrepository.git
```
2. Install Composer dependencies
```
cd yourrepository
composer install
```
3. Install NPM dependencies
```
npm install
```
4. Create a copy of your .env file
```
cp .env.example .env
```
5. Generate an app encryption key
```
php artisan key:generate
```
6. Create an empty database for our application
7. In the .env file, add database information to allow Laravel to connect to the database
8. Migrate the database
```
php artisan migrate
```
9. Seed the database
```
php artisan db:seed
```
10. Run the project
```
php artisan serve
```

## Features

- User Authentication
- Dashboard
- Survey Creation
- Survey Distribution
- Survey Responses
- Analytics
- Settings & Integrations

## Testing

Run the tests with:

```
vendor/bin/phpunit
```

## Security

The application follows best practices for data encryption, regular security audits, rate limiting, DDoS protection, and GDPR compliance.

## Future Enhancements

- Mobile application (iOS & Android)
- Advanced analytics with AI-driven insights
- Integration with more third-party apps
- Multilingual support

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)