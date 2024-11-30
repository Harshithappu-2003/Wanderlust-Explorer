# Wanderlust-Explorer

**Wanderlust-Explorer** is a user-friendly and feature-rich travel website designed to help users find and add holiday destinations to explore. With its intuitive and attractive interface, users can easily choose their next adventure, explore destinations, and create listings. This project leverages modern web technologies to provide a seamless experience from front-end interactions to back-end data management and deployment.

## Features

- **Destination Listings**: Users can browse, search, and add holiday destinations to the website.
- **User Authentication**: Secure login and registration using Passport.js, allowing users to manage their profiles and listings.
- **Interactive Maps**: Integration with Mapbox API for displaying destinations and adding interactive maps for each location.
- **Responsive Design**: The website is fully responsive, ensuring a great experience on both desktop and mobile devices.
- **Data Validation**: Server-side validation using Joi to ensure accurate data entry for listings and user inputs.
- **MVC Architecture**: The project follows the Model-View-Controller (MVC) design pattern for clean code separation and better maintainability.
- **Real-Time Data**: Users can submit their travel listings, which are then stored in MongoDB, allowing for fast data retrieval.

## Technologies Used

### Frontend

- **HTML, CSS, and JavaScript**: These are the core technologies used for building the user interface of the website.
- **EJS (Embedded JavaScript)**: For dynamic content rendering, EJS allows us to embed JavaScript in our HTML files for templating.
- **Bootstrap**: Used for responsive design and to make the site mobile-friendly. Bootstrap helps in creating an attractive and consistent UI with minimal effort.

### Backend

- **Node.js**: The backend server is built using Node.js, providing a fast and scalable environment to handle multiple user requests simultaneously.
- **Express.js**: A minimal web framework for Node.js that simplifies the creation of the server and handling of routes, requests, and responses.
- **RESTful API**: The application is built with RESTful principles, allowing easy interaction with the frontend and providing a clean structure for managing routes and data.

### Database

- **MongoDB**: A NoSQL database that stores user data and holiday listings. It is scalable and flexible, allowing for efficient storage of dynamic data.
- **AWS**: The storage and hosting of the database models are managed through AWS services, ensuring high availability and security of data.

### User Authentication

- **Passport.js (Local Strategy)**: Passport.js handles user authentication and session management, ensuring secure user logins and registration for the site.

### API Integration

- **Mapbox API**: For integrating interactive maps into the website. Mapbox allows users to see their chosen travel destinations on an interactive map with customizable options.

### Validation

- **Joi**: Joi is used for validating the schema for user input and data entries to ensure correctness and data integrity. It prevents invalid data from entering the database.

### Deployment

- **Render**: The app is deployed on Render, a platform that provides a free and easy way to deploy full-stack web applications. This ensures high availability and easy access to the application from anywhere.

## Architecture

This project follows the **Model-View-Controller (MVC)** architecture pattern, where:

- **Model**: Represents the data structure and interaction with the database (e.g., holiday listings, user profiles).
- **View**: Represents the user interface (HTML pages rendered using EJS templates).
- **Controller**: Handles the logic of the application, including processing requests, interacting with the models, and rendering views.
