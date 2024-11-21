# E-Commerce Backend

## Description
This is a backend e-commerce application built with Express.js, Sequelize ORM, and PostgreSQL. It provides a RESTful API for managing products, categories, and tags in an e-commerce platform.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [API Routes](#api-routes)
- [Demo Videos](#demo-videos)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation
1. Clone the repository
2. Install dependencies:
```
npm install
```
3. Create a `.env` file in the root directory with the following variables:
```
DB_NAME=ecommerce_db
DB_USER=your_username
DB_PASSWORD=your_password
```
4. Run the application:
```
npm start
```

## Usage
The application will start a server at `http://localhost:3001`. You can use tools like Postman or curl to interact with the API endpoints.

## Features
- CRUD operations for products, categories, and tags
- Associations between products, categories, and tags
- Error handling and validation

## API Routes


The server will start on port 3001 by default.

## Features
- CRUD operations for Products, Categories, and Tags
- Many-to-Many relationships between Products and Tags
- One-to-Many relationship between Categories and Products
- RESTful API endpoints
- Data validation and error handling

## API Routes
### Categories
- GET `/api/categories` - Get all categories
- GET `/api/categories/:id` - Get category by ID
- POST `/api/categories` - Create new category
- PUT `/api/categories/:id` - Update category
- DELETE `/api/categories/:id` - Delete category

### Products
- GET `/api/products` - Get all products
- GET `/api/products/:id` - Get product by ID
- POST `/api/products` - Create new product
- PUT `/api/products/:id` - Update product
- DELETE `/api/products/:id` - Delete product

### Tags
- GET `/api/tags` - Get all tags
- GET `/api/tags/:id` - Get tag by ID
- POST `/api/tags` - Create new tag
- PUT `/api/tags/:id` - Update tag
- DELETE `/api/tags/:id` - Delete tag

## Demo Videos
[Database Setup & Seeding](https://1drv.ms/v/c/2cebbbbed41529a2/ERwlqPkSH31FucLd6CctUjgBZ_N3o_INt0oxBAjaRaBd-A?e=nRdiws)
[GET POST, PUT, DELETE  Routes Demo](https://1drv.ms/v/c/2cebbbbed41529a2/ETsXzOolvtNItAOE6iEDDagB5bWNcfoaWVJC2i14JaYnjg?e=iFn0Wl)


## Technologies Used
- Node.js
- Express.js
- Sequelize ORM
- PostgreSQL
- dotenv

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


