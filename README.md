# Grocery Web Application

A full-stack web application for managing grocery shopping lists with user authentication and a clean, modern interface.

## Overview

This Grocery Web Application is a comprehensive tool designed to help users manage their shopping lists. It features user authentication, a responsive UI, and real-time updates to grocery lists. The application is built with a separate frontend and backend architecture.

## Features

- **User Authentication**: Secure registration and login system
- **Personalized Grocery Lists**: Each user has their own private grocery list
- **Add/Remove Items**: Add new items with names and prices, or remove items that are no longer needed
- **Price Tracking**: Automatic calculation of the total cost of all items
- **Responsive Design**: Works across desktop and mobile devices
- **Form Validation**: Clear validation messages for user inputs

## Technologies Used

### Frontend
- Angular
- HTML5/CSS3
- TypeScript
- Angular Forms

### Backend
- Spring Boot
- Java
- RESTful API
- MySQL Database

## Screenshots

### Login Page
The login page features a clean, user-friendly interface with a centered login form. It includes fields for username and password, validation messages, and a link to the registration page for new users.

### Register Page
The register page matches the login page styling and includes form validation to ensure all required fields are completed before submission.

### Grocery List Page
The main grocery list interface displays a personalized welcome message, an "Add New Item" form, and the current list of grocery items with their prices. It also shows the total cost and provides a logout button.

## Installation and Setup

### Prerequisites
- Node.js and npm
- Java 11 or higher
- MySQL

### Frontend Setup
```bash
# Navigate to the frontend directory
cd grocery-app-frontend

# Install dependencies
npm install

# Start the development server
ng serve
```

### Backend Setup
```bash
# Navigate to the backend directory
cd grocery-app

# Build the application
./mvnw clean package

# Run the application
java -jar target/grocery-app-0.0.1-SNAPSHOT.jar
```

## Project Structure

The project is organized with separate directories for frontend and backend:

```
grocery-webapp/
├── grocery-app-frontend/   # Angular frontend application
└── grocery-app/            # Spring Boot backend application
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special appreciation to the Angular and Spring Boot communities for their excellent documentation
