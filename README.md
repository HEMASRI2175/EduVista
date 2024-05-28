### EduVista README

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About EduVista

EduVista is a comprehensive e-learning platform designed to bridge the digital divide by providing equitable access to quality education for students, regardless of their geographical location or socioeconomic status. Leveraging modern technology, EduVista ensures that every student has the opportunity to access high-quality educational resources and career guidance.

## Features

- **Universal Accessibility:** Accessible from any device with an internet connection, optimized for mobile use.
- **Affordable Learning Resources:** Offers free and affordable courses, scholarships, and financial aid.
- **Localized and Multilingual Content:** Provides content in multiple languages and tailored to specific regional needs.
- **Interactive Learning:** Includes interactive modules, quizzes, and real-time feedback.
- **Career Guidance:** Collaborates with companies to provide job listings, industry insights, and mentorship programs.
- **Community Support:** Fosters a community of learners for peer-to-peer learning and support.

## Technologies Used

### Frontend Technologies

- **Vue.js:** For building dynamic and responsive user interfaces.
- **Vue Router:** For client-side routing and navigation.
- **Axios:** For making HTTP requests to backend APIs.
- **Tailwind CSS:** For modern and flexible styling.

### Backend Technologies

- **PHP:** Core scripting language for server-side logic.
- **Laravel:** Framework for server-side logic and API development.
- **MySQL:** Database management and data storage.
- **Redis:** Caching and enhancing performance.
- **Laravel Passport:** Secure API authentication.
- **Docker:** Containerization for consistency across environments.

### Middleware Technologies

- **Laravel Middleware:** Handling HTTP requests and responses efficiently.
- **Custom Middleware:** For frontend request validation and user activity tracking.
- **Laravel Echo and Pusher:** Real-time communication and notifications.

### Development Tools

- **Laravel Mix:** Asset compilation, minification, and versioning.
- **Composer:** Dependency management for PHP.
- **npm:** Package management for JavaScript.

## File and Folder Structure

- **`app/`**: Contains application logic, including controllers, models, and middleware.
- **`bootstrap/`**: Initializes the application.
- **`config/`**: Configuration files for the application.
- **`database/`**: Contains database migrations, seeders, and factories.
- **`public/`**: Publicly accessible files and the entry point (`index.php`).
- **`resources/`**: Contains views, JavaScript, and SCSS files.
- **`routes/`**: Defines web and API routes.
- **`storage/`**: Stores logs, cached files, and user uploads.
- **`tests/`**: Contains unit and feature tests.
- **`vendor/`**: Contains Composer dependencies.
- **`.env`**: Environment-specific configuration variables.
- **`artisan`**: The CLI for Laravel.
- **`composer.json`**: Composer metadata and dependencies.
- **`package.json`**: npm metadata and dependencies.
- **`webpack.mix.js`**: Configuration for Laravel Mix.

## Team Contributions

### Member 1: Chettim chetty Hemasri

As the Backend Developer and Project Manager, I focused on designing and implementing RESTful APIs using Laravel, managing the MySQL database schema, and integrating secure user authentication with Laravel Passport. I also ensured seamless project execution by allocating tasks, conducting code reviews, and creating comprehensive documentation. Working with these technologies was a challenging yet rewarding experience, as it allowed me to enhance the application's performance and security while coordinating effectively with the team.

### Member 2: Vootukuru Jyotheesh

As the Frontend Developer, Middleware Developer, and UI/UX Designer, I was responsible for designing a responsive and intuitive user interface using Vue.js, developing reusable components, and managing application state with Vuex. I also integrated Axios for efficient communication with the backend APIs and developed custom middleware to handle frontend request validation and user activity tracking. Diving into these technologies was both exciting and enriching, as it enabled me to create a dynamic, secure, and engaging platform that meets users' needs.

## What's Next for EduVista

We aim to collaborate with companies and industry professionals to provide students with valuable insights and direct access to job opportunities. By enabling companies to post job listings and share industry trends, EduVista keeps students informed about the latest market requirements and career paths. The platform also offers mentorship programs and peer-to-peer learning opportunities, ensuring that students receive the guidance and support they need to succeed. In the future, we plan to incorporate downloadable content for offline use and establish partnerships with local community centers to ensure that even those with limited internet access can continue their education without interruption.

## Setup Instructions

### Prerequisites

- PHP >= 7.3
- Composer
- Node.js & npm
- MySQL
- Docker(optional)
- Docker composer(optional)
- Redis(optional)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/EduVista.git
   cd EduVista
   ```

2. **Install PHP dependencies:**
   ```bash
   composer install
   ```

3. **Install JavaScript dependencies:**
   ```bash
   npm install
   ```

4. **Set up environment variables:**
   - Copy the `.env.example` file to `.env`:
     ```bash
     cp .env.example .env
     ```
   - Update the `.env` file with your database credentials and other settings.

5. **Generate application key:**
   ```bash
   php artisan key:generate
   ```

6. **Run database migrations:**
   ```bash
   php artisan migrate
   ```

7. **Compile assets:**
   ```bash
   npm run dev
   ```

8. **Start the development server:**
   ```bash
   php artisan serve
   ```

9. **Access the application:**
   Open your browser and go to `http://localhost:8000`
   
### Optional: Using Docker

1. **Install Docker and Docker Compose.**
2. **Build and start the Docker containers:**
   ```bash
   docker-compose up --build
   ```

3. **Access the application:**
   Open your browser and go to `http://localhost:8000`

### Why Prerequisites ?

1. **PHP**: Ensure you have PHP >= 7.3 installed. You can install PHP using package managers like `apt` for Ubuntu or `brew` for macOS.
2. **Composer**: Dependency manager for PHP. You can install Composer globally by following the instructions on [getcomposer.org](https://getcomposer.org/download/).
3. **Node.js and npm**: Required for managing JavaScript dependencies and compiling assets. You can download and install them from [nodejs.org](https://nodejs.org/).

### Dependencies Installed via Composer

1. **Laravel Framework**: The core PHP framework.
2. **Laravel Passport**: For API authentication.
3. **Laravel Echo**: For real-time events (optional, with Pusher integration).
4. **Laravel Mix**: For compiling assets.

### Dependencies Installed via npm

1. **Vue.js**: Frontend framework for building user interfaces.
2. **Axios**: HTTP client for making requests to the backend.
3. **Tailwind CSS**: Utility-first CSS framework.
4. **PostCSS**: Tool for transforming CSS with JavaScript plugins.
5. **Lodash**: Utility library for JavaScript.

### Other Tools

- **MySQL**: For database management.
- **Redis**: For caching (optional).
- **Docker**: For containerization (optional).



### Middleware and Blade Templates

- **Blade**: Laravel's templating engine is included by default and does not require separate installation. Blade templates are stored in the `resources/views` directory.
- **Middleware**: Custom middleware can be created and registered in `app/Http/Middleware`. Laravel's default middleware are already configured in `app/Http/Kernel.php`.

By following these steps and ensuring the prerequisites are met, you will have a fully functional Laravel project setup. If you encounter any issues, refer to the Laravel [documentation](https://laravel.com/docs) for detailed guidance.
