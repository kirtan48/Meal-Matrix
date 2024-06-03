# Meal-Matrix

Meal Matrix is a backend project designed to streamline the process of restaurant registration and food ordering. This application allows restaurants to register and manage their menus, while also providing users with the ability to browse and order food from their favorite eateries.


## Features
- Restaurant Registration: Restaurants can register and manage their profiles and menu.  
- User Authentication: Secure authentication for users using JWT.  
- Order Management: Users can place and track their orders.  
- Menu Management: Restaurants can add, update, and delete menu items.  
- Secure Transactions: All sensitive information is encrypted using bcryptjs.



## Tech Stack
- Node.js: JavaScript runtime environment.    
- Express.js: Web framework for Node.js.   
- MongoDB: NoSQL database for storing restaurant and user data.   
- Mongoose: ODM for MongoDB, providing a schema-based solution.    
- BcryptJS: Library for hashing passwords.   
- JWT (JSON Web Tokens): For secure user authentication.   
## Installation
1) Clone the repository:
```
git clone https://github.com/yourusername/meal-matrix.git
```
2) Navigate to the project directory:
```
cd meal-matrix
```
3) Install dependencies :
    ```
   npm install
    ```
4) Set up environment variables:        
Create a .env file in the root directory and add the following:
```
PORT=your_port_number
MONGO_UR=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```
5) Run the application:
```
npm run server
```

# Usage
Once the application is up and running, you can use tools like Postman to interact with the API endpoints.
