Luna Jewelry - Full-Stack E-Commerce Platform
Luna Jewelry is a high-end e-commerce web application developed as a final project for the Web Design and Programming course. The platform offers a seamless shopping experience for luxury jewelry, featuring a modern UI and a robust backend.

Features
Dynamic Product Management: Products are fetched dynamically from a Spring Boot REST API.

Backend-Supported Filtering: Efficient product filtering by category (Rings, Necklaces, Watches, etc.) handled on the server side.

Global State Management: Shopping cart and user preferences are managed using React Context API.

Data Persistence: Integrated localStorage to keep the user's favorite items saved across browser sessions.

Responsive Design: Fully compatible with mobile and desktop devices thanks to Material UI's grid system.

Tech Stack
Frontend: React.js, Material UI, Axios, React Router.

Backend: Java, Spring Boot, Maven, Spring Data JPA.

Database: MySQL / H2.

Project Structure
The repository is organized into three main directories:

/frontend: The React application source code.

/backend: The Spring Boot API source code.

/database: Contains the SQL export file for database schema and initial data.

How to Run
Backend: Open the backend folder in IntelliJ IDEA and run the Spring Boot application (ensure Maven dependencies are loaded).

Database: Import the .sql file located in the database folder into your local database environment.

Frontend: Navigate to the frontend folder in your terminal and run the following commands: npm install npm start
