# Ecom-fullstack-project
This is a full-stack e-commerce web application built with React (Vite) for the frontend and Spring Boot for the backend. It offers a complete solution for online shopping with features like product management, shopping cart, checkout, and much more.

## Features:
- **Product Listing**: Display products dynamically fetched from the backend.
- **Product Images**: Fetch images from the backend dynamically and show them in the product listing.
- **Add to Cart**: Add products to the cart from the product listing.
- **Category Filter**: Filter products by selected categories.
- **Error Handling**: Handle data fetching errors gracefully by displaying a custom error message.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Tech Stack:
- **Frontend**: React (Vite)
- **Backend**: Spring Boot (REST APIs for products, etc.)
- **Database**: H2

## Setup and Installation:
### Frontend
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecom-fullstack-project.git
2. Navigate to the frontend directory:
   ```bash
   cd EcomProject_Frontend
3. Install dependencies:
   ```bash
   npm install
4. Run the frontend application:
   ```bash
   npm run dev
(The frontend should now be running at http://localhost:3000.)

###Backend:
1. Navigate to the backend directory:
   ```bash
   cd EcomProject_Backend
2. Build the Spring Boot project (make sure you have Maven installed):
   ```bash
   mvn clean install
3. Run the backend application:
   ```bash
   mvn spring-boot:run
   
OR 
Just Open IntelliJ and Click on Run
(The backend should now be running at http://localhost:8080.)
