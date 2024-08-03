---

# Faked

## Introduction

Faked is a web application project focused on user authentication and management. It includes features such as user registration, login, password reset, and admin functionalities. This project is built using Node.js and Express, following the MVC architecture.

## Installation

To install and run this project locally, follow these steps:

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/Faked.git
    cd Faked
    ```

2. Install the dependencies:
    ```
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the root directory and add the necessary environment variables. Example:
    ```
    DB_URI=your_database_uri
    JWT_SECRET=your_jwt_secret
    ```

4. Start the application:
    ```
    npm start
    ```

## Usage

Once the application is running, you can access it at `http://localhost:3000` (or your configured port). The application provides the following functionalities:

- User registration
- User login
- Password reset
- Admin functionalities

## API Endpoints

### Authentication Routes

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login a user
- `POST /api/auth/forget-password` - Initiate password reset
- `POST /api/auth/reset-password` - Reset user password

### Admin Routes

- `GET /api/admin/users` - Get list of users (Admin only)
- `POST /api/admin/create` - Create a new user (Admin only)

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
