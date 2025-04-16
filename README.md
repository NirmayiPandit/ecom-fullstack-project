# ecom-fullstack-project
This is a full-stack e-commerce web application built with React (Vite) for the frontend and Spring Boot for the backend. It offers a complete solution for online shopping with features like product management, shopping cart, checkout, and much more.

Features
Product Listing: Display products dynamically fetched from the backend.

Product Images: Fetch images from the backend dynamically and show them in the product listing.

Add to Cart: Add products to the cart from the product listing.

Category Filter: Filter products by selected categories.

Error Handling: Handle data fetching errors gracefully by displaying a custom error message.

Responsive Design: Optimized for both desktop and mobile devices.

Tech Stack
Frontend: React (Vite), Axios (for API calls)

Backend: Spring Boot (REST APIs for products, etc.)

Database: H2

Setup and Installation:

Frontend:

Clone the repository:
git clone https://github.com/your-username/ecom-fullstack-project.git

Navigate to the frontend directory:
cd EcomProject_Frontend

Install dependencies:
npm install

Run the frontend application:
npm run dev

The frontend should now be running at http://localhost:3000.

Backend:

Navigate to the backend directory:
cd EcomProject_Backend

Build the Spring Boot project (make sure you have Maven installed):
mvn clean install

Run the backend application:
mvn spring-boot:run

The backend should now be running at http://localhost:8080.
