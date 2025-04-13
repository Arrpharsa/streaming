# Anime Streaming Website

## Overview
This project is an anime streaming website built with Laravel. It allows users to browse and watch various anime series and movies. The website features an attractive design and user-friendly interface.

## Features
- Browse a list of anime titles
- View detailed information about each anime
- Responsive design for optimal viewing on all devices
- Easy navigation between different sections of the website

## Technologies Used
- Laravel (PHP Framework)
- Blade (Laravel's templating engine)
- MySQL (Database)
- CSS (Styling)
- JavaScript (Interactivity)

## Installation

### Prerequisites
- PHP >= 7.3
- Composer
- Node.js and npm
- MySQL

### Steps
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/anime-streaming-website.git
   cd anime-streaming-website
   ```

2. Install dependencies:
   ```
   composer install
   npm install
   ```

3. Set up the environment file:
   ```
   cp .env.example .env
   ```

4. Generate the application key:
   ```
   php artisan key:generate
   ```

5. Set up your database configuration in the `.env` file.

6. Run migrations to create the database tables:
   ```
   php artisan migrate
   ```

7. Seed the database with sample data:
   ```
   php artisan db:seed --class=AnimeSeeder
   ```

8. Compile the assets:
   ```
   npm run dev
   ```

9. Start the development server:
   ```
   php artisan serve
   ```

10. Visit `http://localhost:8000` in your web browser.

## Usage
- Navigate to the homepage to see featured anime.
- Use the navigation menu to browse different categories.
- Click on an anime title to view its details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.