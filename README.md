*Product Management API

Node.js + Express API for managing products with CRUD operations using MongoDB.

*Setup Instructions

**Prerequisites

- Node.js (v14 or above)
- MongoDB or MongoDB Atlas Account

**Installation

*Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/product-management-api.git
   cd product-management-api

*Install Dependencies 
	npm install

*Configure environment variable
 create .env in root folder and data below

 MONGO_URI=your_mongodb_connection_string
 PORT=5000
and start server : npm start



**API ENDPOINTS

url : http://localhost:5000/api/products

| Method | Endpoint            | Description            |
| ------ | ------------------- | -----------------------|
| POST   | /api/products       | Create a new product   |
| GET    | /api/products       | Get all products       |
| GET    | /api/products/:id   | Get particular product |
| PUT    | /api/products/:id   | Update a product       |
| DELETE | /api/products/:id   | Delete a product       |



**sample product request
{
  "name": "Smartwatch",
  "price": 4999,
  "description": "Waterproof fitness tracker"
}
