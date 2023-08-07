# E-Commerce-website/MERN
Tech Stack
Node.js
Express
MongoDB
React (Frontend)
HTML/CSS/JavaScript
Description
This is a web application developed for Webelight. The project includes a backend built with Node.js and Express, which communicates with a MongoDB database. The frontend is implemented using React, HTML, CSS, and JavaScript. The application allows users to add products, manage their cart, and apply filters based on product categories.

Functionality
User Authentication: The application uses local storage for user authentication. Users can log in and log out of their accounts.
Add Products: Users can add products to the application's database. Each product includes details like name, description, price, and category.
Cart Management: Users can add products to their cart and proceed to the cart page. In the cart, they have the option to either "Add to Cart" or "Buy Now" for each product.
Filter by Category: The application provides the functionality to filter products based on different categories, making it easier for users to find products of interest.
Installation
Clone the repository:
git clone https://github.com/yourusername/webelight-assignment.git
<li>Install dependencies:</li>
<pre><code>cd webelight-assignment
npm install

<li>Start the backend server:</li>
<pre><code>npm run start-server</code></pre>

<li>Start the frontend development server:</li>
<pre><code>npm start</code></pre>

<li>The application should now be accessible at <code>http://localhost:3000</code> in your browser.</li>
API Endpoints
GET /api/products: Get all products from the database.
POST /api/products: Add a new product to the database.
GET /api/products/:id: Get a specific product by its ID.
PUT /api/products/:id: Update a product's details by its ID.
DELETE /api/products/:id: Delete a product by its ID.
Contribution
Contributions to the project are welcome. If you find any issues or have ideas for improvements, please feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
