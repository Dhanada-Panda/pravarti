<h1>E-Commerce Website</h1>
An e-commerce platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js), featuring an Admin Panel and a User Panel to manage and purchase products effectively.


<h2>Features</h2>
<h3>Admin Panel:</h3>
Authentication:
Admin can sign up and sign in securely.

![admin-after-signin](https://github.com/user-attachments/assets/439b37ca-a850-4ce9-9007-49f09922661d)


Profile Management:
Update admin profile details.
Category Management:
Create, update, and delete product categories.



Product Management:
Add new products under categories.
Update and delete existing products.

![admin-create-product](https://github.com/user-attachments/assets/35ea5dbc-fb55-441f-92f0-2b599eead5be)


![admin-product-list](https://github.com/user-attachments/assets/187b0f68-43b6-4e5f-a00d-d98da658b66f)



![Screenshot (248)](https://github.com/user-attachments/assets/c8ace0fe-18aa-42c4-9ca4-71a384646d42)

User Management:
View all registered users.
Update and delete user profiles.
<h3>User Panel:</h3>
Profile Management:
Update user profile information.
Product Browsing:
Filter products by price and category.
![user-homepage](https://github.com/user-attachments/assets/62932523-4a48-482d-8696-3ff4b0d1a564)


View detailed information about a product.
![user-product-details](https://github.com/user-attachments/assets/636b4be7-aac3-42ba-b73b-681d49a5f683)


Cart Management:
Add products to the cart.
View selected products in the cart.

![user-cart](https://github.com/user-attachments/assets/fb607d98-5a7f-4c49-8109-8c922ea647ce)

<h1>Technologies Used</h1>
Frontend: React.js
Backend: Node.js with Express.js
Database: MongoDB
State Management: Context API/Redux (specify based on your implementation)
Styling: CSS/Bootstrap/Material-UI (specify based on your implementation)
API Requests: Axios
Authentication: JWT (JSON Web Token)


<h1>Folder Structure</h1>
<h2>Backend:</h2>
/models – MongoDB models (User, Product, Category).
/routes – API endpoints for admin and user functionalities.
/controllers – Logic for API routes.
/middlewares – Authentication and error-handling middleware.
<h2>Frontend:</h2>
/components – Reusable React components (e.g., Header, Footer, etc.).
/pages – React pages for admin and user functionalities.
/context – Context API for managing state (if used).
/services – Axios calls to interact with the backend.
API Endpoints
Admin Routes:
POST /api/admin/signup – Admin registration.
POST /api/admin/signin – Admin login.
PUT /api/admin/profile – Update admin profile.
POST /api/admin/category – Create a category.
PUT /api/admin/category/:id – Update a category.
DELETE /api/admin/category/:id – Delete a category.
POST /api/admin/product – Create a product.
PUT /api/admin/product/:id – Update a product.
DELETE /api/admin/product/:id – Delete a product.
GET /api/admin/users – View all users.
PUT /api/admin/user/:id – Update user profile.
DELETE /api/admin/user/:id – Delete user profile.
User Routes:
POST /api/user/signin – User login.
PUT /api/user/profile – Update user profile.
GET /api/user/products – Get all products (with filters for price and category).
GET /api/user/product/:id – Get details of a single product.
POST /api/user/cart – Add product to the cart.






