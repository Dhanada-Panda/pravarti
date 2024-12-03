<h1>E-Commerce Website</h1>
An e-commerce platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js), featuring an Admin Panel and a User Panel to manage and purchase products effectively.


<h2>Features</h2><br/>
<h3>Admin Panel:</h3><br/>
Authentication:<br/>
Admin can sign up and sign in securely.<br/>

![admin-after-signin](https://github.com/user-attachments/assets/439b37ca-a850-4ce9-9007-49f09922661d)<br/>


Profile Management:<br/>
Update admin profile details.<br/>
Category Management:<br/>
Create, update, and delete product categories.<br/>

![admin-create-category](https://github.com/user-attachments/assets/54aebe6d-f4ea-4fc3-b65f-505c836f3678)


Product Management:<br/>
Add new products under categories.<br/>
Update and delete existing products.<br/>

![admin-create-product](https://github.com/user-attachments/assets/35ea5dbc-fb55-441f-92f0-2b599eead5be)


![admin-product-list](https://github.com/user-attachments/assets/187b0f68-43b6-4e5f-a00d-d98da658b66f)



![Screenshot (248)](https://github.com/user-attachments/assets/c8ace0fe-18aa-42c4-9ca4-71a384646d42)

User Management:<br/>
View all registered users.<br/>
Update and delete user profiles.<br/>
<h3>User Panel:</h3>
Profile Management:<br/>
Update user profile information.<br/>
Product Browsing:<br/>
Filter products by price and category.<br/>

![user-home](https://github.com/user-attachments/assets/6678c2f0-074c-4176-92e7-3c58f10693d1)<br/>


View detailed information about a product.<br/>
![user-product-details](https://github.com/user-attachments/assets/636b4be7-aac3-42ba-b73b-681d49a5f683)<br/>


Cart Management:<br/>
Add products to the cart.<br/>
View selected products in the cart.<br/>

![user-cart](https://github.com/user-attachments/assets/fb607d98-5a7f-4c49-8109-8c922ea647ce)<br/>

<h1>Technologies Used</h1><br/>
Frontend: React.js<br/>
Backend: Node.js with Express.js<br/>
Database: MongoDB<br/>
State Management: Context API/Redux <br/>
Styling: CSS/Bootstrap/Daisy-UI<br/>
API Requests: Axios<br/>
Authentication: JWT (JSON Web Token)<br/>


<h1>Folder Structure</h1><br/>
<h2>Backend:</h2><br/>
/models – MongoDB models (User, Product, Category).<br/>
/routes – API endpoints for admin and user functionalities.<br/>
/controllers – Logic for API routes.<br/>
/middlewares – Authentication and error-handling middleware.<br/>
<h2>Frontend:</h2><br/>
/components – Reusable React components (e.g., Header, Footer, etc.).<br/>
/pages – React pages for admin and user functionalities.<br/>
/context – Context API for managing state (if used).<br/>
/services – Axios calls to interact with the backend.<br/>
API Endpoints<br/>
Admin Routes:<br/>
POST /api/admin/signup – Admin registration.<br/>
POST /api/admin/signin – Admin login.<br/>
PUT /api/admin/profile – Update admin profile.<br/>
POST /api/admin/category – Create a category.<br/>
PUT /api/admin/category/:id – Update a category.<br/>
DELETE /api/admin/category/:id – Delete a category.<br/>
POST /api/admin/product – Create a product.<br/>
PUT /api/admin/product/:id – Update a product.<br/>
DELETE /api/admin/product/:id – Delete a product.<br/>
GET /api/admin/users – View all users.<br/>
PUT /api/admin/user/:id – Update user profile.<br/>
DELETE /api/admin/user/:id – Delete user profile.<br/>
User Routes:<br/>
POST /api/user/signin – User login.<br/>
PUT /api/user/profile – Update user profile.<br/>
GET /api/user/products – Get all products (with filters for price and category).<br/>
GET /api/user/product/:id – Get details of a single product.<br/>
POST /api/user/cart – Add product to the cart.<br/>






