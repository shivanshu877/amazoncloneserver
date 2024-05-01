## Amazon Clone Server

Welcome to the Amazon Clone Server! This server is built using Node.js and Express, providing backend functionality for an Amazon-like e-commerce application. Below, you'll find a brief overview of the models and middleware used in this server.

### Models

#### Product Model
- The Product model defines the structure of product data, including properties like name, description, images, quantity, price, category, and ratings.

#### Order Model
- The Order model defines the structure of order data, including an array of products, total price, shipping address, user ID, order date, and status.

#### User Model
- The User model defines the structure of user data, including properties like name, email, password, address, type (e.g., admin, user), and cart.

#### Rating Schema
- The Rating schema defines the structure of rating data, including properties like user ID and rating value.

### Middleware

#### Admin Middleware
- The Admin middleware ensures that only users with admin privileges can access certain routes or perform specific actions. It verifies the user's authentication token and checks if the user is an admin before allowing access.

#### Auth Middleware
- The Auth middleware verifies the user's authentication token, ensuring that only authenticated users can access protected routes or perform authorized actions.

### Usage
To start the server, run `npm run index.js` from the terminal.

Feel free to customize and enhance this server according to your project's specific requirements!
